# Dokumentacja Inicjalizacji Projektu

## Część 1: Informacje ogólne o projekcie
1. **PostConflict Solution**  
   Analiza szkód wojennych i opracowanie narzędzi wspomagających szacowanie kosztów odbudowy.
2. Projekt koncentruje się na opracowaniu systemu do analizy zniszczeń wojennych na podstawie danych multimedialnych, raportów i analiz rynkowych. System umożliwi planowanie odbudowy oraz prognozowanie kosztów.

---

## Część 2: Cel i uzasadnienie realizacji projektu

### Zakres projektu
Projekt zakłada opracowanie kompleksowego systemu do analizy szkód wojennych, który integruje zaawansowane technologie sztucznej inteligencji, analizy danych i wizualizacji. Główne elementy projektu obejmują:

1. **Integrację danych multimedialnych:**  
   System centralizuje dane takie jak zdjęcia satelitarne (zarówno archiwalne, jak i aktualne), filmy i fotografie terenowe. Dane te są wykorzystywane do porównywania stanu przed i po konflikcie.

2. **Analiza sztucznej inteligencji (AI):**  
   W projekcie zastosowane będą algorytmy AI, które automatycznie analizują różnice między obrazami, identyfikują zniszczenia infrastruktury i krajobrazu oraz klasyfikują obiekty według poziomu uszkodzeń. Algorytmy te będą trenowane na danych historycznych i wykorzystają techniki deep learning, takie jak sieci konwolucyjne (CNN), do analizy obrazów.

3. **Estymacja kosztów odbudowy:**  
   Moduł oblicza koszty na podstawie danych o aktualnych cenach surowców i usług budowlanych oraz danych historycznych. Uwzględniane są także lokalne przepisy budowlane i plany zagospodarowania terenu.

4. **Generowanie raportów:**  
   Narzędzie automatycznie tworzy raporty dla interesariuszy, zawierające wizualizacje, analizy statystyczne i prognozy. Raporty są dostępne w różnych formatach (np. PDF, interaktywne prezentacje) i wspierają proces decyzyjny.

5. **Moduły wspomagające decyzje:**  
   System uwzględnia także dynamiczne scenariusze odbudowy, które pomagają w określaniu priorytetów i przewidywaniu potencjalnych trudności.

### Cele projektu
1. **Technologiczne:**  
   - Rozwój i implementacja zaawansowanych algorytmów sztucznej inteligencji do analizy danych wizualnych.  
   - Zbudowanie dynamicznego systemu, który automatycznie aktualizuje prognozy na podstawie nowych danych.  
   - Stworzenie platformy, która pozwoli użytkownikom na łatwą interakcję z danymi.

2. **Społeczne:**  
   - Pomoc w efektywnej odbudowie terenów dotkniętych wojną poprzez precyzyjną identyfikację zniszczeń i oszacowanie kosztów.  
   - Udostępnienie narzędzi dla organizacji międzynarodowych, samorządów i lokalnych społeczności.

3. **Biznesowe:**  
   - Redukcja kosztów operacyjnych związanych z ręczną analizą i raportowaniem.  
   - Poprawa efektywności planowania odbudowy poprzez dostarczanie danych w czasie rzeczywistym.

### Uzasadnienie projektu
Projekt odpowiada na pilną potrzebę efektywnego planowania i zarządzania procesami odbudowy terenów dotkniętych wojną. Dzięki zastosowaniu AI i integracji danych multimedialnych, system pozwoli na szybsze i dokładniejsze analizy, co przyczyni się do lepszego wykorzystania zasobów. Automatyzacja i wizualizacja wyników analizy dostarczą decydentom praktycznych informacji w przystępnej formie, wspierając podejmowanie decyzji w trudnych warunkach. System zapewni również przejrzystość i bezpieczeństwo danych, co jest kluczowe dla interesariuszy na każdym poziomie organizacyjnym.

---

## Część 3: Realizacja projektu

## Artefakty

