# C++ Library System 📚

Konsolowy system zarządzania biblioteką. Projekt zrealizowany w ramach przedmiotu **Informatyka (3. semestr)**, służący jako praktyczne wprowadzenie do programowania obiektowego w C++.

## Funkcjonalności
* **System ról:** Logowanie jako Administrator (zarządzanie zasobami) lub Użytkownik (wypożyczanie/zwroty).
* **Trwałość danych:** Odczyt i zapis stanu biblioteki oraz kont do zwykłych plików `.txt`.
* **Podstawy bezpieczeństwa:** Zabezpieczenie haseł w bazie za pomocą prostego hashowania (`std::hash`).

## Kompilacja i uruchomienie
Do uruchomienia na systemach Linux/Ubuntu wymagany jest kompilator `g++`.

1. Sklonuj repozytorium:
   `git clone https://github.com/EloMaks/cpp-library-system.git`
2. Skompiluj pliki:
   `g++ src/*.cpp -o biblioteka_app`
3. Uruchom program:
   `./biblioteka_app`
