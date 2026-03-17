# 🚚 Problem komiwojażera (TSP)

Projekt został zrealizowany w ramach laboratorium z przedmiotu **Zaawansowane Programowanie Obiektowe**.

Celem było zaimplementowanie rozwiązania klasycznego problemu optymalizacyjnego – **problemu komiwojażera (Travelling Salesman Problem, TSP)**.

---

## 📌 Opis problemu

Problem komiwojażera polega na znalezieniu **najkrótszej możliwej trasy**, która:

* odwiedza każde miasto dokładnie jeden raz
* rozpoczyna się i kończy w tym samym punkcie

Problem ten można modelować jako graf, gdzie:

* wierzchołki = miasta
* krawędzie = odległości między miastami

Celem jest znalezienie **najkrótszego cyklu Hamiltona** ([algorytm.org][1])

---

## 🎯 Cel projektu

Celem projektu było:

* zapoznanie się z problemem TSP
* implementacja wybranego algorytmu rozwiązującego problem
* wykorzystanie programowania obiektowego
* praca na gotowym szablonie i jego rozbudowa

---

## ⚙️ Wykorzystane podejście

W projekcie zaimplementowano algorytm rozwiązujący problem komiwojażera.

W zależności od wersji projektu mogą to być m.in.:

* algorytm brute-force (siłowy)
* heurystyki (np. najbliższego sąsiada)
* algorytmy optymalizacyjne

Ze względu na dużą złożoność problemu (rzędu **O(n!)**) rozwiązania dokładne działają efektywnie tylko dla małych danych ([ufkapano.github.io][2])

---

## 🧱 Struktura projektu

Przykładowa struktura repozytorium:

```
.
├── main.py
├── tsp.py
├── utils.py
└── README.md
```

*(Struktura może się różnić w zależności od implementacji)*

---

## ▶️ Uruchomienie

1. Sklonuj repozytorium:

```bash
git clone https://github.com/Aleksander-Mlynarski/Problem_komiwojazera.git
```

2. Przejdź do katalogu projektu:

```bash
cd Problem_komiwojazera
```

3. Uruchom program:

```bash
python main.py
```

---

## 🧪 Testowanie

Program można testować poprzez:

* zmianę danych wejściowych (np. liczby miast)
* analizę wygenerowanej trasy
* porównanie długości ścieżek

---

## 📚 Technologie

* Python
* Programowanie obiektowe (OOP)

---

## 📝 Uwagi

* Projekt został wykonany na podstawie materiałów laboratoryjnych
* Implementacja skupia się na poprawności działania algorytmu
* Dla większych danych czas działania może znacząco wzrosnąć

---

## 👨‍💻 Autor

Projekt wykonany przez:

**Aleksander Młynarski**

[1]: https://www.algorytm.org/algorytmy-grafowe/problem-komiwojazera.html?utm_source=chatgpt.com "Problem komiwojażera - Algorytmy i Struktury Danych"
[2]: https://ufkapano.github.io/download/Piotr_Szestalo_2015.pdf?utm_source=chatgpt.com "Uniwersytet Jagielloński w Krakowie"
