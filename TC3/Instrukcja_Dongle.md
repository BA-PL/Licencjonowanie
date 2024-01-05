# Licencjonowanie Target 

Niniejsza  instrukcja  opisuje  sposób  samodzielnego  aktywowania licencji bezpośrednio na sterowniku.

Instrukcja  nie  opisuje  przypadku  wgrywania  licencji  na  moduł EL6070 lub klucz USB C9900-L100.

## Protokół odbioru

Na początku potrzebujemy nazw licencji oraz numeru rejestracji. Znajdziemy je na Protokole Odbioru Towaru.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/a26da93c-804a-4619-8d4d-b0694eb14fe5)

TCxxxx-xx**40** – **40** oznacza platformę sprzętową.

## TwinCAT

Mając protokół odbioru, otwieramy Solution i nawiązujemy połączenie ze sterownikiem, na który chcemy wgrać licencje. Następnie otwieramy zakładkę licencyjną.

W zakładce *License / Manage Licenses* zaznaczamy *Disable automatic detection of required licenses for project* oraz wybieramy licencje zgodne z zamówieniem (tylko te, które są na zamówieniu).

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/7ffb5261-c446-4091-a818-3d3b4ade6154)

Następnie w zakładce *Order information (Runtime)* dopasowujemy licencję do urządzenia docelowego (dla sterownika – Target ) 

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/4f143ece-52fb-46d0-9862-493d39448c05)

Następnie wpisujemy numer zamówienia oraz wybieramy platformę zgodną z zamówieniem (powinna zostać rozpoznana automatycznie).

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/922fd6dd-cfa9-4449-a71a-e7dd4a93c8e2)

Docelowa platforma zdefiniowana jest w nazwie licencji na zamówieniu np. TC1000-00**40**

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/de09bf99-4b04-446a-8257-2f7bd7731a48)

Wybieramy *Generate File* i zapisujemy plik w dowolnym miejscu na komputerze.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/509f90b9-fa7a-498f-be5c-2828fb5189f3)

Jeżeli mamy skonfigurowaną pocztę to możemy automatycznie utworzyć maila wybierając:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/40fd062b-ec3f-4c56-b096-ad1221f5b7e5)

Wygenerowany przez nas plik wysyłamy w załączniku na adres **tclicense@beckhoff.com**. Zapytanie jest automatycznie przetwarzane przez serwer. Treść maila nie ma znaczenia.  

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/08a1957f-8da1-4d22-84e8-4361374eeca3)

Odpowiedź powinna pojawić się w ciągu kilku minut.

W odpowiedzi otrzymamy plik rejestracyjny – zapisujemy go chwilowo w dowolnym miejscu na swoim komputerze.

W opisie widzimy nazwy wszystkich licencji w pakiecie.

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/74576fe2-e246-40c0-b2b5-5846fd122564)

Dodajemy otrzymany plik rejestracyjny przyciskiem License Response File:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/79e46287-9bc0-4034-9dab-f6a38a79ab0b)

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/69451a24-bd5e-4d2c-88a3-9df1911ee9ff)

Aktywujemy konfigurację TwinCATa:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/9dea9360-7c1c-4cda-a18e-e10a7cdbe3e4)

Licencje są już aktywne:

![image](https://github.com/BA-PL/Licencjonowanie/assets/155453679/f364b055-d7c5-4c9e-931e-4da83f45fa69)










