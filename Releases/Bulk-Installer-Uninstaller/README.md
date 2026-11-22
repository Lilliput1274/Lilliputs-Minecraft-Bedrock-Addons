# 🛠️ Minecraft Bedrock Batch Installer / Uninstaller

**Zwei eigenständige Windows-Werkzeuge zur Installation und Deinstallation von Minecraft-Bedrock-Add-ons.**

Beide Programme sind **keine Minecraft-Packs**. Die ZIP-Dateien werden unter Windows entpackt und über die enthaltene `.cmd`-Startdatei ausgeführt.

## ⬇️ Aktuelle Downloads

| Werkzeug | Version | Download | Versionshinweise |
| --- | --- | --- | --- |
| **Installer** | **V11.8** | **[Installer V11.8 herunterladen (.zip)](https://github.com/Lilliput1274/Lilliputs-Minecraft-Bedrock-Addons/releases/download/bulk-installer-v11.8/Minecraft_Bedrock_Batch_Installer_V11.8.zip)** | [Release ansehen](https://github.com/Lilliput1274/Lilliputs-Minecraft-Bedrock-Addons/releases/tag/bulk-installer-v11.8) |
| **Uninstaller** | **V1.5** | **[Uninstaller V1.5 herunterladen (.zip)](https://github.com/Lilliput1274/Lilliputs-Minecraft-Bedrock-Addons/releases/download/bulk-uninstaller-v1.5/Minecraft_Bedrock_Batch_Uninstaller_V1.5.zip)** | [Release ansehen](https://github.com/Lilliput1274/Lilliputs-Minecraft-Bedrock-Addons/releases/tag/bulk-uninstaller-v1.5) |

## 📦 Paketinhalt

**Installer V11.8:** `Minecraft_Bedrock_Batch_Installer.ps1`, `Start_Installer.cmd`, `ANLEITUNG.txt`.

**Uninstaller V1.5:** `Minecraft_Bedrock_Batch_Uninstaller.ps1`, `Start_Uninstaller.cmd`, `ANLEITUNG.txt`.

## Funktionen

Der **Installer** erkennt vorhandene Packversionen und unterstützt neue Installationen, Updates und optional die Zuordnung zu Welten. Ein Downgrade auf eine niedrigere Version erfordert pro Pack eine ausdrückliche `[j/n]`-Bestätigung.

Der **Uninstaller** entfernt ausgewählte Packs und auf Wunsch deren Weltzuordnungen. Sicherungen werden zunächst versucht; schlägt eine Sicherung fehl, kann der Vorgang nur nach gesonderter Warnung und `[j/n]`-Bestätigung ohne vollständiges Backup fortgesetzt werden.

## Installation und Sicherheit

1. ZIP-Datei herunterladen und vollständig entpacken.
2. Minecraft Bedrock vollständig beenden.
3. Die passende `Start_Installer.cmd` oder `Start_Uninstaller.cmd` auf Windows ausführen.
4. Den Anweisungen im Konsolenfenster folgen.

**Vor Änderungen an wichtigen Welten ein eigenes Backup erstellen.** Für den Installer ist Windows PowerShell 5.1 oder PowerShell 7 vorgesehen.

## Quelle und Build

Die veröffentlichten Pakete stammen aus dem `master`-Branch von [MineCraft_Addons](https://github.com/Lilliput1274/MineCraft_Addons). Beide ZIPs wurden im [erfolgreichen Windows-Build](https://github.com/Lilliput1274/MineCraft_Addons/actions/runs/45017917187) erzeugt und geprüft.

[⬅️ Zurück zur Add-on-Sammlung](../../README.md)
