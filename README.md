# Solaris pedestal audio

`dtmf-pound.wav`: a single DTMF "#" tone (941 Hz + 1477 Hz, 250 ms, 8 kHz mono PCM) used by the Solaris parking phone agent to open the exit-pedestal intercom audio.

`dtmf-pound-2s.wav`: the same "#" tone followed by 2 seconds of silence, so the agent pauses about 2 s after the beep before greeting.

`test/caller-noisy.wav`, `test/caller-quiet.wav`: synthetic 62-second test callers (computer voice plus optional band-limited noise at -26 dBFS) used to validate the agent against a noisy intercom line. Not used in production.
