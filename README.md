# Pneumatiklabbet

Simulator för tryckluftskretsar som körs direkt i webbläsaren, även på mobilen. Bygg kretsar med regulatorer, strypningar, backventiler, säkerhetsventiler, 3/2-, 5/2- och 5/3-ventiler, slangkopplingar och cylindrar, och se tryck och kolvrörelser live.

## Kör

Öppna `index.html` i en webbläsare. Allt ligger i en fil utan byggsteg; typsnitten hämtas från Google Fonts.

För att publicera: slå på GitHub Pages (Settings → Pages → Deploy from branch → `main`, mappen `/`) eller koppla repot till Netlify.

## Innehåll

- **Komponenter:** tryckkälla, tryckregulator (manuell eller automatisk höjdhållning), tryckkärl, ventiler, växel- och tvåtrycksventil, strypventil, backventil, strypbackventil, snabbavluftning, ljuddämpare, säkerhetsventil, manometer, säkerhetszon, T- och korskoppling, skarvnippel, snabbkoppling, kulventil, propp, dubbel- och enkelverkande cylinder.
- **Exempel:** pendlande cylinder, enkelverkande med knapp, tryckkärl och 5/3-ventil, luftfjäder med vikt, T-koppling till båda sidor med säkerhetszon, tvåhandsmanöver.
- **Fysik:** luftmängd och volym per slangnät, flöde enligt förenklad ISO 6358, kolvkrafter med last, friktion och fjäder. Tryck visas som övertryck i bar. Modellen är förenklad och passar för att lära sig och jämföra, inte för exakt dimensionering.

Kretsen sparas automatiskt i webbläsarens lokala lagring.
