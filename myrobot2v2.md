# Min Rbot 2 for WonderKit V2 av MakeKit

Velkommen til programeringen av Min Robot 2 i WonderKit serien fra MakeKit as

## Første testen

Før vi går i gang med programeringen av hele så sjekker vi om lysdiodene er koblet riktig, det er en forkjsel her fra Versjon 1, Nå bruker vi P2 i stedet for P0 for å slå de av og på, så her kommer testen

```blocks
input.onButtonPressed(Button.A, function () {
    pins.digitalWritePin(DigitalPin.P2, 1)
})
input.onButtonPressed(Button.B, function () {
    pins.digitalWritePin(DigitalPin.P2, 0)
})
```
Her bruker vi knapp a for å slå på "Øynene", forsikre deg om at begge LED lysdiodene lyser.

### Fungerte det?

Når dette fungerer kan vi gå videre.

## Oppgaven vår

I denne oppgaven skal vi få roboten til å vinke og blunke med øynene, når det blir for lyst eller for mørkt, bruker du en micro:bit V2 kan du bytte ut lys med lyd.
(Det er også lurt å legge inn slik at man kan teste, derfor legger vi inn slik at den reagerer på knappe A)





