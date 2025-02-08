# Architektura MedFLOW w kontekście formalnoprawnych wymogów dotyczących rejestracji plików audio

Architektura systemu MedFLOW została zaprojektowana z myślą o zapewnieniu wysokiego poziomu bezpieczeństwa i ochrony danych osobowych, jednocześnie minimalizując ryzyko związane z przechowywaniem informacji wrażliwych. Kluczowym aspektem tej architektury jest fakt, że **MedFLOW nie zapisuje plików audio** – dźwięk jest wykorzystywany jedynie do tymczasowego przetwarzania, czyli generowania transkrypcji, po czym zostaje usunięty. Poniższa analiza uzasadnia, że taki sposób przetwarzania nie wymaga uzyskiwania specjalnej, formalnej zgody na rejestrację dźwięku przy pacjencie, zarówno z perspektywy polskiego prawa, jak i przepisów Unii Europejskiej.

#### 1. Zasada minimalizacji danych i przetwarzania tymczasowego

* **Minimalizacja danych:**\
  Zgodnie z art. 5 Rozporządzenia (UE) 2016/679 (RODO), jednym z kluczowych zasad ochrony danych osobowych jest minimalizacja danych. MedFLOW, przetwarzając dane audio jedynie tymczasowo w celu wygenerowania transkrypcji, nie gromadzi ani nie przechowuje tych plików.
* **Przetwarzanie tymczasowe:**\
  Proces polegający na przetwarzaniu sygnału audio w czasie rzeczywistym i natychmiastowym usuwaniu plików po zakończeniu analizy spełnia wymóg ograniczenia przechowywania danych do niezbędnego minimum, co jest zgodne z zasadą ograniczenia celu określoną w RODO.

#### 2. Brak konieczności specjalnej zgody na przetwarzanie dźwięku

* **Zgoda na przetwarzanie danych osobowych:**\
  Podczas rejestracji oraz konfiguracji konta użytkownik wyraża zgodę na przetwarzanie danych osobowych w ramach funkcjonalności MedFLOW. Ta zgoda obejmuje standardowe operacje niezbędne do świadczenia usługi, w tym tymczasowe przetwarzanie danych audio, które są potrzebne do wygenerowania transkrypcji.
* **Brak trwałego zapisu danych audio:**\
  Ponieważ pliki audio nie są przechowywane ani archiwizowane, a jedynie używane jako środek przetwarzania, nie zachodzi potrzeba uzyskiwania dodatkowej, specjalnej zgody na rejestrację dźwięku. W praktyce, jeśli dane nie są zapisywane w sposób trwały i nie mogą być ponownie wykorzystane w sposób, który naruszałby prywatność pacjenta, dodatkowe wymogi formalne nie mają zastosowania.

#### 3. Odniesienie do obowiązujących przepisów

* **RODO (Rozporządzenie (UE) 2016/679):**\
  RODO wymaga, aby przetwarzanie danych osobowych odbywało się zgodnie z zasadami przejrzystości, minimalizacji oraz ograniczenia celu. Tymczasowe przetwarzanie danych audio w celu transkrypcji, przy czym dane te nie są później przechowywane, wpisuje się w te zasady. W konsekwencji nie jest wymagane uzyskanie dodatkowej zgody wyłącznie z powodu samego faktu przetwarzania dźwięku.
* **Krajowe ustawy o ochronie danych osobowych:**\
  W Polsce ustawa o ochronie danych osobowych, implementująca przepisy RODO, również akcentuje potrzebę ograniczenia zakresu przetwarzania danych do niezbędnego minimum. MedFLOW, działając zgodnie z tymi wymogami, nie narusza obowiązków wynikających z polskiej legislacji.
* **Rozporządzenie (UE) 2017/745 (MDR):**\
  MedFLOW nie jest produktem medycznym i nie podlega wymaganiom dotyczącym wyrobów medycznych określonym w MDR. System służy wyłącznie do celów administracyjnych i wspomagających dokumentację, a nie do diagnostyki czy terapii, co dodatkowo wyklucza konieczność stosowania dodatkowych zgód w kontekście rejestracji audio.
* **Kodeksy etyczne i regulacje branżowe:**\
  Choć w obszarze opieki zdrowotnej istnieją regulacje i kodeksy etyczne dotyczące uzyskiwania zgód na rejestrowanie spotkań, MedFLOW, poprzez swoją architekturę, która eliminuje trwałe przechowywanie plików audio, operuje w ramach standardowych procedur uzyskiwania zgody na przetwarzanie danych osobowych.

#### 4. Podsumowanie

Architektura MedFLOW, oparta na tymczasowym przetwarzaniu plików audio, spełnia kryteria minimalizacji i ograniczenia celu określone w RODO oraz krajowych przepisach o ochronie danych osobowych.\
Ponieważ dane audio nie są przechowywane ani wykorzystywane poza kontekstem jednorazowego procesu transkrypcji, system nie wymaga uzyskania dodatkowej, formalnej zgody na rejestrację dźwięku przy pacjencie. Działanie takie jest zgodne zarówno z przepisami Unii Europejskiej, jak i polskimi regulacjami, co potwierdza, że MedFLOW działa w pełnej zgodności z obowiązującymi normami prawnymi, nie naruszając zasad prywatności ani bezpieczeństwa danych.
