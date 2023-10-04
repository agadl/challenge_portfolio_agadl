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


## Subtask 2
*1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?*
Aplikacja OLX jest platformą z ogłoszeniami. Korzystając z aplikacji można kupować, sprzedawać, wymieniać się produktami, ale również można dodać ogłoszenie oferujące usługi jak i oferty pracy. 

*2. Kto ma być użytkownikiem końcowym aplikacji?*
W aplikacji OLX mamy dwie kategorie użytkowników końcowych- tych którzy dodają ogłoszenia i tych którzy tych ogłoszeń szukają.

*3. Czy według Ciebie aplikacja jest user friendly?*
Uważam, że aplikacja OLX jest przyjazna użytkownikom. Jest przejrzysta, czytelna, intuicyjna, szybka oraz bezpłatna.

*4. Jak byś usprawnił aplikację?*
Aby poprawić aplikację dodałabym szerszy wachlarz filtrów. Np. wybierając kategorię ‘Dom i Ogród’ chciałabym mieć możliwość wyboru czego szukam- czy do domu (np. meble, wyposażenie, oświetlenie) czy do ogrodu (np. meble, narzędzia ogrodowe, rośliny).

*5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?*
Testując aplikację internetową nie musimy zastanawiać się, jak dana aplikacja działa na różnych urządzeniach jak w przypadku aplikacji natywnych- na różnych urządzeniach mogą pojawić się inne błędy. 

Podczas testowania aplikacji internetowej dużą pomocą jest zestaw narzędzi DevTools. 





