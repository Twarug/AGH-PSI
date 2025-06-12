# AGH-PSI

Autorzy:
- [Patryk Twardosz](https://github.com/Twarug)
- [Bartosz Pajda](https://github.com/BPajda)

Opisy kamieni milowych:

# Kamień milowy 1: Określenie tematu i celu projektu, analiza wymagań,
Opis: 
Zdefiniowanie celu projektu: stworzenie systemu rekomendacji filmów/seriali, który wykorzystuje filtrację kolaboracyjną.,
Określenie zakresu: jakie funkcje ma mieć system (np. rekomendacje na podstawie ocen, możliwość dodawania recenzji).,
Zebranie wymagań dotyczących wydajności (czas odpowiedzi), skalowalności (liczba użytkowników), oraz bezpieczeństwa (ochrona danych użytkowników).,

Wynik: 
Rozplanowany i podzielony na kamienie milowe projekt. (pierwsza wersja tego pliku).


# Kamień milowy 2: Zbiór danych i ich przygotowanie,
Opis: 
Zbieranie danych o filmach/serialach (np. z API IMDb, TMDb) oraz danych o ocenach użytkowników (np. z platformy społecznościowej lub własnej bazy danych).,
Czyszczenie danych: usuwanie duplikatów, brakujących wartości, normalizacja formatów.,
Wstępna analiza danych: eksploracja danych, wizualizacja rozkładów ocen, identyfikacja potencjalnych problemów.,

Wynik: 
Znalazienie, pobranie i podstawowe przygotowanie dataset'u. [Tutaj](/dataset)


# Kamień milowy 3: Wybór i implementacja modelu AI,
Opis: 
Wybór algorytmu filtracji kolaboracyjnej (np. KNN, macierzowa faktoryzacja).,
Implementacja modelu w wybranym języku programowania (np. Python) z użyciem bibliotek takich jak scikit-learn lub TensorFlow.,
Prototypowanie różnych podejść i testowanie ich wydajności na przygotowanych danych.,

Wynik: 
Wbrano algorytm KNN, wraz z kilkoma sposobami obejścia jego ograniczeń.


# Kamień milowy 4: Ocena wyników modelu i optymalizacja,
Opis: 
Dobór metryk oceny modelu (np. RMSE, MAE, dokładność).,
Testowanie modelu na zestawie danych testowych w celu oceny jego dokładności i wydajności.,
Optymalizacja modelu: dostosowanie hiperparametrów, selekcja cech, poprawa jakości danych.,

Wynik: 
Dostowaniw parametrów K oraz testy kilku sposobów obejścia limitacji algorymtu KNN.


# Kamień milowy 5: Wdrożenie modelu i monitorowanie,
Opis: 
Przeniesienie modelu do środowiska produkcyjnego (np. stworzenie API do rekomendacji).,
Integracja z otoczeniem (np. aplikacja webowa lub mobilna).,
Ustalenie mechanizmów monitorowania wydajności modelu oraz zbierania feedbacku od użytkowników.,

Wynik: 
Prosta aplikacja webowa, pozwalająca na stworzenie listy lubianych filmów oraz zwracająca na ich podstawie rekomendacje.