### 1. Baza Danych Multimedialnych
Baza danych multimedialnych to centralne repozytorium, w którym przechowywane są różnorodne dane wizualne, takie jak zdjęcia satelitarne (archiwalne i aktualne), filmy oraz fotografie. Repozytorium umożliwia użytkownikom łatwy dostęp do zgromadzonych materiałów oraz ich integrację z zaawansowanymi systemami analizy. Dzięki tej bazie użytkownicy mogą porównywać obrazy sprzed i po konflikcie w celu dokładnej identyfikacji zniszczeń. Mechanizmy weryfikacji i filtrowania automatycznie eliminują dane o niskiej jakości, takie jak obrazy zniekształcone przez dym, cienie lub inne czynniki środowiskowe. System obsługuje wyszukiwanie danych według lokalizacji, daty i rodzaju zniszczeń, co wspiera precyzyjną analizę i generowanie szczegółowych raportów wizualnych. Baza danych stanowi fundament dla dalszej analizy i jest kluczowym elementem systemu.

---

### 2. Moduł Analizy Zniszczeń
Moduł analizy zniszczeń to zaawansowane narzędzie wykorzystujące algorytmy sztucznej inteligencji (AI) do analizy wizualnych danych wejściowych. Jego głównym celem jest identyfikacja różnic między obrazami przed i po konflikcie, co pozwala określić zniszczenia budynków, infrastruktury oraz krajobrazów. Moduł został zaprojektowany z wykorzystaniem technik deep learning, takich jak konwolucyjne sieci neuronowe (CNN), co pozwala na skuteczne wykrywanie zniszczeń nawet w trudnych warunkach, takich jak mała rozdzielczość zdjęć czy ukryte uszkodzenia. Dane generowane przez moduł stanowią podstawę do dalszych analiz, w tym oszacowania kosztów odbudowy. Dodatkowo, moduł integruje się z bazami danych planów zagospodarowania terenu i kosztów budowlanych, co pozwala na precyzyjne określanie strat materialnych.

---

### 3. System Estymacji Kosztów Odbudowy
System estymacji kosztów odbudowy odpowiada za dokładne obliczanie kosztów związanych z odbudową infrastruktury i budynków na terenach dotkniętych wojną. System uwzględnia aktualne ceny surowców budowlanych, usług oraz dane historyczne z archiwalnych przetargów. Wykorzystuje zaawansowane modele predykcyjne, które analizują dostępne dane, aby tworzyć szczegółowe prognozy finansowe. System automatycznie dostosowuje prognozy do bieżących zmian rynkowych i generuje alternatywne scenariusze, które można wykorzystać w planowaniu odbudowy, szczególnie w sytuacjach braku kompletnych danych. Uwzględnia także lokalne przepisy budowlane, co czyni go praktycznym narzędziem dla samorządów i organizacji odbudowujących.

---

### 4. Moduł Generowania Raportów
Moduł generowania raportów jest narzędziem do automatycznego tworzenia kompleksowych raportów zawierających zdjęcia, dane analityczne i estymacje kosztów. Raporty te są w pełni konfigurowalne i mogą być dostosowane do potrzeb różnych grup interesariuszy, takich jak samorządy, firmy budowlane czy organizacje międzynarodowe. System obsługuje różne formaty eksportu, w tym PDF oraz interaktywne dokumenty online. Dzięki wizualizacjom, wykresom i szczegółowym analizom, raporty wspierają podejmowanie decyzji w sytuacjach kryzysowych. Automatyzacja procesu generowania raportów pozwala na szybkie dostarczanie wyników, co jest kluczowe w dynamicznie zmieniających się warunkach operacyjnych.

---

### 5. Moduł Zbierania Danych z Otwartych Źródeł
Moduł ten jest odpowiedzialny za automatyczne zbieranie danych z dostępnych źródeł, takich jak obrazy satelitarne, plany zagospodarowania terenu czy archiwalne dokumenty. System przeszukuje różne bazy danych i weryfikuje autentyczność pozyskanych materiałów. Mechanizmy filtrowania eliminują dane niekompletne lub nieistotne, co znacząco poprawia jakość wyników analizy. Moduł integruje się z innymi komponentami systemu, dostarczając kluczowe dane do modułów analizy zniszczeń i generowania raportów. Dzięki niemu użytkownicy mają pewność, że analiza opiera się na najbardziej aktualnych i rzetelnych informacjach.

