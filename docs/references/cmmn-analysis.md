# Analiza CMMN 1.1 — NSS-001

Status: propozycja do review, nie decyzja normatywna.
Źródło: [OMG CMMN 1.1, grudzień 2016](https://www.omg.org/spec/CMMN/1.1), [opis OMG](https://www.omg.org/cmmn/), [rejestr problemów](https://issues.omg.org/issues/spec/CMMN/1.1). Pełne warunki licencyjne wymagają dalszej weryfikacji. Poniższa analiza jest własnym mapowaniem, nie kopią normy.

## Mapowanie

| NSS | CMMN | Ograniczenie |
| --- | --- | --- |
| Sprawa | Case / instancja modelu | NSS nadaje znaczenie społeczne i mandat |
| Dokumentacja | Case File | Dostęp i retencja są odrębnymi wymaganiami NSS |
| Dokument / informacja | Case File Item | Zgłoszenie i potrzeba zachowują własną tożsamość domenową |
| Działanie | Task | Przyjęcie odpowiedzialności wymaga potwierdzenia |
| Grupa działań | Stage | Nie musi odpowiadać statusowi sprawy |
| Kamień milowy | Milestone | Nie jest dowodem rozwiązania potrzeby |
| Warunek | Sentry | Analogowo: zdarzenie i sprawdzalny warunek |
| Uczestnik | Case Role | Nie oznacza automatycznie kompetencji prawnej |

## Luki obecnego rdzenia

- Pięć statusów sprawy nie opisuje równoległych działań; ich stany powinny być niezależne.
- Brak ścieżki przerwania działania po utracie zasobów lub mandatu.
- Weryfikacja może odbywać się dla pojedynczego działania, bez zatrzymywania pozostałych.
- Przyjęcie do rozpatrzenia nie oznacza przyjęcia zobowiązania.
- Ponowne otwarcie NSS nie jest automatycznie odpowiednikiem przejścia CMMN.
- Plan może ewoluować; każda zmiana wymaga zapisu, uzasadnienia i wskazania uprawnionego podmiotu.

## Proponowane minimum do NSS-004 i NSS-005

Oddzielić status sprawy od statusu działania. Kandydaci dla działania: PROPONOWANE, PRZYJETE, W_REALIZACJI, WYKONANE, PRZERWANE; weryfikację zapisywać osobno. Każde działanie ma własny ID, odpowiedzialnego po przyjęciu, warunki rozpoczęcia i kryterium zakończenia. Przerwanie wymaga uzasadnienia i decyzji o dalszym postępowaniu. Zamknięcie sprawy wymaga rozliczenia wszystkich aktywnych zobowiązań, niekoniecznie rozwiązania potrzeby. To propozycja, nie odwzorowanie stanów wykonawczych CMMN.

## Test analogowy — bezpieczne dojście do przystanku

ZG-001 i ZG-002 wiążemy z PO-001 i SP-001. Równolegle: A1 dokumentacja problemu przez mieszkańców, A2 przekazanie informacji zarządcy, A3 konsultacja możliwych rozwiązań. A1 wykonane nie kończy sprawy. A2 wysłane nie oznacza przyjęcia zobowiązania zarządcy. A3 można przerwać z powodu braku uczestników i zaplanować ponownie. Nowe dowody mogą uzasadnić nowe działanie, bez usuwania historii. Efekt oceniamy oddzielnie od zadań.

Na papierze: karta sprawy, tabela działań (ID, stan, odpowiedzialny, warunek, kryterium efektu), dziennik zdarzeń. Test zaliczony, jeśli da się odtworzyć równoległość, przerwanie, zmianę planu i granice kompetencji. Scenariusz hipotetyczny.

## Rekomendacja

Adaptować koncepcję adaptacyjnego zarządzania sprawami, nie wymagać pełnej zgodności CMMN, XML ani silnika. Pełny opcjonalny profil CMMN może powstać po pilotażu, z osobnym mapowaniem i testami. BPMN pozostaje opcjonalny dla przewidywalnych podprocesów. OMG publikuje również otwarte problemy specyfikacji, dlatego ewentualny profil musi wskazać wersję i interpretację niejednoznaczności.

Powiązania: #2, #5, #6, #11. Nie zamykać NSS-001 na podstawie tej analizy.
