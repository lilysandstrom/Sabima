# Sabima
Ideer og kodeukast som kan være nyttige for Sabima og evt. medlemsorganisasjonene som jeg er medlem i - Norsk biologforening og Norsk zoologisk forening, og Ung-satsningene.

For Kalender-nettside-skrape-programmet:

- Justeringer/Customisation: Man må desverre tilpasse "parsing logikken" (som klassenavn) basert på strukturen til HTML-en for hvert nettsted du skraper. Bruk utviklerverktøy i nettleseren (browser developer tools - feks. høyreklikk -> Inspect) for å finne de riktige klassene eller ID-ene å skrape.

- Script-scheduling: man kan planlegge å kjøre skriptet med jevne mellomrom ved bruke av feks "cron" i Unix/Linux eller Task Scheduler i Windows. Men pass på å sette oppdaterings frekvens "sjeldent" nok til at det ikke overbelaster servere.

- Robots.txt: Sjekk gjerne robots.txt-filen til et nettsted før du begynner å skrape, for å sikre at du har tillatelse til å skrape innholdet der.
