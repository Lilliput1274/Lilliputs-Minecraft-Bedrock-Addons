# Minecraft Bedrock Batch Installer V11.8

Windows-Werkzeug zum Installieren von Bedrock .mcpack, .mcaddon und ZIP-Paketen.

## V11.8
- Numerischer Versionsvergleich für installierte und neue Packs.
- Updates werden im Installationsplan kenntlich gemacht; identische Versionen werden nicht ersetzt.
- **Downgrades** erfordern pro Pack eine ausdrückliche `[j/n]`-Bestätigung und werden unmittelbar vor dem Ersetzen nochmals überprüft.
- Backup der vorhandenen Pack-Installation bei Versionswechsel.
- Abhängigkeitskontrolle und optionale Weltzuordnung mit vorherigem Welt-Backup.

## Download / Verwendung
Unter Assets `Minecraft_Bedrock_Batch_Installer_V11.8.zip` herunterladen und entpacken. `Start_Installer.cmd` starten. Die ZIP enthält PowerShell-Skript, CMD-Startdatei und Anleitung.

Minecraft Bedrock vor der Verwendung schließen. Vor Änderungen an wichtigen Welten eine eigene Sicherung erstellen.

## Build-Nachweis
Quelle: `Lilliput1274/MineCraft_Addons`, `master`
Commit: `5b6c02416a0ce8120b027fb6d207fd24094d9e65`
Erfolgreicher Windows-Syntax- und ZIP-Build: https://github.com/Lilliput1274/MineCraft_Addons/actions/runs/45017917187
