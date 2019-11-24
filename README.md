# Testme
# Aplikacja do ćwiczenia testów automatycznych.
Obecnie pod adresem https://testmebank.herokuapp.com/internet/ istnieje mocno uproszczona wersja aplikacji, można nią przejść do konca i uruchomienia. Strona może się za pierwszym razem dłużej wczytywać, musi wstać. Jeśli pojawi się wielki żółty ekran z błędami to tryb debugowanio, znaczy moje niedopatrzenie w kodzie. Można wtedy śmiało zgłosić buga ;)

0. Spróbuj przeprocesować wniosek do końca ręcznie.
1. Jako wstępne zadanko spróbuj uzupełnić pola na pierwszym ekranie i przejść dalej, dozwolone id partnera to 666 i PAYU.
2. Spróbuj przeprocesować wniosek jak nadalej automatyzując. Pola nie sprawdzają poprawności liczb kontrolnych, jedynie długość i typ znaków.
3. Produkty mają różne oprocentowanie, ale nie pozwalają jeszcze wybrać ilości rat. Efekt produktu jest na razie widoczny na ekranie oferty. Oprocentowania to 0, 5 i 15%
4. Parzystość ostatniej cyfra numeru konta bankowego decyduje o radzaju wymaganego przelewu weryfikacyjnego, trzeba to uwzględnić. Nieparzysty koniec symuluje elixir.
5. Dochód poniżej 1000PLN jest za niski i powoduje odrzut. Spróbuj uzyskać taki efekt.
6. Przelew wymaga podania wszystkich poprawnych danych, pomyłki będą skutkować innymi statusami niż akceptacją. Zły numer to zawsze odrzut, pomyłka w imieniu lub nazwisku pozwala na wyslanie do dodatkowej weryfikacji(jeszcze nie obsługiwane)
7. Ekran z dokumentami nic nie robi, to nie jest błąd wczytywania, poprstu jeszcze tego nie zrobiłem :)
