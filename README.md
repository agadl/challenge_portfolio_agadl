# challenge_portfolio_agadl
# TASK 1
## Subtask 1
10 punktów 😊
## Subtask 3
Cześć! Mam na imię Agnieszka. Zdecydowałam się na udział w projekcie, aby zobaczyć jak wygląda część praktyczna oraz żeby poćwiczyć testowanie manualne oprócz samej nauki teorii. 

Moim głównym celem jest sprawdzenie siebie oraz zobaczenie czy jest to kierunek w którym chcę się rozwijać i wiązać z nim moją dalszą przyszłość. 


*Agnieszka*

## Subtask 4
Aplikacja Scouts Panel przeznaczona jest dla skautów piłki nożnej w celu zgromadzenia młodych talentów. Aplikacja polega na dodawaniu i przeglądaniu graczy oraz ich umiejętności, dodawaniu meczów oraz na tworzeniu raportów meczowych.

**Funkcjonalności**

Przed zalogowaniem:
* możliwość zmiany języka
* możliwość przypomnienia hasła
* możliwość zalogowania
  
Po zalogowaniu:
* możliwość wylogowania
* możliwość dodawania graczy oraz ich aktualizowania
* możliwość przeglądania list graczy
* możliwość pobrania oraz wydrukowania listy graczy
* możliwość odznaczenia wybranych kolumn
* możliwość filtrowania według wybranych kryteriów
* możliwość tworzenia meczów oraz edytowania meczów
* możliwość rozpoczęcia meczu
* możliwość dodawania oraz edytowania raportów meczowych

Formularze:
* możliwość wyboru cyfry w polach “waga” oraz “wzrost”
* możliwość wyboru daty z kalendarza w polu “data urodzenia”
* możliwość wyboru województwa oraz dominującej nogi
* możliwość dodania linku do YouTube
* możliwość dodania języków
* możliwość zapisania formularza
* możliwość wyczyszczenia formularza

Raporty:
* możliwość cofnięcia oraz ponowienia wpisanego tekstu
* możliwość zmiany wielkości czcionki
* możliwość pogrubienia pochylenia oraz podkreślenia wpisywanego tekstu
* możliwość dodania nagłowka 1 oraz 2 stopnia
* możliwość dodania bloku kodu
* możliwość dodania cytatu

Interfejs aplikacji wygląda na niedopracowany, uproszczony. Szata graficzna jest spójna, przejrzysta, jednak rozmieszczenie elementów na stronie jest nieczytelne i wygląda na nieprzemyślane. Niektórych funkcji aplikacji (np. listy meczów, raportów lub rozpoczęcie meczu) trzeba poszukać, co komplikuje używanie aplikacji i może być problematyczne dla nowych użytkowników. Nawigacja jest mało intuicyjna (np. logo nie przenosi na stronę główną, nie można dodać nowego gracza z panelu “gracze” tylko przez linki pomocnicze, kontakt znajduje się pod sloganem, w tabeli brak wskaźnika możlowości kliknięcia na wybrany wiersz). Formularz wygląda chaotycznie, dane nie posiadają hierarchii ważności oraz nie są pogrupowane. Funkcja “rozpocznij mecz” nie wyjaśnia zasad oraz celu tej opcji, ciężko się domyśleć, że dane w raporcie pochądzą z tej opcji.

**Błędy**

* formularz dodawania gracza
  * w polu “waga” oraz “wzrost” można wybrać ujemną wartość
  * w polu “data urodzenia” można wybrać dzisiejszą oraz przyszłą datę
  * w polu “telefon” można używać słów
  * w polu "imię", "nazwisko", "główna pozycja", "alternatywna pozycja", "osiągnięcia" można wpisywać cyfyry
  * można zapisać gracza z dodanymi pustymi polami "języki" oraz z pustymi polami do linków do youtube
* formularz dodawania meczu
  * w polach z nazwami drużyn można wpisywać cyfry
  * w polu “data” można wybrać dzisiejszą oraz przyszłą datę
  * w polu “czas gry” można wybrać ujemną wartość 
  * w polu “numer” można dodawać duże wartości
  * w polu “zdobyte gole” można wpisywać inne wartości niż cyfry
  * po wyborze języka polskiego, zostają nagłówki w języku angielskim “web match” oraz “general”
* w obu formularzach: 
  * po wyborze języka polskiego, zostają przyciski “submit” oraz “clear”
* raporty: 
  * po wyborze języka polskiego, zostaje przycisk “save”
  * w zakładce raporty -> dodaj raport- brak możliwości dodania raportu- przenosi do zakładki “mecze” 
* lista zdarzeń:
  * niepoprawne wyświetlane dane w polu “metadane”
* akcja “dodaj grę” 
  * możliwość wyboru więcej niż 2 połowy meczu
  * po nie zapisaniu meczu, brak możliwości powrotu do raportu na stronie głównej (link nie przenosi do raportu) 
* menu boczne:
  * dłuższe imię gracza nie mieści się (nie zawija się/ nie łamie się)
* tabele:
  * tabela nie mieści się na ekranie, trzeba przewijać w bok
  * eksport do pliku CSV nie eksportuje poprawnie danych
* filtry:
  * słowo “rate”,  “age”, “reset”, “filters”  zostaje po angielsku
  * w polach “age” oraz “rate” można wpisywać słowa
  * po kliknięciu “reset” czyści się formularz z filtrami, ale nie odświeża wyników wyszukiwania 


# TASK 2
## Subtask 1
Przypadki testowe na podstawie User Story