---

### 6. Moduł Walidacji Danych
Moduł walidacji danych to zaawansowane narzędzie zapewniające poprawność i wiarygodność danych używanych w systemie. Wykorzystuje algorytmy AI do analizy danych pod kątem spójności czasowej i przestrzennej, a także porównuje je z innymi źródłami w celu identyfikacji potencjalnych błędów lub nieścisłości. Narzędzie to automatycznie wykrywa fałszywe informacje, nieścisłe dane przetargowe lub błędne zeznania świadków. Zapewnia to wysoką jakość analizy, co jest kluczowe dla interesariuszy polegających na wynikach systemu.

---

### 7. System Wizualizacji Danych
System wizualizacji danych pozwala na przedstawianie wyników analiz w sposób przystępny i intuicyjny. Tworzy interaktywne mapy, wykresy i diagramy, które umożliwiają użytkownikom zrozumienie skali i rodzaju zniszczeń. System integruje dane z różnych modułów analitycznych, co pozwala na tworzenie kompleksowych wizualizacji dostosowanych do potrzeb odbiorców. Dzięki temu narzędzie wspiera podejmowanie decyzji i planowanie odbudowy w oparciu o dane w czasie rzeczywistym.

---

### 8. Interfejs Użytkownika
Interfejs użytkownika został zaprojektowany z myślą o intuicyjnej obsłudze, nawet dla osób niezaznajomionych z zaawansowanymi technologiami. Umożliwia łatwy dostęp do wszystkich funkcji aplikacji, takich jak przeglądanie danych, generowanie raportów czy edytowanie parametrów analizy. Dodatkowo, system pozwala na personalizację interfejsu, co umożliwia użytkownikom dostosowanie aplikacji do swoich potrzeb operacyjnych i analitycznych.

---

### 9. Mechanizm Backupu i Archiwizacji
Mechanizm ten zapewnia regularne tworzenie kopii zapasowych i archiwizację danych, co chroni je przed utratą w przypadku awarii systemu. Mechanizm obejmuje wszystkie kluczowe dane, takie jak obrazy, raporty i analizy, zapewniając ich długoterminową dostępność. Jest zgodny z międzynarodowymi standardami bezpieczeństwa danych, co gwarantuje ochronę przed nieautoryzowanym dostępem.

---

### 10. Moduł Zarządzania Ryzykiem
Moduł zarządzania ryzykiem analizuje potencjalne problemy związane z realizacją projektu, takie jak błędy w danych wejściowych, problemy techniczne lub zmienne koszty odbudowy. Opracowuje scenariusze alternatywne i proponuje rozwiązania minimalizujące skutki ryzyk. Dzięki temu użytkownicy mogą podejmować lepsze decyzje oparte na dokładnych analizach ryzyk i ich wpływu na proces odbudowy.

---

## Etapy Pracy

### 1. Projektowanie
Projektowanie to kluczowy etap, w którym określana jest struktura całego systemu. Obejmuje opracowanie szczegółowego projektu interfejsów, logiki działania oraz architektury. Tworzone są szkice koncepcyjne, mapy ścieżek użytkownika oraz interaktywne makiety, które następnie są testowane z użytkownikami. Projektowanie responsywnych interfejsów uwzględnia potrzeby różnych grup użytkowników, a tworzone biblioteki komponentów UI pomagają w standaryzacji wyglądu. Projektanci dbają także o zgodność systemu z zasadami dostępności i przepisami prawnymi, w tym RODO. Przygotowywana dokumentacja projektowa jest podstawą dla kolejnych etapów.

---

### 2. Określenie Celów Projektu
Na tym etapie definiowane są cele projektu, które stanowią fundament dla dalszych działań. Zespół analizuje potrzeby biznesowe oraz techniczne, by wyznaczyć priorytety. Ważnym elementem jest identyfikacja grupy docelowej oraz przeprowadzenie wywiadów z interesariuszami, co pozwala lepiej zrozumieć ich oczekiwania. Opracowane scenariusze użytkowania pomagają w przewidywaniu interakcji użytkowników z systemem. Równocześnie prowadzona jest analiza konkurencji, co umożliwia identyfikację braków na rynku i tworzenie unikalnych rozwiązań.

