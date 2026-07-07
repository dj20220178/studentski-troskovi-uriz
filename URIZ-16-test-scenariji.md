# URIZ-16: Definisati test scenarije za notifikacije i vibraciju (haptic feedback)

## Opis
Ovaj dokument definiše test scenarije za funkcionalnost lokalnih notifikacija i haptic feedback-a, u skladu sa funkcionalnim zahtevom FZ14.

## Test scenariji
1. Notifikacija se prikazuje kada potrošnja dostigne definisani procenat budžeta (npr. 80%).
2. Notifikacija se prikazuje kada je budžet premašen (100%+).
3. Haptic feedback se aktivira prilikom prikaza notifikacije.
4. Notifikacija se NE prikazuje ako limit budžeta nije definisan (edge-case).
5. Provera ponašanja kada korisnik nije dao dozvolu (permission) za notifikacije na uređaju.

## Tehnologije / alati
- Expo Notifications API
- GitHub Copilot (predlog edge-case scenarija)
- ChatGPT (strukturiranje test scenarija)

## Status
Zadatak: URIZ-16
Sprint backlog: UniBudget

## Napomena
Scenariji su osnova za generisanje detaljnijih AI test case-ova (videti URIZ-17).
