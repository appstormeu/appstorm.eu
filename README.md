# appstorm.eu

Strona firmowa AppStorm (statyczny HTML, GitHub Pages, domena w pliku `CNAME`).

- `index.html` i `en.html` – strona główna po polsku i po angielsku (wspólny styl – zmiany w `<style>` przenieś do obu plików)
- `weekend-w-regionie/index.html` i `weekend-w-regionie/en.html` – strona aplikacji „Weekend w regionie” po polsku i po angielsku (wspólny styl – zmiany w `<style>` przenieś do obu plików; zrzuty z sufiksem `-en` są z angielskiego interfejsu). Linki do Google Play mają oznaczenie kampanii (`utm_source=appstorm.eu`, `utm_campaign=strona-aplikacji`, `strona-glowna`, z `-en` w wersji angielskiej) – Play Console pokazuje instalacje według źródła
- `weekend-w-regionie/11-listopada.html` i `jesienne-weekendy.html` – strona promocyjna z miejscami w każdym województwie i jej wariant bez nawiązania do święta; generuje je `tools/promo/11-listopada/strona.ps1` z repozytorium aplikacji (nie edytuj ręcznie). Wariant „jesienne weekendy” nie jest podlinkowany ani w `sitemap.xml`
- `sitemap.xml` i `robots.txt` – dla Google Search Console (usługa domeny appstorm.eu); nową stronę dopisz do `sitemap.xml`
- `weekend-w-regionie/polityka-prywatnosci.html` – polityka prywatności aplikacji „Weekend w regionie”; źródłem jest `site/privacy-policy.html` w repozytorium aplikacji, po zmianie skopiuj plik tutaj
- `assets/` – logo, zrzuty ekranu, czcionka Open Sans (bez zewnętrznych zasobów, bez ciasteczek i analityki)
