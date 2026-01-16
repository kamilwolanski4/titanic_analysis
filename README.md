# Titanic – Exploratory Data Analysis (EDA)

Projekt przedstawia analizę eksploracyjną danych pasażerów Titanica (Titanic dataset).  
Celem było poznanie struktury danych, sprawdzenie braków danych oraz zbadanie zależności pomiędzy cechami pasażerów a przeżywalnością.

---

## Cel projektu

- analiza struktury danych (liczba rekordów, typy danych, podstawowe statystyki)
- identyfikacja braków danych oraz ich interpretacja
- analiza rozkładu wybranych zmiennych (wiek, płeć, klasa biletu, cena biletu)
- sprawdzenie zależności pomiędzy przeżywalnością a cechami pasażerów
- wyciągnięcie kluczowych wniosków i podsumowanie w formie raportu

---

## Technologie

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Opis danych

Dane zawierają informacje o pasażerach Titanica, m.in.:

- `survived` – czy pasażer przeżył
- `pclass` – klasa biletu (1, 2, 3)
- `sex` – płeć pasażera
- `age` – wiek pasażera
- `sibsp` – liczba rodzeństwa/małżonków na pokładzie
- `parch` – liczba rodziców/dzieci na pokładzie
- `fare` – cena biletu
- `embarked` – port wejścia na pokład

---

## Struktura repozytorium

- `notebooks/`
  - `project_titanic.ipynb` – główny notebook z EDA i raportem końcowym
- `raw_data/`
  - plik źródłowy `.csv` z danymi (jeśli jest dołączony do repozytorium)
- `processed_data/`
  - dane przetworzone (opcjonalnie, jeśli wykorzystywane)

---

## Najważniejsze wnioski (skrót)

Na podstawie analizy danych:

- płeć miała bardzo duży wpływ na przeżywalność – kobiety miały wyraźnie większe szanse na przeżycie
- klasa biletu była istotnym czynnikiem – pasażerowie z wyższych klas częściej przeżywali
- w danych występują braki w kolumnach takich jak `cabin`, `body`, `boat`
- część braków danych nie jest losowa, co może wpływać na interpretację wyników

---

## Wartości odstające (outliery)

W analizie wykryto wartości odstające w kilku zmiennych liczbowych:

- **Wiek (age):** 9 rekordów *(0.69%)*
- **Liczba rodzeństwa/małżonków na pokładzie (sibsp):** 57 rekordów *(4.35%)*
- **Liczba rodziców/dzieci na pokładzie (parch):** 307 rekordów *(23.44%)*
- **Cena biletu (fare):** 171 rekordów *(13.05%)*

Największy udział wartości odstających wystąpił w zmiennej **parch**, co może sugerować obecność rzadkich, nietypowych konfiguracji rodzin podróżujących razem.

## Autor
- Kamil Wolański
- Link do notebooka 
- Link do Linkedin https://www.linkedin.com/in/kamil-wola%C5%84ski-48b334292/

