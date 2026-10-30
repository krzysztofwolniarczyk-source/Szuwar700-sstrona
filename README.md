# Wyceniarz. Zaplecze stolarni — strona (wyceniarz.pl)

Biuro wycen i ofert dla stolarni. Strona statyczna (HTML + CSS + JS w `index.html` + `polityka-prywatnosci.html`),
bez zależności zewnętrznych (czcionki z własnego serwera) i bez procesu budowania — wystarczy wrzucić katalog na dowolny hosting
(GitHub Pages, home.pl, OVH itp.).

## Struktura

```
index.html        strona (treść, style, skrypty)
og-image.jpg      podgląd linku w Messengerze / WhatsAppie / Facebooku (1200×630)
lot-jonkowo.mp4   lot kamery po kuchni Jonkowo, 30 s, H.264 bez dźwięku (4,3 MB)
lot-jonkowo.webm  to samo w VP9 (3,0 MB) — przeglądarka bierze lżejszy plik
lot-jonkowo-poster.jpg  klatka startowa filmu
kartka.jpg        odręczna wycena do bloku „Kartka vs pakiet”
realizacje/       pary projekt–wykonanie (render + zdjęcie po montażu)
pliki/            PDF: oferta i karta pytań technicznych
fonty/            Lora, Lato, IBM Plex Mono (woff2, latin + latin-ext)
polityka-prywatnosci.html
rendery/          15 renderów i rysunków z realizacji
  render-NN.jpg        pełny rozmiar (lightbox)
  render-NN-mini.jpg   miniatura (galeria)
  rysunek-NN(.jpg|-mini.jpg)
  manifest.json        lista plików z opisami
```

## Publikacja na zapleczestolarni.pl

Wgraj całą zawartość repo (bez `.git`, `README.md`) do `public_html` na hostingu albo
podepnij domenę pod GitHub Pages (plik `CNAME` z treścią `zapleczestolarni.pl` + rekordy DNS).
`canonical`, `og:url`, `robots.txt` i `sitemap.xml` wskazują już na https://wyceniarz.pl/.

Przed startem (z pakietu z 30.10.2026): odwiesić firmę w CEIDG, sprawdzić PKD 74.10,
zwolnienie z VAT, skrzynkę wyceniarz@zapleczestolarni.pl i WhatsApp na 510 864 253.
Ceny są w `index.html` (sekcja Cennik) i w `pliki/wyceniarz-oferta.pdf` — zmieniaj oba miejsca.
