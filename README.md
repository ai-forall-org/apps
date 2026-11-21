# AI-forAll Apps (installers only)

Public download home for **AI-forAll** desktop and mobile installers.  
Source code stays in separate repos under `aiandcyber` — this repo holds **executables only**.

**Org:** [ai-forall-org](https://github.com/ai-forall-org)  
**End-user download UI:** [Tools → Desktop](https://tools.ai-forall.org/desktop) · [Tools → Mobile](https://tools.ai-forall.org/mobile)

Direct file links below (raw files on `main`). Tools uses the same URLs via configuration.

---

## Desktop

### YouTube Download — v0.1.1

| OS | File | Download |
|---|---|---|
| Windows | `YouTube.Download_0.1.1_x64-setup.exe` | [Download](https://github.com/ai-forall-org/apps/raw/main/desktop/youtube/YouTube.Download_0.1.1_x64-setup.exe) |
| Mac (Apple Silicon) | `YouTube.Download_0.1.1_aarch64.dmg` | [Download](https://github.com/ai-forall-org/apps/raw/main/desktop/youtube/YouTube.Download_0.1.1_aarch64.dmg) |

### AI Powered Anti-Virus — v0.1.1

| OS | File | Download |
|---|---|---|
| Windows | `AI.Powered.Anti-Virus_0.1.1_x64-setup.exe` | [Download](https://github.com/ai-forall-org/apps/raw/main/desktop/antivirus/AI.Powered.Anti-Virus_0.1.1_x64-setup.exe) |
| Mac (Apple Silicon) | `AI.Powered.Anti-Virus_0.1.1_aarch64.dmg` | [Download](https://github.com/ai-forall-org/apps/raw/main/desktop/antivirus/AI.Powered.Anti-Virus_0.1.1_aarch64.dmg) |

### Media Translate

| OS | Status |
|---|---|
| Windows / Mac | Coming soon — place installers under `desktop/media-translate/` |

---

## Mobile

| App | Android | iOS |
|---|---|---|
| AI-forAll Tools | Coming soon | Coming soon |
| AI Powered Anti-Virus | Coming soon | Coming soon |

Store links will be listed here when published. Until then, use [Tools → Mobile](https://tools.ai-forall.org/mobile).

---

## Layout

```text
desktop/
  youtube/
  antivirus/
  media-translate/
mobile/
```

## Note for Tools / developers

Preferred direct URL pattern:

`https://github.com/ai-forall-org/apps/raw/main/<path-to-file>`

Change host/path only in Tools env (`VITE_APPS_DOWNLOAD_BASE` and optional per-file overrides) — not in application logic.
