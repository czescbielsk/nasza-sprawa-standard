# Specyfikacja procesu — projekt 0.1

**Status:** do konsultacji i testów analogowych. Nie jest to przyjęty standard ani procedura urzędowa.

## Zakres

Opisujemy wspólny język i minimalny, możliwy do odtworzenia proces współpracy. Nie narzucamy technologii, organu zarządzającego, budżetu ani polityki lokalnych priorytetów. Właściwe procedury prawne i kanały alarmowe zachowują pierwszeństwo.

## Pojęcia i relacje

- **Zgłoszenie (ZG):** niezmieniony sens pierwotnej informacji, problemu, pomysłu lub oferty pomocy. Ma własny identyfikator, datę i kanał.
- **Potrzeba (PO):** rozpoznany stan wymagający uwagi. Może wynikać z wielu zgłoszeń; jedno zgłoszenie może wskazywać kilka potrzeb.
- **Sprawa (SP):** prowadzony proces rozpatrywania jednej potrzeby w określonym zakresie. Ma opiekuna, historię i własny identyfikator. Jedna potrzeba może mieć kilka spraw prowadzonych przez różne zespoły.
- **Propozycja działania:** możliwa odpowiedź, bez domniemania akceptacji.
- **Decyzja:** rozstrzygnięcie w zakresie rzeczywistych kompetencji konkretnego decydenta.
- **Działanie:** przyjęty zakres pracy z odpowiedzialnym realizatorem.
- **Rezultat:** zaobserwowany efekt działania, odrębny od samego wykonania zadania.

Każdy rekord zachowuje swój identyfikator. Połączenie duplikatów **nie usuwa** zgłoszeń ani ich źródeł: rejestrujemy powiązanie ZG → PO → SP. Na papierze wystarczy tabela powiązań i wpis w dzienniku zdarzeń. Przykład: ZG-001 i ZG-002 → PO-001 → SP-001. Identyfikatory są stabilne w obrębie organizacji prowadzącej; przy wymianie między organizacjami należy dopisać identyfikator wystawcy.

## Role i odpowiedzialność

- **Zgłaszający:** zgłasza potrzebę, również anonimowo; nie musi mieć konta.
- **Pośrednik:** rejestruje przekazaną informację w imieniu osoby, gdy jest to potrzebne, z odnotowaniem kanału, podstawy przekazania i ewentualnego sposobu odpowiedzi. Samo przyjęcie anonimowego zgłoszenia nie wymaga identyfikacji autora.
- **Opiekun:** prowadzi rejestr, dokumentuje historię i koordynuje odpowiedzi; nie otrzymuje automatycznie prawa do podejmowania decyzji.
- **Decydent:** działa wyłącznie w granicach własnego mandatu lub upoważnienia.
- **Realizator:** odpowiada za działanie, które wyraźnie przyjął.
- **Obserwator:** może korzystać z informacji przeznaczonych do publikacji.
- **Instytucja publiczna:** pełnoprawny kontrybutor, zgłaszający i realizator, lecz bez zmiany kompetencji wynikających z prawa.

## Cykl życia sprawy

Minimalne statusy **sprawy**:

| Status | Znaczenie |
| --- | --- |
| NOWA | Przyjęto do rejestru, jeszcze nie rozpoznano |
| W_ROZPATRZENIU | Trwa ustalanie potrzeby, kompetencji i sposobu postępowania |
| W_DZIALANIU | Uprawniony podmiot wyraźnie przyjął własne działanie |
| DO_WERYFIKACJI | Zgłoszono wykonanie, należy ocenić efekt |
| ZAMKNIETA | Rozpatrywanie w danym zakresie zakończono z udokumentowanym wynikiem |

**Przejścia (projekt do pilotażu):**

| Z | Do | Warunek i zdarzenie |
| --- | --- | --- |
| NOWA | W_ROZPATRZENIU | Opiekun odnotował rozpoczęcie analizy |
| W_ROZPATRZENIU | W_DZIALANIU | Uprawniony decydent przyjął konkretne działanie i wskazano realizatora |
| W_ROZPATRZENIU | ZAMKNIETA | Odnotowano decyzję o odmowie, odłożeniu, połączeniu lub zakończeniu obsługi, z powodem i dalszą ścieżką |
| W_DZIALANIU | DO_WERYFIKACJI | Realizator zgłosił rezultat |
| DO_WERYFIKACJI | ZAMKNIETA | Oceniono rezultat, także jako nieskuteczny lub nieznany |
| DO_WERYFIKACJI | W_DZIALANIU | Potrzebne dodatkowe działanie, które zostało przyjęte |
| ZAMKNIETA | W_ROZPATRZENIU | Ponowne otwarcie z uzasadnieniem |

