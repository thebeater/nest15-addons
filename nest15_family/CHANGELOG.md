# 0.2.32

- Die Fotoansicht erhält ein gedämpftes, weiterhin helles Weißgrau. Pfeile und Musiknote erscheinen als kleine Symbole ohne dunkle Kacheln; ihre Touchflächen bleiben mindestens 48 Pixel groß.
- Rechts stehen aktuelles Wetter und die Regenaussicht für die nächsten drei Stunden mit denselben Symbolen und Temperaturen wie in der übrigen NEST15-Oberfläche. Fehlende oder veraltete Daten werden ausdrücklich angezeigt. Die Fotos behalten ihre volle Höhe.
- Präsenz in Flur und Küche weckt ein schlafendes Display in die Ruheansicht. Eine bereits geöffnete Ansicht bleibt bei Präsenzwechseln erhalten; Küchenpräsenz öffnet nicht mehr automatisch Heute.
- Popups schließen nach 20 Sekunden ohne Bedienung. Ungespeicherte Einstellungs- und Artikelentwürfe bleiben beim automatischen Schließen erhalten, solange ihre zugrunde liegenden Daten unverändert sind. Laufende Speicherungen werden vor dem automatischen Schließen abgeschlossen.
- Der Bildschirmschoner startet standardmäßig nach einer Minute ohne Bedienung. Zustands- und Wetteraktualisierungen verlängern die Frist nicht. Die getrennte Abschaltung bei Abwesenheit und der Schutz durch Timer bleiben erhalten.

Bekannter Bestandsbefund: drei konservative Worst-Case-Kontrastprüfungen am Musikdock im hellen Alpensee bleiben unter dem Zielwert. Die unveränderte Gestaltung und der dokumentierte Befund werden im Releaseworkflow ausdrücklich bestätigt; neue Abweichungen blockieren die CI.

Vor dem Update App und Daten sichern. Die feste Repository-App `405685bb_nest15_family`, ihre Daten und der vorhandene Starter bleiben erhalten. Quelle und Images bleiben privat. GitHub installiert das Update nicht automatisch auf dem NEST15.
