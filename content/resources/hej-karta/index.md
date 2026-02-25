+++
title = "hej-karta"
draft = false
+++

## <span class="section-num">1</span> Introduction {#introduction}

Some text.


### <span class="section-num">1.1</span> Background {#background}

Some text.


### <span class="section-num">1.2</span> Purpose {#purpose}

More text.


## <span class="section-num">2</span> Details {#details}

More details here.

<h1 style="margin-bottom: 0.5em; font-size: 3.5rem;">Hej Karta</h1>

Hej Karta, testtext här.

<h1 style="margin-bottom: 0.5em; font-size: 1.0rem;"></h1>

**Innehållsförteckning**
{{&lt; toc &gt;}}


## <span class="section-num">3</span> Hantera geodata och ArcGIS Pro-projekt {#hantera-geodata-och-arcgis-pro-projekt}

Samtliga filer och projekt som du använder i ditt arbete med ArcGIS Pro ska du spara på det så kallade **Fillagret** som tillhandahålls av LiU för alla studenter och anställda. Information om Fillagret hittar du via denna länk.

Du hittar fillagret genom att klicka på den gula mappen nere i menyraden, klicka på ”This PC/Den här datorn” och sedan på Ditt LiU-ID on fillager.liu.se (X:). Observera att OneDrive alltså inte ska användas för arbete med GIS.[1]

När du arbetar med GIS-projekt finns det **tre** viktiga regler att hålla koll på:

1.  Fil- och mappnamn **ska endast innehålla följande tecken**: bokstäverna A-Z (även a-z går bra), siffror eller understreck. Tecken så som exempelvis bokstäverna Å, Ä och Ö, mellanslag eller tecken så som utropstecken (!) eller procent (%) **får inte användas**. Användningen av sådana tecken kan leda till problem så som att filer inte går att spara eller att vissa GIS-analyser inte går att genomföra.[2]

<!--listend-->

1.  Fil- eller mappnamn **måste** inledas med en bokstav (A-Z). Inled alltså inte fil- eller mappnamn med siffror eller understreck.

<!--listend-->

1.  När du arbetar med ett GIS-projekt ska du alltid separera filer som du använder dig av som har skapats av andra personer, så kallad originaldata, från de filer du själv skapar genom din användning av olika GIS-verktyg, så kallad output-data (mer om detta nedan).

Konkret innebär detta att när du börjar arbeta med GIS inom ramen för en kurs bör du gå till väga på följande sätt:

1.  Skapa en så kallad rotmapp i din fillager-mapp. I denna mapp kommer du att spara allt som hör till kursen du för tillfället läser. Döp mappen till t.ex. ”GISHT2025” eller något liknande.

<!--listend-->

1.  I rotmappen du nyss har skapat skapar du (med hjälp av ArcGIS Pro) undermappar för kursens olika moment (se ”3. Starta upp ArcGIS Pro”). Till exempel kan du för den första GIS-övningen skapa en mapp som du döper till ”IntroGIS”. Till den första laborationen skapar du en mapp som du döper till ”Labb1” och så vidare.


## <span class="section-num">4</span> Starta upp ArcGIS Pro {#starta-upp-arcgis-pro}

Starta ArcGIS Pro. Starta ett nytt projekt genom att klicka på Map (se figur 1). Namnge projektet i rutan Name (följ noga reglerna som anges under ”2. Hantera ArcGIS Pro-projekt och geodata”). Om det är det första projektet du skapar kan du exempelvis kalla det för ”IntroGIS”.

Under Location väljer du en mapp på ditt fillager. Se till att rutan Create a new folder for this project är ikryssad.[3] Tryck därefter på den gula mappsymbolen. Leta upp rotmappen där du vill spara ditt projekt (se ” 2. Spara och hantera ArcGIS Pro-projekt och geodata”). Se till att mappen är markerad och tryck på ”OK”.

Du har nu skapat ett Map Document (en aprx-fil). Filen innehåller dock inga data utan bara sökvägar till dem och om du flyttar filen så kommer länken till datan att brytas.

{{&lt; figure src="./saveproject.png" title="Figure 1. Creating a new ArcGIS Pro project" width="400px" alt="Creating a new ArcGIS Pro project" &gt;}}

I mappen för respektive kursmoment skapar du en mapp som du döper till ”originaldata”. Detta kan du göra direkt i Utforskaren i Windows (standardfunktionen för att hantera filer och mappar). I denna mapp sparar du data som du ska använda dig av i momentet som har tagits fram av någon annan, alltså exempelvis data du laddar ner från Lisam eller SLU:s geodatatjänst.

Denna typ originaldata ska du aldrig själva ändra i. Om du ändrar denna data, till exempel genom att skapa en ny fil genom användningen av ett GIS-verktyg (t.ex. Buffer) ska du spara de nya filerna i geodatabasen som hör till ditt ArcGIS Pro-projekt (detta alternativ är vanligtvis förvalt i ArcGIS Pro). Alternativt kan du om du vill spara dessa filer i en separat mapp som du skapar och döper till ”outputdata”.

Geodata levereras oftast i ”zippat” format. Zippade filer måste extraheras innan de går att använda. Extrahera mappar du har laddat ned genom att högerklicka på mappen och klicka på ”Extrahera här”.
