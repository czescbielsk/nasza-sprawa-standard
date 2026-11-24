# Wymagania normatywne v0.1 — projekt konsolidacji
Status: kandydat NSS-005, nie zastępuje spec/README.md. Testy niewykonane. Identyfikatory poniżej mają prefiks NSS-; wcześniejsze identyfikatory kandydackie pozostają do uzgodnienia w macierzy śledzenia. Polska konwencja inspirowana BCP14: MUSI, NIE MOŻE, POWINIEN (odstępstwo uzasadnione), NIE POWINIEN, MOŻE. Obowiązki warunkowe stosuje się tylko gdy zachodzi przesłanka. Brak wymogu implementowania wszystkich opcjonalnych funkcji.
## Rdzeń
- NSS-CORE-001: uczestnictwo NIE MOŻE wymagać znajomości standardu.
- NSS-CORE-002: proces MUSI zapewnić dostępny kanał bez internetu.
- NSS-CORE-003: proces NIE MOŻE wymagać zbędnych danych ani formalności.
- NSS-CORE-004: oryginalna intencja MUSI zostać zachowana.
- NSS-CORE-005: informacja MUSI mieć oznaczone pochodzenie; anonimowe lub nieznane dopuszczalne.
- NSS-CORE-006: istotne decyzje i zmiany MUSZĄ być odtwarzalne w granicach retencji i prawa.
- NSS-CORE-007: proces MUSI respektować autonomię i kompetencje uczestników.
- NSS-CORE-008: standard NIE MOŻE sam nadawać uprawnień ani ustanawiać obowiązków prawnych.
- NSS-CORE-009: proces MUSI umożliwiać korektę błędów.
- NSS-CORE-010: wykonanie działania NIE MOŻE automatycznie oznaczać zaspokojenia potrzeby.
## Przyjęcie informacji
- NSS-IN-001: odbiorca MUSI nadać identyfikator, czas i kanał oraz zachować treść w zakresie zgodnym z prawem.
- NSS-IN-002: autor NIE MOŻE być zobowiązany do tworzenia sprawy, potrzeby, konta lub klasyfikacji bez uzasadnionej konieczności.
- NSS-IN-003: przy pośrednictwie MUSI rozróżnić autora, zapisującego i reprezentanta oraz potwierdzić treść i zakres lub odnotować przyczynę braku potwierdzenia.
- NSS-IN-004: przy łączeniu zgłoszeń MUSI zachować ich odrębne odniesienia.
## Odpowiedzialność i decyzje
- NSS-RESP-001: przy podjęciu działania MUSI określić odpowiedzialność, zakres i kryterium zakończenia oraz podstawę przyjęcia lub mandatu.
- NSS-RESP-002: wskazanie adresata, wysłanie, odbiór, rozpatrzenie i zobowiązanie MUSZĄ pozostać odrębne.
- NSS-RESP-003: oferta NIE MOŻE być traktowana jako przyjęte zobowiązanie; obowiązek prawny dokumentuje się odrębnie.
- NSS-DEC-001: decyzja MUSI mieć decydenta, podstawę mandatu, zakres, datę i uzasadnienie adekwatne do skutków.
- NSS-DEC-002: odmowa MUSI wskazać przeszkody i warunki powrotu lub uzasadnić brak realistycznych warunków.
- NSS-DEC-003: nowe istotne informacje MUSZĄ umożliwić ponowną ocenę, bez automatycznej akceptacji.
- NSS-DEC-004: przy partycypacji MUSI określić zakres wpływu, metodę i decydenta; udokumentować sposób rozpatrzenia wkładu i odpowiedź lub próbę.
- NSS-DEC-005: istotny konflikt interesów MUSI być ujawniony uprawnionym i obsłużony zgodnie z zasadami i prawem.
## Przebieg i rezultaty
- NSS-LC-001: istotna zmiana stanu MUSI mieć czas, aktora, podstawę i uzasadnienie; stany lokalne mogą mapować się na semantykę wspólną.
- NSS-LC-002: zawieszenie MUSI mieć przyczynę, odpowiedzialność i warunek lub termin przeglądu.
- NSS-LC-003: zamknięcie MUSI rozliczyć lub jawnie przekazać pozostające zobowiązania z podstawą; nie uchyla obowiązków prawnych.
- NSS-LC-004: ocena rezultatu MUSI być odrębna od wykonania i wskazywać kryteria, zakres i dostępne dowody; brak wiedzy dopuszczalny.
- NSS-LC-005: przy alokacji zasobów NIE MOŻE podwójnie liczyć tej samej dostępności; deklaracja, uzgodnienie, dostawa, użycie i rozliczenie odrębne.
## Informacja, bezpieczeństwo i interoperacyjność
- NSS-SAFE-001: obserwacje, hipotezy i formalne ustalenia MUSZĄ być rozróżnialne.
- NSS-SAFE-002: pilne zagrożenie NIE MOŻE czekać na głosowanie lub zwykłą kolejkę.
- NSS-SAFE-003: formalna interwencja NIE MOŻE zależeć od zgody podmiotu, którego dotyczy; standard nie zastępuje właściwych procedur.
- NSS-PRIV-001: dostęp MUSI być adekwatny do celu i uprawnień; minimalizacja, retencja, korekta i ochrona danych.
- NSS-INT-001: przy wymianie MUSI zachować wystawcę, identyfikator, pochodzenie i wersję lub równoważne oznaczenie aktualności.
- NSS-INT-002: powtórzona informacja NIE MOŻE tworzyć podwójnego zobowiązania; korekty i wycofania przekazywać uprawnionym odbiorcom w uzasadnionym zakresie.
## Zalecenia i opcje
- NSS-SIM-001: implementacja POWINNA ograniczać ponowne wpisywanie danych i koszt całego procesu; porównanie z papierem i e-mailem.
- NSS-SIM-002: POWINNA umożliwiać stopniowe rozszerzanie dokumentacji bez utraty historii.
- NSS-SIM-003: MOŻE sugerować klasyfikację, powiązania i dopasowania, również AI; nie zmieniać intencji ani mandatu.
- NSS-OPT-001: MOŻE oferować tablice, mapy, głosowania, płatności, harmonogramy, federację i SSO; nie są obowiązkowymi funkcjami rdzenia.
## Weryfikacja wstępna
CORE/IN: CS001,004,008,031–034; RESP: CS022–030; DEC: CS007,009,013,017–021; LC: CS011,023,027,035; SAFE: CS012,035; PRIV: CS004,008,034,035; INT: CS028–030; SIM: RFC0004. To wskazówki, nie pełna macierz ani wyniki testów. Następnie uzgodnić konflikty z dotychczasowym projektem, zakres profili, kryteria testowe i pokrycie wszystkich 35 przypadków. Nie zamyka NSS-005.