---

### 3. Analiza Wymagań
Etap ten skupia się na zbieraniu wymagań funkcjonalnych i niefunkcjonalnych. Przeprowadzane są ankiety i obserwacje użytkowników w kontekście ich działań, a także testy użyteczności konkurencyjnych rozwiązań. Na podstawie wyników badań definiowane są ograniczenia systemowe i weryfikowana zgodność wymagań z celami biznesowymi. Priorytetyzacja i dokumentowanie wymagań umożliwia sprawne zarządzanie zmianami w projekcie. Ostateczne specyfikacje wymagań są weryfikowane z interesariuszami i zespołem technicznym.

---

### 4. Budowa Architektury Systemu
Zespół architektów projektuje strukturę modułów i wybiera technologie oraz narzędzia. Tworzone są diagramy komponentów, przepływu danych oraz schematy integracji zewnętrznych API. Analizowane są wymagania dotyczące danych, w tym ich struktura i mechanizmy kontroli dostępu. Na tym etapie definiowana jest strategia bezpieczeństwa, skalowalności oraz mechanizmy backupu i odzyskiwania danych. Optymalizacja architektury pod kątem wydajności i zgodności z założeniami jest kluczowa dla sukcesu projektu.

---

### 5. Tworzenie Modułu Zbierania Danych
Moduł ten odpowiada za automatyczne pobieranie danych z otwartych źródeł, takich jak zdjęcia satelitarne, plany zagospodarowania terenu czy raporty. Opracowywane są mechanizmy anonimizacji i filtrowania danych oraz narzędzia do monitorowania nowych źródeł. Tworzone są również algorytmy identyfikacji duplikatów oraz systemy oceny jakości danych. Automatyzacja procesu pozwala na sprawne zarządzanie danymi i zapewnia ich wysoką jakość.

---

### 6. Szkolenie i Implementacja Algorytmów AI
Na tym etapie inżynierowie AI tworzą modele sztucznej inteligencji zdolne do analizy danych wizualnych, takich jak zdjęcia satelitarne. Modele są trenowane na danych historycznych, co pozwala im dokładnie identyfikować różne rodzaje zniszczeń. Implementowane algorytmy wspierają identyfikację błędów w danych i optymalizują proces przetwarzania informacji. Opracowywane są również mechanizmy predykcyjne, które wspierają dalsze etapy projektu.

---

### 7. Tworzenie Modułów Aplikacyjnych
Moduły takie jak aplikacja mobilna czy system generowania raportów są projektowane i implementowane w sposób zintegrowany z innymi komponentami systemu. Tworzone są interaktywne prototypy, które następnie są testowane pod kątem użyteczności. Zespół programistów pracuje nad responsywnością, wydajnością i funkcjonalnością aplikacji. Na tym etapie wprowadzane są również systemy analityczne i raportowe, które umożliwiają generowanie kompleksowych analiz dla interesariuszy.

---

### 8. Testowanie i Walidacja
Testowanie obejmuje zarówno testy funkcjonalne, jak i wydajnościowe. Zespół testerów przeprowadza walidację zgodności wymagań z celami biznesowymi oraz sprawdza aplikację w warunkach rzeczywistych. Testy UX i użyteczności pomagają w identyfikacji obszarów wymagających optymalizacji. Testowane są również mechanizmy bezpieczeństwa i backupu. Na podstawie wyników testów wprowadzane są poprawki i aktualizowana dokumentacja projektowa.

---

### 9. Wdrożenie i Utrzymanie
Ostatnim etapem jest wdrożenie systemu oraz jego bieżące utrzymanie. Opracowywane są strategie aktualizacji i rozwoju systemu, a także plany utrzymania aplikacji. Zespół zapewnia szkolenia dla użytkowników końcowych oraz przygotowuje interaktywne samouczki. Monitorowane są wydajność i zużycie zasobów, a także wprowadzane ulepszenia w oparciu o opinie użytkowników i dane analityczne.


---

## Część 4: Zespół Projektowy

