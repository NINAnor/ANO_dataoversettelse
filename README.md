# ANO_dataoversettelse
Oversettelse av ANO NiN kartleggingsenheter fra versjon 2.3 til 3.0.

# Oversettelse

ANO oversettes fra NiN 2.3 hovedtype og kartleggingsenhet 1:5000 til NiN 3.0 hovedtype, kartleggingsenhet 1:20 000 og kartleggingsenhet 1:5000.
For å oversette dataene brukes Vedlegg 6 i Halvorsen (2025) og Artsdatabankens kodebase API (https://nin-kode-api.artsdatabanken.no/swagger/index.html).

Dataene oversettes i X steg:
1) NiN 2.3 oversettes til NiN 2.3 grunntyper.
2) NiN 2.3 grunntyper oversettes til NiN 3.0 grunntyper vha Vedlegg 6 i Halvorsen (2025).
3) NiN 3.0 grunntyper oversettes til NiN 3.0 hovedtyper, kartleggingsenhet 1:20 000 og kartleggingsenhet 1:5000 vha Artsdatabankens kodebase API.


# Vurdering av usikkerhet

Det er ikke et 1:1 forhold mellom NiN 2.3 og NiN 3.0. (hvordan kvantifisere usikkerhet)

# Referanser
* Halvorsen, R. 2025. Oversettelse mellom natursystem-typesystemene i NiN (Natur i Norge) versjonene 2.0 (2015), 2.1 (2016), 2.3 (2021) og 3.0 (2023). ‒ Natur i Norge Systemdokumentasjon 2: 1-232.
