# CLI-konkurranse – Deal Day

Velkommen til **CLI-konkurranse** 🎯  
Målet er å bruke kommandolinja til å løyse små oppgåver så raskt og presist som mogleg.

Alle oppgåvene tek utgangspunkt i filene i dette repoet.

## Oppsett

1. Klon repoet og gå inn i katalogen:

   ```bash
   git clone <url-til-dette-repoet>
   cd cli-konkurranse
   ```

2. Forutsetningar:
   - Unix-shell (macOS eller Linux)
   - Vanlege CLI-verktøy: `grep`, `find`, `wc`, `sort`, `uniq`, `tar`, `ps`, `chmod`
   - For oppgåve 14:  
     - `jq` **eller**
     - `python` med `python -m json.tool`

Alle oppgåvene er tenkte løyste frå **rotkatalogen i repoet**.

---

## Oppgåver

### Oppgåve 1: Finn filen
I katalogen `finn-filen/` ligg det fleire tekstfiler.  
**Éi** av filene inneheld ordet `tulipan`.

**Finn filnamnet** på fila som inneheld `tulipan`.

---

### Oppgåve 2: Komprimer katalogen
Lag ein komprimert fil **`rapport.tar.gz`** som inneheld katalogen `rapport/`.

---

### Oppgåve 3: Tell linjer
Tell kor mange **linjer** det er i `data.txt`.

---

### Oppgåve 4: Sorter og fjern duplikatar
Sorter alfabetisk og fjern duplikatar frå `navn.txt`.

---

### Oppgåve 5: Kven brukar mest memory?
Vis dei tre prosessane som brukar mest minne.

---

### Oppgåve 6: Tell forekomster
Tell kor mange gonger `error` opptrer i `logs/system.log` (case-insensitive).

---

### Oppgåve 7: Finn største fil
Finn kva fil i `logs/` som er størst.

---

### Oppgåve 8: Vis kun fjerde kolonne
Vis berre kolonne 4 frå `sales.csv`.

---

### Oppgåve 9: Tell filer rekursivt
Tell kor mange filer (`-type f`) som finst under `src/`.

---

### Oppgåve 10: Endre rettigheiter
Endre slik at `secret.txt` berre kan lesast og skrivast av eigaren.

---

### Oppgåve 11: JSON-prettyprint
Pretty-print `data.json` (på éi linje) med `jq` eller `python -m json.tool`.

---
