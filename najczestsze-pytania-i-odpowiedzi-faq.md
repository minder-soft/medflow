---
icon: seal-question
---

# Najczęstsze Pytania i Odpowiedzi (FAQ)

Poniżej prezentujemy pogłębione odpowiedzi na najczęściej zadawane pytania dotyczące MedFlow, aby ułatwić zrozumienie funkcjonalności systemu i rozwiać ewentualne wątpliwości.

***

#### 1. Czy MedFlow przechowuje nagrania audio sesji?

**Odpowiedź:**\
Nie, MedFlow **nie zapisuje** plików audio w żadnej trwałej formie. Pliki dźwiękowe są wykorzystywane wyłącznie w trakcie **tymczasowego procesu transkrypcji**, polegającego na konwersji mowy na tekst (funkcja Web Speech API i wewnętrznych algorytmów AI). Po zakończeniu transkrypcji, wszelkie dane audio są natychmiast usuwane z systemu. Zapisywany i przechowywany jest jedynie wynik tekstowy (transkrypcja), natomiast sam dźwięk nie podlega archiwizacji. Dzięki temu system spełnia wymogi minimalizacji danych (RODO) i chroni prywatność uczestników sesji.

***

#### 2. Czy MedFlow może być traktowany jako narzędzie diagnostyczne lub wyrób medyczny?

**Odpowiedź:**\
Nie, MedFlow **nie jest** produktem medycznym i **nie** pełni funkcji narzędzia diagnostycznego w rozumieniu Rozporządzenia (UE) 2017/745 (MDR). Stanowi wsparcie administracyjne, ułatwiające gromadzenie dokumentacji (np. transkrypcji rozmów, raportów, ankiet). Ostateczną odpowiedzialność za diagnozę medyczną, terapeutyczną czy decyzje dotyczące leczenia ponoszą wyłącznie specjaliści. MedFlow, poprzez automatyzację transkrypcji czy zbieranie danych z ankiet, **wspomaga** proces analizy, ale nie zastępuje profesjonalnej wiedzy i doświadczenia użytkownika.

***

#### 3. Jak przenieść sesję z grupy jednorazowych do konkretnego pacjenta?

**Odpowiedź:**\
Aby utrzymać porządek w dokumentacji, każdą sesję można przypisać do pacjenta lub konkretnej grupy. Wystarczy w panelu sesji (np. w zakładce „Zapisane sesje” lub w szczegółach danej sesji) wybrać opcję **„Przenieś sesję”**. Następnie:

1. Wskazujemy grupę/pacjenta docelowego (albo tworzymy nowego pacjenta, jeśli nie istnieje na liście).
2. System automatycznie aktualizuje historię wizyt, a przeniesiona sesja będzie widoczna w kontekście danego pacjenta, co pozwala wygodniej przeglądać komplet zapisów.

***

#### 4. Co zrobić w przypadku błędnej transkrypcji?

**Odpowiedź:**\
Podczas transkrypcji mogą wystąpić błędy związane z niewyraźną mową, szumem tła lub akcentem. MedFlow oferuje różne mechanizmy korygowania zapisu:

1. **Korekta ręczna:** klikając w tekst transkrypcji, użytkownik może bezpośrednio edytować fragment, który został błędnie rozpoznany.
2. **Propozycje AI (ikona „gwiazdki”):** wywołanie sztucznej inteligencji do analizy konkretnego zdania lub frazy; AI zaproponuje alternatywny zapis – użytkownik decyduje, czy go przyjąć czy odrzucić.
3. **Komentarze i notatki:** w trakcie sesji lub tuż po niej można dodać komentarze (również w formie edycji transkrypcji) w celu zaznaczenia fragmentu do ewentualnej poprawki później.

***

#### 5. Czy muszę mieć pisemną zgodę pacjenta na przetwarzanie jego danych w MedFlow?

**Odpowiedź:**\
Kwestia zgody jest regulowana przez lokalne i unijne przepisy dotyczące ochrony danych osobowych (RODO), a także ustaw krajowych dot. świadczenia usług zdrowotnych. W większości przypadków:

