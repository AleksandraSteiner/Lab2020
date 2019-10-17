
# Metody Statystyczne w Zarz�dzaniu Wierzytelno�ciami Masowymi
# Laboratorium 4

## Zadanie 1

Przygotuj dane aplikacyjne jak w Li�cie 3.

## Zadanie 2

Sprawd� oszacowanie treningowego b��du prognozy (zbi�r ucz�cy to jednocze�nie zbi�r testowy) regresyjnego modelu k-najbli�szych s�siad�w prognozuj�cego 6-cio miesi�czn� skuteczno�� za pomoc� cech aplikacyjnych:

*	Wykorzystaj funkcj� `knn.reg` z pakietu `FNN`.
*	Sprawd� dla liczb najbli�szych s�siad�w od 1 do 30 oraz dla w�skiego oraz szerokiego zbioru cech obja�niaj�cych.
*	W tym i kolejnych zadaniach jako funkcj� straty przyjmij funkcj� kwadratow�: $$L(Y,\hat{f}(X))=(Y-\hat{f}(X))^2$$
*	Jakie s� problemy zwi�zane z bezpo�rednim prognozowaniem skuteczno�ci?
*	Jaka jest optymalna liczba cech obja�niaj�cych oraz liczba najbli�szych s�siad�w?

## Zadanie 3

Sprawd� oszacowanie testowego b��du prognozy regresyjnego modelu k-najbli�szych s�siad�w prognozuj�cego 6-cio miesi�czn� skuteczno�� za pomoc� cech aplikacyjnych.

*	Wykorzystaj pr�b� treningow�, walidacyjn� oraz testow� w proporcjach 50%, 25%, 25%.
*	Za�� sta�y zbi�r cech obja�niaj�cych wybrany w poprzednim zadaniu.
*	Jak zachowuje si� oszacowanie b��du testowego w zale�no�ci od liczby najbli�szych s�siad�w?
*	Jaka jest optymalna liczba najbli�szych s�siad�w i zwi�zane z ni� oszacowanie testowego b��du prognozy?

## Zadanie 4

Sprawd� oszacowanie testowego b��du prognozy regresyjnego modelu k-najbli�szych s�siad�w prognozuj�cego 6-cio miesi�czn� skuteczno�� za pomoc� cech aplikacyjnych wykorzystuj�c 5 i 10-krotn� kroswalidacj�. Sprawd� dla liczb najbli�szych s�siad�w od 1 do 30 oraz por�wnaj z wynikami z poprzednich punkt�w.

## Zadanie 5

Sprawd� oszacowanie testowego b��du prognozy regresyjnego modelu k-najbli�szych s�siad�w prognozuj�cego 6-cio miesi�czn� skuteczno�� za pomoc� cech aplikacyjnych wykorzystuj�c metod� bootstrap oraz leave one-out bootstrap dla optymalnej liczby najbli�szych s�siad�w wybranej w poprzednim punkcie. 

## Zadanie 6

Zbierz oraz por�wnaj wyniki uzyskane w punktach 2-5.