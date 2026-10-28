# szuwar700 — strona promocyjna (nazwa robocza)

Biuro wycen i ofert dla stolarni. Jednoplikowa strona statyczna (HTML + CSS + JS w `index.html`),
bez zależności i bez procesu budowania — wystarczy wrzucić katalog na dowolny hosting
(GitHub Pages, home.pl, OVH itp.).

## Struktura

```
index.html        strona (treść, style, skrypty)
og-image.jpg      podgląd linku w Messengerze / WhatsAppie / Facebooku (1200×630)
lot-jonkowo.mp4   lot kamery po kuchni Jonkowo, 30 s, H.264 bez dźwięku (4,3 MB)
lot-jonkowo.webm  to samo w VP9 (3,0 MB) — przeglądarka bierze lżejszy plik
lot-jonkowo-poster.jpg  klatka startowa filmu
rendery/          15 renderów i rysunków z realizacji
  render-NN.jpg        pełny rozmiar (lightbox)
  render-NN-mini.jpg   miniatura (galeria)
  rysunek-NN(.jpg|-mini.jpg)
  manifest.json        lista plików z opisami
```

## Do uzupełnienia przed publikacją

- adres e-mail w sekcji „Kontakt” (`biuro@szuwar700.pl` to placeholder),
- nazwa firmy / NIP w stopce i w danych JSON-LD,
- adres `og:url` i `canonical` po wykupieniu domeny,
- ewentualnie docelowa nazwa zamiast „szuwar700”.
