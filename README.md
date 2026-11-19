# Været på MC tur

Enkel værapp som viser helgevarsel (fredag–søndag) for 14 steder langs
sørlandskysten, fra Stavanger til Solsetra.

- Én enkelt `index.html` — ingen byggesteg, kun Bootstrap via CDN
- Værdata fra [Yr / MET Norway Locationforecast](https://developer.yr.no/)
  (kompakt format, ingen API-nøkkel — kun `User-Agent`)
- Nedbør vises for tidsrommet 09–22 med tidsvindu (f.eks. «1.7 mm kl. 12–18»)
- Værikon fra [metno/weathericons](https://github.com/metno/weathericons)
- Caching som respekterer `Expires` / `If-Modified-Since`, og automatisk
  oppdatering tilpasset prognosesyklusen

## Bruk

Åpne `index.html` i en nettleser. Ingen installasjon nødvendig.

## Datakilde

Værdata fra [Yr](https://www.yr.no/), levert av
[Meteorologisk institutt](https://www.met.no/).
