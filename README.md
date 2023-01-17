Task 1
======

* * *

Subtask 1
---------

 9 punktów

* * *

Subtask 3
---------

Zastanawiam się nad zmianą pracy i branży, a mieliśmy szkolenie w pracy powiązane z programowaniem i IT, co zawsze mnie ciekawiło, ale nigdy nie miałam okazji próbować. Chciałam przekonać się jak praktycznie wygląda testowanie, do tego lubię wyszukiwać szczegóły i błędy oraz nie boję się klikać :)

* * *

Subtask 4
---------

### Aplikacja Scouts panel:

Gromadzi informacje na temat zawoników piłki nożnej w celu wyselekcjonowania najlepszych graczy, dlatego najważniejszym jest aby te informacje były łatwo dostępne i przejrzyście uporządkowane.

### Funkcjonalności aplikacji:

*   możliwe jest zalogowanie/wylogowanie

*   dla każdego gracza możliwe jest dopisanie rozegranego meczu i jego dokładnych statystyk

*   z dostępnych meczy możliwe jest wygenerowanie raportów, które można uzupełnić o opis

*   tworzenie nowych profili graczy/uzupełnienie bazy graczy
*   przeglądanie bazy graczy, także sortowanie i wyszukiwanie graczy
    
*   dla każdego gracza możliwe jest dopisanie rozegranego meczu i jego dokładnych statystyk
    
*   z dostępnych meczy możliwe jest wygenerowanie raportów, które można uzupełnić o opis
    

### Intuicyjność dostępnych funkcjonalności:

#### Nie wszystkie z dostępnych funkcjonalności są intuicyjne np.:

*   Na podstronie „Gracze”,gdzie jest lista piłkarzy w bazie nie ma przycisku umożliwiającego dodanie nowego gracza – trzeba wrócić na stronę główną i znaleźć odnośnik w linkach pomocniczych. Nieporozumienie może także powodować przycisk „Dodaj raport” na podstronie z wygenerowanymi raportami, ponieważ przenosi on bez wyjaśnienia do zakładki „mecze” nie informując, co właściwie należy dalej zrobić, żeby otrzymać raport.
    
*   Na stronie wyświetlanych jest jedynie 10 graczy, nie ma możliwości zmiany liczby wyświetlanych wyników, ani przejścia na koniec listy.
    
*   Brak wskazówki pod względem jakiego kryterium jest wyświetlana lista meczów zawodnika – podpowiedzią mogłaby być data dodania lub opcja sortowania pod względem klikniętego nagłówka. Po dodaniu meczu pokazuje się on na końcu listy wszystkich meczów, co jest nieintuicyjne oraz przy dużej liczbie pozycji niewygodne.
    
*   Niewykorzystaną informacją jest minuta meczu zaznaczanej akcji w zakładce „Rozpocznij mecz” – powinno to być ujęte w raporcie.
    
*   Dodawanie zdarzeń do meczu w zakładce „Rozegraj mecz” jest zupełnie nieintuicyjne, ponieważ po na jechaniu na ikonki nie wyświetla się jej funcka, po dodaniu akcji nie można już tego znacznika usnąć ani edytować oraz nie wiadomo, który znacznik był jakim zdarzeniem, ponieważ nie wyświetlają się o nim żadne informacje (ani w oknie po najechaniu na niego, ani w formie listy poniżej).
    
*   Niektóre informacje wprowadzane w profilu gracza oraz meczu powinny być rozwijaną listą np. pozycja piłkarza. W „dodawaniu meczu” powinna być jeszcze rubryka na jakiej pozycji grał piłkarz w tym konkretnym meczu, ponieważ w profilu gracza możliwe jest wpisanie pozycji głównej i alternatywnej, a wyświetlane opcje w danym meczu w „rozpocznij mecz” są domyślnie ustawione dla pozycji głównej, co najczęściej będzie się zgadzało, ale nie zawsze.
    
*   Po każdej zmianie w zestawieniu meczu oraz w rozgrywce trzeba generować nowy raport, nie aktualizuje się już istniejący, prowadzi to do dublowania i mnożenia liczby aktualnych i nieaktualnych raportów, których dodatkowo nie można usunąć.
    

Dodałabym podsumowanie (nieedytowalne) na profilu piłkarza, a edycję jako kolejny krok do przejścia z profilu.

Brakuje możliwości porównywania graczy, a także podsumowania statystyk gracza po wejściu w jego profil (niepełne dostępne są tylko w widoku całej listy graczy).

### Wygląd:

*   Plusem jest stonowana kolorystyka i przejrzystość (brak wielu chaotycznych elementów), jednak całość sprawia wrażenie wersji roboczej i niedokończonej.
    
*   Boczne menu jest nieintuicyjne, nie odzwierciedla relacji i hierarchii elementów listy.
    
*   Strona główna jest niepraktyczna, informacje i odnośniki wydają się niewystarczające, strona główna funkcjonuje właściwie jedynie w celu skorzystania z opcji „dodaj gracza” oznaczonej jako linki pomocnicze, gdzie nie jest jej miejsce, ponieważ dodawanie graczy jest jedną z głównych funkcji tego panelu. Brak tu też okna wyszukiwania.
    
*   Przy obsłudze klawiszami podświetlenia są nieczytelne i pojawiają się po dwa razy.
    

### Błędy:

*   Bardzo niska wydajność – długi czas wstępny reakcji serwera. Przy wolniejszym połączeniu internetowym bardzo długo ładuje się każda podstrona, gdzie jest dużo informacji, np. „Gracze”.
*   Przy obsłudze klawiszami w niektórych przypadkach nie można wejść w zawartość naciskając enter.
    
*   W opcji „Przypomnij hasło” nie ma informacji o błędzie, jeśli wpisze się coś innego niż mail.
    
*   Przy wyszukiwaniu piłkarza w oknie „Szukaj” opcja ta nie działa, jeśli wpisuje się imię i nazwisko, działa jedynie przy wpisaniu tylko albo imienia albo nazwiska.
    
*   W edycji gracza: można dodać wagę i wzrost ujemne, przy wadze brak określonej jednostki, brak ograniczeń dla znaków wpisywanych w telefon (dopuszczalne litery i za długie/ za krótkie ciągi cyfr), możliwe jest dodanie przyszłej daty urodzenia, brak kontroli co jest wpisywane w rubryce z linkami. Dodatkowo linki nie wyświetlają się jako hiperłącza, tylko jako zwykły tekst, który trzeba skopiować, żeby w niego wejść. Gdy niepoprawnie wpisze się adres e-mail niemożliwe jest zapisanie profilu, jednak nie ma informacji, w której rubryce jest błąd.
    
*   W „dodanie meczu”: możliwe jest wpisanie daty w przyszłości, możliwe jest dodawanie ujemnych liczb w czasie oraz numerze koszulki, nie ma kontroli wklejanego tekstu w rubryce „Web match”.
    
*   W „Raportach”: przy tworzeniu id meczu i gracza nie działa przycisk „clear”, opcja „cytat” w edycji tekstu w raporcie daje tylko wcięcie tekstu. Nie działa przycisk „wróć do raportu” w przypadku wyjścia i nie zapisania tworzonego raportu.
    
*   W „Rozpocznij mecz”: za późno o 1 sekundę pauzuje się zegar, dodawanie zdarzeń możliwe tylko jak jest uruchomiony zegar (dodawanie akcji nie pauzuje go), można dodać ujemny czas, ale może to być przydatne przy dogrywce, można za to ustawić więcej niż dwie połowy.
    
*   Nie wyświetla się favicon (błąd 404).
