# UnkiSocialManager

**UnkiSocialManager** is a local-first desktop app for Windows that helps creators run their own channels: prepare videos, write titles, descriptions and tags with optional AI help, schedule and publish to YouTube after your final approval, and review analytics. Your videos, drafts and platform data stay on your computer.

Developed and published by **UnkiSoftware**.

## Download

**[Download the latest version](https://github.com/UnkiSoftware/UnkiSocialManager/releases/latest)** — `UnkiSocialManager-Setup-<version>.exe`.

The installed app checks this page for new versions and installs an update only after verifying the UnkiSoftware signature of the release (`update-manifest.json` and `.sig`). You can turn automatic checks off in Settings → About.

### System requirements

- Windows 10 or Windows 11, 64-bit
- An internet connection for sign-in, publishing, AI providers you enable and updates

### Check the download (SHA-256)

Every release has `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\UnkiSocialManager-Setup-<version>.exe -Algorithm SHA256
```

The hash must match the line for that file in `SHA256SUMS.txt`. The installer is not yet code-signed, so Windows SmartScreen may show "Unknown publisher".

## Links

- Website: https://unkisocialmanager.pp.ua
- Privacy Policy: https://unkisocialmanager.pp.ua/privacy/
- Terms of Service: https://unkisocialmanager.pp.ua/terms/
- Refund & Cancellation Policy: https://unkisocialmanager.pp.ua/refunds/
- Support: https://unkisocialmanager.pp.ua/support/
- Security reports: see [SECURITY.md](SECURITY.md)

## Open-source components

The app includes open-source components; their licenses are in `THIRD_PARTY_NOTICES.txt`, attached to every release and installed next to the app.

The app ships FFmpeg and ffprobe builds licensed under the GNU GPL v3 (and FFmpeg libraries inside PyAV under the GPL). The exact corresponding source code and build information is attached to every release as `ffmpeg-<version>-source.tar.xz`. In addition, for at least three years after we last distribute a version, we will provide the complete corresponding source code on request to the support address in [SECURITY.md](SECURITY.md), for no more than the cost of the transfer.

## По-русски

UnkiSocialManager — локальное приложение для Windows: подготовка видео, названия и описания с помощью AI, публикация на YouTube только после вашего одобрения, аналитика. Видео и данные остаются на вашем компьютере. **[Скачать последнюю версию](https://github.com/UnkiSoftware/UnkiSocialManager/releases/latest)**. Приложение обновляется само и устанавливает обновление только после проверки подписи UnkiSoftware. Контрольные суммы — в `SHA256SUMS.txt` каждого выпуска.

---

© 2026 UnkiSoftware. Proprietary software. The source code is not public.
