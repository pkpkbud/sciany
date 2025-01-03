# Ściany murowe i żelbetowe w ABC

[Zakup](#zakup) | [Instalacja](#instalacja) | [Wideo](#wideo) | [Instrukcja](#instrukcja) | [Kontakt](#kontakt)

Moduł do szybkiego projektowania ścian murowych i żelbetowych zgodnie z Eurokodami w
programach **ABC** firmy [PRO-SOFT](https://www.pro-soft.gliwice.pl/).

W celu zapoznania się z możliwościami modułu można obejrzeć [wideo](#wideo)
lub go [zainstalować](#instalacja). Przed [zakupem](#zakup) działa w trybie DEMO,
gdzie nie można zmieniać parametrów materiałowych jak: element murowy, beton i stal.
Szczegółowy opis działania zawarty jest w [instrukcji](#instrukcja).

## Zakup

Cena **900,- zł** netto za licencję wieczystą, na fakturze kwota będzie powiększona
o podatek VAT w wysokości 23%.

> Migracja z modułu **[Ściany murowe](https://pkpkbud.github.io/mury/)**,
który stanowi część niniejszego modułu, jest możliwa w cenie **300,- zł** netto + VAT.

Wymagana jest aktualizacja programu **ABC** do wersji minimum 6.24 zgodnie z
[cennikiem](https://www.pro-soft.gliwice.pl/cennik.html).
Moduł działa w systemach operacyjnych Microsoft Windows w wersji 7, 8, 10 i 11.
Do pobrania, aktualizacji oraz autoryzacji modułu wymagane jest połączenie z siecią.

Jeden zakup dotyczy jednej licencji (jednego klucza USB lub jednego użytkownika) i jest
niezależny od ilości programów. Kupując więcej niż jedną licencję otrzymuje się upusty:
drugi i trzeci egzemplarz - 40%, czwarty i dalsze egzemplarze - 60%.

Zakupy w formie grupowej prowadzi firma [TINSERWIS](https://www.tinserwis.pl/),
gdzie można uzyskać maksymalnie 50% rabatu. Istnieje możliwość dzierżawy modułu razem
z programami **ABC**. W celu zakupu i dzierżawy prosimy o [kontakt](#kontakt).

## Instalacja

Plik instalacyjny pobieramy w zależności od tego, jaki program **ABC** posiadamy na
kluczu USB.

W przypadku posiadania kilku kluczy USB, moduł instalujemy kilka razy w lokalizacji
programu **ABC**.

Wybieramy jeden z poniższych linków, aby rozpocząć pobieranie:

- [Mam kilka programów **ABC** na kluczu USB](https://github.com/pkpkbud/sciany/releases/download/0.2.0/Sciany-ABC6-0.2.0-win32.msi)
- [Mam tylko **ABC Płyta** na kluczu USB](https://github.com/pkpkbud/sciany/releases/download/0.2.0/Sciany-ABC6p-0.2.0-win32.msi)
- [Mam tylko **ABC Obiekt3D** na kluczu USB](https://github.com/pkpkbud/sciany/releases/download/0.2.0/Sciany-ABC6s-0.2.0-win32.msi)

Moduł instalujemy w lokalizacji programu **ABC** w folderze *EXE*
(np. *C:\ABC6\EXE*).

Spis zmian oraz poprzednie wersje są dostępne w serwisie
[GitHub](https://github.com/pkpkbud/sciany/releases).

```
Moduł podlega ochronie prawa autorskiego bez udzielania jakiejkolwiek gwarancji.
Jest sprzedawany jako narzędzie do wsparcia zarobkowego procesu projektowego.
Jest dostarczany "taki jaki jest" i nie ma gwarancji, że jest wolny od błędów pomimo
dołożenia wszelkich starań. Autor modułu nie ponosi odpowiedzialności za skutki powstałe
w wyniku nieumiejętnego posługiwania się oprogramowaniem, w tym związane z utratą
danych. Instalujący dobrowolnie wyraża zgodę na powyższe warunki licencyjne oraz
na przetwarzanie udostępnionych danych osobowych w celu obsługi zakupu licencji.
```

## Wideo

<iframe width="560" height="315" src="https://www.youtube.com/embed/CLbIOKY00J4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/4C1No9RfA6Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Instrukcja

Podczas korzystania z modułu, można uzyskać wskazówki dotyczące danej funkcji po
najechaniu na opis kursorem myszy. Jednostki, w jakich podane są wartości są po
lewej stronie każdego pola. Wartości można zmieniać, wpisując na klawiaturze i
zatwierdzając klawiszem `Enter`, klikając na znaki `góra`-`dół` po prawej stronie
pola lub wciskając klawisze strzałek `↑`-`↓` na klawiaturze.

### Uruchomienie

Moduł można uruchomić samodzielnie w trybie kalkulatora. W tym celu należy uruchomić
odpowiedni skrót z pulpitu, alternatywnie plik `mury.exe` lub `zelbet.exe`
z lokalizacji instalacji (np. *C:\ABC6\EXE*). Plik `mury.exe` uruchamia kalkulator
do projektowania ścian murowych, natomiast `zelbet.exe` uruchamia kalkulator do
projektowania ścian żelbetowych.
**Pierwsze uruchomienie należy wykonać z poziomu programu ABC.**

![image](https://github.com/user-attachments/assets/e28004e6-35af-4dd7-b590-d9aada4b6fc4)

W programach **ABC** dla podpór typu `Ściana` można zaprojektować ścianę murową
lub żelbetową. Odpowiedni moduł uruchamia się w zależności od rodzaju podpory.
W wynikach zadania w menu `Wymiar` dostępna jest opcja `Projektowanie ściany`.
W przypadku, gdy ta możliwość nie jest dostępna trzeba zaktualizować program
**ABC** do wersji 6.24, włączyć pełny zakres menu przyciskiem "M" lub wybrać
z menu opcję `Pokaż → Wybór wymiarowania`.

![image](https://github.com/user-attachments/assets/bb4f9e64-ada9-4b93-be87-0c52d6bca5b5)

### Obciążenia

Po uruchomieniu pokaże się pytanie o obciążenia. W przypadku wariantu będzie można
zmienić mnożnik obciążenia, podpowiadany z opisu obciążeń przyjmowanych do obwiedni.
Obwiednia generalnie będzie obliczana jako `Automat EN`, chyba, że są zdefiniowane
własne kombinacje wg PN-EN, to wtedy będzie można je wybrać. Przycisk `Usuń` usuwa
wcześniej zadane miejsca.

![image](https://github.com/user-attachments/assets/ffbf5d0d-0e3a-485d-86ea-5c49da33e798)

### Wybór miejsca

Po zatwierdzeniu obciążeń plansza zostanie zamknięta i pokaże się rysunek modelu.
Pojawią się podpory liniowe typu `Ściana`, należy wybrać dwa skrajne węzły
projektowanego miejsca. Punkty należy wybierać między innymi ścianami, między ścianą
i otworem lub pomiędzy otworami. Alternatywnie, w przypadku muru, można wybrać dowolne
punkty na długości ściany w celu sprawdzenia wybranego obszaru ściany pod obciążeniem
skupionym.

### Usztywnienia

![image](https://github.com/user-attachments/assets/2e0d0f91-0566-4a31-9d49-14fa1edc07ec)

W oknie można wybrać dla każdego z węzłów czy jego krawędź pionowa jest `Podparta`
czy `Swobodna`. Wybór ten ma wpływ na wysokość efektywną ściany i wartości momentów
gnących (schemat statyczny belki w przypadku braku usztywnień lub płyty).
Dodatkowo, w przypadku ścian murowych, wybór ten wpływa na stan graniczny
użytkowalności (sprawdzenie ograniczenia wysokości i długości ściany w zależności
od jej grubości zgodnie z załącznikiem F normy *PN-EN 1996-1-1*).
Opcja `Ściana obciążona siłą skupioną` pozwala na sprawdzenie wybranego obszaru
ściany pod obciążeniem skupionym, np. w miejscu oparcia belki.

### Projektowanie

Po wprowadzeniu danych na pierwszej planszy można przyciskiem `OK` przejść do planszy
głównej modułu. Odpowiednia plansza otworzy się w zależności od zadanego materiału.
Na niej przeprowadzane jest całe projektowanie. Składa się z opisanych poniżej elementów.

![image](https://github.com/user-attachments/assets/6f62a0a0-8c08-440b-b8d6-f75c98e12cb8)

**Ramki z danymi u góry**, gdzie podobnie jak na pierwszej planszy należy podać
wartości, tym razem dotyczące przyjętych założeń projektowych, materiałów, wymiarów
oraz obciążeń obliczeniowych. Opcja `Typowy` pozwala na wybór elementu murowego
z listy i automatyczne uzupełnienie parametrów elementu murowego oraz ciężaru.

![image](https://github.com/user-attachments/assets/822edd18-6677-4d66-9c33-02817b3bfffd)

Opcja `Ściana zbrojona` pozwala na zwymiarowanie zbrojenia ściany żelbetowej na
ściskanie ze zginaniem. Jest to rozwiązanie zalecane w przypadku, gdy zostanie
przekroczona wartość dopuszczalnego mimośrodu. Po wybraniu tej opcji odblokuje się
przycisk `Krzywa interakcji` w menu `Wyniki` po prawej stronie, którego włączenie
pokazuje nośność przekroju symetrycznie zbrojonego jako zależności siły podłużnej
do granicznego momentu gnącego. Wykres można przybliżać i oddalać za pomocą pokrętła
myszy. Wartości na wykresie można odczytać dowolnym przyciskiem myszy. Przycisk
`Do pliku` pozwala na zapisanie krzywej interakcji jako obrazu w formacie *.PNG*.

![image](https://github.com/user-attachments/assets/d9bc39c2-4514-40f9-9ca6-b5c8c752f235)

`Opis` można dowolnie modyfikować, domyślnie wpisane są numery węzłów.
W celu policzenia ściany jako metrowego pasma ściany o nieskońcoznej długości
należy odznaczyć opcję `Długość`. Przycisk `Wiatr` otwiera okno, gdzie po
wprowadzeniu danych dotyczących lokalizacji oraz obiektu budowlanego,
oddziaływanie wiatru według normy *PN-EN 1991-1-4* zostaje wprowadzone jako
obciążenie prostopadłe do powierzchni. Jeżeli jest zadana długość ściany i nie
ma zadanych usztywnień pionowych krawędzi, możemy określić inne niż długość
ściany pasmo zbierania obciążenia od wiatru. Przycisk `Do schowka` kopiuje
notkę z oddziaływaniem wiatru do schowka.

![image](https://github.com/user-attachments/assets/ab98d01a-f211-438d-bb29-58e5c66d73b1)

**Siły oraz momenty przyjmowane w module są wyliczone na podstawie obliczeń statycznych.**
**W programie ABC należy uwzględniać ewentualne obciążenia z wyższych kondygnacji.**
Po włączeniu opcji `Własne` wszystkie wartości obciążeń można dowolnie modyfikować oraz
można wybrać wariant z obwiedni sił. W ten sposób można zadać własną siłę skupioną,
np. w przypadku obliczeń wariantu `Ściana pod obciążeniem skupionym` albo można zadać
własne momenty gnące, np. obliczone uproszczoną metodą zgodnie z załącznikiem C normy
*PN-EN 1996-1-1*. Przycisk `Zeruj` zeruje wszystkie podane obciążenia. Ponowne
wciśnięcie przywraca wartości przed zerowaniem. Wymiary ściany oraz materiał są
pobierane z opisu podpory w programie **ABC** lub są przyjmowane wartości domyślne.

![image](https://github.com/user-attachments/assets/c38d01d3-4cac-40ec-a5d4-d65b59bea011)

**Ramka z wynikami u dołu**, która aktualizuje się po zmianie wartości parametrów
lub po naciśnięciu przycisku `Oblicz`. Każda linijka zawiera opis sprawdzanego warunku,
wzór oraz stopień wytężenia podany w procentach. W przypadku, gdy któryś warunek nie
jest spełniony, kolor tekstu zmienia się na czerwony. Nie są również pokazywane
sprawdzenia wyników o zerowym wytężeniu. W przypadku wymiarowania na obwiednię sił,
na końcu każdego wzoru w nawiasie kwadratowym podany jest decydujący przypadek.
Po najechaniu na niego kursorem myszy wyświetlone zostaną wartości sił pobrane
z programu **ABC**. Nazwa przypadku oznacza wiodące obciążenie dla warunku.

W przypadku konstrukcji murowych sprawdzane są następujące warunki nośności zgodnie
z normą *PN-EN 1996-1-1*:
- Smukłość ściany murowej zgodnie z punktem 5.5.1.4.
- Ściana murowa niezbrojona obciążona głównie pionowo zgodnie z punktem 6.1.2
(obciążenia pionowe u góry, dołu lub w środku wysokości ściany).
- Ściana murowa niezbrojona obciążona prostopadle do swojej powierzchni zgodnie
z punktem 6.3.1 (zginanie równolegle lub prostopadle do spoin wspornych).

Jeżeli została wybrana opcja `Ściana obciążona siłą skupioną` sprawdzany jest warunek
nośności ściany obciążonej siłą skupioną zgodnie z p. 6.1.3 normy *PN-EN 1996-1-1*:

![image](https://github.com/user-attachments/assets/5ec68d97-c6ad-400c-ab4d-59e2b528a8e2)

W przypadku konstrukcji z betonu sprawdzane są następujące warunki nośności zgodnie
z normą *PN-EN 1992-1-1*:
- Smukłość ściany zgodnie z punktem 12.6.5.1(5).
- Nośność obliczeniowa ze względu na moment zginający i siłę podłużną zgodnie
z punktem 12.6.1 (obciążenia pionowe u góry, dołu lub w środku wysokości ściany) lub
w przypadku wybrania opcji `Uproszczona metoda obliczania ścian usztywnionych`
nośność obliczeniowa sprawdzana jest w sposób uproszczony zgodnie z punktem 12.6.5.2.

![image](https://github.com/user-attachments/assets/20fbf9e5-4cf2-429a-9e8e-86ac9e3d63fd)

Po włączeniu opcji `Ściana zbrojona` sprawdzane są następujące warunki normowe:
- Nośność obliczeniowa jako moment graniczny przekroju symetrycznie zbrojonego według
wytycznych podanych w punkcie 6.1. Przyjmowany jest prostokątny rozkład naprężeń jak
w punkcie 3.1.7(3).
- Wymagane zbrojenie wynikające z sił wewnętrznych oraz reguł podanych w punkcie 9.6.
Ze względów praktycznych zbrojenie przyjmowane jest jako symetryczne po obu stronach
oraz pręty poziome są zlokalizowane bliżej powierzchni ściany niż pręty pionowe (główne).
- Szerokość rys zgodnie z punktem 7.3.4.

Podczas obliczeń wykonywana jest uproszczona analiza efektów drugiego rzędu zgodnie
z zasadami z punktu 5.8 normy *PN-EN 1992-1-1*. Po wybraniu opcji `Automatyczny`
sprawdzane jest kryterium smukłości elementów wydzielonych (p. 5.8.3.1). Jeżeli nie
jest spełnione, wybierana jest jedna z metod, oparta na nominalnej sztywności lub
oparta na nominalnej krzywiźnie, prowadząca do większych wartości momentów zginających.
Wybranie opcji `Brak` powoduje pominięcie efektów drugiego rzędu.

**Ramka przycisków po prawej** stronie zawierająca następujące funkcje: 
- Przycisk `Oblicz` aktualizuje część z wynikami dla zadanych wartości.
- Przycisk `Usztywnienia` otwiera ponownie wcześniej opisane okno
[Usztywnienia](#usztywnienia).
- Przycisk `Wczytaj` umożliwia otwarcie pliku zadania (z końcówką *.MUR* w przypadku
ścian murowych, *.BET* w przypadku ścian żelbetowych) w celu wczytania wcześniej
zapisanych danych.
- Przycisk `Zapisz` pozwala na zapisanie danych do pliku (z końcówką *.MUR* w
przypadku ścian murowych, *.BET* w przypadku ścian żelbetowych) w wybranej lokalizacji
na dysku.
- Przycisk `Folder` pozwala określić domyślny folder do wczytywania i zapisywania
plików z danymi.
- Przycisk `Do schowka` kopiuje listę z notką obliczeniową do schowka. Po zamknięciu
modułu schowek zostaje wyczyszczony.
- Przycisk `Do Worda` otwiera nowy dokument zawierający notkę obliczeniową. Ponowne
naciśnięcie przycisku powoduje dopisanie wyników do otwartego dokumentu. W przypadku
posiadania innego pakietu niż *Microsoft Office*, jest tworzony i otwierany
nowy plik *Nazwa_zadania.MUR.DOCX* lub *Nazwa_zadania.BET.DOCX* w lokalizacji zadania.
- Przycisk `Aktualizuj` sprawdza, czy jest uruchomiona aktualna wersja modułu oraz w
razie potrzeby umożliwia pobranie i aktualizację do najnowszej wersji. Plik instalacyjny
jest pobierany w tle, trzeba poczekać na jego pobranie. Następnie moduł jest wyłączany
i uruchamia się instalacja. Zaleca się zamknięcie programu **ABC** przed instalacją.
- Przycisk `Zamknij` zapisuje wyniki i zamyka moduł, skąd można przejść do wyboru
kolejnego miejsca.
- Przełączanie opcji `Zawsze na wierzchu` powoduje przypięcie lub odpięcie modułu ponad
innymi oknami.
- Zaznaczenie opcji `Domyślne` powoduje, że po zamknięciu modułu bieżące ustawienia
zostają zapisane jako domyślne do wymiarowania kolejnych miejsc.

## Kontakt

Wszelkie sugestie i ewentualne błędy w programie można zgłaszać poprzez e-mail
lub serwis [GitHub](https://github.com/pkpkbud/sciany/issues).

**PKPKBUD Paweł Kowalski Projektowanie Konstrukcji Budowlanych**\
NIP: 2220810920, REGON: 522155974

tel. 603 088 626\
e-mail: <pkpkbud@gmail.com>
