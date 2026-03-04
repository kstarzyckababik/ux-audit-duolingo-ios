# Analiza UX Onboarding aplikacji Duolingo (iOS, wersja darmowa)

## Założenia analizy

Grupa docelowa: młodzież 13-15 lat  
Platforma: iOS  
Wersja: darmowa  

---

## 1. Wybór języka i lokalizacja aplikacji

### Obserwacja
Po uruchomieniu aplikacji onboarding prowadzony jest w języku angielskim. Dopiero po wybraniu ścieżki „for polish speakers” oraz wyborze języka angielskiego jako docelowego, interfejs zmienia się na język polski.

### Potencjalny problem
Brak języka polskiego na pierwszym ekranie może powodować dezorientację u młodszych użytkowników (13-15 lat), szczególnie tych rozpoczynających naukę języka.

### Rekomendacja
Automatyczne wykrywanie języka systemowego lub możliwość wyboru języka interfejsu przed rozpoczęciem onboardingu.

### Priorytet
Średni

---

## 2. Samodzielna ocena poziomu językowego

### Obserwacja
Użytkownik proszony jest o samodzielną ocenę swojego poziomu zaawansowania.

### Potencjalny problem
Użytkownicy w wieku 13-15 lat mogą mieć trudność z obiektywną oceną własnych kompetencji. Może to prowadzić do:
- wyboru zbyt łatwego poziomu (utrata motywacji),
- wyboru zbyt trudnego poziomu (frustracja).

### Rekomendacja
Zastosowanie krótkiego testu adaptacyjnego:
- pytania od najłatwiejszych,
- zakończenie testu po kilku błędnych odpowiedziach,
- automatyczne dopasowanie poziomu.

### Priorytet
Wysoki

---

## 3. Pytanie o motywację nauki

### Obserwacja
Aplikacja pyta użytkownika o powód nauki języka (np. edukacja, praca, podróże). Można wybrać kilka opcji.

### Wątpliwość
Nie jest jasno komunikowane, w jaki sposób odpowiedź wpływa na dalszą ścieżkę nauki.

### Potencjalne ryzyko
Brak transparentności może powodować wrażenie, że pytanie nie ma realnego znaczenia.

### Rekomendacja
Dodanie krótkiej informacji:
„Twoja odpowiedź pomoże nam dopasować tematy lekcji”.

### Priorytet
Niski

---

## 4. Ustalanie dziennego celu i presja streaka

### Obserwacja
Użytkownik wybiera dzienny cel (5-20 minut). Następnie aplikacja informuje o liczbie słów do poznania w pierwszym tygodniu oraz zachęca do utrzymywania serii.

### Pozytywne elementy
- Jasno określony cel
- Widoczna informacja o postępie

### Potencjalne ryzyko
Silne eksponowanie streaka może generować presję i poczucie obowiązku, co w grupie 13-15 lat może prowadzić do:
- stresu,
- zniechęcenia po przerwaniu serii.

### Rekomendacja
Rozważenie trybu „elastycznej nauki” dla młodszych użytkowników (np. brak utraty serii w weekend).

### Priorytet
Średni

---

## 5. Widget - problem z kontynuacją procesu

### Obserwacja
Aplikacja zachęca do dodania widgetu. Po jego dodaniu użytkownik nie otrzymuje jasnej instrukcji, jak wrócić do aplikacji i kontynuować onboarding.

### Problem
Brak komunikatu:
„Wróć teraz do aplikacji, aby kontynuować”.

Proces nie jest automatycznie wznowiony.

### Wpływ na użytkownika 13–15 lat
Może powodować:
- dezorientację,
- przerwanie procesu,
- porzucenie aplikacji.

### Rekomendacja
Dodanie jednoznacznego komunikatu po dodaniu widgetu lub automatyczne przekierowanie do aplikacji.

### Priorytet
Wysoki

---

## 6. Tworzenie hasła - brak wymagań przed walidacją

### Obserwacja
Podczas tworzenia konta użytkownik otrzymuje komunikat, że hasło jest zbyt krótkie. Wcześniej nie podano wymagań dotyczących długości ani znaków specjalnych.

### Problem
Brak prewencyjnej informacji o wymaganiach bezpieczeństwa.

### Klasyfikacja
Błąd UX (brak zapobiegania błędom)  
Nie jest to błąd techniczny, lecz projektowy.

### Rekomendacja
Wyświetlenie wymagań hasła przed wpisaniem:
- minimalna długość,
- wymagane znaki,
- przykład poprawnego hasła.

### Priorytet
Średni

---

## 7. Presja codziennej aktywności i mechanizmy behawioralne

### Obserwacja
Aplikacja silnie promuje codzienną naukę poprzez:
- eksponowanie serii (streak),
- komunikaty zachęcające do codziennego logowania,
- intensywne powiadomienia push,
- dynamiczną zmianę ikony aplikacji (np. „smutna” wersja logo przy dłuższej nieaktywności).

### Analiza z perspektywy użytkownika 13–15 lat
W tym wieku mechanizmy oparte na utrzymywaniu serii mogą:
- wzmacniać motywację krótkoterminową,
- ale także generować poczucie presji i winy przy przerwaniu ciągłości.

Zmiana ikony aplikacji może być odbierana jako forma wywierania emocjonalnej presji (mechanizm FOMO - fear of missing out).

### Potencjalne ryzyko
- nadmierne przywiązanie do serii,
- stres przy utracie streaka,
- demotywacja po przerwaniu ciągłości,
- uzależnienie od mechaniki nagród.

### Rekomendacja
Rozważenie:
- trybu „łagodnej motywacji” dla młodszych użytkowników,
- możliwości wyłączenia presji streaka,
- neutralnej komunikacji przy przerwaniu serii (bez języka emocjonalnego).

### Priorytet
Średni

---

## 8. Oferta premium - przejrzystość i kontrola użytkownika

### Obserwacja
Oferta wersji premium jest:
- jasno opisana,
- możliwa do pominięcia,
- możliwa do aktywowania później.

Nie stwierdzono ryzyka nieświadomego zakupu w trakcie onboardingu.

### Otwarte pytanie do dalszej analizy
Brak weryfikacji procesu rezygnacji z subskrypcji (nie testowano zakupu).

### Ocena
Pozytywny przykład zachowania kontroli użytkownika nad decyzją finansową.

### Priorytet
Brak problemu

---

## Pozytywne elementy onboardingowe

- Ekrany początkowe są czytelne i intuicyjne, łatwo przechodzi się do kolejnych etapów.
- Kolorystyka stonowana, nie męczy wzroku (dobry balans kontrastu – kolory podstawowe zajmują ~70% powierzchni, kolory akcentujące ~30%).
- Oferta wersji premium jasno przedstawiona, możliwa do pominięcia.
- Wybór dziennego celu i liczby słów do nauki jest przejrzysty i motywujący.

