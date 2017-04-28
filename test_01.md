Test
====

1. Sygnał masz w zmiennej `raw`, montaż w zmiennej `lisek`.
  a) Wpisz komendę która filtruje sygnał górnoprzepustowo - powyżej 0.5 Hz 
  b) Wpisz komendę która filtruje sygnał dolnoprzepustowo - poniżej 40 Hz
  c) połącz dwie komendy powyżej w jedną
  c) Wpisz komendę która dodaje montaż do sygnału


2. Przyporządkuj w odpowiedniej kolejności poniższe kroki  

A - epokujemy i zapisujemy w zmiennej `epochs`  
B - wczytujemy informacje o wydarzeniach
C - wczytujemy montaż do zmiennej `montage`
D - wczytujemy dane i zapisujemy w zmiennej `raw`  
E - `raw.set_montage(montage)`
F - `raw.filter(1, None)`  

bez stresu - jest więcej niż jedna poprawna kolejność.


3. Po co filtrujemy sygnał?
```

```


4. Mamy poepokowany sygnał w zmiennej `epochs` - co robi nam poniższa komenda, po co to robimy?
```python
erp = epochs['face_0'].average()
```
```

```


5. Co robią (w notebooku) te komendy:
```
cd C:\Dane\super_badanie\eeg
```

```python
raw = mne.io.read_raw_fif('super_dane_jejku_jej.fif')
```

```
ls
```
