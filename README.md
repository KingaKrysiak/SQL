# SQL

Zapytanie służy do analizy aktywności klientów sklepu internetowego w określonym przedziale czasowym (rok 2024). Celem jest wyłonienie pięciu najbardziej aktywnych klientów na literę K, którzy złożyli co najmniej trzy zamówienia, oraz prezentacja dodatkowych informacji o ich zamówieniach i preferencjach produktowych. 

W zapytaniu wykorzystano:

- **INNER JOIN** do połączenia klientów z ich zamówieniami oraz szczegółami tych zamówień,
- **LEFT JOIN** do dołączenia informacji o produktach i ich kategoriach, pozwalając na uwzględnienie wszystkich zamówień, nawet jeśli niektóre produkty nie mają przypisanej kategorii,
- filtrację zamówień z 2024 roku za pomocą **WHERE** z warunkiem **BETWEEN** na daty,
- selekcję klientów o statusie 'active' lub 'premium' za pomocą **IN**,
- wyszukiwanie klientów, których nazwa zaczyna się na literę "K" dzięki operatorowi **LIKE**,
- agregację danych według klienta i kategorii produktów z zastosowaniem **GROUP BY**,
- liczenie unikalnych zamówień klienta za pomocą **COUNT(DISTINCT)** oraz wyliczenie średniej wartości zamówienia przez **AVG**,
- filtrowanie wyników na podstawie liczby zamówień (minimum 3) przy użyciu **HAVING**,
- sortowanie wyników malejąco według liczby zamówień oraz średniej wartości zamówienia przez **ORDER BY**,
- ograniczenie liczby wyników do top 5 przy pomocy **LIMIT**.

Takie zapytanie pokazuje moje umiejętności w łączeniu i filtrowaniu danych, pracy z agregatami, warunkami oraz organizacji wyników — wszystko niezbędne w analizie biznesowej i raportowaniu danych.
