# Specyfikacja procesu — szkic 0.1

**Status:** draft. Wymagania poniżej są propozycjami do przetestowania, nie zatwierdzonym standardem.

## Cel i granice

Standard opisuje wspólny język oraz minimalny, możliwy do odtworzenia proces obsługi potrzeb i inicjatyw. Nie określa technologii, rodzaju instytucji, budżetu ani sposobu wyboru lokalnych priorytetów.

Nie zastępuje postępowań administracyjnych, zgłoszeń alarmowych, skarg i wniosków obsługiwanych według obowiązujących przepisów. Sprawy wykraczające poza kompetencje uczestników powinny być oznaczane jako skierowane do właściwego kanału, bez deklarowania decyzji w imieniu tego podmiotu.

## Podstawowe pojęcia

- **Zgłoszenie:** pierwotna informacja od osoby lub organizacji; może zawierać problem, pomysł lub propozycję pomocy.
- **Potrzeba:** zrozumiany stan rzeczy wymagający uwagi; wiele zgłoszeń może dotyczyć jednej potrzeby.
- **Propozycja działania:** możliwy sposób odpowiedzi na potrzebę, jeszcze nie zatwierdzony.
- **Sprawa:** jednostka pracy z identyfikatorem, historią decyzji i wskazanym opiekunem.
- **Decyzja:** rozstrzygnięcie podjęte przez uprawnioną osobę lub grupę z uzasadnieniem.
- **Działanie:** przyjęty do realizacji zakres pracy, z odpowiedzialnością i sposobem oceny efektu.
- **Rezultat:** udokumentowane wykonanie i ocena tego, czy pomogło rozwiązać potrzebę.

## Role (jedna osoba może pełnić kilka)

- **Zgłaszający:** przedstawia problem lub pomysł, także anonimowo.
- **Pośrednik:** za zgodą lub na żądanie zainteresowanego wprowadza sprawę, np. przez telefon, na dyżurze lub z papieru; odnotowuje kanał i zakres umocowania.
- **Opiekun sprawy:** dba o kompletność danych, kontakt i aktualny status.
- **Decydent:** podejmuje tylko decyzje należące do jego rzeczywistych kompetencji.
- **Realizator:** odpowiada za konkretne działanie.
- **Obserwator społeczny:** może zapoznawać się z bezpiecznymi do publikacji informacjami.
- **Instytucja publiczna:** może pełnić każdą adekwatną rolę jako równorzędny kontrybutor; udział w standardzie nie daje jej dodatkowych uprawnień ustawowych.

## Minimalny przebieg

1. **Przyjęcie:** zarejestruj zgłoszenie i nadaj stabilny identyfikator.
2. **Rozpoznanie:** ustal, jaka potrzeba stoi za zgłoszeniem; sprawdź duplikaty i właściwość.
3. **Rozpatrzenie:** odnotuj decyzję: przyjęcie do realizacji, odłożenie, przekazanie, połączenie, odrzucenie lub prośba o uzupełnienie — z uzasadnieniem.
4. **Działanie:** jeśli podjęto realizację, wskaż odpowiedzialność i sposób sprawdzenia wyniku.
5. **Weryfikacja:** udokumentuj wynik, ocenę potrzeby oraz dalsze kroki, jeśli sprawa nie została rozwiązana.
6. **Zamknięcie / ponowne otwarcie:** zachowaj ślad decyzji i powód zmiany.

Zalecane czytelne statusy: `NOWA`, `W_ANALIZIE`, `OCZEKUJE_NA_DECYZJE`, `PRZYJETA`, `W_REALIZACJI`, `DO_WERYFIKACJI`, `ZAKONCZONA`, `ODLOZONA`, `PRZEKAZANA`, `ODRZUCONA`. Są to statusy robocze; ich sens i przejścia wymagają sprawdzenia w pilotażu. „Przekazana” nie oznacza, że adresat przyjął sprawę.

## Minimum informacji dla każdej sprawy

- Identyfikator i data przyjęcia.
- Opis zgłoszenia i rozpoznanej potrzeby (osobno).
- Kanał: osobisty, telefoniczny, papierowy, cyfrowy, integracja albo inny.
- Opiekun lub organizacja odpowiedzialna za obsługę.
- Aktualny status oraz data jego zmiany.
- Chronologia istotnych zdarzeń i decyzji; kto i w jakiej roli je podjął.
- Uzasadnienie decyzji, o ile nastąpiło rozstrzygnięcie.
- Jeśli jest realizacja: właściciel działania, rezultat i sposób weryfikacji.
- Reguły udostępnienia informacji bez ujawniania danych wrażliwych.

Dane kontaktowe zgłaszającego są opcjonalne, zbierane tylko gdy potrzebne i przechowywane oddzielnie od publicznego rejestru. Anonimowość może ograniczyć możliwość dopytania, ale nie powinna wykluczać zgłoszenia.

## Przenoszalność

Proces musi dać się przeprowadzić i odtworzyć na papierze. Migracja między narzędziami powinna zachowywać identyfikatory, znaczenie stanów, historię decyzji i źródło informacji. Papierowy rejestr może być zgodny proceduralnie bez API; aplikacja może dodatkowo podlegać testom zgodności technicznej.

## Pytania otwarte

Jak rozpoznawać pilność? Jakie decyzje wymagają weryfikacji drugiej osoby? Jak obsługiwać sprawy wieloorganizacyjne i konflikty kompetencji? Jak długo przechowywać informacje? Kto może publikować rezultaty i na jakiej podstawie?
