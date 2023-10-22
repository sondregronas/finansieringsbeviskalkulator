# Finansieringsbeviskalkulator

[![GitHub Pages](https://badgen.net/badge/visit/github%20pages/?icon=chrome)](https://sondregronas.github.io/finansieringsbeviskalkulator/)
[![License](https://img.shields.io/github/license/sondregronas/finansieringsbeviskalkulator)](https://github.com/sondregronas/finansieringsbeviskalkulator/blob/main/LICENSE)

En enkel kalkulator som beregner hvor mye du kan låne i boliglån, basert på inntekt og gjeld. Dette er en mer pessimistisk / realistisk versjon av kalkulatorene du finner på de fleste banker sine nettsider.

Mange banker har en forenklet kalkulator ofte er langt mer optimistisk enn hva banken faktisk vil gi deg i lån. Denne kalkulatoren er basert på mange av de samme reglene som bankene bruker, og vil gi deg et mer realistisk bilde av hvor mye du kan låne.

## Hovedforskjellene

Kalkulatoren tar for seg følgende forskjeller fra de fleste bankers kalkulatorer:

- Den tar hensyn til skattepliktig egenkapital, som f.eks. aksjer og fond. Dette er ikke 1:1 med egenkapital i bolig, og bankene
  vil derfor ikke gi deg lån for hele beløpet.
- Den tar hensyn for sikkerhetsbuffer og avgifter knyttet til salg av bolig med tanke på hvor mye som utgjør egenkapital.
- Den tar hensyn til at du ikke kan låne mer enn 5 ganger inntekt.
- Den inkluderer 2.5% dokumentasjonsavgift i beregningen av hvor mye du kan låne, dette er en avgift som kommer i tillegg til
  kjøpesummen og som du må betale selv. (Krav om 15% egenkapital er derfor i realiteten 17.5%)

## Feil og mangler

Jeg kan ikke garantere at metodene som blir brukt er identiske hos de fleste banker, men den er basert på dialog med flere banker og litt research på nettet. Den tar ikke hensyn til alt, men det er en god start for å få et bilde av hvor mye du kan låne uten å bli møtt med optimistiske tall som ikke stemmer med virkeligheten.

Jeg er ikke økonom, og jeg kan ikke garantere at denne kalkulatoren er 100% korrekt. Dette er kun laget for gøy, og ikke ment som en fasit.
