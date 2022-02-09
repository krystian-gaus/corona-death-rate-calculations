# Sources

**deaths_per_day**
- source:
    - *Gesamtübersicht der pro Tag ans RKI übermittelten Fälle und Todesfälle, Stand: 4.2.2022*
    - https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Daten/Fallzahlen_Gesamtuebersicht.html
- composed of:
    - date = Berichtsdatum
    - deaths = Differenz Vortag Todesfälle

---

**infections_hospitalizations_deaths_per_week**
- source:
    - *Anzahl Infektionen mit dem Coronavirus (COVID-19), Hospitalisierungen und Todesfälle\* in Deutschland nach Meldewoche(Stand: 2. Februar 2022)*
    - https://de.statista.com/statistik/daten/studie/1190592/umfrage/coronainfektionen-und-hospitalisierte-faelle-in-deutschland-nach-meldewoche/#professional
- composed of:
    - week = Merkmal
    - infections = Gemeldete Infektionen
    - hospitalizations = Hospitalisierte Fälle
    - deaths = Todesfälle
- calculations:
    - hospitalization_rate = hospitalizations / infections
    - death_rate = deaths / infections
    - hospitalization_death_rate = deaths / hospitalizations

---

**zeitreihe-deutschland**
- source:
    - *Daten zu den Zeitreihen: COVID-ITS-Fälle, ITS-Kapazitäten, Betriebssituation, Anzahl Meldebereiche, Erstaufnahmen, Betriebseinschränkungsgründe*
        - Aggregationsebene: Deutschland
        - Behandlungsgruppe(n): Kinder; Erwachsene
        - Letzte Änderung: 06.02.2022 12:34 Uhr
    - direct link to download: https://diviexchange.blob.core.windows.net/%24web/zeitreihe-deutschland.csv
    - https://www.intensivregister.de/#/aktuelle-lage/downloads
