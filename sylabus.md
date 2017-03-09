Sylabus
-------

Zajęcia z analizy sygnału I oswajają studentów z podstawowymi operacjami wykonywanymi na sygnale EEG. Droga od surowych danych EEG do danych gotowych do analizy jest stosunkowo długa i najeżona różnymi trudnościami. Studenci nauczą się kolejnych kroków przygotowywania danych do analizy, które minimalizują bądź przezwyciężają owe trudności. Omówione zostaną również podstawowe metody analizy przygotowanych danych. Aby przyswoić podstawowe umiejętności analizy sygnału student musi zmierzyć się z projektem końcowym - samodzielnym przeanalizowaniem otrzymanych danych. Zaliczenie projektu następuje drogą pisemną - student dokumentuje kolejne kroki przygotowania i analizy danych, wliczając w to ilustracje kluczowych kroków takich jak - odrzucanie artefaktów, klasyfikacja komponentów oraz policzenie potencjałów wywołanych. Istotna jest zarówno jakość przeprowadzonych analiz, kompletność udokumentowania kroków analizy oraz trafność decyzji podejmowanych podczas przygotowywania danych do analizy.

2. Jako że nie mam 100% pewności czy będę torturował studentów pythonem czy może Brainstormem (ma wersję standalone), najlepiej wywalić:

z Tematu 1:
* środowisko MATLAB - wprowadzenie
* eeglab - przyjazne narzędzie do analizy EEG

z Tematu 3:
* jak zorganizowane są dane w eeglabie
* komendy tekstowe i automatyzacja

z Tematu 4:
* komendy tekstowe przydatne do liczenia ERPów


3. zmieniłbym natomiast:




1. Wprowadzenie do tematyki zajęć
  * struktura zajęć i wymagania
  * sygnał EEG i jego analiza - wprowadzenie
  * podstawowe kroki przygotowania danych do analizy

2. Podstawowe operacje na danych EEG, część I
  * wczytywanie danych
  * filtrowanie
  * przeglądanie sygnału
  * źródła artefaktów w danych
  * identyfikowanie artefaktów

3. Podstawowe operacje na danych EEG, część II
  * wczytywanie danych w różnych formatach
  * dodawanie informacji o pozycji elektrod
  * rereferencja
  * wydarzenia i epokowanie

4. Potencjały związane ze zdarzeniem (ERP)
  * dzielenie sygnału na epoki względem wydarzeń
  * usuwanie artefaktów
  * wyświetlanie potencjałów, wywoływanie duchów
  * komendy tekstowe przydatne do liczenia ERPów

5. W stronę czystszych danych - ICA
  * zmieszane sygnały - jedna elektroda to wiele źródeł sygnału
  * jak to rozplątać - analiza niezależnych komponentów (ICA)
  * klasyfikacja komponentów i usuwanie komponentów reprezentujących
artefakty

6. Analizy częstotliwościowe I: widmo mocy
  * domena czasu i częstości: dwie perspektywy na sygnał
  * dobór okna analizy i rodzielczość w częstotliwości
  * analiza welch'a, zero-padding

7. Analizy częstotliwościowe II: czas-częstość
  * czas i częstość - jak to połączyć?
  * ilość cykli i analiza falkowa
  * wizualizacja
