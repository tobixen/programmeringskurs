| ``= Variabler, konstanter, de fire regneartene og sirkelen =``
| ``== Tallvariabler ==``
| ``Nesten alle programmeringsspråk har noe som heter ``\ *``variabel``*\ ``.  En variabel har et navn og en verdi.  Eksempel på navn er f.eks. ``\ *``a``*\ ``, ``\ *``b``*\ ``, ``\ *``antall_elever``*\ ``, ``\ *``lengde``*\ ``, ``\ *``vinkel``*\ ``.  Verdien kan f.eks. være et tall - som 3.  En variabel kan endre seg mens programmet kjører.``
| ``Dersom man har en variabel som ikke skal endre seg mens programmet kjører, kaller man det en konstant.  I python er det ingen forskjell mellom konstanter og variabler - men det er vanlig å bruke STORE BOKSTAVER når man navngir konstanter og små bokstaver når man navngir variabler.``
| ``Du bestemmer navnet på variabelen.  I python (og de fleste andre programmeringsspråk) kan et variabelnavn bestå av bokstaver, tall og understrek (_), men kan ikke begynne på et tall.``
| ``Vi kommer tilbake til variabler i bash senere.``
| ``=== Eksempel ===``
| ``Start python fra et terminalvindu, og skriv:``
| `` a = 3``
| `` print(a)``
| `` a = 6``
| `` print(a)``
| `` b = 9``
| `` print(b)``
| ``== De fire regneartene ==``
| ``I python (og de fleste andre programmeringsspråk) bruker vi plusstegn og minustegn (bindestrek) for addisjon og subtraksjon, stjernetegn (*) for multiplikasjon, og skråstrek (/) for divisjon.``
| ``Gjett hva dette vil gi oss:``
| `` b - a``
| `` b/3``
| `` b = b + 1``
| `` a*b``
| ``Dere kan også prøve ut to gangetegn (**) for eksponenten, to skråstreker (//) for heltallsdivisjon og prosenttegn (%) for modulo.``
| `` 64**64``
| `` 5//2``
| `` 5/2``
| `` 5%2``
| ``Hva tror du dette vil gi?``
| `` 2+2*2``
| `` 2*2+2``
| `` (2+2)*2``
| ``== Vinkler ==``
| ``Hva er en ``\ *``vinkel``*\ ``?``
| ```http://www.youtube.com/watch?v=iw8hBzSjxlg`` <http://www.youtube.com/watch?v=iw8hBzSjxlg>`__
| ``I forrige leksjon gjorde vi ``\ *``left(90)``*\ `` og lagde en ``\ *``rett``*\ `` vinkel.  En rett vinkel er en fjerdedels sirkel.  En sirkel er 360 grader.  Prøv:``
| `` SIRKEL=360``
| `` left(SIRKEL)``
| `` left(SIRKEL/4)``
| `` left(SIRKEL/2)``
| `` left(SIRKEL*5)``
| ``Prøv dette:``
| `` forward(60)``
| `` left(SIRKEL/3)``
| `` forward(60)``
| `` left(SIRKEL/3)``
| `` forward(60)``
| ``= Oppgaver =``
| ``Regn ut:``
| ``* Seks ganger seks``
| ``* 1456 pluss 6621``
| ``* Lag en firkant ved bruk av konstanten SIRKEL``
| ``= Neste leksjon =``
| ``I ``\ ```Leksjon``\ ````\ ``3`` <Leksjon_3>`__\ `` skal vi lære hvordan vi kan bruke ``\ *``for-løkker``*\ `` til å kjøre de samme kommandoene tusen ganger uten å måtte skrive kommandoene tusen ganger.``
