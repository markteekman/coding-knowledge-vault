Ik heb het verschil geleerd tussen `localStorage`/`sessionStorage`, `Cookies` en `IndexedDB`. In feite voor wat simpele dingen gebruik je over het algemeen localStorage, voor dingen die ook naar een server moeten worden verstuurd `Cookies` en voor een complexe applicatie die ook offline moet kunnen werken (Google Sheets bijv.) `IndexedDB`. Let wel, al deze data methoden zijn gemakkelijk te beïnvloeden via de console door gebruikers. Persistente data, data die gedeeld moet kunnen worden of gevoelige data doe je dus beter via een database op een server.