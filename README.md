# Oppdatering av vedtekter

Ved oppdatering av vedtektene skal det opprettes en pull request for hver enkel vedtektsendring. Dette er til for å kunne diskutere sakene utenfor diskusjonskvelder, og for god sporing av endringer gjennom tidene. Pull requesten skal bruke `Vedtektsendring` templaten som ligger i repoet. Innlemmingsforespørsler skal kun godkjennes etter de er fremmet på generalforsamling, godkjent av forsamlingen, og så godkjent av paraferer.

# Signering av vedtekter

Paraferer godkjenner endringer etter generalforsamling. Dette gjennomføres ved å kommentere en godkjennelse på alle relevante innlemmingsforespørsler.

Ved godkjenning skal det også opprettes en forside for opplasting, i tilfellet vedtektene skal lastes opp for offentlige etater eller liknende. Malen `forside_mal.pdf` signeres av paraferer og lastes opp på formatet `forside_semester_signert.pdf`, eksempelvis `forside_h2022_signert.pdf`.

Kun én signert forside skal ligge i repoet om gangen.

# Opplasting av vedtekter

** Dette er for eksempel relevant for å sende oppdaterte vedtekter til Brønnøysundsregisteret **

Det er noen prerequisites for å konvertere .adoc til en PDF:

`ruby >=2.5`

Det er noen gems i tillegg som kan lastes ned med:

`gem install asciidoctor`
`gem install asciidoctor-pdf --pre`

PDF kan så genereres ved å kjøre `asciidoctor-pdf vedtekter.adoc`.

Slå sammen `forside_semester_signert.pdf` med den genererte `vedtekter.pdf`, så har man signerte vedtekter.
