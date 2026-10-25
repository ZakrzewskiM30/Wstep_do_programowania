# Zadania lab 3

## Zadanie 1

Napisz program który dla zadanej tablicy liczb stworzy i zwróci tablicę kwadratów tych liczb.

## Zadanie 2

Napisz program który dla podanej liczby `n` wczyta od użytkownika `n` liczb i stworzy z nich tablicę.

## Zadanie 3

Napisz program który przepiszę tablicę dwuwymiarową na tablicę jednowymiarową. Zastanów się nad numeracją elementów w nowej tablicy.

## Zadanie 4

Napisz program który dla podanej tablicy dwuwymiarowej o wartościach `0` lub `1`, wypisze na ekranie prostokąt o wymiarach zależnych od wymiarów tablicy. Na współrzędnych odpowiadającym wartości 1 umieść znak 'x'

Przykład:
{{1,0},{0,1}}
```
|--|  
|x |  
| x|  
|--|  
```
## Zadanie 5

Napisz program który pobierze od użytkownika dwie pary liczb z zakresu `1,10`.
Program powinien wyświetlać planszę `10x10` i piłeczkę oznaczaną przez 'x'. Pierwsza para liczb `a1,b1` określa początkową pozycję piłeczki, druga para `a2,b2` pozycję w następnym kroku. Program powinien w nieskończonej pętli przemieszczać piłeczkę z pozycji `a1,b1` na pozycję `a2,b2` oraz wyznaczać nową pozycję `a2,b2` zgodnie z dotychczasowym ruchem piłeczki, w przypadku gdy piłeczka wykroczy poza zakres planszy program powinien się zakończyć.

## Zadanie 6

Zmodyfikuj rozwiązanie `zadania 5` tak aby piłeczka mogła "odbijać" się od krawędzi planszy.

## Zadanie 7

Napisz program który dla podanej tablicy trójwymiarowej wypisze te elementy które są większe od swoich sąsiadów. Za sąsiadów elementu `T[x][y][z]` uznajemy te elementy których współrzędne różnią się o co najwyżej 1 poza samym `T[x][y][z]`.
