![pjona z driftem](https://user-images.githubusercontent.com/32707076/125853266-12323818-a49d-47e8-9393-058153ccf595.png)

# DashoBot
Darmowy i szybki DiscordBot muzyczny mający funkcje moderacyjno-rozrywkowe oraz dodatkowo funkcje dla streamerów Fortnite

# Zaproszenie
Użyj linków poniżej aby zaprosić bota na serwer

Link z ograniczonymi uprawnieniami (BETA): AKTUALNIE NIE DZIAŁA I POWODUJE MASĘ BŁĘDÓW! 

Link z uprawnieniami Admina (działa na pewno): https://discord.com/api/oauth2/authorize?client_id=865266891617861683&permissions=8&scope=bot

# Funkcje

Poniżej przedstawione są różne funkcje bota oraz porady dotyczące ich użycia


# Rozrywka
AI - Sztuczna inteligencja z którą mogą rozmawiać uczestnicy serwera. Kofiguracja za pomocą d!setai (użyj będąc na kanale na którym ma działać AI)

LICZENIE - Obsługa dynamicznej zmiany opisu kanału na którym ma odbywać się liczenie. Kofiguracja za pomocą d!setliczenie (użyj będąc na kanale na którym ma działać LICZENIE)

Więcej opisów funkcji i komend dostępne jest pod komendą d!info

# Muzyka
Bot posiada możliwość włączenia muzyki z serwisu YouTube!
Aby użyć tej funkcji skorzystaj z poniższych komend:

**d!p /lub/ d!play** [tytuł lub link z yt]

**d!purl /lub/ d!playurl** [URL do pliku muzycznego lub wideo]
  
**d!stop** - zatrzymuje
  
**d!skip** - pomija obecnie grające
  
**d!pause** - wstrzymuje
  
**d!unpause /lub/ d!resume** - Oczywiste...
  
**d!loop** - Zapętla aktualnie grającą piosenkę
  
**d!unloop** - No wiadomo...
  
**d!fix** - Naprawia odtwarzanie w razie problemów! WAŻNE: Czyści kolejkę!

# Funkcje dla streamerów Fortnite

d!weryfikacja <nick z fortnite> - Weryfikacja Custom (weryfikacja nicku Fortnite + przyznanie użytkownikowi pozwolenia na dostęp do kanału z kodami custom)

# Funkcje Moderacyjne
d!clear <0-50> - Masowe czyszczenie wiadomości (usuwanie kilku wiadomości na raz) DashoClear

d!ban <@user> - Banowanie użytkowników + pisanie powodu na DM (Coming Soon) DashoBan

d!kick <@user> <opcjonalnie: powód bana> - Kickowanie użytkowników | DashoKick
  
  ![image](https://user-images.githubusercontent.com/32707076/125937930-5c95dd56-188b-4308-90f2-5c4fad8bf611.png)


d!banchan <@user> - Blokowanie użytkownikom dostępu do określonego kanału (aktualnie w fazie testów) DashoBanChan
  

# Konfiguracja

  Kroki 4 - 7 są dla Streamerów Fortnite
  
## Krok 1. Stwórz następujące kanały
  
  Kanał informacyjny do powiadomień
  
  **---- dla streamerów Fortnite ----**
  
  Kanał do weryfikacji custom
  
  Kanał z kodami custom
  
## Krok 2. Oznacz kanały za pomocą komend (wejdź do kanału i użyj komendy)
  
  Informacyjny - d!setinfo
  
  **---- dla streamerów Fortnite ----**
  
  Kody custom - d!setcustom
  
  
## Krok 3. Zapisz swoją nazwę na YT/Twitch itp.
  
  użyj komendy - d!setchann < twoja nazwa na yt lub twitch >
  
## Krok 4. Jeżeli używasz weryfikacji custom to ukryj kanał z kodami custom (żeby tylko ranga bota mogła go zobaczyć)
 
  1.
 ![image](https://user-images.githubusercontent.com/32707076/125871514-4ee28041-2111-4859-9d61-6d0f99101ec4.png)
  
  
  2. 
  ![image](https://user-images.githubusercontent.com/32707076/125871560-00f06945-fd19-49e3-9490-a0b93562a757.png)

## Krok 5. Stwórz rolę "Zweryfikowany" i nadaj uprawnienia aby kanał z kodami custom widziała tylko ta rola (zrób to w ustawieniach kanału kody custom)
  
  ![image](https://user-images.githubusercontent.com/32707076/125872882-55b17427-4f04-4848-91c2-51e7b0cff7b6.png)
  
  ![image](https://user-images.githubusercontent.com/32707076/125872906-19075b68-2a8b-488e-a8a3-b4914476987a.png)

  ![image](https://user-images.githubusercontent.com/32707076/125872917-4233743b-b5e7-4a7d-a1d4-db36aa2943a2.png)


## Krok 6. Pozwól botowi znaleść rolę "Zweryfikowany"
  
  **WAŻNE** Upewnij się że na serwerze znajduje się tylko jedna rola "Zweryfikowany" ponieważ bot wyszuka ją po nazwie! Po zakończeniu tego kroku 
  nazwa roli będzie mogła zostać zmieniona.
  
  Wyszukaj rolę komendą - d!rola
  
  Jeżeli bot znalazł i oznaczył poprawną rolę to wpisz - d!ok
  
  ![image](https://user-images.githubusercontent.com/32707076/125913430-d0623e7c-6bdc-4cac-ab99-743d82141fcb.png)
  
  Jeżeli zamiast oznaczenia widzisz "undefined" musisz oznaczyć rolę ręcznie wpisując - d!rola @zweryfikowany
  
  ![image](https://user-images.githubusercontent.com/32707076/125913543-f41c8983-dc99-4e6e-84a0-1537f0df5ec2.png)
  
## Krok 7. Ustaw aby ŻADNA rola oprócz roli bota NIE MIAŁA pozwolenia na ZMIANĘ NICKU na serwerze!
  
  Weryfikacja działa na takiej zasadzie:
  
  Użytkownik po weryfikacji dostaje dostęp do kanału kody custom i jego nick zmienia się na ten wpisany w komendzie
  
  Zakładamy że nick wpisany w komendzie to nick z Fortnite dzięki czemu w przypadku trolla, znamy jego nick i banujemy użytkownika na serwerze 
  
  Metoda ta działa najlepiej jeżeli ustawimy na serwerze poziom weryfikacji na:
  
  ![image](https://user-images.githubusercontent.com/32707076/125917278-3837e3ea-0456-45f2-96e5-3d8c92bb53f3.png)

  Lub najlepiej na wyższy poziom tak aby trolle nie mogły szybko założyć nowego konta Discord i znowu się zweryfikować

  
## Krok 7. Przetestuj bota!
  
  Pobierz zaproszenie do serwera
  
  Wyłącz Discorda (jeżeli używasz wersji pobranej na PC)
  
  Użyj zaproszenia do serwera w KARCIE INCOGNITO! Nie loguj się do discorda!
  
  Włącz Discorda
  
  
  Teraz powinieneś/powinnaś widzieć serwer tak jak zwykły oraz tak jak widzi go właściciel serwera.
  
  Teraz przejdź weryfikację w kanale #weryfikacja-custom
  
  ![image](https://user-images.githubusercontent.com/32707076/125915334-f63a69c7-5728-475a-b4f0-14f3cdf1a7b4.png)

  Jeżeli wszystkie kroki zostały wykonane poprawnie, w karcie incognito powinieneś widzieć kanał z kodami custom dopiero po weryfikacji.
  
  Jeżeli coś poszło nie tak, patrz poniżej!
  
# Rozwiązywanie problemów
  
  
## Znane błędy
  
  Czasami bot może mieć problem z ponownym znalezieniem kanału kody custom. W takim wypadku zobaczysz następującą wiadomość:
  
  ![image](https://user-images.githubusercontent.com/32707076/125915661-184458df-86aa-4e20-bbf5-91f7bcb2e94d.png)

  Aby ją rozwiązać zweryfikuj ponownie kanał kody custom, wchodząc na niego i wpisując - d!setcustom
  
# Zgłoś błędy!
  
  Jeżeli widzisz jakiś błąd który uniemożliwia korzystanie z bota, zgłoś go tutaj w zakładce Issues!
 
  Link do zakładki Issues: https://github.com/Shieldowskyy/DashoBot/issues
  
  Link do formularza zgłaszania błędu: https://github.com/Shieldowskyy/DashoBot/issues/new
  
  Możesz też zgłosić się do mnie o pomoc na Discord! DM: Shieldowskyy#5834
  
  Przyjmuję prywatne wiadomości
  
  # Kod źródłowy i projekt
  
  Jeżeli chcesz stworzyć własną instancję DashoBota to nie ma problemu ale musisz oznaczyć w opisie bota i/lub statusie że został on stworzony przeze mnie!
  Wstaw np. "Stworzony przez Shieldowskyy" lub "Created by Shieldowskyy". Nie usuwaj informacji o autorze i nie przywłaszczaj sobię projektu. 
