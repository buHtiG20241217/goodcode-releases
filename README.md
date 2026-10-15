# GoodCode: downloads

Installers for **GoodCode**, a calm, fast code editor for Windows and Linux.

**→ [Latest release](https://github.com/buHtiG20241217/goodcode-releases/releases/latest)** · every older version
stays under [Releases](https://github.com/buHtiG20241217/goodcode-releases/releases).

This repository holds **installers only**. GoodCode's source code is not published here.

## Which file?

| You have | Download |
|---|---|
| Windows 10 / 11 (64-bit) | `GoodCode-<version>-setup.exe`, no admin needed |
| Ubuntu, Debian, Mint | `goodcode_<version>_amd64.deb`, then `sudo apt install ./goodcode_<version>_amd64.deb` |
| Any other 64-bit Linux | `goodcode-<version>-linux-x86_64.tar.gz`, then extract it and run `./goodcode/goodcode` |

Windows may say "Windows protected your PC" because the beta isn't code-signed yet: choose
**More info**, then **Run anyway**.

## Check your download

Each release includes `SHA256SUMS.txt`. On Windows:

```powershell
Get-FileHash .\GoodCode-<version>-setup.exe -Algorithm SHA256
```

On Linux: `sha256sum -c SHA256SUMS.txt`. The hash must match the one in the file.

## Feedback

Ideas, bugs, questions: hemalathakiransoorya2099@gmail.com

© 2026 GoodCode, Kiran Soorya R S. Free during the beta; all rights reserved. Third-party credits
ship inside each download (NOTICE).
