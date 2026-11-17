# PokéRole – Schede (Allenatore + Pokémon, GM, INFO)

App separata, in italiano. Il testo del manuale NON è incluso: ogni utente importa il proprio PDF (PokéRole Core Book 3.0, in inglese) dal tab **📚 Manuale**. La lettura avviene sul dispositivo (1–2 minuti) e il catalogo resta nel dispositivo.

## Pubblicare
1. Carica tutto il contenuto di questa cartella in un repo GitHub (incluso `.github`).
2. Actions → "Build APK" produce l'artifact `pokerole-apk`; "Pages" pubblica la WebApp (copia pdf.js in `www/lib`).

## Contenuto
- Scheda Allenatore: attributi, sociali, abilità (limiti per rango), PF/Will/Difesa/Iniziativa/Dolore, status, zaino, obiettivi, squadra.
- Scheda Pokémon: scelta specie dal Pokédex importato, valori base, abilità, mosse per rango con tiri Precisione/Danno (STAB, dolore), felicità/lealtà.
- GM: iniziativa e turni, azioni per round (difficoltà crescente), PF/Will/status, Pokémon selvatici dal Pokédex, dadi d6 (successo 4–6).
- INFO: regole per argomento (effetti secondari, status, meteo, turni, ecc.), Pokédex, Movedex filtrabile, Abilitydex, Nature, ricerca su tutto il manuale.

## Limiti noti
Estrazione automatica da PDF: pochissime mosse possono mancare (852 lette), alcune voci Pokédex hanno altezza/rango suggerito vuoti, i titoli di alcune sezioni possono risultare spezzati. Le mosse di rango sono dedotte dal colore delle icone. Si può sempre aggiungere una mossa personalizzata.
