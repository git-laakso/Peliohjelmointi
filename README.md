# Peliohjelmointi
## Johdanto
Tämä on jatkokehitetty peli <a href="https://github.com/git-laakso/My-Zombie-Survival">kurssiprojektista.</a> <br>
<b>Lataa tämän version projekti <a href="https://www.dropbox.com/s/72t64jv2yvico6a/MyZombieSurvival.zip?dl=0">täältä</a> tai pelaa valmiiksi buildattua peliä <a href="https://www.dropbox.com/sh/6e0ve3pgz7zoua8/AADXhu0E8XoFimNSoB0r-k51a?dl=0">täältä</a>.</b>

## Peliin on lisätty seuraavat ominaisuudet alkuperäisestä:
-Paranneltu elämäpistejärjestelmä. Int damage vaihdettu float damageen ja collisioneita muutettu sopivammaksi pelin mekaniikkaan <br> 
-Aseen luotiin lisätty suurempi voima (<a href="https://docs.unity3d.com/ScriptReference/Rigidbody.AddForce.html">AddForce</a>) <br> 
-Pelaajan nopeutta lisätty <br>
-Teleport käyttäen transform new Vector3:sta, kun lasketaan killCount lukemaksi 17. Pelaajaa liikutellaan näin eri tasoille <br> 
-Lisätty uutta pelialuetta <br>
-Korjattu bugina pelaajan tippuminen pois pelikentältä, kun vihollista katsoo 80 asteen kulmassa vasten seinää ja kulkemalla taaksepäin
