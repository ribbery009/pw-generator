# Lakáskassza

Közös költségkövető az új lakásra, két főre.

- Tételenkénti rögzítés: megnevezés, összeg (Ft), dátum, ki fizette, fizetési mód (utánvét, utalás, bankkártya), kategória, megjegyzés.
- Összesítés: ki mennyit költött, fizetési módonkénti és kategóriánkénti bontás.
- Egyenleg: minden tétel közös, fele-fele arányban számolva. Az oldal kiírja, kinek mennyit kell utalnia a másiknak.
- Egymásnak utalt összegek külön fülön rögzíthetők, és az egyenleg ezekkel együtt számol.

## Használat

Az `index.html` a claude.ai-on közzétett Artifact forrása. Ott a tételek közös adatbázisba mentődnek, így mindketten ugyanazt látjátok.

Ha a fájlt közvetlenül böngészőben nyitod meg, helyi módban működik: az adatok csak abban a böngészőben mentődnek (localStorage).
