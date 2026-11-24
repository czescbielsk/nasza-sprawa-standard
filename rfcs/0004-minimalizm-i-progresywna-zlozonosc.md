# RFC 0004 — Minimalizm i progresywna złożoność
Status: uzgodniony kierunek projektowy; wymagania kandydackie, nie norma. NSS-004/005/010/011/014.
## Zasada
Standard zmniejsza koszt współpracy, nie tworzy dodatkowej administracji. Celem implementacji cyfrowej jest prostsze wykonanie porównywalnej czynności niż przygotowanie kartki lub wiadomości e-mail. Papier pozostaje pełnoprawnym kanałem. Nie wymagamy znajomości modelu domenowego od uczestnika.
## Minimalny rdzeń — propozycja
Wspólna semantyka identyfikowalności i pochodzenia, intencji, kontekstu, odpowiedzialności i mandatu (gdy powstaje), decyzji i uzasadnienia (gdy zapada), istotnych zmian, rezultatu i oceny (gdy dostępne), prywatności, korekty oraz dostępności. Nie wszystkie obiekty ani pola są wymagane w każdej interakcji. Jedna karta może reprezentować wiele pojęć. Zgłoszenie nie wymaga utworzenia SP ani PO przez autora. Inicjatywa może powstać bez ZG. Przyjęcie zgłoszenia wymaga treści i kontekstu niezbędnego do zrozumienia; identyfikator, czas i kanał nadaje odbiorca lub implementacja. Kontakt opcjonalny, chyba że konkretna czynność lub prawo go wymaga. Nie publikować automatycznie danych ani nie domniemywać zobowiązania.
## Kandydaci
NSS-SIM-REQ-001: przyjęcie prostej intencji bez obowiązkowego konta, klasyfikacji domenowej i tworzenia dodatkowych obiektów przez autora, z uwzględnieniem prawnych wyjątków.
002: pozyskiwać dodatkowe dane dopiero gdy potrzebne; wyjaśnić cel obowiązkowego pola.
003: nie wymagać osobnego formularza dla każdego pojęcia; ponownie wykorzystywać dane z zachowaniem pochodzenia i uprawnień.
004: umożliwić stopniowe rozszerzanie dokumentacji bez utraty oryginału i historii; nie wymuszać migracji na inny standard.
005: automatyzacja może sugerować klasyfikację, powiązania i streszczenia, ale nie zmienia intencji ani nie podejmuje zobowiązań bez właściwej podstawy.
006: testować koszt całego procesu dla autora i odbiorcy, nie tylko czas wypełnienia formularza. Porównywać z papierem, telefonem i e-mailem; uwzględnić korekty, dostępność, odpowiedź i błędy. Cel użyteczności, nie gwarancja uniwersalnej przewagi czasowej.
007: minimalizm nie znosi wymogów bezpieczeństwa, prawa, prywatności i rozliczalności.
## Poziomy użycia
Minimalny: jedna karta lub wiadomość, prosta odpowiedzialność i wynik. Rozszerzony: zadania, zapotrzebowania, kontrybucje, decyzje. Złożony: niezależne rejestry, dowody, zależności, formalne interwencje. To przykłady stopniowego rozwijania, nie poziomy certyfikacji.
## Testy kandydackie
SIM-T01 sąsiedzki grill na jednej karcie; SIM-T02 zgłoszenie telefoniczne bez konta; SIM-T03 oferta bez obowiązkowej PO; SIM-T04 rozwinięcie szopki z jednej karty do rejestru wkładów; SIM-T05 konflikt środowiskowy z zachowaniem dowodów i mandatów; SIM-T06 korekta błędnej klasyfikacji; SIM-T07 porównanie z e-mailem i papierem na tych samych zadaniach, z pomiarem czasu, liczby czynności, błędów i pracy odbiorcy. Testy niewykonane.
