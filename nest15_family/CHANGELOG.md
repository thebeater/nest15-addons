# 0.2.29

- Aufwecken setzt zunächst die bestehende Companion-Oberfläche fort. Mehrere Bewegungs-/Präsenzmeldungen öffnen nicht mehr unmittelbar nacheinander neue WebViews. Nur bei ausbleibender frischer Rückmeldung wird nach 15 Sekunden gezielt geöffnet; höchstens zwei automatische Versuche mit mindestens einer Minute Abstand.
- Präsenz in der Küche hat Vorrang vor Flurbewegung. Eine belegte Küche behält ihre Ansicht; Flurbewegung darf das Display weiterhin wecken. Beim Verlassen der Küche bleibt der Wechsel zu Ruhe erhalten.
- Maggy erhält in der oberen Leiste Status, Akku-/Fehleranzeige und Start/Fortsetzen, Pause, Station sowie native HA-Raumauswahl. Raumreinigung erfordert gültige Kartensegmente und die Zuordnung zu HA-Räumen.
- Im Fotobildschirmschoner blättern dezente Ecktasten vor/zurück, ohne Ruhe zu verlassen. „Einrichten“ zeigt die von HA gelieferten verfügbaren Fotos.
- Die vorgelagerte Einschränkung gemischter iCloud-Alben ist als eigener geprüfter HA-/PyiCloud-Patchsatz vorbereitet. Dieses NEST15-Update installiert keinen HA-Core-/SDK-Patch; die vollständige Fotoquelle benötigt diese separate Bereitstellung und reale Abnahme.

Bekannter Bestandsbefund: drei konservative Worst-Case-Kontrastprüfungen am Musikdock im hellen Alpensee bleiben unter dem Zielwert. Die unveränderte Gestaltung und der dokumentierte Befund werden im Releaseworkflow ausdrücklich bestätigt; neue Abweichungen blockieren die CI.

Vor dem Update App und Daten sichern. Die feste Repository-App `405685bb_nest15_family`, ihre Daten und der vorhandene Starter bleiben erhalten. Quelle und Images bleiben privat. GitHub installiert das Update nicht automatisch auf dem NEST15.
