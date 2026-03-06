## 📝 Beschreibung der Änderungen
Bitte beschreibe kurz, was du geändert hast und warum. Welches Problem wird gelöst? Welches neue Feature wird hinzugefügt?

## 🛠️ Art der Änderung
- [ ] 🐛 Bugfix (behebt einen Fehler in Hard- oder Software)
- [ ] 💡 Neues Feature (fügt Funktionalität hinzu)
- [ ] 🎨 Refactoring / Dokumentation (keine Code-Änderung)
- [ ] ⚡ Performance-Verbesserung
- [ ] 🚀 Hardware-Optimierung (PCB / BOM)

## ✅ Checkliste
Bevor du den PR abschickst, prüfe bitte folgende Punkte:
- [ ] Mein Code/Layout folgt dem Stil des Projekts.
- [ ] Ich habe meine Änderungen auf der **V1-Hardware live getestet** (falls zutreffend).
- [ ] Die Dokumentation (README/Wiki) wurde entsprechend aktualisiert.
- [ ] Bei Hardware-Änderungen: Die 1,34 mm Leiterbahnbreite für die 5V-Hauptversorgung (3A Peak) sowie die 0,25 mm Clearance an den IC-Pins wurden zwingend eingehalten.
- [ ] Bei Software-Änderungen: Ich habe sichergestellt, dass keine Zugangsdaten im Klartext im Code stehen. Für sensible Parameter wurden stattdessen die `!secret` Variablen (api encryption, ota password, wifi ssid, wifi password und ap password) genutzt.

## 📷 Screenshots / Belege (optional)
Falls du das Platinen-Layout (Routing) geändert oder eine neue Sensorik/Pumpensteuerung implementiert hast, füge hier bitte ein Foto oder einen Screenshot des CAD-Programms bzw. des ESPHome-Dashboards an.

## 🔗 Verknüpfte Issues / Discussions
Gibt es ein bestehendes Issue oder eine Diskussion dazu? (z.B. "Closes #12" oder "Refers to Discussion #5")
