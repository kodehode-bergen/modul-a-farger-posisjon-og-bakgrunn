# 🎨 Modul A - CSS: Farger, Posisjonering og Bakgrunner

Dette prosjektet er laget for å utforske hvordan man kan bruke **farger**, **bakgrunnsbilder**, **sticky navigasjon**, **scrolling**, og ulike posisjoneringsstrategier i CSS. Det kombinerer statiske og dynamiske elementer for å vise hvordan design og brukeropplevelse kan styrkes gjennom bevegelse, fargevalg og struktur.

---

## 🧠 Hva du lærer

✅ Bruk av **bakgrunnsbilder** og `background-attachment: fixed`  
✅ Navigasjonslenker med `scroll-behavior: smooth`  
✅ **Sticky header** som følger med ved scrolling  
✅ Hvordan `rgba()` og `hsl()` gir kontroll over gjennomsiktighet og nyanser  
✅ Bruk av `position: fixed`, `relative`, og `sticky` (kommentert for eksperimentering)  
✅ Effektiv bruk av `vh`, `vw`, `em`, `%`, og `rem` i responsivt design  
✅ Hvordan `conic-gradient()` kan gi kreative bakgrunnsoverganger

---

## 🖼️ Visuell struktur

- `section.bg-img` → store seksjoner med **bakgrunnsbilde** og `background-attachment: fixed`
- `section.bg-color` → innhold med **tekst og fargebakgrunn** lagt i midten
- Sticky `header` og fast `footer` som rammer inn siden
- Scroll-til-top `button` for brukerkomfort

---

## 🎨 Farger brukt

| Fargetype | Eksempel                            | Beskrivelse                            |
|-----------|-------------------------------------|-----------------------------------------|
| `rgba()`  | `rgba(92, 81, 68, 0.674)`           | Halvtransparente bakgrunner på tekst   |
| `hsl()`   | `hsl(313, 85%, 50%)`                | Kreative nyanser og kontraster         |
| `background-image` | `conic-gradient(...)`       | Fargerik bakgrunn på hele `body`       |

---

## 🔗 Navigasjonsoppsett

```html
<ul>
  <li><a href="#section-positioning1">Section 1</a></li>
  <li><a href="#section-positioning3">Section 2</a></li>
  <li><a href="#section-positioning5">Section 3</a></li>
  <li><a href="#section-positioning7">Section 4</a></li>
</ul>
