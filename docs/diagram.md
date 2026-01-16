# Diagram Projektu

```mermaid
flowchart TD
    A[START] --> B[Użytkownik otwiera aplikację]
    B --> C{Czy ma konto?}
    C -->|TAK| D[Logowanie]
    C -->|NIE| E[Rejestracja]
    D --> F[Panel główny (zadania)]
    E --> F[Panel główny (zadania)]
    F --> G[Dodaj / edytuj zadania]
    G --> H[Zapis danych]
    H --> I[KONIEC]
