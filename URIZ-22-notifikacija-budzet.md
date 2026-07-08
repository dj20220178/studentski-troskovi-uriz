# URIZ-22: Local notification is not displayed when budget is exceeded

## Opis
Ovaj dokument opisuje konkretnu grešku: lokalna notifikacija se ne prikazuje korisniku kada je definisani budžetski limit premašen.

## Koraci za reprodukciju
1. Korisnik definiše budžetski limit za određenu kategoriju (npr. Hrana).
2. Korisnik unosi trošak koji premašuje definisani limit.
3. Očekivano ponašanje: prikazuje se lokalna notifikacija upozorenja.
4. Stvarno ponašanje: notifikacija se ne prikazuje.

## Moguć uzrok
Greška u izračunavanju procenta iskorišćenosti budžeta kada je limit jednak 0 ili nije definisan (edge-case identifikovan uz pomoć GitHub Copilot-a).

## Predloženo rešenje
Dodati proveru za slučaj limit = 0 pre izračunavanja procenta, i eksplicitno testirati graničnu vrednost od tačno 100% iskorišćenosti.

## Status
Zadatak: URIZ-22
Sprint backlog: UniBudget

## Napomena
Povezano sa zadatkom URIZ-19 (evidentiranje grešaka u notifikacijama).