[Subtask 1- Test Cases](https://docs.google.com/document/d/1x5sTsQI7IxQ1qleXNk3y63XW2KPiHL8rcuWvVYaJn6g/edit)

## Subtask 2
Przypadków testowe na podstawie “własnych doświadczeń”

[Subtask 2- Test Cases](https://docs.google.com/document/d/1TIAIRdCGoh3Ij8Lw7SZsQgytXLdsQKmNmWlpwGDcZKs/edit)

## Subtask 3
*Dlaczego piszemy przypadki testowe?*

Przypadki testowe piszemy aby określić rożne możliwości obsłużenia funkcjonalności w danej aplikacji, określają krok po kroku jak przetestować dane funkcjonalności, zachowują spójność testowania oraz dzięki nim możemy określić czy funkcjonalności w tej aplikacji działają jak w założeniach.


# TASK 3
## Subtask 1
Testowanie według planów testów i raportowanie błędów

[Subtask 1- Bug report](https://docs.google.com/document/d/1zn6VZvY1f6JkUeFM6WFJZrCZsTYoVDdlK1gc_G4ba0Q/edit)

## Subtask 2
Raport z wykonanych testów

[Subtask 2- Test report](https://docs.google.com/document/d/1zazY6ulPNHTESfX71vTq3DC_WG9-BBsXxT9IcacUb6g/edit)


# TASK 4
## Subtask 1
Testowanie eksploracyjne i raportowanie błędów

W aplikacji OLX nie znaleziono blędów. 

[Subtask 1- Bug report](https://docs.google.com/document/d/1yewbd12gb6GrFdQXLg27buW5Mb5ZMsNBcn1UdiNUQRg/edit)

## Subtask 2
*1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?*

Aplikacja OLX jest platformą z ogłoszeniami. Korzystając z aplikacji można kupować, sprzedawać, wymieniać się produktami, ale również można dodać ogłoszenie   oferujące usługi jak i oferty pracy. 

*2. Kto ma być użytkownikiem końcowym aplikacji?*

W aplikacji OLX mamy dwie kategorie użytkowników końcowych- tych którzy dodają ogłoszenia i tych którzy tych ogłoszeń szukają.

*3. Czy według Ciebie aplikacja jest user friendly?*

Uważam, że aplikacja OLX jest przyjazna użytkownikom. Jest przejrzysta, czytelna, intuicyjna, szybka oraz bezpłatna.

*4. Jak byś usprawnił aplikację?*

Moim zdaniem aplikacja działa bardzo dobrze, funkcjonalności są przemyślane oraz łatwe w obsłudze i na ten moment nie widzę potrzeby usprwniania żadnych z funkcjonalności. 

*5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?*

Testując aplikację internetową nie musimy zastanawiać się, jak dana aplikacja działa na różnych urządzeniach jak w przypadku aplikacji natywnych- na różnych  urządzeniach mogą pojawiać się inne błędy. 

Podczas testowania aplikacji internetowej dużą pomocą jest zestaw narzędzi DevTools. 

# TASK 5
## Subtask 3

*1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

```sql
SELECT *
FROM actors
ORDER BY surname;
```

<img width="244" alt="Screenshot 2023-10-06 at 14 58 36" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/ad9ba75f-6d04-4b45-8d8c-576a2d3fd4bd">


*2. Wyświetl film, który powstał w 2019 roku.

```sql
SELECT *
FROM movies
WHERE year_of_production = 2019;
```

<img width="327" alt="Screenshot 2023-10-06 at 14 43 34" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/7e581d4c-38ff-4876-b137-5e3b8657bd4f">

*3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

```sql
SELECT *
FROM movies
WHERE year_of_production BETWEEN 1900 AND 1999;
```

<img width="484" alt="Screenshot 2023-10-06 at 14 51 54" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/5bfdbe3b-3585-46c4-ae23-b0e5f317b091">

*4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

```sql
SELECT title, price
FROM movies
WHERE price < 7;
```

<img width="283" alt="Screenshot 2023-10-10 at 11 01 23" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/089571c0-8311-4214-91c2-7927cdcfb922">

*5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

```sql
SELECT *
FROM actors
WHERE actor_id >= 4 AND actor_id <= 7;
```

<img width="229" alt="Screenshot 2023-10-10 at 11 18 09" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/a9e7e801-d522-45c5-8cbd-3b12b5afe4a4">


*6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

```sql
SELECT * 
FROM customers 
WHERE customer_id % 2 = 0;
```

<img width="344" alt="Screenshot 2023-10-10 at 11 25 24" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/0593d37a-a12c-412e-9daa-9a12c888b7fd">

*7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

```sql
SELECT * 
FROM customers 
WHERE customer_id IN (1, 3, 5);
```

<img width="344" alt="Screenshot 2023-10-10 at 11 27 49" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/8020fb19-cec6-40e2-81b3-8141df72fa10">

*8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

```sql
SELECT * 
FROM actors 
WHERE name LIKE 'An%';
```

<img width="208" alt="Screenshot 2023-10-10 at 12 08 27" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/acc41964-2f63-43ce-a963-a1f08d721565">

*9. Wyświetl dane klienta, który nie ma podanego adresu email.

```sql
SELECT * 
FROM customers
WHERE email IS null;
```

<img width="283" alt="Screenshot 2023-10-10 at 11 31 28" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/33891b66-0bbe-49ea-8d68-9c9041e672de">

*10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

```sql
SELECT *
FROM movies
WHERE (price > 9) AND (movie_id BETWEEN 2 AND 8);
```

<img width="350" alt="Screenshot 2023-10-10 at 11 38 22" src="https://github.com/agadl/challenge_portfolio_agadl/assets/144120639/b1ad5709-f10e-44cd-beaa-ccddcb50b820">
