# Sisu Garmin -laajennuksen lataukset

Tämä julkinen repo sisältää vain jakeluohjeet ja valmiit julkaisut.
Laajennuksen kehitysrepo ja sen Git-historia ovat yksityisiä.

## Asennus

1. Avaa [julkaisut](https://github.com/sieni-io/garmin-extension-releases/releases).
2. Lataa haluamasi version `sisu-garmin-extension-VERSION.zip` ja `metadata.json`.
3. Tarkista ZIPin SHA-256 metadatasta tai julkaisun tiedoista.
4. Pura ZIP pysyvään hakemistoon.
5. Avaa Chromessa `chrome://extensions`, ota Developer mode käyttöön ja valitse
   `Load unpacked` sekä purettu hakemisto.
6. Kirjaudu [Sisuun](https://sieni.io/sisu/), käynnistä paritus laajennuksen
   toimintopainikkeesta ja hyväksy paritus Sisu-webissä.

Garmin Connectin aktiviteettisivun tuontipainike toimii parituksen jälkeen.
Päivitys ja palautus tehdään purkamalla valittu ZIP samaan hakemistoon ja
valitsemalla Chromessa `Reload`. Julkaistuja versioita ei ylikirjoiteta.

ZIP sisältää asennettavan laajennuksen JavaScriptin, CSS:n, manifestin ja ohjeet.
Se ei sisällä käyttäjätietoja tai Sisu-tuontitunnuksia. Julkinen manifestiavain
säilyttää extension ID:n `ddhdopncnngamakicmecidmcpicibhjd`.
