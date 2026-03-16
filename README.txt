# Energy Resilience Landing Page

Plik jest gotowy do wrzucenia na hosting statyczny.

## Zawartość
- `index.html` — gotowa strona landing page
- `assets/exeliq-logo.webp` — oryginalne logo Exeliq Group

## Jak opublikować
Najprościej:
1. wrzuć cały folder na Vercel / Netlify / własny hosting,
2. ustaw stronę startową na `index.html`,
3. podmień w `index.html` wartość `FORM_ENDPOINT` na prawdziwy webhook lub formularz.

## Gdzie podpiąć formularz
W dolnej części `index.html` znajdziesz:

```js
const FORM_ENDPOINT = "";
```

Tutaj wklejasz endpoint z:
- Formspree
- Make
- Zapier
- Netlify Forms
- własnego backendu / CRM

## Uwaga
W obecnej wersji formularz działa jako demo i pokazuje komunikat sukcesu bez wysyłki danych.
