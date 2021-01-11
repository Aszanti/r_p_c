
# Rock paper scissors game

## Cel projektu

Celem projektu jest stworzenie aplikacji, która pozwoli na grę dla dwóch osób w popularną grę Papier-Kamień-Nożyce

Aplikacja powinna zostać podzielona na 3 ekrany:
- Ekran startowy
- Ekran ustawień
- Ekran gry

## Ekran startowy:
- wyświetla losowe zdjęcie (może byc pobrane z https://picsum.photos/, może być wybrane przez Ciebie)
- po naciśnięciu na zdjęcie przejście do ekranu ustawień

## Ekran ustawień
- wyświetla dwa pola input type=text: Gracz 1 i Gracz 2
- w pola można wpisać imiona dwóch użytkowników, które są zapisywane w state globalnym
- wyświetla przycisk "Start game", który jest disabled, jeśli imię któregoś z graczy jest puste
- przycisk "Start game"(jeśli jest aktywny), przenosi do ekranu gry

## Ekran gry
- wyświetla imiona graczy
- wyświetla przycisk "Play", który jest opisany niżej

## Przycisk "Play"

Po naciśnięciu losuje dla każdego gracza jedną z wartości - "Kamień", "Papier" lub "Nożyce" i wyświetla je obok imion graczy. Dodatkowo, w zależności od wylosowanych wartości wypisuje na środku informację o zwycięzcy lub remisie.

Przykład:
Gracz1 -> Adam
Gracz2 -> Ewa

Zostaje naciśnięty przycisk "Play":
1. Dla Adama zostaje wylosowana wartość "Papier"
2. Dla Ewy zostaje wylosowana wartość "Nożyce"
3. Odpowiednie wartości zostają wyświetlone obok imion graczy
4. Na środku ekranu wyświetla się informacja: "Winner: Ewa"

*Uwaga W przypadku gdy została wylosowana taka sama wartość dla obu graczy wyświetl "Draw"*


## Technologie

### Core:
* Javascript/Typescript - z naciskiem na Typescript
* React - duży plus, jeśli użyjesz hooków
* State management - dowolne rozwiązanie, polecam coś z grupy: ReactContext, MobX, ReduX, Recoil

### Style:
* styled-components
* jeśli uznasz za konieczne, to możesz także użyć jakiejś biblioteki z gotowymi komponentami(MaterialUI, ElasticUI)

### Testy:
* jest - testy, napisz proszę kilka testow jednostkowych dla komponentów Reactowych, oraz kilka testujących logikę aplikacyjną
* enzyme/react-testing-library

### Pozostałe narzędzia:
- npm/yarn - wybierz jedno z nich
- node
- git

Oprócz powyższych oczywiście możesz użyć dodatkowych bibliotek.

## Co będzie brane pod uwagę:

0. Przede wszystkim proces powstawania projektu
1. Funkcjonalność, działające zapisywanie imion graczy, losowanie symboli oraz oznaczanie zwycięzcy
2. Wykorzystanie nowych standardów javascript
3. Wykorzystanie Typescripta
4. Wykorzystanie Reacta - podział na komponenty, wykorzystanie state, state management
5. Testy - kilka testów jednostkowych, sprawdzających poprawność komponentów oraz logiki aplikacji
6. Style nie są aż tak ważne jak pozostałe punkty, nie poświęcaj zbyt dużo czasu na ostylowanie jakiegoś elementu
7. Czytelne README.md




