# Smack In

Distribution repo for **Smack In** — the standalone `sound_generator` build
of [Smack](https://github.com/timncox/schwung-smack) for
[schwung](https://github.com/charlesvestal/schwung) on the Ableton Move.

Smack In reads Move's selected audio input (mic, line, or USB-C — the XMOS routes the source) directly (with schwung's boot
feedback protection), so you get quantized loop capture + seeded per-slice
glitch FX in a single chain slot — no `linein` module needed in front.

**Source, issues, and documentation live in the main repo:**
https://github.com/timncox/schwung-smack — this repo only hosts
`release.json` and release tarballs so the Module Store can install
`smack-in` independently (schwung resolves one module per repo).

Install: Module Store (if listed), or schwung-manager → Install Custom
Module → `timncox/schwung-smack-in`.

Set Move's **MIDI Clock to Out** so capture locks to the transport.

MIT — see the main repo for license and credits.
