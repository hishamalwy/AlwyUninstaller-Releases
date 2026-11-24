# Privacy

AlwyUninstaller works only on your computer. It makes no network connections: it sends no data, telemetry, crash reports or usage statistics anywhere, and it has no account or sign-in.

## What it reads

To list and remove programs, it reads the Windows uninstall registry entries, the Store apps registered for your account, program folders, Windows Prefetch (to show when you last opened a program), Start menu and desktop shortcuts, and the cache folders it can clean. None of this leaves your computer.

## What it writes

- `%LocalAppData%\AlwyUninstaller\settings.json`: your language, appearance, filter and sort choices.
- `%ProgramData%\AlwyUninstaller\Backups`: the leftovers you removed, kept for 14 days so you can restore them, then deleted automatically. You can delete a backup sooner from the Backups page.
- `%LocalAppData%\AlwyUninstaller\errors.log`: details of unexpected errors, only when one happens.

Deleting these folders removes everything the app has stored.

## Contact

Report privacy questions in [Issues](https://github.com/hishamalwy/AlwyUninstaller-Releases/issues). Do not include personal information.
