# Porsche Retirement Widget v5

Widget Android z trzema srebrnymi zegarami, przezroczystym tłem i odliczaniem do 07.11.2028.

## Zmiany w v5
- SEKSAPIL: 60% i 40% naprzemiennie w kolejne dni, na wskazówce i wyświetlaczu. Nie wymaga animacji w tle.
- Przywrócona cyfra 50 na lewej tarczy.
- Skala środkowa: 700 dni dokładnie na cyfrze 7, 0 dni na 0, wartości powyżej 700 wychodzą nieco poza 7 (maks. 375 stopni).
- Usunięto część pozostałości po statycznych wskazówkach z bitmapy; retusz należy ocenić na urządzeniu.
- Cały zestaw powiększony o 4,5% bez zmiany proporcji (na bardzo wąskich widgetach brzegi mogą być lekko przycięte).
- `versionCode` zwiększony do 5.

## Budowa APK
GitHub Actions: `.github/workflows/build.yml`. Po wysłaniu plików do repozytorium sprawdź Actions, pobierz artifact APK.

## Uwaga
Zależnie od launchera widget może odświeżać się z opóźnieniem po północy. Android nie gwarantuje dokładnego czasu wybudzenia aplikacji bez dodatkowych uprawnień. Zmiana daty telefonu może wymusić przeliczenie.