### **1. Architekt Systemu**  
**Opis:**  
Architekt systemu odpowiada za zaprojektowanie ogólnej struktury aplikacji oraz zapewnienie, że wszystkie jej komponenty współpracują ze sobą efektywnie. Jego zadaniem jest wybór odpowiednich technologii, dbanie o skalowalność, elastyczność oraz bezpieczeństwo systemu.  

**Wymagania:**  
- Minimum 5 lat doświadczenia w projektowaniu systemów informatycznych.  
- Dogłębna znajomość wzorców projektowych i architektury mikroserwisów.  
- Umiejętność wyboru technologii (frontend, backend, bazy danych, chmura) odpowiednich do specyfikacji projektu.  
- Doświadczenie w projektach o dużej skali i złożoności, obejmujących analizy geograficzne oraz AI.  
- Znajomość protokołów bezpieczeństwa i narzędzi ochrony danych (np. szyfrowanie, firewalle).  
- Umiejętność projektowania skalowalnych i odpornych na awarie systemów.  
- Certyfikaty, takie jak TOGAF, będą dodatkowym atutem.  

---

### **2. UX/UI Designer**  
**Opis:**  
Projektant UX/UI odpowiada za tworzenie intuicyjnego i estetycznego interfejsu użytkownika. Skupia się na zrozumieniu potrzeb użytkowników oraz zaprojektowaniu interfejsów, które będą zarówno funkcjonalne, jak i atrakcyjne wizualnie.  

**Wymagania:**  
- Minimum 3 lata doświadczenia w projektowaniu interfejsów użytkownika.  
- Znajomość narzędzi do prototypowania, takich jak Figma, Adobe XD lub Sketch.  
- Doświadczenie w projektowaniu aplikacji mobilnych i webowych zgodnych z zasadami UX.  
- Znajomość zasad projektowania dostępności (WCAG).  
- Umiejętność przeprowadzania testów użyteczności z użytkownikami końcowymi.  
- Doświadczenie w tworzeniu design systemów i spójnych interfejsów wizualnych.  
- Portfolio zawierające projekty związane z tworzeniem aplikacji opartej na analizie danych.  

---

### **3. Tester Oprogramowania**  
**Opis:**  
Tester oprogramowania jest odpowiedzialny za zapewnienie, że aplikacja działa zgodnie z wymaganiami, jest wolna od błędów oraz spełnia standardy jakości. Jego praca obejmuje zarówno testy manualne, jak i automatyczne.  

**Wymagania:**  
- Minimum 2 lata doświadczenia w testowaniu aplikacji mobilnych i webowych.  
- Znajomość narzędzi do automatyzacji testów, takich jak Selenium, JMeter lub Cypress.  
- Doświadczenie w tworzeniu planów testowych i scenariuszy testowych.  
- Znajomość podstawowych metodyk Agile i DevOps.  
- Umiejętność raportowania błędów i współpracy z zespołem programistów.  
- Wiedza na temat testowania aplikacji związanych z analizą danych i integracjami API.  

---

### **4. Front-End Developer**  
**Opis:**  
Front-End Developer zajmuje się tworzeniem interfejsu aplikacji, z którym użytkownicy będą wchodzić w interakcje. Implementuje projekt graficzny w funkcjonalną i responsywną stronę internetową lub aplikację.  

**Wymagania:**  
- Minimum 3 lata doświadczenia w tworzeniu aplikacji webowych.  
- Bardzo dobra znajomość HTML, CSS, JavaScript oraz frameworków takich jak React, Angular lub Vue.js.  
- Doświadczenie w implementacji responsywnych interfejsów użytkownika (RWD).  
- Umiejętność pracy z narzędziami do kontroli wersji, takimi jak Git.  
- Znajomość zasad optymalizacji wydajności interfejsów użytkownika.  
- Doświadczenie w integracji aplikacji z API.  

---

### **5. Back-End Developer**  
**Opis:**  
Back-End Developer jest odpowiedzialny za logikę aplikacji oraz zarządzanie danymi i integracją z zewnętrznymi systemami. Tworzy i utrzymuje serwery, API oraz bazy danych.  