* **Jeśli wykorzystujesz MedFlow w ramach praktyki terapeutycznej, psychologicznej czy medycznej**, powinieneś mieć prawidłową podstawę prawną do przetwarzania danych pacjentów (może to być np. wyraźna zgoda pacjenta lub konieczność realizacji usługi zdrowotnej).
* Gromadzenie i przetwarzanie danych wrażliwych, takich jak informacje o zdrowiu, wymaga szczególnej dbałości i dokumentowania zgody lub innej podstawy (np. art. 9 ust. 2 lit. h RODO).\
  Zalecamy konsultację z prawnikiem lub specjalistą ds. ochrony danych, aby zapewnić pełną zgodność z prawem.

***

#### 6. Jak wygenerować raport z przeprowadzonej sesji?

**Odpowiedź:**\
Po zakończeniu transkrypcji i ewentualnych korektach użytkownik może przejść do zakładki **„Raporty”** w obrębie danej sesji:

1. Wybiera jeden z dostępnych **szablonów** raportów standardowych lub własny szablon (jeśli został dodany).
2. System może zaproponować funkcję **„Wnioskowanie AI”** – automatyczne wypełnienie dodatkowych sekcji, np. sugerowanych diagnoz, pytań kontrolnych.
3. Raport generuje się w ciągu kilkunastu sekund–kilku minut (zależnie od długości sesji). Po wygenerowaniu można go pobrać w formacie PDF lub Word, ewentualnie przechowywać w systemie.

***

#### 7. Czy można używać MedFlow na urządzeniach mobilnych?

**Odpowiedź:**\
Tak, MedFlow działa w nowoczesnych przeglądarkach mobilnych (Chrome, Firefox na Androidzie lub Safari, Chrome na iOS). Niemniej pewne aspekty mogą być mniej wygodne:

* **Transkrypcja w czasie rzeczywistym** wymaga zezwolenia w przeglądarce na dostęp do mikrofonu i może być mniej precyzyjna w środowisku z większym hałasem otoczenia.
* **Interfejs** (np. edycja transkrypcji, przesuwanie okien) został zaprojektowany pod kątem ekranu komputerowego i laptopów, więc na małym ekranie telefonu część funkcji może wymagać powiększania lub przewijania.\
  Jednak dla przeglądania i prostych operacji (np. wgląd w historię sesji, generowanie raportów krótkich) korzystanie z urządzeń mobilnych jest możliwe i przydatne w sytuacjach awaryjnych.

***

#### 8. Gdzie i w jaki sposób przechowywane są transkrypcje oraz dane pacjentów?

**Odpowiedź:**\
Wszystkie dane (transkrypcje, wyniki testów, informacje o pacjencie) są gromadzone wyłącznie na **zabezpieczonych serwerach zlokalizowanych w Unii Europejskiej**. MedFlow wykorzystuje infrastrukturę chmurową Google, która:

* Posiada certyfikaty bezpieczeństwa (np. ISO/IEC 27001, 27017, 27018).
* Zapewnia szyfrowanie danych w trakcie przesyłania (TLS/SSL) oraz w spoczynku (at-rest).\
  Takie rozwiązanie pozwala spełnić standardy RODO w zakresie lokalizacji i bezpieczeństwa danych. Ponadto MedFlow wprowadziło polityki anonimizacji i kontroli dostępu, aby tylko uprawnione osoby miały wgląd w treści sesji.

***

#### 9. Czy MedFlow można zintegrować z moim obecnym systemem gabinetowym?

**Odpowiedź:**\
Tak, MedFlow oferuje **integracje** z popularnymi systemami gabinetowymi. Integracja może polegać np. na:

* **Dwukierunkowej wymianie danych**: tworzenie kart pacjentów w systemie gabinetowym i synchronizowanie ich z MedFlow, a także pobieranie raportów z MedFlow bezpośrednio do oprogramowania gabinetowego.
* **API**: Otwarty interfejs programistyczny pozwala integratorom zewnętrznym zbudować niestandardowe rozwiązania pasujące do Twojego środowiska IT.\
  Aby skonfigurować integrację, skontaktuj się z pomocą techniczną MedFlow lub sprawdź szczegółową dokumentację programistyczną (API docs).

