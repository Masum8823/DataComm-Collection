# Pulse Modulation (PAM, PWM, PPM)

![Topic](https://img.shields.io/badge/Topic-Data%20Communications-blue)
![Chapter](https://img.shields.io/badge/Chapter-Pulse%20Modulation-orange)
![Status](https://img.shields.io/badge/Status-Study%20Notes-brightgreen)

Pulse Modulation is a technique where a **periodic pulse train** is used as the carrier signal instead of a continuous wave. Depending on which property of the pulse we change, we get different types of pulse modulation.

---

## <a id="toc"></a>📑 Table of Contents
- [What is Pulse Modulation?](#pulse-modulation)
- [Pulse Amplitude Modulation (PAM)](#pam)
  - [Natural PAM](#natural-pam)
  - [Flat-top Sampling](#flat-top)
  - [Natural PAM vs Flat-top Sampling](#pam-comparison)
- [Pulse Width Modulation (PWM)](#pwm)
- [Pulse Position Modulation (PPM)](#ppm)
- [Overall Comparison: PAM vs PWM vs PPM](#overall-comparison)
- [Memory Trick](#memory-trick)
- [Exam Notes](#exam-notes)

---

## <a id="pulse-modulation"></a>📶 What is Pulse Modulation?

**Definition:** Pulse Modulation is a technique where a periodic pulse train is used as a carrier signal. The **amplitude**, **width**, or **position** of the pulses changes according to the analog message signal.

**Why it is used:**
- To transmit analog signals efficiently
- Used in communication systems and power control

> 🧠 **Real-life analogy:** Think of Morse code sent with a flashlight — you're not sending a continuous beam of light, you're sending a train of flashes (pulses). Depending on how bright the flash is, how long it lasts, or when it happens, you can encode different information. That's the whole idea behind pulse modulation — just applied to analog signals instead of dots and dashes.

Every pulse has 3 properties we can play with: **Amplitude, Width, Position**. Change only one, keep the rest fixed — and that gives us PAM, PWM, and PPM.

---

## <a id="pam"></a>📊 Pulse Amplitude Modulation (PAM)

**Definition:** PAM is an analog modulation technique where the **amplitude (height)** of each pulse changes according to the instantaneous amplitude of the message signal.

**Key Points:**
- ✅ Pulse amplitude changes
- ❌ Pulse width and position remain the same
- The PAM signal follows the shape of the original analog signal

```
Message signal:     ___
                ___/    \___

PAM pulses:      |  ||  |||  ||  |
                  ↑ height of each pulse follows the message signal
```

> 🧠 **Analogy:** Imagine taking quick "snapshots" of a song's volume every few milliseconds, and drawing a bar for each snapshot whose height matches how loud the song was at that instant. Line up all the bars — that's a PAM signal.

### <a id="natural-pam"></a>🌿 Natural PAM

- The analog signal is sampled at the **Nyquist rate**
- The original signal is recovered using a **Low Pass Filter (LPF)** with the correct cutoff frequency

**Problem:** Even after using an LPF, the recovered signal may still have **distortion (noise)** — because in natural PAM, the top of each pulse actually follows the shape of the signal during the sampling time, not a fixed flat value, which makes clean recovery harder.
