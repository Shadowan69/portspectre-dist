```
   .-~~~~~-.    ┌─ PORTSPECTRE ───────────────────┐
  /  o   o  \   │ the ghost in your network        │
  |    ‿    |   │ passive Windows defense monitor, │
  |         |   │ not a port scanner — on YOUR     │
  |         |   │ side, watching your own host.    │
   |_|_|_|_|    └──────────────────────────────────┘
```

**PORTSPECTRE** is a *passive* Windows network-defense tray app — the friendly
ghost that watches **your own** machine's connections and quietly raises the
alarm when something looks wrong.

It is **not a port scanner.** It never probes, scans, or reaches out to remote
hosts. It haunts a single endpoint — yours — surfacing C2 beaconing, data
exfiltration, newly exposed services, suspicious processes and more, in real
time. Defensive by design, working for the good side. 👻

---

## 📦 This repository

`portspectre-dist` is PORTSPECTRE's **distribution channel** — compiled release
binaries only, **no source code**. It also serves the update feed read by the
in-app **SOFTWARE UPDATE** check.

- **Download the latest build:** [`releases/latest`](https://github.com/Shadowan69/portspectre-dist/releases/latest/download/PORTSPECTRE.exe)
- The `.exe` is unsigned, so Windows SmartScreen may warn on first run — choose **More info → Run anyway**.

> If you arrived here looking for an unrelated, similarly-named port *scanning*
> tool, this isn't it. PORTSPECTRE is defensive software that monitors your own host.