***

#### 10. Jak zrezygnować z subskrypcji MedFlow?

**Odpowiedź:**\
Anulowanie subskrypcji odbywa się w sekcji **„Subskrypcja”** albo **„Billing”** w ustawieniach konta:

1. Kliknij przycisk „Anuluj subskrypcję” (lub podobny).
2. Zostaniesz poproszony o potwierdzenie decyzji – czasem jest to ankieta zwrotna, abyśmy mogli poznać powód rezygnacji.
3. Po potwierdzeniu, system automatycznie wyłącza odnowienia płatności przy najbliższym cyklu rozliczeniowym. Jeżeli opłaciłeś już bieżący okres (np. miesiąc), dostęp do funkcji płatnych zostanie zachowany do końca tego okresu, po czym subskrypcja wygaśnie.

***

#### 11. Czy MedFlow obsługuje ankiety diagnostyczne i testy psychologiczne?

**Odpowiedź:**\
Tak, w MedFlow istnieje moduł **„Ankiety i Testy”**, który pozwala:

* Wysyłać do pacjenta gotowe formularze online, np. testy oceny nastroju, ADHD czy kwestionariusze psychometryczne.
* Śledzić wyniki i analizować je w kontekście historii pacjenta.
* Tworzyć własne ankiety niestandardowe lub importować szablony testów z systemów zewnętrznych.\
  Wszystkie dane z ankiet są wiązane z danym pacjentem i można je uwzględnić w raportach sesji, ułatwiając proces diagnozy (choć MedFlow nie diagnozuje samodzielnie – jest to rola specjalisty).

***

#### 12. Co zrobić, jeśli napotykam problemy techniczne (np. mikrofon nie działa)?

**Odpowiedź:**\
W razie trudności z konfiguracją sprzętu audio lub innego problemu związanego z funkcjonowaniem aplikacji MedFlow, sugerujemy:

1. **Sprawdź ustawienia systemowe**: upewnij się, że mikrofon jest włączony i ustawiony jako domyślne urządzenie nagrywania.
2. **Zezwolenia w przeglądarce**: w Chrome/Firefox/Edge wejdź w sekcję „Ustawienia prywatności i bezpieczeństwa” → „Ustawienia witryn” → „Uprawnienia do mikrofonu” i przyznaj zgodę medflow.site.
3. **Aktualizacja sterowników**: w systemach Windows/macOS/Linux aktualne sterowniki audio mogą być kluczowe dla prawidłowego działania.
4. **Kontakt z pomocą techniczną**: jeśli powyższe kroki nie pomogą, zgłoś problem, opisując możliwie dokładnie sytuację (jakie komunikaty o błędzie się pojawiają, jakiego sprzętu używasz). Nasz dział wsparcia przeanalizuje i pomoże Ci szybko przywrócić pełną funkcjonalność.

***

#### 13. W jaki sposób MedFlow chroni dane pacjentów i spełnia wymogi RODO?

**Odpowiedź:**\
MedFlow wdraża szereg procedur i zabezpieczeń zgodnych z **Rozporządzeniem (UE) 2016/679** (RODO):

* **Minimalizacja danych:** system nie przechowuje plików audio, a jedynie przetworzony tekst.
* **Szyfrowanie transmisji (TLS/SSL):** podczas przesyłania danych między przeglądarką a serwerem.
* **Zabezpieczenia serwerów:** hosting w UE, certyfikaty ISO (m.in. ISO/IEC 27001, 27017, 27018).
* **Pseudonimizacja / Anonimizacja:** tam, gdzie jest to potrzebne (np. w testach wewnętrznych i w raportach zbiorczych).
* **Polityki dostępu:** wyłącznie uprawniony użytkownik (specjalista) i upoważniony personel wsparcia technicznego mają wgląd w określone fragmenty danych.\
  Ponadto użytkownik (terapeuta/psycholog) jest zobowiązany do uzyskania właściwej podstawy prawnej do przetwarzania danych pacjentów (np. zgoda pacjenta). Dzięki temu zachowany jest pełen łańcuch zgodności z przepisami o ochronie danych osobowych.