**Wymagania:**  
- Minimum 3 lata doświadczenia w programowaniu back-endowym.  
- Znajomość języków takich jak Python, Java, C#, Ruby lub PHP.  
- Doświadczenie z frameworkami, np. Django, Flask, Spring Boot.  
- Znajomość baz danych SQL i NoSQL (np. PostgreSQL, MongoDB).  
- Doświadczenie w budowaniu i integracji API RESTful.  
- Wiedza na temat bezpieczeństwa aplikacji i ochrony danych.  

---

### **6. AI Engineer**  
**Opis:**  
AI Engineer opracowuje modele sztucznej inteligencji, które analizują dane wizualne i przestrzenne. Jego praca koncentruje się na projektowaniu algorytmów wykorzystywanych w analizie zniszczeń.  

**Wymagania:**  
- Minimum 2 lata doświadczenia w pracy z algorytmami uczenia maszynowego.  
- Znajomość języków takich jak Python oraz bibliotek ML/AI (TensorFlow, PyTorch, scikit-learn).  
- Doświadczenie w projektowaniu i trenowaniu modeli opartych na sieciach neuronowych.  
- Znajomość technik przetwarzania obrazu (computer vision).  
- Doświadczenie w pracy z dużymi zbiorami danych oraz narzędziami big data.  

---

### **7. GIS Specialist**  
**Opis:**  
Specjalista GIS analizuje dane geograficzne i przestrzenne, aby wspierać system w generowaniu map i wizualizacji geograficznych. Współpracuje z zespołem przy integracji danych przestrzennych.  

**Wymagania:**  
- Minimum 2 lata doświadczenia w pracy z systemami GIS.  
- Znajomość narzędzi takich jak QGIS, ArcGIS, Google Earth Engine.  
- Doświadczenie w analizie i wizualizacji danych przestrzennych.  
- Znajomość formatów danych geograficznych, np. GeoJSON, shapefile.  
- Umiejętność integracji danych GIS z aplikacjami webowymi.  

---

### **8. Specjalista ds. Integracji Danych**  
**Opis:**  
Specjalista ds. integracji danych odpowiada za łączenie danych z różnych źródeł, takich jak zdjęcia satelitarne, plany zagospodarowania terenu i raporty.  

**Wymagania:**  
- Minimum 2 lata doświadczenia w procesach ETL (Extract, Transform, Load).  
- Znajomość narzędzi takich jak Apache NiFi, Talend, Informatica.  
- Umiejętność pracy z bazami danych SQL i NoSQL.  
- Doświadczenie w integracji danych z zewnętrznych API.  
- Znajomość zasad czyszczenia i przetwarzania danych.  

---

### **9. Ekspert Prawny**  
**Opis:**  
Ekspert prawny zapewnia, że wszystkie działania projektu są zgodne z obowiązującymi przepisami prawnymi, w tym prawem międzynarodowym i lokalnym.  

**Wymagania:**  
- Wykształcenie prawnicze z doświadczeniem w prawie międzynarodowym.  
- Znajomość regulacji dotyczących odbudowy infrastruktury w rejonach objętych konfliktami.  
- Doświadczenie w ochronie danych osobowych (RODO, GDPR).  
- Umiejętność analizy przepisów związanych z zamówieniami publicznymi.  

---

### **10. Specjalista ds. Cyberbezpieczeństwa**  
**Opis:**  
Specjalista ds. cyberbezpieczeństwa chroni system przed zagrożeniami, zapewniając bezpieczeństwo danych i aplikacji.  

**Wymagania:**  
- Minimum 3 lata doświadczenia w obszarze cyberbezpieczeństwa.  
- Znajomość narzędzi do analizy bezpieczeństwa, takich jak Nessus, Metasploit.  
- Doświadczenie w zabezpieczaniu API oraz systemów bazodanowych.  
- Znajomość standardów bezpieczeństwa, np. OWASP, ISO 27001.  

---

### **11. Pentester**  
**Opis:**  
Pentester przeprowadza testy penetracyjne, aby wykryć luki w systemach i aplikacjach. Symuluje ataki hakerskie, aby sprawdzić odporność na zagrożenia.  

