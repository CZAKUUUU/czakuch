## **Przypadek użycia: UC01 - Generowanie raportu przez urzędnika**
**Aktorzy:** Urzędnik  
**Priorytet:** Wysoki  

### **Scenariusz główny**  
1. Urzędnik loguje się do systemu.  
2. Urzędnik wybiera obszar geograficzny do analizy.  
3. Urzędnik wybiera zakres czasowy analizy (np. przedział konfliktu).  
4. Urzędnik określa typ danych do uwzględnienia w raporcie (np. szkody infrastrukturalne, koszty odbudowy).  
5. System generuje raport w wybranym formacie (PDF, interaktywna mapa).  
6. Urzędnik pobiera raport.  

### **Rozszerzenia**  
- **3.A.** Urzędnik dodaje komentarze lub opisy do raportu.  
- **4.A.** Urzędnik włącza dane z zewnętrznych źródeł (np. OSINT, AI).  

---

## **Przypadek użycia: UC02 - Zgłaszanie szkód przez obywatela**
**Aktorzy:** Obywatel  
**Priorytet:** Wysoki  

### **Scenariusz główny**  
1. Obywatel loguje się do aplikacji mobilnej.  
2. Obywatel wybiera opcję „Zgłoś szkodę”.  
3. Obywatel uzupełnia formularz zgłoszenia (opis, lokalizacja, zdjęcia).  
4. Obywatel przesyła zgłoszenie do systemu.  
5. System potwierdza przyjęcie zgłoszenia i nadaje numer sprawy.  

### **Rozszerzenia**  
- **3.A.** Obywatel załącza dodatkowe dokumenty (np. akty własności).  
- **5.A.** Obywatel monitoruje status zgłoszenia w aplikacji.  

---

## **Przypadek użycia: UC03 - Tworzenie sprawy przez urzędnika**
**Aktorzy:** Urzędnik  
**Priorytet:** Średni  

### **Scenariusz główny**  
1. Urzędnik loguje się do systemu.  
2. Urzędnik wybiera opcję „Utwórz nową sprawę”.  
3. Urzędnik przypisuje zgłoszenie obywatela do sprawy.  
4. Urzędnik dodaje własne notatki lub dokumenty do sprawy.  
5. System zapisuje sprawę w bazie danych.  

### **Rozszerzenia**  
- **3.A.** Urzędnik przypisuje sprawę do innego departamentu.  

---

## **Przypadek użycia: UC04 - Weryfikacja zgłoszenia przez urzędnika**
**Aktorzy:** Urzędnik  
**Priorytet:** Wysoki  

### **Scenariusz główny**  
1. Urzędnik loguje się do systemu.  
2. Urzędnik wybiera zgłoszenie do weryfikacji.  
3. Urzędnik analizuje załączone dane (zdjęcia, opisy).  
4. Urzędnik zatwierdza lub odrzuca zgłoszenie.  
5. System aktualizuje status zgłoszenia i informuje obywatela.  

### **Rozszerzenia**  
- **3.A.** Urzędnik prosi obywatela o uzupełnienie brakujących informacji.  

---

## **Przypadek użycia: UC05 - Wysyłanie powiadomień do obywatela**
**Aktorzy:** System  
**Priorytet:** Średni  

### **Scenariusz główny**  
1. System identyfikuje zmiany statusu zgłoszeń obywatela.  
2. System generuje powiadomienie o zmianie statusu.  
3. System wysyła powiadomienie do aplikacji mobilnej obywatela.  

---

## **Przypadek użycia: UC06 - Pobieranie danych z satelity**
**Aktorzy:** System  
**Priorytet:** Wysoki  

### **Scenariusz główny**  
1. System łączy się z bazą danych satelitarnej (np. Polskiej Agencji Kosmicznej).  
2. System pobiera aktualne zdjęcia dla wybranego obszaru.  
3. System zapisuje zdjęcia w bazie danych.  

### **Rozszerzenia**  
- **2.A.** System porównuje zdjęcia z wcześniejszymi danymi w celu identyfikacji zniszczeń.  

---

## **Przypadek użycia: UC07 - Analiza danych z otwartych źródeł**
**Aktorzy:** System  
**Priorytet:** Wysoki  

### **Scenariusz główny**  
1. System identyfikuje nowe dane w otwartych źródłach (np. portale informacyjne).  
2. System pobiera dane tekstowe, obrazy lub wideo.  
3. System klasyfikuje dane według kategorii.  
4. System zapisuje dane w bazie danych.  

### **Rozszerzenia**  
- **2.A.** System weryfikuje autentyczność danych za pomocą algorytmów AI.  

---

## **Przypadek użycia: UC08 - Tworzenie cyklicznych raportów**
**Aktorzy:** Urzędnik  
**Priorytet:** Średni  

### **Scenariusz główny**  
1. Urzędnik loguje się do systemu.  
2. Urzędnik wybiera opcję „Utwórz cykliczny raport”.  
3. Urzędnik określa harmonogram generowania raportów.  
4. System automatycznie generuje raporty zgodnie z harmonogramem.  

### **Rozszerzenia**  
- **3.A.** Urzędnik dodaje niestandardowe parametry do raportu.  

---

## **Przypadek użycia: UC09 - Zarządzanie użytkownikami systemu**
**Aktorzy:** Administrator  
**Priorytet:** Średni  

### **Scenariusz główny**  
1. Administrator loguje się do systemu.  
2. Administrator dodaje nowych użytkowników (urzędników).  
3. Administrator przypisuje role i uprawnienia użytkownikom.  
4. System zapisuje zmiany w konfiguracji użytkowników.  

---

## **Przypadek użycia: UC10 - Monitorowanie spraw przez obywatela**
**Aktorzy:** Obywatel  
**Priorytet:** Wysoki  

### **Scenariusz główny**  
1. Obywatel loguje się do aplikacji mobilnej.  
2. Obywatel wybiera opcję „Moje zgłoszenia”.  
3. System wyświetla listę zgłoszeń obywatela wraz ze statusem.  
4. Obywatel wybiera szczegóły wybranego zgłoszenia.  

### **Rozszerzenia**  
- **3.A.** Obywatel zgłasza zastrzeżenia do decyzji urzędnika.  
