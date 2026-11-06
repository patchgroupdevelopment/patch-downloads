# Patch Downloads

Direct installer downloads for the free Windows apps from Patch Group.

Both apps are Windows desktop tools. They run locally. There is no account, no internet connection is needed and nothing leaves your PC.

## PawDrop Lite (freeware)

A desktop cat for your Windows taskbar. The graphite cat walks along the taskbar, taps a paw every time you press a key, naps on the window you are working in, and runs after your pointer when you shake the mouse. Clicks go straight through the cat, it hides while a video, game or presentation is full screen, and quiet hours put it to sleep. It starts with Windows and lives in the tray.

PawDrop only counts that a key went down. It never records which key, and nothing is saved or sent anywhere.

- Version: 1.0.1
- License: freeware for personal use. No source code is published.
- Download: [PawDrop-Lite-Setup-1.0.1.exe](https://github.com/patchgroupdevelopment/patch-downloads/releases/download/pawdrop-lite-v1.0.1/PawDrop-Lite-Setup-1.0.1.exe) (about 107 MB)
- SHA-256: `24aef450da23c35141d892b76fbee2f72836bbc2ff2c44c320f8c3f25f68ab61`
- VirusTotal: [scan report](https://www.virustotal.com/gui/file/24aef450da23c35141d892b76fbee2f72836bbc2ff2c44c320f8c3f25f68ab61)
- Full version with five more cats: https://patchgroup.gumroad.com/l/pawdrop

## FocusDrop Lite (7-day trial)

FocusDrop dims or blurs everything except the window you are working in. The active window, its menus and dialogs and the taskbar stay bright. Click another window and it comes forward at once while the one you left fades into the background. Shake the pointer left and right to turn it off and on, or press Ctrl+Alt+F, or click the tray icon. Settings: dim or blur, darkness from 5 to 90 percent, smooth transitions, your own shortcut, a list of apps to leave alone, and one or all displays.

The trial is the whole app with every setting. It works for 7 days from the first start and then turns itself off.

- Version: 1.0.1
- License: trial, 7 days. Freeware for personal evaluation during the trial. No source code is published.
- Download: [FocusDrop-Trial-Setup-1.0.1.exe](https://github.com/patchgroupdevelopment/patch-downloads/releases/download/focusdrop-lite-v1.0.1/FocusDrop-Trial-Setup-1.0.1.exe) (about 107 MB)
- SHA-256: `832272ef5eb1a2a285f095028ffd9b0626a0f6561d1796dd651174a15e59355f`
- VirusTotal: [scan report](https://www.virustotal.com/gui/file/832272ef5eb1a2a285f095028ffd9b0626a0f6561d1796dd651174a15e59355f)
- Full version: https://patchgroup.gumroad.com/l/focusdrop

## System requirements

- Windows 10 (version 1903 or later) or Windows 11, 64-bit
- FocusDrop blur needs Windows 11 with transparency effects on. Dim works on Windows 10 and 11.

## Windows SmartScreen warning

The installers are not code-signed yet, because they come from an independent developer. The first time you run one, Windows may show "Windows protected your PC". Click **More info**, then **Run anyway**.

To check your download, compare its SHA-256 with the value above. In PowerShell:

```
Get-FileHash .\PawDrop-Lite-Setup-1.0.1.exe -Algorithm SHA256
```

## Licenses and support

Terms for all Patch Group apps: https://patchgroup.gumroad.com/license

Store and help: https://patchgroup.gumroad.com

Contact: infopatchgroup@gmail.com
