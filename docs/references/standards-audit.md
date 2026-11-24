# NSS-001 — audyt standardów i metodyk

Status: wersja wstępna; rekomendacje nie są jeszcze decyzjami normatywnymi. Zadanie #2 pozostaje otwarte.

## Kryteria

Zakres, status publikacji, wersja, możliwość działania bez komputera, koszt wdrożenia, interoperacyjność i prawa do ponownego wykorzystania tekstu. Dostępność dokumentu nie jest równoznaczna z otwartą licencją.

## Zweryfikowane źródła pierwotne

| Źródło | Zastosowanie | Paper-first | Rekomendacja |
| --- | --- | --- | --- |
| [IETF BCP 14 — RFC 2119 i 8174](https://www.rfc-editor.org/info/bcp14/) | Poziomy wymagań normatywnych | Tak | Przyjąć konwencję słów kluczowych, zdefiniować polskie odpowiedniki w NSS-005 |
| [OECD Guidelines for Citizen Participation Processes, 2022](https://doi.org/10.1787/f765caf6-en) | Projektowanie partycypacji, dostępność, informacja zwrotna i ocena | Tak | Adaptować w NSS-006, własne sformułowania |
| [OMG CMMN 1.1](https://www.omg.org/spec/CMMN/1.1) | Sprawy o zmiennym przebiegu | Model można interpretować ręcznie | Analiza mapowania pojęć w NSS-004; nie wymagać silnika ani pełnej notacji |
| [OMG BPMN 2.0.2](https://www.omg.org/spec/BPMN/2.0.2) | Powtarzalne procedury | Diagramy możliwe na papierze | Opcjonalny sposób dokumentowania procesów |
| [W3C DCAT 3](https://www.w3.org/TR/vocab-dcat/) | Katalogi danych i usług danych | Nie jako pełny profil techniczny | Odłożyć do konkretnego przypadku wymiany danych |
| [Open Referral HSDS 3.0.1 — governance](https://docs.openreferral.org/en/latest/about/specification-governance.html) | Dane usług społecznych; wzorzec zarządzania specyfikacją | Model pojęciowy tak, wymiana maszynowa nie | Opcjonalny przyszły profil; HSDS deklaruje CC BY-SA 4.0, sprawdzić zakres przed adaptacją |

## Kolejka dalszej weryfikacji

IAP2 Spectrum, Decidim Social Contract, Open311 GeoReport v2, W3C PROV, OMG DMN, GOV.UK Assisted Digital, ISO 18091, ISO 10002, Sociocracy 3.0, Scrum, Kanban. Ustalić źródła pierwotne, wersje i warunki licencyjne. Dla każdego wskazać konkretne wymaganie lub przypadek użycia.

## Wstępna decyzja projektowa do konsultacji

Rdzeń ma własne wymagania proceduralne i testy. BCP 14 to kandydat do bezpośredniego wykorzystania konwencji specyfikacji; OECD i CMMN to kandydaci do adaptacji pojęć i praktyk. BPMN nie jest obowiązkowy. Profile cyfrowe nie są warunkiem zgodności papierowej. Nie deklarujemy zgodności z zewnętrzną normą bez mapowania wymagań i odpowiednich dowodów.

## Licencje

Poza wskazaną deklaracją HSDS szczegółowe warunki kopiowania, tłumaczenia, używania znaków i adaptacji pozostają do sprawdzenia. Na tym etapie stosujemy wyłącznie odsyłacze i własne opisy. Nie przenosimy całych tabel, diagramów ani tekstów norm. Decyzja licencyjna projektu należy do NSS-002.

## Następne kroki

- Uzupełnić źródła i licencje dla kolejki.
- Porównać CMMN z modelem ZG/PO/SP i pięcioma stanami, w tym przerwanie działania oraz wiele równoległych działań.
- Przypisać rekomendacje do zadań NSS-004–010 i NSS-013.
- Przed zamknięciem #2 zatwierdzić macierz oraz rozróżnienie zależności normatywnych od inspiracji.
