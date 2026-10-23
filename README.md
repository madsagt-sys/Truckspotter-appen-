# 🚛 TruckSpotter – Collector Edition

Mobilvenlig truckspotter-app med garage, billeder, XP, levels og 103 missioner.

## Udgiv på GitHub Pages

1. Opret et **public** repository på GitHub, fx `truckspotter`.
2. Upload **indholdet af denne mappe** til repositoryets rod (ikke ZIP-filen som én fil). Sørg for at `index.html` ligger i roden.
3. Åbn **Settings → Pages** i repositoryet.
4. Under **Build and deployment** vælger du **Deploy from a branch**.
5. Vælg branch **main**, folder **/(root)**, og tryk **Save**.
6. Efter udgivelse er adressen typisk `https://DIT-BRUGERNAVN.github.io/truckspotter/`.

## Installer på telefon

- **iPhone (Safari):** Åbn linket → Del → Føj til hjemmeskærm.
- **Android (Chrome):** Åbn linket → menuen ⋮ → Installer app / Føj til startskærm.

## Vigtigt om data

- Spots og billeder gemmes **lokalt i browseren på den aktuelle enhed**, ikke på GitHub.
- Brug appens **Eksportér backup** regelmæssigt. Rydning af browserdata kan slette samlingen.
- Hvis appen åbnes på et andet domæne, en anden telefon eller i en anden browser, følger data **ikke automatisk med**. Brug eksport/import.
- Del ikke følsomme oplysninger, nummerplader eller børns præcise placering offentligt. Denne version har ingen offentlig feed eller login.
- Store billeder kan fylde browserlageret. Gem backup løbende.

## Opdatering

Erstat `index.html` med en ny version og upload ændringerne til `main`. Ved større ændringer af offlinefilerne kan cacheversionen i `sw.js` opdateres.

## Lokal test

Åbn `index.html` direkte for en hurtig forhåndsvisning. Installation/offline kræver HTTPS (GitHub Pages) eller localhost.

## Kamera
Under **Nyt spot**: **TAG BILLEDE** åbner kameraet på understøttede telefoner, og **VÆLG FRA GALLERI** vælger et eksisterende foto. Adfærden afhænger af browseren.

## Vognmand / firma
Under Nyt spot vælges firma fra 50 danske transportvirksomheder eller 'Tast selv'. Listen er en blanding af de 20 øverste fra CVRLeads' omsætningsliste og 30 andre navne; den er ikke en verificeret rangliste over de 50 største. Kilde: https://cvrleads.dk/transport-virksomheder og https://www.danskindustri.dk/medlemsforeninger/647/medlemmer .

## Dynamisk firmaliste (v7)
BHC, Sejer og Sønnichsen og Brdr. Nørulf er tilføjet. Firmalisten sorteres efter antal registrerede spots, med alfabetisk sortering ved samme antal. Nye firmaer fra Tast selv gemmes lokalt og føjes automatisk til listen. Ingen cloud-synkronisering.
