BOOKSTORE.postman_collection

1. Projekt 'BOOKStore' testuje przykladowe REST API 'Simple Books API' dostepne na https://simple-books-api.glitch.me
   Dokumentacja dostepna na https://github.com/vdespa/introduction-to-postman-course/blob/main/simple-books-api.md

2. Opis projektu:
   Projekt ma za zadanie przetestowac mozliwosc:
   - odczytu katalogu z ksiazkami oraz informacji o pojedynczej ksiazce na podstawie ID
   - utworzenia i odczytu nowego zamowienia
   - edycji i usuniecia zamowienia
   - odczytu wszystkich utworzonych zamowien.

   Projekt wykorzystuje podstawowe metody (CRUD): POST, READ, PUT(PATCH), DELETE i uzywa autoryzacji typu Bearer Token, ustawionej dla calej 
   kolekcji w zmiennej 'bearerToken'.
   
   Zmienne 'url', 'bookID', 'orderID' i 'customerName' sa zdefiniowane w zmiennych kolekcji a nastepnie przekazywane do kolejnych requestow, 
   wykonujacych opisane zadania.

   Na poczatku wystepuje request 'API Authentication', z ktorego pozyskiwany jest token i zapisywany w zmiennej kolekcji 'bearerToken'.     

3. Celem tego prostego projektu 'end-to-end' jest zaprezentowanie podstawowych umiejetnosci z zakresu testowania REST API 
   w POSTMAN, ktore nabylem korzystajac z online'owych tutoriali. 

4. Zakres wiedzy:
   - Tworzenie kolekcji, requestow, podstawowych testow i skryptow.
   - Korzystanie z Collection Runnera
   - Tworzenie i odwolywanie sie do zmiennych (wew. body, endpoint'ow, testow, query parameter, path parameter)
   - Tworzenie prostych skryptow:
     > Przekazywanie zmiennych pomiedzy requestami i ustawianie zmiennych na roznych poziomach.
     > Tworzenie prostych testow
     > Logowanie na konsole
     > Korzystanie ze Snippets'ow
   