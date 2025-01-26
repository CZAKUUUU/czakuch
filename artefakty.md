# Artefakty projektu

1. **Interfejs www urzędnika**
2. **Aplikacja mobilna**
3. **Moduł zbierania danych**
4. **Moduł zbierania danych z satelity**
5. **Moduł zbierania danych z otwartych źródeł**
6. **Moduł generowania raportów**


# Artefakt 1: Moduł zbierania danych z satelity

## Użytkownicy
- Analitycy danych przestrzennych – pracownicy agencji kosmicznych, instytucji geodezyjnych i planistycznych.
- Organy państwowe i organizacje międzynarodowe – zainteresowane analizą zniszczeń w czasie rzeczywistym.

## Źródła danych
- Aktualne obrazy satelitarne dostarczane przez Polską Agencję Kosmiczną.
- Zasoby archiwalne i dane z satelitów komercyjnych (np. Maxar, Sentinel).

## Wymagania

### Funkcjonalne
- Automatyczne pobieranie i integracja zdjęć satelitarnych w czasie rzeczywistym.
- Obsługa obrazów w wysokiej rozdzielczości (min. 0.5 m/piksel).
- Możliwość różnicowania danych (zdjęcia przed i po zniszczeniach).
- Interfejs API do integracji z innymi modułami.

### Wydajnościowe
- Pobranie i przetworzenie danych z obszaru 100 km² w czasie nie dłuższym niż 2 godziny.
- Wsparcie dla analizy obrazów w partiach (minimum 1 TB danych miesięcznie).

### Bezpieczeństwa
- Szyfrowanie przesyłanych danych (SSL/TLS).
- Ograniczenie dostępu wyłącznie dla autoryzowanych użytkowników.
- Regularne tworzenie kopii zapasowych danych (min. raz na dobę).

---

# Artefakt 2: Moduł zbierania danych z otwartych źródeł

## Użytkownicy
- Specjaliści OSINT – pracownicy monitorujący sytuację w regionach dotkniętych konfliktem.
- Agencje wywiadowcze i bezpieczeństwa narodowego – zainteresowane analizą otwartych źródeł informacji.

## Źródła danych
- Serwisy informacyjne i raporty (np. TASS, UNIAN, BlackSeaNews).
- Dane ze źródeł społecznościowych (np. Telegram, Twitter, YouTube).
- Oficjalne strony rządowe oraz rejestry publiczne (np. plany urbanistyczne, przetargi).

## Wymagania

### Funkcjonalne
- Automatyczne skanowanie i analiza tekstu, zdjęć i wideo z otwartych źródeł.
- Wykrywanie fake newsów za pomocą AI (np. analiza wzorców językowych).
- Klasyfikacja danych według kategorii (np. infrastruktura, ludność, środowisko).

### Wydajnościowe
- Przetwarzanie danych z min. 100 stron internetowych dziennie.
- Aktualizacja wyników analizy w czasie rzeczywistym (maks. 15 minut opóźnienia).

### Bezpieczeństwa
- Monitorowanie legalności pobieranych danych (zgodność z przepisami RODO).
- Anonimizacja danych użytkowników wrażliwych (np. osób występujących w materiałach).

---

# Artefakt 3: Moduł generowania raportów

## Użytkownicy
- Rządy i organizacje międzynarodowe – potrzebujące szczegółowych analiz w celu planowania odbudowy.
- Instytucje statystyczne i badawcze – analizujące koszty i wpływ konfliktu.

## Źródła danych
- Wyniki z modułu analizy zdjęć satelitarnych.
- Dane z modułu OSINT (raporty, materiały wizualne, dane statystyczne).
- Ceny surowców i usług z rynków budowlanych.

## Wymagania

### Funkcjonalne
- Generowanie szczegółowych raportów w formatach PDF i interaktywnych (np. mapy GIS).
- Możliwość dodawania załączników (zdjęcia, wideo, wykresy).
- Automatyczne kalkulowanie szacunkowych kosztów odbudowy na podstawie aktualnych danych rynkowych.

### Wydajnościowe
- Tworzenie raportu dla obszaru 10 km² w czasie nieprzekraczającym 30 minut.
- Obsługa jednoczesnego generowania 5 raportów bez spadku wydajności.

### Bezpieczeństwa
- Ograniczenie dostępu do raportów (autoryzacja użytkowników na podstawie ról).
- Ochrona przed nieautoryzowanym kopiowaniem danych (np. znaki wodne).