***

#### 14. Czy mogę wykorzystać MedFlow do wideokonferencji z pacjentem?

**Odpowiedź:**\
Tak, MedFlow umożliwia **sesje online**, w których możesz jednocześnie:

* Przeprowadzać wideorozmowę przez zintegrowane narzędzie do wideokonferencji (przeglądarkowe lub dedykowany moduł).
* Nagrywać dźwięk (wyłącznie tymczasowo) i generować transkrypcję w tle.
* Udostępniać ekran (jeżeli trzeba coś pokazać pacjentowi).\
  Warto jednak zadbać o stabilne łącze internetowe (optymalnie powyżej 5 Mb/s) oraz używać **słuchawek z mikrofonem**, by uniknąć efektu sprzężenia. Wówczas jakość transkrypcji i komfort rozmowy będą najwyższe.

***

#### 15. Czy w MedFlow można tworzyć własne raporty i szablony?

**Odpowiedź:**\
Jak najbardziej. Użytkownicy mają możliwość dodawania **własnych szablonów** raportów, które mogą zawierać:

* Unikalny układ sekcji (np. „Opis sytuacji”, „Rekomendacje”, „Plan terapii”).
* Tabelki lub pola do wypełnienia automatycznego przez system (np. dane pacjenta, fragmenty transkrypcji).
* Logo gabinetu lub inne elementy graficzne.\
  Po przygotowaniu własnego szablonu (np. w pliku Word, który następnie można wgrać do MedFlow) raporty generowane są w podobny sposób jak raporty domyślne, z tą różnicą, że wypełniane są spersonalizowane sekcje, co znacząco oszczędza czas i ujednolica dokumentację.

***

#### 16. Jakie modele AI są używane w MedFlow?

**Odpowiedź:**\
Korzystamy z trzech głównych dostawców AI:

* **OpenAI (np. GPT-4, GPT-4o, o1, o3-mini  i podobne warianty)** – głównie do generowania rozbudowanych podsumowań, raportów, korekt stylistycznych.
* **Google Vertex AI (np. Gemini)** – do tłumaczeń i analizy słów kluczowych, sentymentu oraz integracji z chmurowymi usługami Google.
* **Anthropic (Claude 3.5 Sonnet)** – do kreatywnych przekształceń krótszych tekstów, konstruowania pytań w ankietach lub interpretacji komentarzy.

Każdy z tych modeli jest używany w określonych scenariuszach, w zależności od rodzaju zadania i wymagań (np. długość wypowiedzi, kontekst).

***

#### 17. Czy AI zastępuje decyzje specjalisty?

**Odpowiedź:**\
Nie, modele sztucznej inteligencji w MedFlow pełnią **wyłącznie rolę pomocniczą**. Generują podsumowania, sugerują interpretacje czy korekty stylistyczne, ale **nie podejmują** decyzji o charakterze medycznym, diagnostycznym ani terapeutycznym. Ostateczna odpowiedzialność za interpretację wyników i ewentualne wdrożenie zaleceń spoczywa zawsze na specjaliście korzystającym z platformy.

***

#### 18. W jaki sposób dane są przekazywane do modeli AI?

**Odpowiedź:**\
Zanim jakiekolwiek dane (np. fragmenty rozmów, wyniki ankiet) trafią do zewnętrznego modelu, są **anonimizowane** przez MedFlow. Oznacza to, że np. nazwiska, adresy, PESEL, nazwy miejscowości czy inne szczegółowe informacje zostają zaszyfrowane lub zastąpione metadanymi (np. `[pacjent_1]`). Dopiero tak przetworzony tekst jest wysyłany do API dostawcy AI (OpenAI, Google, Anthropic). Po wykonaniu zadania (generowanie podsumowania, korekty) wynik wraca do MedFlow, gdzie może być scalony z oryginalnym kontekstem, ale **bez** ujawniania dodatkowych danych modelowi AI.

***

#### 19. Czy model AI przechowuje dane pacjenta?

