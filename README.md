# NortwindPowerBI
**Scenariusz biznesowy.**

Interaktywne rozwiązanie analityczne stworzone w Power BI, które umożliwia firmie Northwind analizowanie danych sprzedażowych, logistycznych oraz produktów w celu podejmowania lepszych decyzji biznesowych. Dashboard jest podzielony na cztery główne sekcje: Przegląd (Overview), Produkty (Products), Przewoźnicy (Shippers) oraz Zamówienia (Orders).

Celem wdrożenia dashboardu jest:

- Zwiększenie przejrzystości danych sprzedażowych i logistycznych.

- Umożliwienie szybkiej analizy trendów sprzedaży oraz identyfikacji najlepiej i najsłabiej sprzedających się produktów.

- Monitorowanie efektywności przewoźników oraz średnich czasów dostawy.

- Dostarczenie informacji potrzebnych do podejmowania decyzji dotyczących oferty produktowej i polityki cenowej.

Główne funkcje:

- Sekcja Overview:

  - Podgląd wskaźników: liczba zamówień, ilości sprzedanych produktów, przychody netto i brutto.

  - Wizualizacja trendów przychodów oraz zamówień na przestrzeni kwartałów.

  - Mapa prezentująca przychody netto w podziale na kraje.

- Sekcja Products:

  - Analiza zamówień według kategorii produktów.

  - Ranking najlepiej i najsłabiej sprzedających się produktów.

  - Szczegółowe dane o liczbie zamówień, ilościach oraz przychodach netto i brutto w podziale na kategorie.

- Sekcja Shippers:

  - Analiza zamówień realizowanych przez poszczególnych przewoźników.

  - Wizualizacja średnich czasów dostawy.

  - Mapa prezentująca lokalizacje zamówień obsługiwanych przez przewoźników.

- Sekcja Orders:

  - Analiza liczby zamówień według dni, kwartałów i krajów.

  - Mapa prezentująca rozkładu zamówień w podziale na kraje.

Korzyści biznesowe:

- Lepsza widoczność danych:

  - Łatwy dostęp do kluczowych wskaźników dzięki interaktywnym wizualizacjom.

- Poprawa decyzji strategicznych:

  - Możliwość identyfikacji najbardziej dochodowych produktów, kategorii i regionów.

- Optymalizacja logistyki:

  - Monitorowanie efektywności przewoźników oraz czasów dostaw.

**Opis techniczny**

- Proces ETL – dane zostały przygotowane w oddzielnym projekcie Powe BI przy użyciu Power Query, gdzie przeprowadzono:

  - Czyszczenie i transformację danych.

  - Przygotowanie danych do analizy.

- Eksport danych do SQL Server - Dane z Power BI zostały przesłane do SQL Server za pomocą narzędzia DAX Studio.

- Finalny model analityczny z warstwą raportową – zbudowany na podstawie danych pobranych z SQL Server.

Technologie i narzędzia:

- **Baza Danych**: SQL Server (Baza Northwind wcześniej poddana procesowi ETL, a następnie eksportowana do magazynu danych).

- **Power Query**: Przygotowanie danych wstępnych oraz transformacje.

- **Power BI Desktop**: Tworzenie modelu analitycznego i warstwy raportowej.

- **DAX Studio**: Eksport danych z Power BI do SQL Server.

- **SQL Server**: Magazyn danych.

Interfejs użytkownika:

- Panel nawigacyjny

  - Widoki: Overview, products, shippers, orders.

  - Wyraźny podział na moduły.

- Widoczność danych

  - Dane przedstawione w czytelnej formie za pomocą wykresów kołowych, słupkowych i map.

- Interaktywność

  - Dynamiczne zmiany widoków na podstawie filtrów.

Przyszłe rozszerzenia:

- Wprowadzenie przewidywania sprzedaży z wykorzystaniem ML.

- Usprawnienie przepływu danych między procesami.

- Rozbudowa o kolejne moduły analiz.
