# 🛠️ Minecraft Bedrock Batch Installer / Uninstaller

**Ganze Minecraft-Bedrock-Add-on-Sammlungen auf einmal installieren – und mehrere Packs ebenso bequem wieder entfernen.**

Beide Programme sind **keine Minecraft-Packs**. Die ZIP-Dateien werden unter Windows entpackt und über die enthaltene `.cmd`-Startdatei ausgeführt.

## 🚀 Der entscheidende Vorteil gegenüber Minecraft Bedrock

Während Minecraft Bedrock Add-on-Dateien normalerweise **einzeln importiert**, erledigt der **Bulk-Installer die Installation einer gesamten Paket-Sammlung in einem einzigen Durchlauf**. Du legst die `.mcpack`-, `.mcaddon`- und `.zip`-Dateien gemeinsam in einen Ordner. Der Installer durchsucht die Archive, erkennt die enthaltenen Behavior- und Resource-Packs, prüft Versionen und Abhängigkeiten und verarbeitet sie anhand eines gemeinsamen Installationsplans.

Der **Bulk-Uninstaller** ist das Gegenstück: Du kannst **mehrere oder alle erkannten Packs in einem Durchgang zur Deinstallation auswählen**. Auf Wunsch werden auch ihre Zuordnungen zu Welten bereinigt – statt jede Installation einzeln aufräumen zu müssen.

**Kurz gesagt: Eine Sammlung hinein, ein Installationsdurchlauf. Mehrere Packs auswählen, ein Deinstallationsdurchlauf.** Besonders praktisch für größere Modpacks, Testinstallationen und häufig wechselnde Add-on-Zusammenstellungen.

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