**Odpowiedź:**\
W większości wypadków polityka dostawców AI (OpenAI, Google, Anthropic) **nie** pozwala na długotrwałe gromadzenie treści przesyłanych przez klientów, a MedFlow dodatkowo stosuje anonimizację. W efekcie nawet gdyby wystąpiło czasowe buforowanie tekstu przez model, to i tak nie zawiera on żadnych identyfikujących informacji pacjenta. Dodatkowo, MedFlow kończy sesję po uzyskaniu odpowiedzi, dzięki czemu nie ma trwałego „śledzenia” danych przez sam model.

***

#### 20. Jak zapewniana jest zgodność z RODO?

**Odpowiedź:**

1. **Anonimizacja danych** – kluczowy mechanizm, który uniemożliwia modelom zewnętrznym dostęp do informacji pozwalających zidentyfikować pacjenta.
2. **Szyfrowane połączenie (HTTPS/TLS)** – wszystkie przesyłane informacje są chronione przed nieuprawnionym przechwyceniem.
3. **Serwery w UE** – MedFlow stara się kierować przetwarzanie na infrastrukturę w Unii Europejskiej tam, gdzie to możliwe, spełniając wymóg lokalizacji danych.
4. **Umowy powierzenia** – z dostawcami AI zawierane są stosowne umowy (lub korzystamy z ich standardowych warunków), aby zapewnić zgodność z przepisami o ochronie danych.

***

#### 21. Co się dzieje z danymi pacjenta po zakończeniu sesji z AI?

**Odpowiedź:**

* **Plik audio**: nie jest w ogóle przechowywany, a jedynie tymczasowo przetwarzany do transkrypcji.
* **Tekst transkrypcji**: pozostaje w bazie MedFlow na serwerach UE, dopóki użytkownik nie usunie lub nie zanonimizuje go w archiwum.
* **Dane przesłane do AI**: były w formie zanonimizowanej i nie są dalej przechowywane przez model – tym bardziej, że np. OpenAI, Google i Anthropic zapewniają w swoich politykach wzmocnioną ochronę danych klientów, a MedFlow dodatkowo minimalizuje przesyłane fragmenty.

***

#### 22. Czy AI może popełnić poważne błędy w interpretacji danych?

**Odpowiedź:**\
Należy pamiętać, że AI generuje wyniki statystycznie poprawne, ale wciąż może wystąpić **błąd interpretacji** lub niewłaściwa sugestia, szczególnie przy nieprecyzyjnych danych. Dlatego kluczowe jest, by specjalista:

1. Zawsze weryfikował wygenerowane rekomendacje i raporty.
2. Nanosił korekty, gdy cokolwiek wyda się niezgodne z realiami sesji.\
   Rolą AI jest **wspomaganie** – decyzje i ostateczne interpretacje należą do doświadczonych profesjonalistów.

***

#### 23. Czy w przyszłości dodacie inne modele AI?

**Odpowiedź:**\
MedFlow stale rozwija się wraz z postępem w dziedzinie sztucznej inteligencji. Jeśli pojawią się nowe, bezpieczne i wartościowe modele, które mogą przynieść korzyści specjalistom w branży medycznej i psychologicznej, rozważamy ich integrację. Wszystkie nowe integracje zawsze będą przebiegać z zachowaniem naszych zasad anonimowości i wysokich standardów ochrony danych.

***

#### 24. Gdzie mogę znaleźć dodatkowe informacje lub zgłosić problemy z AI?

**Odpowiedź:**\
Wszelkie sugestie, pytania czy problemy można kierować:

1. **Bezpośrednio w aplikacji** – w panelu „Pomoc” lub „Kontakt”.
2. **E-mail** – na adres wsparcia technicznego MedFlow, podany w dokumentacji.
3. **Portal Pomocy** – w sekcji FAQ możesz przeszukać artykuły na temat AI, integracji i różnych przypadków użycia.\
   Zespół MedFlow aktywnie reaguje na zgłaszane przypadki, starając się jak najszybciej rozwiązać ewentualne trudności i usprawnić działanie funkcji opartych na sztucznej inteligencji.

