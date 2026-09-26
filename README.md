# Tcp

VB6 ActiveX DLL (`TCP`) wrapping Oleg Gdalevich's `CSocket` Winsock API class (`ws2_32`) plus a thin `Peer` server helper that listens for connection requests, an alternative to the MS Winsock OCX. Distinct from sibling `TCPClient` / `TCPServer` logon apps. Open `Tcppeer.vbp` in the VB6 IDE.

**Source last updated:** 2003-02-10 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TCP` (`Tcppeer.vbp`) | VB6 | ActiveX DLL | CSocket Winsock wrapper + Peer helper |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Tcppeer.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Tcp`.
`CSocket` / `MSocketSupport` attribution in source: Oleg Gdalevich, vbip.com (2002).

## License

MIT © 2026 VaderConsulting for Dave Robinson's packaging; third-party `CSocket` remains under its original terms (or none, where none were supplied).
