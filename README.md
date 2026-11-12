# 🙌 Diada Castellera del Càlcul Mental (1vs1)

Aplicació web educativa interactiva dissenyada especialment per a **pantalles digitals tàctils d'aula (PDI / Panells Interactius)** en format horitzontal. 

Dos alumnes s'enfronten en una batalla de càlcul mental simultània (1vs1). Cada operació resolta correctament fa pujar un pis del seu castell humà a la plaça central (pinya, tronc, dosos, acotxador) fins que l'enxaneta corona el castell fent **l'aleta**!

---

## ✨ Característiques principals

* **Optimitzada per a pantalles tàctils en horitzontal:** Interfície dividida en tres zones (Colla Blava, Plaça Major i Colla Vermella) amb teclats numèrics grans i resposta multitàctil simultània.
* **Botó de Pantalla Completa:** Permet aprofitar el 100% de la superfície del panell digital de l'aula amb un sol toc.
* **Temàtica Castellera:** Visualització progressiva de la construcció del castell amb efectes sonors inspirats en el *Toc de Castells* (activables/desactivables).
* **Panell de Configuració Docent:**
  * **Tipus d'operacions:** Sumes (`+`), Restes (`−`) i Multiplicacions (`×`), combinables entre si.
  * **Nivells de dificultat:** 1 xifra, 2 i 1 xifra, 2 xifres o 3 xifres.
  * **Alçada del castell:** Castell de 6, 8 o 10 pisos (nombre d'encerts per guanyar).
  * **Validació automàtica:** Opció per validar la resposta automàticament en teclejar les xifres correctes sense haver de prémer `OK`.
* **Zero dependències complexes:** Tot el codi està contingut en un únic fitxer HTML (utilitza Tailwind CSS via CDN), sense necessitat de servidors ni instal·lacions.

---

## 🚀 Com utilitzar l'aplicació

Pots fer servir l'aplicació de dues maneres molt senzilles:

### Opció 1: En línia a través de GitHub Pages (Recomanat)
1. Accedeix directament a l'enllaç de GitHub Pages del projecte:
   (https://bmarquil.github.io/CalculMentalCasteller/)
2. Prem el botó **"Pantalla Completa"** a la cantonada superior dreta de la pantalla digital de l'aula.

### Opció 2: En local (sense connexió a internet o des de l'ordinador de l'aula)
1. Descarrega el fitxer `batalla_calcul_mental.html` (o clona aquest repositori).
2. Fes doble clic sobre el fitxer per obrir-lo amb qualsevol navegador web modern (Chrome, Edge, Firefox, Safari).

---

## 🛠️ Per a docents i desenvolupadors

Si vols fer un *fork* o allotjar-ho al teu propi compte de GitHub:
1. Puja el fitxer HTML al teu repositori (pots reanomenar-lo a `index.html` perquè carregui directament a l'arrel).
2. Ves a **Settings > Pages** del teu repositori.
3. A **Source**, selecciona la branca `main` i desa els canvis. En pocs segons tindràs l'enllaç actiu.

---

## 📄 Llicència

Aquest projecte està distribuït sota la **Llicència MIT**. Pots consultar-ne els detalls a continuació:

```text
MIT License

Copyright (c) 2026 @bmarquil

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
