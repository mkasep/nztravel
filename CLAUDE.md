# nztravel

Interaktiivne reisikava (Uus-Meremaa lõunasaar + Melbourne, 12.11–01.12.2026), avaldatud GitHub Pages'is: https://mkasep.github.io/nztravel/

## Töövoog
- Iga kord, kui reisikava muutub (marsruut, ööbimised, broneeringute staatus, lennud, tegevused), uuenda `index.html` andmeid (`DAYS`, `BRON`, `FLIGHTS`, `CHECK`, `PAID`/`DUE`, `SUMMARY` (päeva kokkuvõtte paneel); Ööbimise vahekaart tuleb `DAYS[].night`-ist) ja **push'i kohe `main` harusse** — kasutaja jälgib lehte telefonist.
- Hoia sama info kooskõlas Exceliga kasutaja arvutis: `~/Documents/NZReis/NZ_reisiplaan_2026_v2.xlsx` (ja kaardifailiga `NZ_reisikava_2026.kml`).
- Leht on avalik repo — ära lisa nimesid (kasuta „Mees”, „Naine”, „Laps”), broneeringunumbreid, telefoninumbreid, aadresse ega makseandmeid. Eelarve võib olla.
- Commit'i autor: `mkasep <mkasep@users.noreply.github.com>`; ajalugu on puhastatud, ära lisa isikuandmeid ka commit'i sõnumitesse.
