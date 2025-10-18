# ZTAPI
Projekt ZTAPI 2025 Zima
# Wypożyczalnia Aut

Projekt przedstawia nowoczesną stronę internetową dla wypożyczalni samochodów.  
Umożliwia użytkownikom przeglądanie dostępnych aut, filtrowanie ofert, a także rezerwację wybranego pojazdu online.

---

## Opis projektu

Celem projektu jest stworzenie przejrzystej, responsywnej aplikacji webowej, która:
- pozwala użytkownikom przeglądać i rezerwować samochody,
- udostępnia właścicielowi wypożyczalni panel administracyjny do zarządzania flotą i rezerwacjami,
- działa w sposób szybki i intuicyjny na różnych urządzeniach (mobile-first).

---

## Technologie

### Frontend
**React**  
Projekt został oparty o bibliotekę **React**, ponieważ:
- umożliwia tworzenie aplikacji typu **Single Page Application (SPA)**,  
- zapewnia wysoką wydajność dzięki mechanizmowi **Virtual DOM**,  
- oferuje modularność i reużywalność komponentów,  
- posiada bogaty ekosystem narzędzi i społeczność.

Dodatkowe technologie frontendowe:
- **Tailwind CSS** – do stylizacji interfejsu i zapewnienia nowoczesnego wyglądu,
- **React Router** – do obsługi nawigacji między podstronami,
- **Axios** – do komunikacji z backendowym API.

### Backend (planowany)
- **Node.js + Express** – tworzenie lekkiego, szybkiego serwera API do obsługi rezerwacji i danych o autach,
- **MongoDB** – baza danych NoSQL przechowująca informacje o samochodach, użytkownikach i rezerwacjach.

---

## Dlaczego taki wybór?

- **React** pozwala na szybki rozwój nowoczesnych aplikacji webowych,
- **Tailwind CSS** znacząco przyspiesza pracę nad interfejsem, zachowując spójność wizualną,
- **Node.js** i **Express** umożliwiają obsługę backendu w tym samym języku co frontend (JavaScript),
- **MongoDB** dobrze sprawdza się przy dynamicznej strukturze danych (np. różne modele aut).

---

## Funkcjonalności

- Lista dostępnych samochodów, z możliwością filtrowania i wyszukiwania,  
- Szczegółowe informacje o każdym pojeździe,  
- Formularz rezerwacji online,  
- Panel administracyjny do zarządzania flotą i rezerwacjami,  
- Responsywny design (działanie na komputerach i urządzeniach mobilnych).

---

## Plan rozwoju

1. Implementacja podstawowego interfejsu w React.  
2. Dodanie backendu opartego o Node.js + Express.  
3. Integracja z bazą danych MongoDB.  
4. Wdrożenie systemu autoryzacji użytkowników.  
5. Testy oraz optymalizacja działania aplikacji

