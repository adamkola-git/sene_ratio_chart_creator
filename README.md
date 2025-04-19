# 📊 Sene Ratio Chart Creator

**Sene Ratio Chart Creator** to narzędzie do analizy i wizualizacji danych dotyczących wskaźników `sene_ratio` na podstawie plików CSV/Excel. Wykorzystuje Pythona, Pandas, Matplotlib i zaawansowane możliwości formatowania Excela przez `openpyxl`.

---

## 🚀 Funkcje

- 📥 Wczytywanie danych z plików CSV
- 📊 Obliczanie i sortowanie komponentów SED wg udziałów procentowych
- 🧼 Czyszczenie i walidacja danych
- 📈 Eksport do Excela z zaawansowanym formatowaniem:
  - dynamiczne nagłówki
  - kolory warunkowe
  - pogrubienia, obramowania, wyrównania
  - podświetlenia wybranych komponentów (np. **Airfoil**)
- 🎯 Gotowe do dalszej analizy lub raportowania

---

## 🧰 Wymagania

Projekt działa na Pythonie 3.8+ i wymaga poniższych bibliotek (zawarte w `requirements.txt`):

```
pandas>=1.0
openpyxl>=3.0
matplotlib>=3.0
```

Instalacja (po aktywacji środowiska np. z `pyenv`):

```bash
pip install -r requirements.txt
```

---

## 🗂️ Struktura projektu

```
├── sene_ratio_chart_creator.ipynb        # Główny notatnik analityczny
├── run_name_SED.csv                      # Dane wejściowe
├── processed_data_SED.xlsx               # Dane wyjściowe (Excel)
├── requirements.txt                      # Lista zależności
├── .gitignore                            # Pliki do pominięcia przez Git
└── README.md                             # Ten plik
```

---

## ▶️ Jak uruchomić

1. Upewnij się, że masz aktywne środowisko Pythona (np. przez `pyenv`)
2. Zainstaluj zależności:

```bash
pip install -r requirements.txt
```

3. Uruchom notatnik:

```bash
jupyter notebook
```

4. Otwórz `sene_ratio_chart_creator.ipynb` i wykonaj komórki krok po kroku.

---

## 📊 Dane

**Wejście**:
- `run_name_SED.csv` – dane źródłowe (zawierające m.in. `mode`, `FREQ`, `SENE_*_Ratio`)

**Wyjście**:
- `processed_data_SED.xlsx` – raport z analizą
- Formatowanie kolumn, sortowanie komponentów, oznaczenia kolorystyczne

---

## 👨‍💻 Autor

Adam Kołakowski  
GitHub: [@adamkolak-git](https://github.com/adamkolak-git)

---

## 📄 Licencja

Ten projekt udostępniony jest na licencji MIT – używaj śmiało, ale z szacunkiem 💙

---
