# Variant counting - skrypt to identyfikacji wariantów w danych sekwencjonowania długich odczytów
Repozytorium zawiera skrypt do identyfikacji i zliczania wariantów w danych mitochondialnych z sekwencjonowania Oxford Nanopore - dotyczy dwóch wybranych pozycji w genomie mitochodrialnym.

Dane zostały poddane analizie z wykorzystaniem języka programowania Python. Proces ten obejmował ekstrakcję odczytów z danych w formacie SAM, które wykazywały pokrycie na obu badanych pozycjach genomowych. Dla każdego z tych odczytów dokonano identyfikacji nukleotydów w kluczowych pozycjach 3460 i 9889, aby sprawdzić, czy występują tam poszukiwane warianty genetyczne.


Input: 
  sekwencje w formacie bam lub sam

Output:
  tabela z informacjami, jakie nukleotydy znajdują się na pozycjach 3460 i 9889 w genomie mitochodrialnym.

Wymagania: 
samtools 1.10
Python 3.X


Biblioteki:
matplotlib
numpy
pandas
seaborn
re
