## Oppdatering av vedtekter

Ved oppdatering av vedtektene skal det opprettes en innlemmingsforespørsel for hver enkel vedtektsendring. Dette er til for å kunne diskutere sakene utenfor diskusjonskvelder, og for god sporing av endringer gjennom tidene. Innlemmingsforespørselen skal bruke `Vedtektsendring` templaten som ligger i repoet. Innlemmingsforespørsler skal kun godkjennes etter de er fremmet på generalforsamling, godkjent av forsamlingen, og så godkjent av paraferer.

## Opplasting av vedtekter

**Dette er for eksempel relevant for å sende oppdaterte vedtekter til Brønnøysundsregisteret**

Det er noen prerequisites for å konvertere .adoc til en PDF:

`ruby >=2.5`

Med `ruby >=2.5` må man laste ned noen gems i tillegg. Dersom ruby er lagt til i PATH kan du kjøre følgende kommandoer i terminal:

`gem install asciidoctor`
`gem install asciidoctor-pdf --pre`

PDF kan så genereres ved å kjøre `asciidoctor-pdf vedtekter.adoc`.
