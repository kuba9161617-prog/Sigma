# Narzędzie Sigmy — darmowy prototyp PWA

## Co potrafi
- działa jako strona, którą można dodać do ekranu początkowego iPhone'a;
- pozwala wybrać wiele zdjęć przez systemowy picker iOS;
- kopiuje gotową instrukcję do ChatGPT i otwiera ChatGPT;
- pozwala wkleić odpowiedzi, rozdzielić je na pozycje i wywołać osobne powiadomienia.

## Ograniczenia (ważne)
- ChatGPT Go nie udostępnia zewnętrznym aplikacjom dostępu do abonamentu ani API.
- Nie ma automatycznego przesyłania zdjęć z tej strony do ChatGPT — zdjęcia trzeba dołączyć ręcznie w ChatGPT.
- iOS nie pozwala stronie samodzielnie przeszukiwać biblioteki zdjęć z ostatnich 5 minut. Wybierasz je ręcznie.
- Powiadomienia webowe wymagają HTTPS, dodania do ekranu początkowego, zgody i iOS 16.4+. Ta wersja nie gwarantuje powiadomień w tle.
- Nie wymaga klucza API ani płatnej integracji.

## Darmowe opublikowanie przez GitHub Pages (z iPhone'a)
1. W Safari zaloguj się na GitHub i utwórz publiczne repozytorium `narzedzie-sigmy`.
2. Dodaj pliki z tego folderu do repozytorium (Add file → Upload files).
3. Otwórz Settings → Pages.
4. W Build and deployment wybierz Deploy from a branch, branch `main`, folder `/ (root)` i zapisz.
5. Gdy GitHub Pages opublikuje stronę, otwórz podany adres w Safari.
6. W Safari wybierz Udostępnij → Dodaj do ekranu początkowego.

## Użycie
1. Wybierz zdjęcia.
2. Naciśnij „Kopiuj instrukcję”.
3. Otwórz ChatGPT, wklej instrukcję i ręcznie dołącz zdjęcia.
4. Skopiuj odpowiedzi i wróć do aplikacji.
5. Wklej odpowiedzi i wybierz „Podziel odpowiedzi”.
6. Użyj powiadomień przy odpowiedziach lub przycisku zbiorczego.

To prototyp pomocniczy, nieoficjalna aplikacja, nie gwarantuje poprawności odpowiedzi AI.
