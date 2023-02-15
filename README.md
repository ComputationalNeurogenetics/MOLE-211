# MOLE-211

Tässä repossa on tarvittava koodi (html ja Rmd tiedosto /code kansiossa) sekä lähtödata (/data kansiossa) MOLE-211 kurssin scRNA harjoitustöihin.

Harjoituksissa lähdetään yhdestä hiiren alkion (E13.5) taka-aivojen alueen (rhombomere 1) scRNA sekvensointi näytteen sekvensointi tuloksesta. Sekvensointi data on kansiossa /data/. Tavoitteena on piirtää näytteestä solutason hajotelma UMAP algoritmilla sekä katsoa muutamien markkeri geenien ilmentymistä soluissa.

Harjoitus on tarkoitus tehdä R-Studiolla ja se vaatii yhden ylimääräisen paketin (Seurat) sekä sen riippuvuudet. Tarvittavat R komennot analyysiin on annettu /code/MOLE211_scRNA_pipeline.nb.html tiedostossa. Koodin joukossa on selityksiä vaiheista sekä myös kysymyksiä merkattuna lyhenteellä SA (=SelfAssesment). Voit käyttää niitä arvioidaksesi oletko sisäistänyt keskeisimmät asiat.

Voit tehdä harjoituksen useammalla eri tavalla.
1. Kopioida komennot html tiedostosta R promptiin ja ajaa siinä.
2. Kopioida komennot html tiedostosta R-scripti tiedostoon ja ajaa se.
3. Avata MOLE211_scRNA_pipeline.Rmd (joka on se tiedosto mikä on luonut myös html tiedoston) ja ajaa R koodi siellä osa kerrallaan.

Valitse näistä oman R osaamisen suhteen, 1 on yksinkertaisin ja helpoin tapa aloittaa aivan alusta R:n kanssa työskentely. 3 on tavallaan vaativin, mutta loppujen lopuksi myös antoisin ja hyödyllisin tapa oppia R-Studion käyttöä. Varsinaisen analyysin tuloksen kannalta ei ole väliä minkä tavan valitset.
