####1.5 Característiques dels llenguatges més difosos

Existeixen molts llenguatges de programació diferents, fins al punt que moltes tecnologies tenen el seu llenguatge propi. Cada un d’aquests llenguatges té un seguit de particularitats que el fan diferent de la resta.
Els llenguatges de programació més difosos són aquells que més es fan servir en cadascun dels diferents àmbits de la informàtica.

**1.5.1 Característiques de la programació estructurada**

Es basa en el denominat teorema de l'estructura. Per això utilitza únicament tres estructures: sequència, selecció i iteració.

**Claredat**

Hi haurà d'haver prou informació al codi per tal que el programa pugui ser entès i verificat. Tot programa estructurat pot ser llegit des del principi a la fi sense interrupcions en la sequència normal de lectura.

**Teorema de l'estructura**

  * Sequència: instruccions executables successivament una darrere l'altra.
  * Selecció: la instrucció condicional amb doble alternativa de la forma "si condició, lalvors SentènciaA, sinó SentènciaB".
  * Iteració: el bucle condicional "mentre condició, fes SentènciaA", que executa les instruccions repetidament mentre la condició es compleixi.


**Disseny descendent**

El disseny descendent és una tència que es basa en el concepte de "divideix i venceràs" per tal de resoldre un problema en l'àmbit de la programació. Es tracta de la resolució delp roblema al llarg de diferents nivells d'abstracció partint d'un nivell més abstracte i finalitzant en un nivell de detall.

**Programació modular**

La realització d'un programa sense seguir una tècnica de programació modular produeix sovint un conjunt enorme de sentències l'execuó de les quals és complexa de seguir i d'entendre, amb la qual cosa es fa gairebé impossible la depuració d'errors i la introducció de millores.
Quan es parla de programació modular, ens referim a la divisió d'un programa en parts més manejables i independents. Una rela pràctica per aconseguir aquest propòsit és establir que cada segment del programa no excedeixi, en longitud d'un pam de codificació.
En la majoria de llenguatges, els mòduls es tradueixen a:
  * Procediments: Són subprogrames que duen a terme una tasca determinada i retornen 0 o més d'un valor. S'utilitzen per estructurar el programa i millorar la seva claredat.

  * Funcions: Són subprogrames que duen a terme una determinada tasca i retornen un únic resultat o valor. S'utilitzen per crear operacions noves que no ofereix el llenguatge.

**Tipus d'abstractes de dades (TAD)**

En programació, el tipus de dades d'una variable és el conjunt de valors que la variable pot assumir. Per exemple, una variable de tipus booleà pot adoptar només dos valors possibles: vertader o fals. A més hi ha un conjunt limitat per ben definit d'operacions que tenen sentit sobre els valors d''un tipus de dades; aixó operacions típiques ssobre el tipus booleà són AND o OR.
Els llenguatges de programació assumeixen un nombre determinat de tipus de dades, que pot variar d'un llenguatge a un altre.

**1.5.2 Característiques de la programació orientada a objectes**


L’**orientació a objectes** (en endavant, OO) és un paradigma de construcció de programes basat en una abstracció del món real. En un programa orientat a objectes, l’abstracció no són els procediments ni les funcions, són els objectes. Aquests objectes són una representació directa d’alguna cosa del món real, com ara un llibre, una persona, una organització, una comanda, un empleat...

Un **objecte** és una combinació de dades (anomenades atributs) i mètodes (funcions i procediments) que ens permeten interactuar amb ell. En OO, doncs, els programes són conjunts d’objectes que interactuen entre ells a través de missatges (crides a mètodes).

**Abstracció**

És el procés en el qual se separen les propietats més importants d’un objecte de les que no ho són. És a dir, per mitjà de l’abstracció es defineixen les característiques essencials d’un objecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari.

**Encapsulació**

Permet als objectes triar quina informació és publicada i quina informació és amagada a la resta dels objectes. Per això els objectes solen presentar els seus mètodes com a interfícies públiques i els seus atributs com a dades privades o protegides, essent inaccessibles des d’altres objectes. Les característiques que es poden atorgar són:
Entorns de desenvolupament 30 Desenvolupament de programari
  * Públic: qualsevol classe pot accedir a qualsevol atribut o mètode declarat
    com a públic i utilitzar-lo.
  * Protegit: qualsevol classe heretada pot accedir a qualsevol atribut o mètode
    declarat com a protegit a la classe mare i utilitzar-lo.
  * Privat: cap classe no pot accedir a un atribut o mètode declarat com a privat
    i utilitzar-lo.
    
**Modularitat**

Permet poder modificar les característiques de cada una de les classes que defineixen un objecte, de forma independent de la resta de classes en l’aplicació.

**Jerarquia**

Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són l’herència i l’agregació. L’herència també es pot veure com una forma de compartir codi, de manera que quan s’utilitza l’herència per definir una nova classe només s’ha d’afegir allò que sigui diferent, és a dir, reaprofita els mètodes i variables, i especialitza el comportament.

**El polimorfisme**

És una característica que permet donar diferents formes a un mètode, ja sigui en la definició com en la implementació.

La **sobrecàrrega (overload)** de mètodes consisteix a implementar diverses vegades un mateix mètode però amb paràmetres diferents, de manera que, en invocar-lo, el compilador decideix quin dels mètodes s’ha d’executar, en funció dels paràmetres de la crida.

Un exemple de mètode sobrecarregat és aquell que calcula el salari d’un treballador en una empresa. En funció de la posició que ocupa el treballador tindrà més o menys conceptes a la seva nòmina (més o menys incentius, per exemple).

La **sobreescriptura (override)** de mètodes consisteix a reimplementar un mètode heretat d’una superclasse exactament amb la mateixa definició (incloent nom de mètode, paràmetres i valor de retorn).

Un exemple de sobrecàrrega de mètodes podria ser el del mètode *Area()*. A partir d’una classe *Figura* que conté el mètode *Area()*, existeix una classe derivada per a alguns tipus de figures (per exemple *Recangle* o *Quadrat*).


[Tornar a l'Índex](index.md)
