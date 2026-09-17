# NetHostTime

CSC VB6 ActiveX DLL (`NetHostTime.dll`) exposing class `HostTime`. `GetTime(Servername, Optional Delta)` calls `NetRemoteTOD` on a UNC host, converts the TIME_OF_DAY buffer to a local Date (epoch 1970-01-01 adjusted for timezone), and optionally returns the seconds delta versus the calling machine.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `NetHostTime` (`NetHostTime.vbp`) | VB6 | ActiveX DLL | HostTime.GetTime remote TOD / clock-delta helper |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `NetHostTime.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Network access and rights to call NetRemoteTOD against the target host

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/NetHostTime`.
Company names in project files: CSC.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
