####1.3 Tipus de llenguatges de programació

Un **llenguatge de programació** és un llenguatge que permet establir una comunicació entre l'home i la màquina. El llenguatge de programació identificarà el codi font, que el programador desenvoluparà per indicar a la màquina, una vegada aquest codig s'hagi convertit en codi executable, quins passos ha de donar.

Durant el pas del temps els llenguatges de programació han anat evolucionant. Avui en dia, existeixen, fins i tot, llenguatges de programació que permeten la creació d'aplicacions informàtiques a persones sense coneixements tcnics d'informàtica, pel fet d'existir una creació pràcticament automàtica del codi a partir d'unes preguntes.

Els diferents tipus de llenguatges són:
  * Llenguatge de primera generació o llenguatge màquina.
  * Llenguatges de segona generació o llenguatge d'assemblador.
  * Llenguatges de tercera generació o llenguatges d'alt nivell.
  * Llenguatges de quarta generació o llenguatges de propòsit específic.
  * Llenguatges de cinquena generació.
  
El primer tipus de llenguatge que es va desenvolupar és l'anomenat **llenguatge de primera generació o llenguatge màquina**. És l'únic llenguatge que entén l'ordinador directament.
  * La seva estructura està totalment adaptada als circuits impresos dels ordinadors o processadors electrònics. Això fa que la programació en aquest llenguatge resulti tediosa i complicada, ja que es requereix un coneixement profund de l'arquitectura física de l'ordinador. Es un llenguatge en desús degut a la seva complexitat

El segon tipus de llenguatge de programació són els **llenguatges de segona generació on llenguatges d'assemblador**. Es tracta del primer llenguatge de programació que utilitza codis mnemotècnics per indicar a la màquina les operacions que ha de dur a terme. Aquestes operacions, molt bàsiques, han estat dissenyades a partir de la coneixença de l'estructura interna de la pròpia màquina.
  * Cada instrucció en llenguatge d'assemblador correspon a una instrucció en llenguatge màquina.

**1.3.1 Característiques dels llenguatges de primera i segona generació**

Avantatges:
  * Permeten escriure programes molt optimitzats que aprofiten al màxim el maquinari.
  * Permeten al programador especificar exactament quines instruccions vol que s'executin.

Inconvenients:
  * Els programes escrits en llenguatges de baix nivell estan completament lligats al maquinari on s'executaran i no es poden traslladar fàcilment a altres sistemes amb un maquinari diferent.
  * Cal conèixer a fons l'arquitectura del sistema i del processador per escriure bons programes.
  * No permeten expressar de forma directa conceptes habituals a nivells d'algorisme.
  * Son difícils de codificar, documentar i mantenir


El següent grup de llenguatges es coneix com a **llenguatges de tercera generació o  llenguatges d'alt nivell**. Aquests llenguatges, més evolucionats, utilitzen paraules i frases relativament fàcils d'entendre i proporcionen també facilitats per expressar alteracions del  flux de control d'una forma bastant senzilla i intuïtiva. S'utilitzen quan volen desenvolupar aplicacions grans i complexes, on es prioritza el fet de facilitar i comprendre com fer les coses per sobre del rendiment del programari o del seu ús de la memòria.

Els **compiladors** son programes que tradueixen el programa escrit amb un llenguatge d'alt nivell al llenguatge màquina. El compilador detectarà els possibles errors del programa font per aconseguir un programa executable depurat. El procediment que haurà de seguir un programador és el següent:

  * Crear el codi font.
  * Crear el codi executable fent ús de compiladors i enllaçadors.
  * El codi executable depèn de cada sistema operatiu. er a cada sistema hi ha un compilador,
    és a dir, si es vol executar el codi amb un altre sistema operatiu s'ha de recompilar el codi
    font.
  * El programa resultant s'executa directament des del sistema operatiu.
  
L'**intèrpret** és un programa que tradueix el codi d'alt nivell a codi de bytes, però, a diferència del compilador, ho fa en temps d'execució. És a dir, no es fa un procés previ de traducció de tot el programa font a codi de bytes, sinó que es va traduint i executant instrucció per instrucció.
Algunes característiques són:
  * El codi interpretat no és executat directament pel sistema operatiu. sinó que fa ús d'un intèrpret.
  * Cada sistema té el seu propi intèrpret.

**1.3.2 Característiques dels llenguatges de tercera, quarta i cinquena generació**

Són aquells que són capaços de contenir i executar, en una sola instrucció, l'equivalent a diverses instruccions d'un llenguatge de segona generació.

Avantages:

  * El codi dels programes és molt més senzill i comprensible.
  * Son independents del maquinari. Per aquest motiu es possible portar el programa entre diferents ordinadors/arquitectures etc...
  * És més fàcil i ràpid escriure els programes i més fàcil mantenir-los. 

Inconvenients:

  * La seva execució en un ordinador pot resultar més lenta que el mateix programa escrit en llenguatge de baix nivell, tot i que això depèn molt de la qualitat del compilador que faci la traducció

Els **llenguatges de quarta generació o llenguatges de propòsit específic**. Aporten un nivell molt alt d’abstracció en la programació, permetent desenvolupar aplicacions sofisticades en un espai curt de temps, molt inferior al necessari per als llenguatges de 3a generació.

Alguns dels aspectes positius que mostren aquest tipus de llenguatges de programació
són:
  * Major abstracció.
  * Menor esforç de programació.
  * Menor cost de desenvolupament del programari.
  * Basats en generació de codi a partir d’especificacions de nivell molt alt.
  * Es poden dur a terme aplicacions sense ser un expert en el llenguatge.
  * Solen tenir un conjunt d’instruccions limitat.
  * Són específics del producte que els ofereix.

Els **llenguatges de cinquena generació** són llenguatges específics per al tractament de problemes relacionats amb la intel·ligència artificial i els sistemes experts.
  * En lloc d'executar només un conjunt d'ordres, l'objectiu d'aquests sistemes és "pensar" i anticipar les necessitats dels usuaris.

[Torna a l'Índex](index.md)
