# Instrukcja obsługi aplikacji

Aby uruchomić naszą aplikacje wymagane są:
1. Komputer z systemem Windows 10
2. Oprogramowanie JAVA minimum w wersji 11. (Do pobrania ze strony [oracle.com](https://www.oracle.com/java/technologies/downloads/#jdk17-windows))

> Jeśli po zainstalowaniu Javy i uruchomieniu komendy `java -version` w cmd.exe nie jest widoczna wersja ta, która została zainstalowana należy w `Komputer/właściwości/zaawansowane ustawienia systemu/zmienne środowiskowe` dodać nową zmienną w formacie: `JAVA_HOME` - `ścieżka do lokalizacji folderu bin` (w folderze zainstalowanej javy)

Aby aplikacja działała poprawnie w folderze, gdzie jest PrzychodniaLekarska.jar musi znajdować się dołączona baza danych w formacie .db

Przykładowy fragment struktury katalogu `przychodnia`:
```bash
C:\Users\admin\Desktop\przychodnia
|----images
|    |---1
|        |---zdjecie.png
|        |---zdjecie2.png
|----przychodnia.db
|----PrzychodniaLekarska.jar
```

> Folder `images` generuje się automatycznie podczas tworzenia pierwszego opisu badania.