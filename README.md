# MEME//TERMINAL

Terminale memecoin Solana / pump.fun, solo lettura. Single-page statica (HTML/CSS/JS vanilla).
Dati live da DexScreener, GeckoTerminal e RugCheck (chiamate dal browser). Nessuna chiave, nessun wallet, nessun trade.
Non è consulenza finanziaria.

## v4.0 (01/11/2026)
- Pannello **Punteggio 0–100** calcolato nel browser con le stesse regole dello scanner (v4.0-2026-11-01): sotto-punteggi sicurezza 30% · holder 25% · dev 20% · mercato 15% · social 10%, motivi e cap.
  Fonti: DexScreener, GeckoTerminal (drawdown 72h), report completo RugCheck (CORS aperto).
- Non calcolabile nel browser (serve RPC Solana o API senza CORS): bundle/snipe primi slot, cluster wallet freschi, collegamenti holder, storia/finanziatore dev, narrativo X. Per i token analizzati dallo scanner il terminale mostra il punteggio e i collegamenti holder dello snapshot.
- Wallet watch: tabella delle uscite (vendite/chiusure) dei wallet seguiti; snapshot aggiornato ai run v4.0.
- Versione pubblica degli audit senza importi o posizioni personali.