**Wymagania:**  
- Minimum 3 lata doświadczenia w testach penetracyjnych.  
- Znajomość narzędzi takich jak Burp Suite, Kali Linux, Metasploit.  
- Doświadczenie w testach bezpieczeństwa sieci i aplikacji webowych.  
- Znajomość technik ataków, takich jak SQL Injection, XSS, CSRF.  
- Certyfikaty, takie jak CEH, OSCP, będą dodatkowym atutem.  

---

### **12. Ekspert ds. odbudowy infrastruktury**  
**Opis:**  
Ekspert ds. odbudowy infrastruktury tworzy strategie odbudowy terenów dotkniętych wojną, bazując na analizach i danych systemowych.  

**Wymagania:**  
- Wykształcenie w zakresie inżynierii budowlanej lub pokrewnych dziedzin.  
- Minimum 5 lat doświadczenia w realizacji projektów budowlanych.  
- Znajomość nowoczesnych technologii budowlanych i zarządzania projektami.  
- Doświadczenie w oszacowywaniu kosztów odbudowy infrastruktury.  
- Umiejętność analizy zniszczeń i planowania odbudowy na podstawie danych wizualnych i przestrzennych.  

---

## Część 5: Budżet Projektu

Budżet projektu został podzielony na kluczowe kategorie, aby zapewnić odpowiednią alokację środków na każdą fazę realizacji. Poniżej przedstawiono szczegóły:

### 1. Research and Analysis
**Przeznaczenie:**  
Badania rynkowe, analiza użytkowników, przeprowadzanie wywiadów z interesariuszami oraz zbieranie danych wejściowych.  
**Przydzielony budżet:** 600 000 PLN

---

### 2. Development (AI, Backend, Frontend)
**Przeznaczenie:**  
Projektowanie i implementacja modułów aplikacji, w tym sztucznej inteligencji, backendu, frontendowego interfejsu oraz integracji API.  
**Przydzielony budżet:** 1 800 000 PLN

---

### 3. Infrastructure and Tools
**Przeznaczenie:**  
Zakup i utrzymanie serwerów, narzędzi chmurowych, baz danych oraz niezbędnego oprogramowania do zarządzania projektem i danymi.  
**Przydzielony budżet:** 1 200 000 PLN

---

### 4. Testing and QA
**Przeznaczenie:**  
Testowanie funkcjonalne, wydajnościowe oraz zgodności systemu. Zespół QA przeprowadzi także testy penetracyjne i użyteczności.  
**Przydzielony budżet:** 500 000 PLN

---

### 5. Training and Documentation
**Przeznaczenie:**  
Szkolenie zespołu oraz użytkowników końcowych, tworzenie dokumentacji technicznej i użytkowej.  
**Przydzielony budżet:** 400 000 PLN

---

### 6. Risk Mitigation Reserve
**Przeznaczenie:**  
Rezerwa na ryzyko związane z nieprzewidzianymi kosztami, takimi jak zmienne ceny surowców, opóźnienia czy błędy w implementacji.  
**Przydzielony budżet:** 1 000 000 PLN


---

## Część 6: Wymagania Techniczne

### 1. Wymagania sprzętowe
- **Serwery i infrastruktura chmurowa:**  
  System wymaga skalowalnych serwerów do przetwarzania dużych ilości danych multimedialnych (zdjęcia satelitarne, filmy, modele AI). Zalecane są serwery z co najmniej:
- **Karty graficzne:**  
  Dla modułów AI wymagane są karty graficzne z obsługą CUDA
- **Urządzenia końcowe:**  
  Minimalne wymagania dla użytkowników korzystających z aplikacji mobilnej lub webowej:

---

### 2. Wymagania programowe
- **System operacyjny:**  
  - Serwery: Linux (Ubuntu 20.04 LTS, CentOS 8) jako główny system operacyjny.  
  - Klient: Kompatybilność z systemami Windows 10+, macOS 11+, Android 10+, iOS 13+.
- **Języki programowania:**  
  - Backend: Python (Django/Flask), Node.js.
  - Frontend: React.js/Angular.
  - AI: Python z bibliotekami TensorFlow, PyTorch.
