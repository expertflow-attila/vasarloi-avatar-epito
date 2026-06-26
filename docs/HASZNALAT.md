# Használati útmutató — 3 mód

A rendszert háromféleképpen használhatod, attól függően, milyen eszközöd van. Mindhárom ugyanazt
a 9-részes avatart építi fel — a különbség csak a kényelem.

---

## 1. mód — Bármelyik chatbot (ChatGPT / Claude / Gemini) — *a legegyszerűbb*

1. Nyiss egy **új beszélgetést**.
2. Másold be a teljes [`prompts/avatar-epito-prompt.md`](../prompts/avatar-epito-prompt.md) tartalmát (a kódblokk részt).
3. Küldd el. Az AI köszön, és felteszi az első kérdést.
4. **Válaszolj egyesével.** Ne siess — minél konkrétabb vagy, annál jobb az avatar.
5. A végén az AI legenerálja a teljes dokumentumot. Másold ki és mentsd el (pl. Google Docs / Word).

> Új avatarhoz → **új beszélgetés**, hogy ne keveredjenek.

---

## 2. mód — Claude Code (agent) — *ha fejlesztői eszközt használsz*

1. Klónozd a repót, és nyisd meg Claude Code-ban.
2. Hívd az **`avatar-epito`** agentet (pl.: „építsünk egy vásárlói avatart").
3. Végigkérdez, majd a kész avatart **fájlba menti** az `avatarok/` mappába.
4. Bónusz: kérd meg, hogy az elkészült avatarból csináljon egy **reviewer-subagentet** is.

---

## 3. mód — Kézzel, papíron — *AI nélkül is működik*

1. Nyisd meg a [`docs/SABLON.md`](SABLON.md)-et.
2. Menj végig a [`docs/INTERJU.md`](INTERJU.md) kérdésein, és írd be a válaszokat a sablon mezőibe.
3. A vezérlő kérdések segítenek, ha elakadsz.

---

## A marketinged tesztelése a kész avatarokkal (Claude Code)

A `.claude/agents/` mappában 5 **reviewer-avatar** van. Mindegyik egy-egy vevőtípus fejével gondolkodik.

1. Hívd a megfelelő reviewert (pl. `avatar-roi-hajtos-ecom`).
2. Adj neki egy marketinganyagot — beillesztett szöveget, vagy egy kép/landing elérési utat (Read-eli).
3. Visszaad **7 pontot**: scroll-stop, relevancia, érthetőség, első kifogás, hitelesség, cselekvési szándék, „egy mondat, ami megfogna".
4. Futtasd több avataron → összehasonlítod, **kinél üt** az anyag és **kinél nem**.

> Tipp: készíts a saját avatarjaidból is reviewer-agenteket (az építő agent ezt felajánlja), és a saját
> célközönségeden teszteld a kreatívjaidat, mielőtt pénzt költesz rájuk.

---

## Gyakori hibák, amiket ez a rendszer kiszűr

- **Túl általános** („30–50 éves nők") → a sablon egyetlen élő emberre kényszerít.
- **A vevő nyelvének hiánya** → a VII/4 rész szó szerinti idézeteket követel.
- **Csak a fájdalom** → a rendszer a döntési mechanizmust és a kiváltó eseményt is feltérképezi.
- **Mindenki a célközönség** → a VIII. rész (anti-avatar) kimondja, kinek NE adj el.
