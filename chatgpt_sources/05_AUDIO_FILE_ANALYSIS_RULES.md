# Audio File Analysis Rules

Use these rules whenever the user uploads a WAV, AIFF, FLAC, MP3 or exported mix/master.

## First ask only if necessary

If the user did not say whether the file is mix or master, make a best effort and state your assumption.

Example:

> Я буду считать, что это предварительный мастер, потому что файл звучит уже лимитированно.

## Analysis order

1. Overall impression.
2. Vocal vs beat balance.
3. Low-end: kick, 808, bass.
4. Low-mids: 150–500 Hz.
5. Midrange: 500 Hz–2 kHz.
6. Presence/harshness: 2.5–6 kHz.
7. Sibilance: 5–10 kHz.
8. Air: 10–16 kHz.
9. Stereo image.
10. Dynamics and loudness.
11. Priority fixes.

## Frequency guide

### 20–60 Hz

Sub weight. Too much here can eat headroom.

### 60–120 Hz

Kick/808 body. Conflict here makes the low-end unstable.

### 120–250 Hz

Warmth and body. Too much makes vocal/beat boomy.

### 250–500 Hz

Mud, boxiness, cloudiness. Very common problem in bedroom trap vocals.

### 500 Hz–1.5 kHz

Nasal tone, body, small speaker translation.

### 1.5–3 kHz

Intelligibility and forwardness.

### 3–6 kHz

Presence and harshness. Too much here makes the track painful.

### 5–10 kHz

Sibilance and brightness.

### 10–16 kHz

Air and expensive top. Too much can sound fake/noisy.

## Vocal balance rules

If vocal is behind the beat:

- check 2–4 kHz presence
- reduce masking from beat in 1–5 kHz
- use sidechain dynamic EQ on beat against vocal
- reduce reverb wetness
- check compression makeup gain

If vocal is muddy:

- check 180–350 Hz
- check room resonance
- check too much low reverb
- check wide/chorus plugins causing smear

If vocal is harsh:

- check 3–6 kHz
- check saturation before EQ
- check over-compression
- use dynamic EQ/de-esser, not only static EQ

## Mastering rules

Do not judge only by LUFS.

Check:

- peak / true peak
- clipping artifacts
- limiter pumping
- kick/808 stability
- vocal distortion
- high-end harshness
- mono compatibility

## Final response format for audio

**Короткий вывод**

**Главная проблема**

**Баланс вокала и бита**

**Низ**

**Муть / low-mid**

**Резкость / верх**

**Мастер / громкость**

**Что исправить по шагам**

**Настройки для старта**
