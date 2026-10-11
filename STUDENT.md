# Moje wykonanie Lab00

- Login GitHub / pseudonim: s4r4xx
- System i terminal (np. Windows + WSL Ubuntu): Windows 11 + Wiersz poleceń
- Edytor / IDE: Visual Studio Code
- Wersja Git: 2.54.0.windows.1
- Wersja kompilatora C++: 15.2.0 (MSYS2)
- Wersje java i javac: 25.0.4.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/s4r4xx/oop-lab00-s4r4xx2/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++!
Wow
```
Wynik programu Java:
```text
Hello from Java!
Wow
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: linia nr 6, komunikat: "expected ';' before 'return'"
- Przyczyna oraz sposób naprawy: Dopisanie brakującego średnika (`;`) na końcu linijki kodu, tuż przed instrukcją `return 0;`.
- Commit z błędem (SHA lub link): https://github.com/s4r4xx/oop-lab00-s4r4xx2/pull/1
- Czy Actions pokazały błąd, a po naprawie sukces? Tak.

## Krótkie odpowiedzi
1. Co różni commit od push? commit zapisuje zmiany na moim własnym komputerze, a push wysyła zapisane zmiany do repozytorium zdalnego
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Ponieważ "Merge pull request" odbywa się tylko na serwerze. Folder na dysku komputera posiada starą wersję plików. Lokalne wykonanie pull pobiera nową, połączoną wersję z serwera na dysk lokalny i następuje synchronizacja.
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Potwierdza, że kod jest poprawny pod kątem składni i że program daje się uruchomić, kończąc działanie bez błędów systemowych. Nie potwierdza poprawności merytorycznej ani logiki działania programu.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: ...
