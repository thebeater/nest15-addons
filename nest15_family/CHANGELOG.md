# 0.2.31

- Hochformatfotos nutzen jetzt die gesamte verfügbare Displayhöhe. Der bisherige vertikale Außenabstand und die hohe Fußzone entfallen.
- Passende Hochformate werden im gesamten ausgewählten Album zu Zweiergruppen zusammengestellt, auch wenn Querformate dazwischenliegen. Der Fotomodus beginnt bei einem verfügbaren Paar. Jedes Foto bleibt genau einmal im Umlauf.
- Eine ruhige rechte Informationsleiste nutzt den freien Platz neben Hochformaten für Uhr, Termine, Timer, Musik und beide Fotopfeile. Einzelfotos werden im übrigen Bildbereich zentriert. Bei bildfüllenden Querformaten öffnet „Uhr · Info“ die Informationen; Timer- und Musikstatus bleiben am Öffner erkennbar.
- Die Formaterkennung liest begrenzte Bildheader mit höchstens drei parallelen Anfragen und speichert nur einen begrenzten privaten Metadaten-Cache. Sie lädt das Album nicht vorab als große Browserbilder.
- Langsame Partner haben dieselbe Ladefrist wie das erste Foto. Fehler ändern den Albumplan nicht; ein Foto kann erneut geladen werden. Nachtansicht, Übergänge und Pause bei unsichtbarem Display bleiben erhalten.
- Albumquelle, Wechselintervall, App-Kennung und vorhandener Android-Starter bleiben erhalten.

Bekannter Bestandsbefund: drei konservative Worst-Case-Kontrastprüfungen am Musikdock im hellen Alpensee bleiben unter dem Zielwert. Die unveränderte Gestaltung und der dokumentierte Befund werden im Releaseworkflow ausdrücklich bestätigt; neue Abweichungen blockieren die CI.

Vor dem Update App und Daten sichern. Die feste Repository-App `405685bb_nest15_family`, ihre Daten und der vorhandene Starter bleiben erhalten. Quelle und Images bleiben privat. GitHub installiert das Update nicht automatisch auf dem NEST15.
