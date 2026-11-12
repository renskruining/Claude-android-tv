# Android TV debloat + launcher (Philips TPM191E)

Files copied from [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) at commit `b953804` (MIT, see `LICENSE`):

- `tools/`: ADB helpers (`tv.py`, `disable.sh`/`restore.sh` with their safety checks, `adb-closed.py`, `relay.py`, `philips-api.py`, ...)
- `launcher/`: the reference Apple TV style launcher. Change the dock and grid in `launcher/app/src/main/res/values/config.xml`, then build and install with `launcher/build-and-install.sh`.
- `examples/philips-tpm191e/`: a tested debloat list for this chassis, plus the lists for the same board that its header refers to.
- `docs/TROUBLESHOOTING.md`, `docs/REMOTE.md`, `PROMPT.md`: what the tools and the prompt point to.

Run Claude Code from this folder on a computer on the same network as the TV and paste `PROMPT.md`.
