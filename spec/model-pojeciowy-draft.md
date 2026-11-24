# Model pojęciowy Nasza Sprawa v0.1 — projekt

Status: kandydat NSS-004, nie zastępuje spec/README.md. Konsolidacja RFC 0001–0003, analiz w docs/references i CS001–034. Weryfikacja źródeł, licencji i testów pozostaje otwarta.

## Uczestnictwo
Uczestnik: osoba lub podmiot działający w kontekście. Osoba nie wymaga konta. Organizacja i grupa mogą być autonomiczne; grupa nie musi mieć osobowości prawnej. Członkostwo, rola i mandat są kontekstowe i odrębne. Obszar geograficzny, tematyczny i organizacyjny jest wielowartościową klasyfikacją, nie mandatem. Pośrednik zapisuje i przekazuje, przedstawiciel działa w granicach upoważnienia.

## Informacje i motywacje
ZG: oryginalne zgłoszenie z identyfikatorem, wystawcą, kanałem i pochodzeniem. Może zawierać wiele potrzeb, pomysłów lub ofert. PO: potrzeba, pożądana zmiana lub stan; wiele ZG może wskazywać tę samą PO. Problem: przeszkoda w zaspokojeniu potrzeby. Pomysł: propozycja rozwiązania lub przedsięwzięcia, nie zobowiązanie. Możliwość: rozpoznana szansa współpracy. Zasób: dostępny potencjał materialny lub niematerialny; kompetencja: zdolność uczestnika; dostępność: warunki czasowe i ilościowe. Oferta: deklaracja gotowości udostępnienia zasobu lub wykonania pracy, nie zobowiązanie. Zapotrzebowanie: określony brak zasobu lub zdolności w danym kontekście.

## Organizacja współpracy
SP: sprawa, jednostka odpowiedzialnego rozpatrywania jednej potrzeby w określonym zakresie; zachować dotychczasowy model jednej PO na SP do czasu uzgodnienia zmiany. Inicjatywa: zamierzone wspólne przedsięwzięcie, może powstać z pomysłu, oferty lub potrzeby, obejmować wiele SP i działań; nie wymaga uprzedniego ZG. Projekt: opcjonalna forma organizacji inicjatywy z określonym zakresem, czasem i zasobami; nie obowiązkowy typ rdzenia. Inicjatywa może być indywidualna, społeczna, komercyjna, publiczna lub mieszana. Każda organizacja zachowuje własny mandat i rejestr.
Działanie: jednostka pracy z zakresem, kryterium zakończenia i odpowiedzialnością po przyjęciu; zadanie jako operacyjna nazwa działania, nie osobna obowiązkowa encja. Zobowiązanie: potwierdzony zakres odpowiedzialności, nie automatycznie umowa prawna. Kontrybucja: uzgodniony wkład w inicjatywę lub działanie, powiązany z zobowiązaniem i ewentualną ofertą oraz zapotrzebowaniem. Jedna potrzeba zasobowa może być pokrywana wieloma kontrybucjami, jedna oferta może zostać podzielona bez podwójnego liczenia. Odróżniać uzgodnienie, dostarczenie, wykorzystanie, zwrot i rozliczenie. Zwierzęta wymagają odrębnej oceny dobrostanu i opieki (CS027).

## Decyzje i wiedza
Decyzja: rozstrzygnięcie w granicach mandatu z uzasadnieniem, kryteriami, podstawą i datą. Przeszkoda: warunek blokujący lub ograniczający realizację; nie status całej sprawy. Warunek powrotu: przesłanka ponownej oceny, nie automatycznej akceptacji. Zdarzenie: zapis zmiany lub czynności z pochodzeniem. Dowód: materiał wspierający ocenę, nie gwarancja prawdziwości. Rezultat: obserwowany efekt działania. Ocena: porównanie efektu z kryteriami i potrzebą. Doświadczenie: wniosek do wykorzystania później. Bank pomysłów: widok zachowanych propozycji i decyzji zgodnie z retencją, nie osobna obowiązkowa encja.

## Niezależne cykle życia
SP: dotychczasowe NOWA, W_ROZPATRZENIU, W_DZIALANIU, DO_WERYFIKACJI, ZAMKNIETA. Działanie: kandydaci PROPONOWANE, PRZYJETE, W_REALIZACJI, WYKONANE, PRZERWANE. Blokada jako cecha. Oferta i zobowiązanie odrębne; cykle do dopracowania. Nie wyprowadzać automatycznie statusu potrzeby ze statusu sprawy. Odbiór informacji, przyjęcie do rozpatrzenia i zobowiązanie odrębne. Zamknięcie sprawy nie oznacza zaspokojenia potrzeby.

## Relacje i reguły
ZG ↔ PO wiele do wielu; PO → SP zero lub wiele; SP → PO jedna w aktualnym rdzeniu. Inicjatywa ↔ SP zero lub wiele po obu stronach (kandydat); inicjatywa → zapotrzebowania i działania; działanie może należeć do SP lub inicjatywy, zakres odpowiedzialności jednoznaczny. Oferta → uzgodnione kontrybucje; kontrybucja → zobowiązanie oraz opcjonalne zapotrzebowanie. Decyzje, dowody i zdarzenia odnoszą się do identyfikowalnych obiektów. Identyfikator wystawcy + lokalny ID; wersja, pochodzenie, widoczność i retencja. Papier równoważny proceduralnie. Brak centralnej tożsamości, obowiązkowej bazy danych lub technologii.

## Otwarte decyzje
Czy inicjatywa jest osobną encją rdzenia czy profilem? Jak modelować inicjatywy bez PO bez naruszenia istniejącego SP? Czy kontrybucja zawsze wymaga osobnego rekordu zobowiązania czy wystarczy semantycznie odrębne potwierdzenie? Jak obsługiwać wiele zapotrzebowań w jednym wkładzie i częściowe dostawy? Jak mapować lokalne statusy? Rozstrzygnąć przez testy CS001,013–015,018–027,028–034. Następnie macierz pojęcie–wymaganie–test i przegląd wszystkich 34 przypadków. Nie deklarować wykonania testów ani zamknięcia NSS-001/004.
