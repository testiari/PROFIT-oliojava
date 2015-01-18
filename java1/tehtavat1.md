#1. Teht�v�t#

Ensimm�isen tapaamiskerran teht�v�t.

##L�mmittelyt##

Tee n�m� teht�v�t ensin

###Kokonaislukuja###

Luo luokka, jolla on yksi metodi. Metodi osaa tulostaa kaikki kokonaisluvut 0 - 1000, joiden neli�juuri on kokonaisluku.

###Muuttujia###

Luo tekstitiedosto (esim muuttujia.txt) ja vastaa:

Miten esittelisit (tyyppi ja nimi) muuttujat seuraavia tilanteita varten. Anna my�s esimerkki miten sijoittaisit muuttujalle jonkin arvon. Vastauksen voit palauttaa Java-tiedostonakin.

+ Ty�matkan pituus polkupy�r�ll�
+ Suoritettujen opintopisteiden m��r� 
+ Koko tutkinnon laajuus opintopisteiss�
+ Tehtyjen demojen lukum��r� 
+ Kirjan ensimm�inen kirjain
+ Sadan metrin juoksun voittajan aika.

Arvostele seuraavat muuttujien tyypit ja nimet. Ovatko syntaktisesti oikein? Ent� ovatko hyvi� valintoja:

+ int mansikanKiloHinta;
+ double first,second,final;
+ char omaNimi;
+ double metriMm;
+ double tuntejaVuorokaudessa;
+ real nopeus;
+ double AuringonEtaisyys;
+ int kuukaudenKeskiLampo:
+ int kissoja,2_kanaa,kolmeKoiraa;
+ int i,j,l,I;

###Merkkijonoja###

OSA I

1. Luo luokka Merkkijono
Tutki String-luokan dokumentaatiota ja tee sen avulla seuraavat teht�v�t:

2. Luo p��ohjelmassa merkkijono "Aasin silta alla auringon maan taivaan p��kallon"
3. Luo metodi, joka muuttaa joka toisen kirjaimen isoksi ja ottaa sen talteen uuteen muuttujaan ja palauttaa sen metodin kutsujalle
4. Luo p��ohjelmassa tarvittavat oliot ja testaa 

P�hkin�: miksi String-olioiden ankara k�sittely voi aiheuttaa turhaa muistink�ytt��?

OSA II

Lyhyk�idyysess��n: luo luokka, jonka metodi osaa parsia merkkijonoista erilleen kaikki v�limerkill� erotetut sanat ja palauttaa ne lista-oliona.

###Toistorakenteita###

1. Tee luokka, jolla on metodi, joka osaa tulostaa parametrina annetun pituuden verran Fibonaccin lukujonoa. T�m� metodi tekee homman while-toistorakenteella
2. Tee toinen metodi, joka tekee saman tempun, mutta for-rakenteella 

##Hello World##

Muuta HelloWorld.java siten, ett�

1. Muuta luokka HelloWorld ei-staattiseksi
2. Luo luokalle metodi yellToWorld, joka ottaa parametrina vastaan nimen ja huutaa sen maailmalle (esim. "Hello World it's Ari here!")
3. Luo staattisessa p��ohjelmassa yksi HelloWorld-olio
4. Kutsu olion yellToWorld metodia omalla nimell�si

##Simple Graphics##

1. Luo luokalle SimpleGraphics metodit, joka osaa piirt�� yhden viivan. Metodille annetaan parametrina ikkuna, johon piirret��n ja viivan koordinaatit
2. Luo my�s metodi, joka kutsuu edellist� viivan piirtoa ja tekee automaattisesti neli�n parametreina sy�tettyihin koordinaatteihin
3. Luo staattisessa p��ohjelmassa ikkuna
4. Luo SimpleGraphics olio ja viskaa sen avulla ikkunaan 150 kappaletta neli�it� satunnaisiin koordinaatteihin

##Olioportaat##

Voit nasauttaa koko h�sk�n olioiksi tai k�ytt�� viel� t�ss� teht�v�ss� staattisia aliohjelmia

###Porras yl�s###

Toteuta metodi, joka piirt�� portaan yl�s

###Porras alas###

Toteuta metodi, joka piirt�� portaan yl�s

###Portaat toimimaan###

Pist� luokka Portaat toimimaan, kuten p��ohjelman kommenteissa sanotaan..

Esimerkiksi piirraPortaat(window,0,0,5) syntyv� kuva on seuraavan n�k�inen:

```

          _ (5,5)
        _| |_
      _|     |_
     |         |

```





