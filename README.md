# Predykcja nawrotu raka tarczycy z wykorzystaniem danych medycznych

Celem projektu jest opracowanie modelu predykcyjnego nawrotu raka tarczycy na podstawie danych medycznych. Projekt obejmuje przygotowanie danych, eksploracyjną analizę danych, wybór cech oraz budowę i ocenę modeli uczenia maszynowego.

## 📌 Opis projektu

- **Cel:** Przewidywanie nawrotu raka tarczycy na podstawie wybranych zmiennych klinicznych.
- **Wykorzystane metody:** Czyszczenie danych, wizualizacja, selekcja cech, nadzorowane uczenie maszynowe.
- **Narzędzia:** Python, pandas, scikit-learn, matplotlib, seaborn.


## 🧬 Dane

Zbiór danych zawiera informacje medyczne dotyczące pacjentów po leczeniu raka tarczycy. Każdy rekord zawiera zmienne kliniczne i demograficzne.

> ⚠️ **Uwaga**: Ze względu na poufność danych medycznych, zbiór danych nie jest publicznie dostępny.

## 🔍 Przykładowe zmienne

- Wiek
- Płeć
- Stopień zaawansowania guza
- Obecność przerzutów do węzłów chłonnych
- Typ histologiczny
- Rodzaj leczenia
- Czas do nawrotu (jeśli wystąpił)

## ⚙️ Zastosowane modele

- Regresja logistyczna
- Drzewo decyzyjne
- Random Forest
- Maszyna wektorów nośnych (SVM)
- Sieć neuronowa (MLP)

Ocena modeli obejmuje:
- Accuracy (dokładność)
- Precision (precyzja)
- Recall (czułość)
- F1-score

## 📊 Wyniki

Najlepsze wyniki osiągnął model **regresji logistycznej**, uzyskując:

| Miara       | Wynik |
|-------------|-------|
| Accuracy    | 97%   |
| Precision   | 98%   |
| Recall      | 98%   |
| F1-score    | 98%   |


✍️ Autor
Zuzanna Winiarska
Data: czerwiec 2025

📄 Licencja
Projekt przeznaczony wyłącznie do celów edukacyjnych. Nie służy do podejmowania decyzji klinicznych. Dane medyczne nie są jawnie udostępnione.
