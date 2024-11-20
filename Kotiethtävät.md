# H3 - Demoni

## x) Tiivistelmä

## a) Apache easy mode

Asensin Apache2 virtuaalikoneelle. 

![apache asennus](https://github.com/JohannaLap/H3-Demoni/blob/main/apache%20asennus%20t002.png)

Muokkasin apachen aloitussivua. Ja varmistin että apache käynnistyy.

![apachesivu muokattu t002](https://github.com/JohannaLap/H3-Demoni/blob/main/muokattu%20apachesivu%20t002.png)

Tarkistin, että apachen tila näkyy aktiivisena. 

![apache active](https://github.com/JohannaLap/H3-Demoni/blob/main/apache%20active%20t002.png)

Loin apachelle kansion.

![mkdirapache](https://github.com/JohannaLap/H3-Demoni/blob/main/mkdir%20apache.png)

Lisäsin seuraavat sisällöt

![testisivun korvaus](https://github.com/JohannaLap/H3-Demoni/blob/main/testisivun%20korvaus%20-%20Copy.png)

Varmistin että apache edelleen käynnissä.

![apache varmistus](https://github.com/JohannaLap/H3-Demoni/blob/main/varmistus.png)

Kun yritin ajaa komentoa 'sudo '*' state.apply apache.sls' ilmaantui ongelmia. Ongelmana, ettei masteri ja minion saa enää toisiinsyhteyttä.
Yritin selvittää ongelmaa mutta tuloksetta...

![ongelmia](https://github.com/JohannaLap/H3-Demoni/blob/main/ongelmia.png)

![ongelmi](https://github.com/JohannaLap/H3-Demoni/blob/main/ongelmia2.png)

![ongelmia](https://github.com/JohannaLap/H3-Demoni/blob/main/ongelmia3%20-%20Copy.png)

b) SSHouto

Avasin configuraaion ja lisäsin portin 1234.

![etcsshsshdconfig](https://github.com/JohannaLap/H3-Demoni/blob/main/etcsshsshdconfig.png)
![portinlisäys](https://github.com/JohannaLap/H3-Demoni/blob/main/portin%20lis%C3%A4ys.png)

Käynnistin ssh:n uudelleen. 

![ssh uudelleenkäynnistys](https://github.com/JohannaLap/H3-Demoni/blob/main/ssh%20uudelleenk%C3%A4ynnistys.png)




c) Oma moduuli
Vielä mietinnässä...


d) VirtualHost

Aloitin luomalla uuden html tiedoston kotihakemistoon.

![uusi html tiedosto kotihakemistoon](https://github.com/JohannaLap/H3-Demoni/blob/main/uusi%20html%20tiedosto%20kotihakemistoon.png)

Sitten avasin apache configuraatiotiedoston ja muutin documentrootiksi äskeisen kotihakemiston

![document root vaihdettu](https://github.com/JohannaLap/H3-Demoni/blob/main/document%20root%20vaihdettu.png)

Jälleen törmäsin ongelmaan, kun en jostain syystä saa isäntäkoneelta pingattua vagrantkonetta...Jatkan selvittelyä..









