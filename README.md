# Vásárlói Avatar Építő 🎯

> Építs **extrém részletes vásárlói avatarokat** AI segítségével — úgy, hogy az AI **végigkérdez** (interjúztat),
> és a válaszaidból megírja a kész, használható avatar-dokumentumot.

A legtöbb „vásárlói avatar" sablon felszínes: kor, nem, „szereti a minőséget". Ez kevés. Ez a rendszer
egyetlen, **élő embert** rajzol ki — akit felismersz az utcán, és tudod, mit mondana —, mert a marketing
csak akkor működik, ha egy konkrét emberhez beszélsz, nem egy kategóriához.

---

## Mit kapsz

| Rész | Mi ez |
|---|---|
| 🧩 **[Sablon](docs/SABLON.md)** | A 9-részes (RÉSZ I–IX), extrém részletes avatar-váz. Minden mezőnél magyarázat + vezérlő kérdés. |
| 🎤 **[Interjú](docs/INTERJU.md)** | A kérdéssor, amivel az AI (vagy te magad) feltérképezed a vevődet — egy kérdés egyszerre. |
| 🤖 **[Építő prompt](prompts/avatar-epito-prompt.md)** | Copy-paste prompt bármelyik AI-ba (ChatGPT, Claude, Gemini): elindítja az interjút és megírja az avatart. |
| 🧠 **[Claude Code agent](.claude/agents/avatar-epito.md)** | Az `avatar-epito` agent: végigkérdez, majd fájlba menti a kész avatart. |
| 📚 **[Példák](peldak/)** | 3 forrásminta + 5 teljes példa-avatar, hogy lásd, milyen mélységet ad a rendszer. |

---

## Hogyan használd — 3 lépés

### 1. Építsd fel az avatart (az AI interjúztat)
Másold be a **[`prompts/avatar-epito-prompt.md`](prompts/avatar-epito-prompt.md)** tartalmát egy új AI-beszélgetésbe
(ChatGPT / Claude / Gemini). Az AI köszön, és **elkezd kérdezni — egyesével**. Csak válaszolj őszintén.
Ha elakadsz, segít. A végén legenerálja a teljes avatar-dokumentumot.

> Claude Code-ban: hívd az **`avatar-epito`** agentet — ugyanezt csinálja, és fájlba is menti.

### 2. Mentsd el a kész avatart
A kapott dokumentumot tedd el (Google Docs / Word / Markdown). Ez lesz minden hirdetésed, landingoldalad
és emailed alapja.

### 3. Építsd meg a többi szegmensed
Több vevőtípusod van? Futtasd újra — **egyszerre egy avatart** építs, hogy mindegyik egy konkrét ember maradjon.
A [példák](peldak/avatarok/) mutatják, milyen mélységet érdemes megcélozni.

---

## Miért működik (a módszer)

A sablon Eugene Schwartz **tudatossági szintjeit**, a **Jobs To Be Done** keretet, az **előtte–utána**
átalakulást, a **közös ellenség** elvét és a **vevői szó szerinti nyelvet** ötvözi. A 9 rész:

```
I.   Ki ő (demográfia, pszichográfia, értékrend, egy napja)
II.  Hol tart a fejében (tudatossági szint, piaci kifinomultság)
III. Mit akar (célok, előtte→utána, Jobs To Be Done)
IV.  Mi fáj neki (fájdalom, közös ellenség, félelmek)
V.   Mit csinál helyetted (alternatívák, kifogások)
VI.  Hogyan dönt (mechanizmus, kiváltó esemény)
VII. Hogyan éred el (csatornák, Dream 100, vevői nyelv)
VIII.Kit NE célozz (anti-avatar)
IX.  Mi a siker neki
```

A kulcs a **VII/4 — a vevő saját szavai**: ezeket szó szerint visszateszed a hirdetéseidbe, és a vevő magára ismer.

---

## Az 5 példa-avatar (demó)

| Avatar | Ki ő | Fő szűrője |
|---|---|---|
| [Túlterhelt Katalin](peldak/avatarok/tulterhelt-katalin.md) | 42, könyvelőiroda-tulaj | bizalom + „ne nekem kelljen" |
| [ROI-hajtós Gábor](peldak/avatarok/roi-hajtos-gabor.md) | 35, webshop-tulaj | konkrét szám, ROAS |
| [Megégett Tamás](peldak/avatarok/megegett-tamas.md) | 48, B2B gyártó ügyvezető | bizonyíték, anti-hype |
| [Brandtudatos Eszter](peldak/avatarok/brandtudatos-eszter.md) | 30, D2C márka alapító | kreatív-minőség, brand-illeszkedés |
| [Lokális József](peldak/avatarok/lokalis-jozsef.md) | 50, helyi étterem/szerviz | egyszerűség, ár-érthetőség |

---

## Licenc

[MIT](LICENSE) — használd szabadon, alakítsd a magad piacára. Ha hasznos volt, egy ⭐ jólesik.
