# URIZ-19: Evidentirati greške pronađene u notifikacijama

## Opis
Ovaj dokument prati evidentiranje grešaka pronađenih tokom testiranja funkcionalnosti notifikacija, na osnovu test case-ova definisanih u URIZ-17.

## Evidentirane greške
- Notifikacija se ne prikazuje uvek pri prekoračenju budžeta (videti URIZ-22)
- Haptic feedback kasni u odnosu na prikaz notifikacije na pojedinim uređajima
- Notifikacija se duplira ako korisnik brzo unese više troškova zaredom

## Tehnologije / alati
- Manuelno testiranje na Android/iOS emulatoru
- GitHub Copilot (analiza koda za obradu notifikacija)

## Status
Zadatak: URIZ-19
Sprint backlog: UniBudget

## Napomena
Greška opisana pod URIZ-22 je direktno povezana sa ovim zadatkom i detaljnije je opisana u posebnom zadatku.
