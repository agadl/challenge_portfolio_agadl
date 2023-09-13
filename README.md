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
  * po wyborze języka polskiego, zostają nagłówki w języku angielskim “web mach” oraz “general”
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


