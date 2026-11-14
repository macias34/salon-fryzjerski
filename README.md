# Salon fryzjerski – rezerwacje wizyt

Projekt zaliczeniowy z Inżynierii oprogramowania II.

System pozwala klientom salonu fryzjerskiego sprawdzić wolne terminy i zarezerwować wizytę bez zakładania konta. Fryzjerzy ustalają swoje godziny pracy, prowadzą listę usług i widzą rezerwacje w kalendarzu. System obsługuje jeden salon, w którym pracuje kilku fryzjerów.

## Skład

- Maciej Radzimirski ([macias34](https://github.com/macias34))

## Zakres podstawowy

| Id | Przypadek użycia | Aktor |
|---|---|---|
| PU01 | Przeglądanie usług (nazwa, cena, czas trwania) | Klient |
| PU02 | Sprawdzenie wolnych terminów dla wybranej usługi i fryzjera | Klient |
| PU03 | Rezerwacja wizyty | Klient |
| PU04 | Przegląd rezerwacji w kalendarzu | Fryzjer |
| PU05 | Ustalanie godzin pracy | Fryzjer |
| PU06 | Zarządzanie usługami (dodanie, edycja, usunięcie) | Fryzjer |

Rozszerzeń nie planuję.

Poza zakresem: akceptacja rezerwacji przez salon (rezerwacja jest od razu potwierdzona), płatności i zadatki, konta klientów, odwoływanie wizyt, obsługa nieobecności klienta, program lojalnościowy, statystyki finansowe, powiadomienia, obsługa wielu salonów.

## Technologie

- TypeScript
- Next.js i React – interfejs użytkownika
- Hono – REST API
- PostgreSQL z Drizzle ORM – baza danych
- Vitest i Testcontainers – testy automatyczne
- Zewnętrzny dostawca uwierzytelniania do logowania fryzjerów, np. Supabase Auth

## Struktura repozytorium

- `docs/` – dokumentacja kolejnych etapów projektu i pliki źródłowe diagramów
- `src/` – kod aplikacji
- `tests/` – testy automatyczne

## Uruchomienie

Instrukcja pojawi się razem z implementacją.
