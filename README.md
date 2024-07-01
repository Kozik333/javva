# javva
Utwórz program, który pozwoli użytkownikowi na wprowadzanie ocen dla słuchaczy i 
studentów. 
Wymagania dot. aplikacji 
• Aplikacja konsoli, powinna składać się z 2 projektów MAVEN (odseparowana logika 
od modelu dziedziny). 
• Program powinien kompilować się i uruchamiać. 
• Program musi być zabezpieczony przed wszelkimi błędami i posiadać odpowiednie 
komunikaty dla użytkownika. 
• Program powinien być napisany zgodnie z zasadami tworzenia czystego kodu. 
Zaimplementuj menu dla użytkownika, które umożliwi: 
1. Dodanie nowej osoby
2. Wyświetlenie listy osób
3. Wygenerowanie raportu 
4. Zapis do pliku 
5. Zakończenie programu 
AD 1. Dodanie nowej osoby: 
1. Osoba może być Studentem lub Słuchaczem. 
Dla Studenta należy zdefiniować: 
• Imię (maksymalnie 120 znaków) 
• Nazwisko (maksymalnie 120 znaków) 
• Numer albumu (maksymalnie 10 znaków)
Dla słuchacza należy podać: 
• Imię (maksymalnie 120 znaków) 
• Nazwisko (maksymalnie 120 znaków) 
• Czy jest zarejestrowany (prawda / fałsz)
Dla każdej osoby należy dodatkowo podać oceny tej osoby. Użytkownik po wpisaniu 
podstawowych danych otrzymuje pytanie, ile ocen chcemy dodać. Następnie pobierane są 
oceny z przedziału (1-5)
AD 2. Program powinien wyświetlić na ekranie listę w postaci: 
numer porządkowy. „Student- „, Imię, nazwisko, album (dla studenta)
numer porządkowy. „Słuchacz -”, Imię, nazwisko, czy zarejestrowany (dla słuchacza)
! Do zróżnicowania sposobu wyświetlania nie używaj bloku warunkowego! Powinna być 
tylko jedna kolekcja osób.
AD 3. Program powinien umożliwić generowanie raportów pokazujących informacje zbiorcze. 
Użyj obiektu Stream
• Lista studentów i słuchaczy wraz z ich średnimi. 
• Średnia wszystkich wprowadzonych osób.
• Liczba osób z przynajmniej jedną oceną niedostateczną (2).
AD 4. Program powinien umożliwić eksport listy osób do pliku tekstowego (dowolny 
sposób zapisu i format)
• Po zapisie pliku wyświetl odpowiedni komunikat dla użytkownika. 
• Zapis powinien zostać zrealizowany z wykorzystaniem odpowiedniego interfejsu. 
(OPCJONALNIE) Zapis pliku powinien odbywać się w sposób, który nie będzie blokował 
interfejsu użytkownika (zastosowanie wielowątkowości).
AD 5. Po wykonaniu każdej operacji powinien wyświetlić się menu do czasu, aż użytkownik 
nie wybierze opcji zakończ
Utwórz odpowiednią strukturę klas. Pamiętaj o enkapsulacji pól. 
Zaimplementuj logikę zgodnie z wyższym opisem. 
Pamiętaj o poprawnym zaprojektowaniu klas tak, aby zgodnie z zasadą segregacji 
interfejsów charakteryzowały się metodami ściśle powiązanymi poprzez obszar swojej 
funkcjonalności. 
Dostęp do implementacji metod powinien być możliwy poprzez odpowiednio zdefiniowane 
interfejsy i klasy abstrakcyjne.
