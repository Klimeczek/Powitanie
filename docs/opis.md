# Opisy pojęć Androida

**setContentView** – ustawia, jaki layout XML ma być wyświetlony na ekranie.

**findViewById** – znajduje element (np. przycisk) po jego id, żeby móc go użyć w kodzie Javy.

**R** – klasa, przez którą odwołujesz się do layoutów i id z zasobów (np. R.layout.activity_main).

**onCreate** – metoda, którą system wywołuje przy starcie ekranu – tu przygotowujesz wszystko.

**super.onCreate** – wywołanie metody z klasy nadrzędnej; bez tego aplikacja nie wystartuje.

**AndroidManifest.xml** – plik z podstawowymi informacjami o aplikacji (metryczka).

**@+id/** – nadaje elementowi unikalne id w layoutcie (znak + tworzy nowe id).

**match_parent** – element zajmuje całą dostępną przestrzeń rodzica (zwykle cały ekran).

**dp** – jednostka rozmiaru niezależna od gęstości ekranu – wygląda tak samo na każdym telefonie.

**sp** – jednostka rozmiaru tekstu, która dodatkowo dostosowuje się do ustawień czcionki użytkownika.