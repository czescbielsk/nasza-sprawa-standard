# Relacje modelu — projekt NSS-004
Status: propozycja do przeglądu, nie norma. Rozwija model-pojeciowy-draft.md i CS001–035.
## Kardynalności
Notacja A -> B: liczba B na A; odwrotność podana osobno.
- ZG -> PO 0..n, PO -> ZG 0..n. Zachować oryginały; ZG może zawierać ofertę lub pomysł bez PO.
- PO -> SP 0..n, SP -> PO 1 (utrzymanie aktualnego rdzenia).
- PO <-> pomysł 0..n po obu stronach.
- PO <-> inicjatywa 0..n po obu stronach.
- SP <-> inicjatywa 0..n po obu stronach.
- Inicjatywa: samodzielny kandydat rdzenia, cel i co najmniej jeden potwierdzony organizator, bez obowiązkowej PO/ZG/SP.
- SP lub inicjatywa -> działanie 0..n; działanie ma co najmniej jeden kontekst pracy i jednoznaczny zakres odpowiedzialności, może mieć dodatkowe powiązania. Nie duplikować pracy przy współdzieleniu.
- Uczestnik <-> rola kontekstowa 0..n; każda rola ma uczestnika i kontekst, mandat odrębny; organizacja <-> obszar 0..n; obszar nie nadaje mandatu.
- Zasób <-> oferta 0..n; oferta może dotyczyć pracy bez osobnego zasobu. Oferta -> kontrybucja 0..n, kontrybucja -> oferta 0..n (bez obowiązkowej wcześniejszej publikacji). Zapotrzebowanie <-> kontrybucja 0..n; alokacja określa ilość, jednostkę, termin i warunki, nie podwaja pokrycia. Kontrybucja wymaga potwierdzonego zobowiązania, niekoniecznie osobnego fizycznego rekordu. Strony i zakres jawne dla uprawnionych. Rozróżnić dostępność, rezerwację, dostarczenie, wykorzystanie, zwrot i rozliczenie.
- Działanie -> rezultat 0..n; rezultat -> działanie 0..n (efekt może wynikać z wielu działań lub czynników zewnętrznych). Ocena wskazuje rezultat, kryteria i kontekst potrzeby lub celu. Nie zakładać przyczynowości.
- Decyzja, zdarzenie, dowód, przeszkoda i warunek powrotu odnoszą się do co najmniej jednego identyfikowalnego obiektu. Decyzja ma decydenta i podstawę mandatu; dowód ma pochodzenie, nie jest automatycznie ustaleniem.
## Konflikt i interwencja (CS035)
Podmiot wskazany w zgłoszeniu nie staje się automatycznie odpowiedzialny ani uczestnikiem. Rola podmiotu, którego dotyczy sprawa, odrębna od właściciela sprawy, wykonawcy i decydenta. Powiązanie zarzutu z podmiotem wymaga oznaczenia źródła i statusu weryfikacji. Zawiadomienie, odbiór, wszczęcie kontroli, ustalenie, decyzja i wykonanie odrębne. Obowiązek prawny nie jest dobrowolnym zobowiązaniem; rejestr może odnotować udokumentowany obowiązek i podstawę bez nadawania kompetencji. Pilne zagrożenie poza zwykłą kolejką. Nie wymagać zgody podmiotu na formalną interwencję. Prywatność, korekty i stanowiska stron.
## Minimalizacja
Kardynalność semantyczna nie oznacza osobnego formularza ani tabeli. Mała inicjatywa może mieć jedną kartę zawierającą cel, organizatora, działanie, uzgodniony wkład i rezultat. Identyfikatory wystawcy i lokalne, powiązania zewnętrzne nie przenoszą mandatu. Papier równoważny proceduralnie.
## Weryfikacja kandydacka
CS001: wiele ZG jedna PO; CS013: zainteresowanie nie zamówienie; CS018–021: warunki powrotu; CS025–026: autonomiczne rejestry; CS027: inicjatywa bez ZG, alokacje i zwroty; CS028–030: niezależni wystawcy; CS031–034: pośrednictwo; CS035: konflikt, obowiązek prawny i brak automatycznego przypisania winy. Testy niewykonane.
Otwarte: szczegółowe cykle życia, reprezentacja alokacji częściowych, rozstrzygnięcie granic rdzenia, macierz wszystkich 35 przypadków. Nie zamyka NSS-004.
