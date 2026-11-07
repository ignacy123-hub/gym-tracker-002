# Gym Tracker – instalacja z GitHuba

Aplikacja działa jako PWA: hostujesz ją za darmo na GitHub Pages, a na telefonie dodajesz do ekranu głównego.

## 1. Wrzuć na GitHub Pages
1. Wejdź na github.com, kliknij **New repository**, nazwij np. `gym-tracker`, zostaw **Public**.
2. Kliknij **uploading an existing file** i przeciągnij WSZYSTKIE pliki z tego folderu (także ukryty `.nojekyll`). `index.html` musi być w głównym katalogu repozytorium, nie w podfolderze.
3. Kliknij **Commit changes**.
4. Wejdź w **Settings → Pages**. W sekcji *Build and deployment* wybierz **Deploy from a branch**, branch **main**, folder **/ (root)**, kliknij **Save**.
5. Po 1–2 minutach adres pojawi się na górze strony: `https://TWOJA-NAZWA.github.io/gym-tracker/`.

## 2. Zainstaluj na telefonie
- **iPhone (Safari)**: otwórz adres, stuknij **Udostępnij**, potem **Dodaj do ekranu początkowego**.
- **Android (Chrome)**: otwórz adres, menu ⋮, **Zainstaluj aplikację**. W aplikacji jest też pozycja *Więcej → Zainstaluj aplikację*.

Po pierwszym otwarciu działa offline.

## Aktualizacja
Wgraj nowe pliki do repozytorium (nadpisz stare). Telefon pobierze nową wersję przy następnym otwarciu z internetem. Jeśli nie, zamknij aplikację całkiem i otwórz ponownie.

## Dane i Coach AI
- Dane treningowe są w pamięci przeglądarki na telefonie. Rób kopię w *Ustawienia*. Zainstalowana aplikacja i strona w przeglądarce mają osobne dane, więc przenieś je przez kopię.
- Klucz API do Coacha wpisujesz w aplikacji (*Coach → Połączenie z AI*). Nie wrzucaj go na GitHuba.
