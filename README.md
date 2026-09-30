## Installazione

1. Copia il contenuto di `Aniimo_Data` dentro la `Aniimo_Data` del gioco (sovrascrivendo).
   **Non toccare** `LuaScripts.xdt` e `LuaCacheVer.txt`: devono restare quelli del gioco.
2. Nel gioco seleziona la lingua che appare come **"Indonesia"** (viene sovrascritta la lingua Indonesiana con Italiano).
3. Al primo avvio dopo l'installazione il gioco può ricostruire la sua cache e
   mostrare ancora il testo originale: **riavvia il gioco una seconda volta**.
   
## Contenuto

- `Aniimo_Data/cvs/res/lua/LuaScripts.xdf` — xdf del gioco con la coppia id_ID italiana,
  riscritto preservando il layout originale (le entry non toccate sono byte-identiche);
  **non include** `LuaScripts.xdt`/`LuaCacheVer.txt`: vanno lasciati quelli del gioco,
- `Aniimo_Data/cvs/res/lua/LuaScripts/Data/I18N/` — bin sparso per ogni lingua (15):
  l'italiano tradotto, le altre identiche allo xdf della patch (set autoconsistente:
  tutte le lingue funzionano su qualunque installazione)

**La patch è legata alla versione del gioco da cui è stata generata**:
dopo un aggiornamento del gioco, rigenerarla (Estrai → Allinea → Build).
