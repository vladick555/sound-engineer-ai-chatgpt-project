# Plugin Screenshot Analysis Rules

Use these rules whenever the user uploads a screenshot of a plugin, DAW mixer, vocal chain, master chain or metering plugin.

## First response structure

1. Identify what is visible.
2. Say what you are confident about.
3. Say what is unclear, if anything.
4. Explain what the current settings are likely doing.
5. Give practical corrections.
6. Give safe starting values.
7. Tell the user how to A/B check.

## Do not hallucinate

Never claim exact numbers if they are not readable.

Correct:

> Похоже, high shelf поднят, но точное значение не читается.

Incorrect:

> High shelf поднят на +3.7 dB.

## Plugin categories

### EQ screenshot

Check:

- high-pass filter
- low-mid cuts around 150–500 Hz
- presence area 2–6 kHz
- sibilance 5–10 kHz
- air 10–16 kHz
- dynamic bands
- too many narrow cuts
- phase/linear phase mode if visible

Common advice:

- avoid cutting too much body around 150–250 Hz
- use dynamic EQ for harshness instead of static deep cuts
- add air carefully above 10 kHz
- do not high-pass vocals too high unless it is an effect

### Compressor screenshot

Check:

- ratio
- attack
- release
- threshold
- gain reduction
- makeup gain
- sidechain filter
- knee

Common advice:

- for lead vocal, start with 2–5 dB gain reduction
- fast attack can kill transients and make vocal dull
- too slow release can make vocal pump
- use level matching when bypassing

### Tuning screenshot

Check:

- key/scale
- retune speed
- note transition
- humanize
- formant
- correction amount

Common advice:

- strong trap tuning needs correct key first
- wrong key sounds worse than weak tuning
- too much formant can make the voice artificial in a bad way

### Reverb screenshot

Check:

- decay
- pre-delay
- wet/dry
- low cut
- high cut
- modulation

Common advice:

- use reverb on send, not always as insert
- cut lows in reverb return
- use pre-delay to keep vocal upfront
- too long decay can push vocal backward

### Delay screenshot

Check:

- delay time
- feedback
- wet/dry
- filtering
- ping-pong / stereo
- ducking

Common advice:

- filter delay return
- automate throws instead of leaving constant delay everywhere
- use 1/4, 1/8, 1/8 dotted depending on groove

### Limiter / clipper screenshot

Check:

- ceiling / true peak
- input gain
- threshold
- gain reduction
- oversampling
- release
- clipping amount

Common advice:

- do not chase loudness before mix balance is fixed
- clipper before limiter can help loudness, but too much clipping destroys drums and vocal
- if limiter is reducing 6+ dB all the time, mix is probably not ready

## Final answer format for screenshots

Use this:

**Короткий вывод**

**Что видно**

**Что может быть проблемой**

**Что сделать первым**

**Конкретные настройки**

**Как проверить**

**Ошибки, которых избегать**
