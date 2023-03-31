:O

# BankosDeLaKolunios - Sebastian Kozak, Łubkowski Jakub, Marcin Mikuła

<h2> Technologie</h2>
<ul>
  <li> Backend Java Spring </li>
  <li> Frontend JavaFX </li>
  <li> Baza danych H2 </li>
</ul>


## Zmianlog

#### Backend

<ol>

  <li> Nasłuchiwanie folderu storage </li>

  <li> Obsługa plików z rozszerzeniem csv na podstawie prefiksów banków XXX_nazwapliku.csv </li>

  <li> Utworzenie parserów dla banków z zastosowaniem wzorca strategia </li>

  <li> Zapisywanie tranzakcji do bazy danych </li>

  <li> Wystawienie endpointu umożliwiającego przesłanie tranzakcji z zewnątrz </li>
  
</ol>

#### Frontend

<ol>

  <li> Stworzenie UI pobierającego i wyświetlającego załadowane tranzakcje </li>
  
  <li> Dodanie przycisku wysyłającego request do bakendu w celu pobrania wszystkich dostępnych tranzakcji </li> 
  
</ol>

## Zmianlog2

#### Backend
<ol>

  <li> Stworzenie encji Tag i połączenie jej z tranzakcjami </li>

  <li> Dodanie filtrowania - query do bazy pobierające liste tranzakcji zawierających odpowiednie tagi </li>
  
  <li> Wystawienie endointu do pobierania tranzakcji zawierających tylko wybrane tagi </li>

  <li> Wystawienie endointu do przesyłania zmienionej listy tagów dla danej tranzakcji </li>
  
  <li> Dodanie paginacji </li>
  
</ol>

#### Frontend
<ol>

  <li> Dodanie widoku do edytowania tranzakcji </li>
  
  <li> Stworzenie klasy obsługującej widok edytowania tranzakcji </li>

  <li> Aktualizacja głownego widoku - dodanie filtrowania po tagach </li>

  <li> Delikatne zmiany upiększające </li>
  
  <li> Dodanie przycisków do przewijania stron </li>
  
</ol>