**Przekazanie**, **odłożenie**, **odrzucenie** i **połączenie** są *rodzajami decyzji/zdarzeń*, a nie obowiązkowymi dodatkowymi statusami. Przekazanie sprawy innemu podmiotowi **nie oznacza jej przyjęcia**. Odnotuj osobno: wysłano, potwierdzono odbiór, przyjęto do rozpatrzenia (tylko jeśli potwierdzone). Sprawa może pozostać w W_ROZPATRZENIU do kolejnej decyzji albo zostać zamknięta jako przekazana, ze wskazaniem braku potwierdzenia.

Zamknięcie sprawy **nie oznacza** zaspokojenia potrzeby. Rezultat zapisujemy osobno: TAK / CZĘŚCIOWO / NIE / NIE WIADOMO.

## Dziennik zdarzeń

Każda zmiana istotna dla historii sprawy wymaga dopisania nowego wpisu (nie nadpisania poprzedniego). Minimalne pola:

| Pole | Znaczenie |
| --- | --- |
| Numer wpisu | Kolejność w ramach sprawy |
| Data (i godzina, jeśli potrzebna) | Kiedy nastąpiło zdarzenie |
| Typ zdarzenia | Przyjęcie, powiązanie, zmiana statusu, decyzja, przekazanie, potwierdzenie, rezultat, ponowne otwarcie |
| Podmiot i rola | Kto wykonał czynność; dla anonimowego zgłoszenia można wskazać pośrednika |
| Treść i uzasadnienie | Co się wydarzyło, dlaczego, z jakim skutkiem |
| Odniesienie | Numer dokumentu, powiązanej potrzeby, zgłoszenia lub sprawy |

Na papierze prowadzimy numerowane wiersze i skreślenia z datą oraz adnotacją zamiast wymazywania historii. Publiczna wersja dziennika jest redagowana pod kątem prywatności. Przenoszenie między papierem a aplikacją musi zachować identyfikatory wraz z wystawcą, kolejność, źródła i znaczenie zdarzeń.

## Decyzje i granice kompetencji

Każda decyzja wskazuje **decydenta, organizację, zakres uprawnienia, przedmiot i uzasadnienie**. Decyzja grupy mieszkańców może wiązać wyłącznie ich własne działania. Nie stanowi decyzji administracyjnej, nie obciąża budżetu urzędu i nie przypisuje urzędowi obowiązku bez odrębnego potwierdzenia. Informację o formalnym rozstrzygnięciu instytucji wolno zarejestrować tylko jako udokumentowany fakt, z podaniem źródła.

## Interfejs białkowy i prywatność

Osoba bez Internetu może zgłosić sprawę, uzyskać informację o statusie i przekazać uwagę przez rozmowę, telefon, dyżur lub papier. Pośrednik zapisuje własną rolę, kanał, podstawę przekazania i uzgodniony sposób odpowiedzi. **Nie wymagamy identyfikacji zgłaszającego**, jeżeli nie jest konieczna. Dane kontaktowe, jeśli potrzebne, są oddzielone od publicznych kart i rejestrów. Samo upoważnienie do wpisania zgłoszenia nie oznacza prawa do publikacji danych osobowych.

## Zgodność i przenoszalność

Podstawowa zgodność jest proceduralna: można ją sprawdzić bez komputera według [listy kontrolnej](zgodnosc-proceduralna.md). Implementacje cyfrowe mogą dodatkowo podlegać osobnym profilom API, importu/eksportu i federacji. Nie należy deklarować formalnej certyfikacji na podstawie roboczej listy.

## Pytania do pilotażu

Jak rozpoznawać pilność? Jak rozwiązywać spory o właściwość? Jak prowadzić kilka spraw dla jednej potrzeby? Jak długo przechowywać dokumenty i kto ma do nich dostęp? Kiedy i jak poinformować anonimowego zgłaszającego? Jakie decyzje wymagają drugiej osoby?