- **Bazy danych:**  
  - Relacyjne: PostgreSQL dla danych strukturalnych.
  - NoSQL: MongoDB dla przechowywania danych multimedialnych i nieustrukturyzowanych.
- **Inne narzędzia:**  
  - Docker/Kubernetes: Do zarządzania kontenerami i orkiestracji aplikacji.
  - Git: Do kontroli wersji kodu.
  - Jenkins/CircleCI: Do automatyzacji procesów CI/CD.

---

### 3. Wymagania dotyczące bezpieczeństwa
- **Szyfrowanie danych:**  
  Wszystkie dane w tranzycie i w spoczynku powinny być szyfrowane przy użyciu standardu AES-256.
- **Ochrona dostępu:**  
  Wdrożenie systemu uwierzytelniania wieloskładnikowego (MFA) oraz kontrola dostępu oparta na rolach (RBAC).
- **Testy penetracyjne:**  
  Regularne testy bezpieczeństwa prowadzone przez pentesterów, aby wykrywać i usuwać potencjalne luki w systemie.
- **Zgodność z regulacjami:**  
  System musi być zgodny z RODO i innymi lokalnymi przepisami dotyczącymi ochrony danych.

---

### 4. Wymagania sieciowe
- **Przepustowość:**  
  Minimalna przepustowość łącza internetowego dla serwerów powinna wynosić 1 Gbps, z opcją zwiększenia do 10 Gbps w przypadku przetwarzania dużych zestawów danych.
- **Redundancja sieciowa:**  
  Serwery muszą być podłączone do redundantnych połączeń sieciowych w celu zapewnienia wysokiej dostępności.
- **Zapory sieciowe i VPN:**  
  Wdrożenie zaawansowanych zapór ogniowych (firewall) oraz sieci VPN do zabezpieczenia połączeń zdalnych.

---

### 5. Wymagania dotyczące przechowywania danych
- **System przechowywania danych:**  
  - S3-kompatybilne magazyny danych w chmurze dla danych multimedialnych.
  - LOKALNE RAID 10 dla bezpieczeństwa i wydajności w przypadku krytycznych operacji.
- **Replikacja danych:**  
  Codzienna replikacja danych do lokalizacji zapasowej w celu zabezpieczenia przed awariami.
- **Backup:**  
  Regularne tworzenie kopii zapasowych, co najmniej raz dziennie, z możliwością odzyskania danych w ciągu 24 godzin.

---

### 6. Wymagania wydajnościowe
- **Czas odpowiedzi:**  
  System musi zapewniać czas odpowiedzi poniżej 1 sekundy dla podstawowych operacji użytkowników.
- **Przetwarzanie danych:**  
  Algorytmy AI powinny analizować obrazy i generować raporty w czasie nie dłuższym niż 5 minut dla zestawu 100 zdjęć.
- **Skalowalność:**  
  System musi być w stanie obsłużyć jednocześnie 10 000 użytkowników aktywnych.

---

### 7. Wymagania integracyjne
- **Integracja z systemami zewnętrznymi:**  
  System powinien umożliwiać integrację z:
  - API mapowych (np. Google Maps, OpenStreetMap).
  - Zewnętrznymi bazami danych (np. źródła satelitarne, rządowe rejestry).
- **API:**  
  System musi posiadać otwarte API RESTful z obsługą autoryzacji OAuth2.

---

### 8. Wymagania dotyczące dostępności
- **Dostępność systemu:**  
  Wysoka dostępność (99.9%) z minimalnym czasem przestoju dzięki wykorzystaniu rozwiązań chmurowych.
- **Optymalizacja mobilna:**  
  System musi działać sprawnie na urządzeniach mobilnych przy minimalnym zużyciu baterii i pamięci.

---

### 9. Wymagania dotyczące zarządzania danymi
- **Standardy formatowania danych:**  
  Wszystkie dane muszą być przechowywane w ustalonych formatach, takich jak GeoJSON, CSV, czy TIFF dla danych geograficznych.
- **Kontrola wersji danych:**  
  Wdrożenie systemu do śledzenia zmian w danych i zarządzania konfliktami w źródłach danych.
- **Anonimizacja:**  
  Mechanizmy anonimizacji danych w celu ochrony prywatności użytkowników.
