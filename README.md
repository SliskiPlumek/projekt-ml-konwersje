# Predykcja zakupu po reklamie społecznościowej — projekt z Uczenia Maszynowego

> Hubert Śliwiński, gr. 2, nr 32532

**Linki:**

- GitHub: https://github.com/SliskiPlumek/projekt-ml-smads
- Google Colab: https://colab.research.google.com/drive/1fD6GqeMK8xh1kBzAsX3HOB0200vUzXLM?usp=sharing

## Opis

Klasyfikacja binarna: czy użytkownik kupił reklamowany produkt po reklamie w sieci
społecznościowej (`Purchased` 0/1). Problem „reklama -> konwersja".

- **Dane:** publiczny zbiór z Kaggle _Social Network Ads_ (`rakeshrau/social-network-ads`),
  pobierany w kodzie przez `kagglehub`.
- **Modele:** porównanie dwóch modeli drzewiastych — **drzewo decyzyjne** i **las losowy**;
  do szczegółowej analizy wybrano las losowy.
- **Wynik:** las losowy ok. 90% dokładności (drzewo decyzyjne ok. 88%).
- **Wizualizacje:** porównanie modeli, wiek i zarobki, macierz pomyłek, ważność cech.

## Pliki

- `Projekt_ML_reklamy_kaggle.ipynb` — główny notebook
- `README.md` — ten plik
