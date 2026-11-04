# Wyceniarz. Zaplecze stolarni — strona (wyceniarz.pl)

Biuro wycen i ofert dla stolarni. Strona statyczna (HTML + CSS + JS w `index.html` + `polityka-prywatnosci.html`),
bez zależności zewnętrznych (czcionki z własnego serwera) i bez procesu budowania — wystarczy wrzucić katalog na dowolny hosting
(GitHub Pages, home.pl, OVH itp.).

## Struktura

```
index.html              strona główna (treść, style, skrypty)
realizacje.html         pełna galeria, film i historie realizacji K&B
majsterkowicze.html     oferta dla osób robiących meble samodzielnie
formularz-start.html    lista na start współpracy — do wypełnienia w telefonie
formularz-zasady.html   zasady budowy mebli — do wypełnienia w telefonie
regulamin.html, polityka-prywatnosci.html
logo/                   logo Wyceniarza (SVG: czarne, brązowe, białe, na drewnie),
                        favicon-32.png, apple-touch-icon.png
og-image.jpg            podgląd linku w Messengerze / WhatsAppie / Facebooku (1200×630)
lot-kuchnia.mp4/.webm   lot kamery po kuchni z wyspą, 30 s, bez dźwięku
lot-kuchnia-poster.jpg  klatka startowa filmu
kartka.jpg              odręczna wycena do bloku „Kartka vs pakiet”
realizacje/             zdjęcia i rysunki realizacji (pełne + -mini)
rendery/                15 renderów i rysunków z realizacji
pliki/                  do pobrania: oferta PDF, lista na start i zasady (PDF z polami + Word)
fonty/                  Lora, Lato, IBM Plex Mono (woff2, latin + latin-ext)
```

## Publikacja

GitHub Pages z gałęzi `main`, domena `wyceniarz.pl` (plik `CNAME`). Statystyki: GoatCounter
(szuwar700.goatcounter.com). Kontakt na stronie: kontakt@wyceniarz.pl (główny),
wyceniarz@zapleczestolarni.pl (drugi), WhatsApp 510 864 253.
Ceny są w `index.html` (sekcja Cennik) i w `pliki/wyceniarz-oferta.pdf` — zmieniaj oba miejsca.
