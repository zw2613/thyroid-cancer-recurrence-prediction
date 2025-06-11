# Predykcja nawrotu raka tarczycy z wykorzystaniem danych medycznych

Celem projektu jest opracowanie modelu predykcyjnego nawrotu raka tarczycy na podstawie danych medycznych. Projekt obejmuje przygotowanie danych, eksploracyjną analizę danych, wybór cech oraz budowę i ocenę modeli uczenia maszynowego.

## 📌 Opis projektu

- **Cel:** Przewidywanie nawrotu raka tarczycy na podstawie wybranych zmiennych klinicznych.
- **Wykorzystane metody:** Czyszczenie danych, wizualizacja, selekcja cech, nadzorowane uczenie maszynowe.

## 📌 Środowisko i narzędzia
- **Język programowania**: R
- **Środowisko pracy**: RStudio
- **Format raportu**: R Markdown (plik .Rmd), co umożliwia łączenie kodu, wyników i opisu w jednym dokumencie.

## 📌 Opis plików
- **thyroid_cancer.Rmd** — skrypt R Markdown z pełną analizą i wizualizacjami
- **thyroid_cancer.html** — wygenerowany raport w formacie HTML
- **filtered_thyroid_data.csv** — dane wejściowe


## 🧬 Dane

Zbiór danych zawiera informacje medyczne dotyczące pacjentów po leczeniu raka tarczycy. Każdy rekord zawiera zmienne kliniczne i demograficzne.

## 🔍 Przykładowe zmienne

- Wiek
- Płeć
- Stopień zaawansowania guza
- Historia radioterapii
- Rodzaj patologii
- Zaawansowanie węzłów chłonnych

## ⚙️ Zastosowane modele

- Regresja logistyczna
- Drzewo decyzyjne
- Random Forest
- Maszyna wektorów nośnych (SVM)
- k-NN
- XGBoost

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


## ✍️ Autor
- **Zuzanna Winiarska**
- **Data**: czerwiec 2025

## 📄 Licencja
Projekt przeznaczony wyłącznie do celów edukacyjnych. Nie służy do podejmowania decyzji klinicznych.
