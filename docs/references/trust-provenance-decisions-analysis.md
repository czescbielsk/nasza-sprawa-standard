# Zaufanie, pochodzenie informacji i decyzje — NSS-001

Status: propozycje, nie norma. Źródła sprawdzone 2026-11-24: W3C PROV-DM https://www.w3.org/TR/prov-dm/ (Recommendation 2013); OMG https://www.omg.org/spec/DMN/ (formalna 1.6, beta 1.7), https://www.omg.org/dmn/index.htm oraz model pojęciowy 1.5 https://www.omg.org/spec/DMN/1.5/PDF. Decidim Social Contract https://decidim.org/social-contract/ — niedostępny podczas próby odczytu, analiza źródła i licencji pozostaje otwarta. Nie deklarujemy zgodności ani praw do kopiowania tekstów.

## PROV
Mapowanie: informacja/dokument = Entity, czynność = Activity, odpowiedzialny podmiot = Agent. Rejestrować użycie źródeł, powstanie nowej informacji, korekty i odpowiedzialność. Pochodzenie nie dowodzi prawdziwości; dopuszczalne źródła anonimowe i nieustalone. Wersja publiczna chroni dane. Retencja i prawnie wymagane usunięcie mają pierwszeństwo nad zachowaniem pełnego zapisu. Nie wymagać RDF ani centralnego rejestru.

## DMN
Oddzielić dane, reguły, rekomendację i decyzję właściwego podmiotu. Tabele decyzyjne opcjonalne; brak danych nie jest wynikiem negatywnym bez jawnej reguły. Zapisać wersję kryteriów, źródła, wyjątki i uzasadnienie. Nie automatyzować mandatu. Formalne profile po pilotażu.

## Zaufanie — własne propozycje do późniejszego porównania z Decidim
Przejrzystość procedur, możliwość zakwestionowania informacji, jawność konfliktów interesów, dostępność, poufność oraz kontrola uczestnika nad własnymi zobowiązaniami. Jawność nie oznacza publikacji wszystkich danych.

## Kandydaci
- NSS-INFO-REQ-001: rozróżnić deklarację, obserwację, opinię, hipotezę, ustalenie i formalną decyzję; można oznaczyć informację jako niezweryfikowaną.
- NSS-INFO-REQ-002: zapisać źródło lub jego nieustalony charakter, czas i zakres weryfikacji.
- NSS-INFO-REQ-003: korekta nie może wprowadzać w błąd co do wcześniejszych ustaleń; uwzględnić retencję i prawo usunięcia.
- NSS-DEC-REQ-001: zapisać decydenta, mandat, kryteria, wykorzystane informacje, rozstrzygnięcie i uzasadnienie.
- NSS-DEC-REQ-002: rekomendacja nie oznacza decyzji ani zobowiązania.
- NSS-DEC-REQ-003: udokumentować istotne konflikty interesów i sposób ich obsługi, bez zbędnych danych.
- NSS-DEC-REQ-004: umożliwić zgłoszenie błędu i rozpatrzenie nowych dowodów.

## Testy i zależności
CS001: przekazanie nie jest zobowiązaniem; CS007: sprzeczne stanowiska; CS013: zainteresowanie nie jest przychodem; CS016: sprzeczne dane i korekta; CS017: konflikt interesów. Wszystkie niewykonane. Powiązania NSS-004, 005, 007, 008, 010, 014. Licencje i pełna analiza Decidim pozostają otwarte.
