# Interoperacyjność i federacja — NSS-001
Status: analiza wstępna, nie norma. Źródła do szczegółowej weryfikacji i audytu licencji: https://wiki.open311.org/GeoReport_v2/ ; https://docs.openreferral.org/ ; https://www.w3.org/TR/vocab-dcat-3/ ; https://www.w3.org/TR/activitypub/ ; https://cloudevents.io/ .
Open311: opcjonalne mapowanie zgłoszeń usług miejskich, nie pełnego modelu potrzeb. HSDS: katalog organizacji, usług i lokalizacji, nie zobowiązań. DCAT: odkrywanie zbiorów i usług danych, nie katalog wszystkich spraw. ActivityPub: kandydat na publiczne aktualności, nie protokół wiążących decyzji. CloudEvents: opcjonalna koperta zdarzeń, nie semantyka domenowa.
## Kandydaci
NSS-INT-REQ-001: identyfikator obiektu wraz z identyfikatorem wystawcy; zachować powiązania źródłowe, nie scalać na podstawie podobieństwa nazw.
NSS-INT-REQ-002: wymiana określa typ, wersję, wystawcę, czas, zakres widoczności i pochodzenie informacji; odbiorca może nie obsługiwać rozszerzenia.
NSS-INT-REQ-003: odróżnić publikację, przekazanie, odbiór, przyjęcie do rozpatrzenia i zobowiązanie; żadna synchronizacja nie tworzy mandatu.
NSS-INT-REQ-004: aktualizacja, korekta, wycofanie i wygaśnięcie informacji mają jawne znaczenie; odbiorca rozpoznaje nieaktualność; nie obiecywać usunięcia wszystkich kopii.
NSS-INT-REQ-005: powtórzone dostarczenie tej samej informacji nie tworzy kolejnego zobowiązania; konflikty wersji rozpatrywane z zachowaniem źródła.
NSS-INT-REQ-006: udostępniać tylko dane potrzebne i uprawnione; federacja domyślnie nie replikuje danych prywatnych.
NSS-INT-REQ-007: możliwa wymiana papierowa, telefoniczna i ręczna; profile cyfrowe opcjonalne, bez wymogu centralnej tożsamości.
## Granice
Wystawca odpowiada za własny zapis, nie za wszystkie kopie. Publiczne ogłoszenie nie jest zamówieniem. Uwierzytelnienie techniczne nie dowodzi prawdziwości ani kompetencji. Wersje, licencje, bezpieczeństwo i konkretne formaty wymagają dalszego audytu. Powiązania RFC 0003, NSS-004,005,008,009,010,013,014; CS027–030. Testy niewykonane.
