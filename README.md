# ML_projekt_system_rekomendacji
 
 
** Collaborative Filtering ** - rekomendacje na podstawie ocen i zakupów użytkownika. Gdy dwóch użytkowników kupuje podobne produkty, możemy stwierdzić, że mają zbliżone upodobania i polecać im wzajemnie sprawdzone dla nich artykuły.
 
** SVD (Singular Value Decomposition) ** - Algorytm ten wykorzystuje metodę faktoryzacji macierzy. Macierz ocen użytkownik-element jest faktoryzowana na macierze użytkowników i elementów o mniejszym wymiarze, składające się z ukrytych czynników (ukrytych cech). Domyślnie liczba czynników ukrytych wynosi 100. Te ukryte czynniki są w stanie uchwycić znane preferencje użytkownika dotyczące oceny elementu, a tym samym są w stanie przewidzieć szacunkową ocenę dla wszystkich par użytkownik-element, w których użytkownik jeszcze nie ocenił elementu
 
 
 Pozostałe rzeczy zrobimy w oddzielnym notatniku wczytując przetworzone dane.
 
 
#### Data Preprocessing 
Przygotowanie danych [oparte na tym repozytorium](https://github.com/RadhikaRM/Bookrecommendersystem/blob/main/Final_Book_Recommender_System.ipynb)
Przygotowane dane zostały wyeksportowane do pliku **prepared_data.csv**.

## Zastosowane zmiany:
- zmiana nazw kolumn,
- sprawdzenie i zmiana typów danych,
- uzupełnienie braków,
- stworzenie nazw grup wiekowych,
- uzupełnienie kraju użytkownika,
- wyodrębnienie książek posiadających ocenę
- połączenie danych i eksport


## Linki warte przejrzenia:
* [How to Build a Book Recommendation System](https://www.analyticsvidhya.com/blog/2021/06/build-book-recommendation-system-unsupervised-learning-project/)
* [Algorytmy rekomendacyjne - przykład implementacji w Pythonie](https://blog.consdata.tech/2018/08/07/algorytmy-rekomendacyjne-przyklad-implementacji-w-pythonie.html)

## Dalsze prace:
- [EDA](https://www.kaggle.com/code/eyadgk/books-eda-vis-recommendation-systems)
- [rekomendacja oparta na kraju + implementacja kNN](https://github.com/RadhikaRM/Bookrecommendersystem/blob/main/Final_Book_Recommender_System.ipynb)
- [wynik wyszukiwania okładka + ocena](https://www.kaggle.com/code/hilalmleykeyuksel/book-recommender)
- [Collaborative Filtering](https://www.kaggle.com/code/fahadmehfoooz/book-recommendation-system)
