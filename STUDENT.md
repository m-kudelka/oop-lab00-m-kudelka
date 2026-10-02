# Moje wykonanie Lab00

- Login GitHub / pseudonim: m-kudelka
- System i terminal (np. Windows + WSL Ubuntu): macOS
- Edytor / IDE: Visual Studio Code
- Wersja Git: git version 2.50.1 (Apple Git-155)
- Wersja kompilatora C++: Apple clang version 17.0.0 (clang-1700.6.4.2)
- Wersje java i javac: openjdk version "17.0.20.1" / javac 17.0.20.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/m-kudelka/oop-lab00-m-kudelka/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++! m-kudelka
```
Wynik programu Java:
```text
Hello from Java! m-kudelka
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: cpp/main.cpp:5:53: error: expected ';' after expression
- Przyczyna oraz sposób naprawy: brak srednika na koncu linii, dodanie srednika na koncu linii
- Commit z błędem (SHA lub link): 9a2a484
- Czy Actions pokazały błąd, a po naprawie sukces? Tak

## Krótkie odpowiedzi
1. Co różni commit od push? commit zpasiuje zmiany lokalnie w reppzytorium, a push wysyla te zmiany do zdalnego repozytorium
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Żeby pobrać do lokalnego repozytorium zmiany, które zostały dodane na GitHubie podczas scalania PR.
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Zielony CI potwierdza, ze kod przeszedł skonfigurowane automatyczne test, np.kompilacje. Nie potwierdza,ze program jest w 100% poprawny ani ze nie zawiera błędów kogicznych.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: brak
