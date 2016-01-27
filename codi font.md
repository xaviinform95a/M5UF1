####1.2 Codi font, codi objecte i codi executable: màquines virtuals.

Per crear un programa el que es farà serà crear un arxiu i escriure a un fitxer el seguit d'instruccions que es vol que l'ordinador executi. Aquestes instruccions hauran de seguir unes pautes determinades en funció del llenguatge de programació escollit. A més , haurien de seguir un ordre determinat que donarà sentit al programa escrit. Per  començar n'hi haurà prou amb un editor de text simple.

Un cop s'ha acabat d'escriure el programa, el conjunt de fitxers de text resultants, on es troben les instruccions, es diu que contenent **el codi font**. Aquest codi font pot ser des d'un nivell molt alt, molt a prop del llenguatge humà, fins a un de nivell més baix, més proper al codi de les màquines, com ara el codi assemblador.

El procés anomenat **compilació** és la traducció del cdi font dels fitxers del programa en fitxers en format binari que contenen les instruccions en un format que el processador pot entendre. El cntingut d'aquests fitxers s'anomena **codi objecte**. El programa que fa aquest procés s'anomena **compilador**.

El **codi objecte** és el codi font traduït (pel compilador) a codi màquina, però aquest codig encara no pot ser executat per l'ordinador.

El **codi executable** és la traducció completa a codi màquina, duta a terme per l'enllaçador (en anglès, *linker*). El codi executable és interpretat directament per l'ordinador.

L'**enllaçador** és l'encarregat d'inserir al codi objecte les funcions de les llibreries que són necessàriues per al programa i de dur a terme el procés de muntatge generarnt un arxiu executable.

Una **llibreria** és un col·lecció de codi predefinit que facilita la tasca del programador a l'hora de codificar un programa.

**1.2.1 Màquina virtual**

El concepte de màquina virtual sorgeix amb l’objectiu de facilitar el desenvolupament de compiladors que generen codi per a diferents processadors.
La compilació consta de dues fases:
  * La primera parteix del codi font a un llenguatge intermedi obtenint un
    programa equivalent amb un menor nivell d’abstracció que l’original i que
    no pot ser directament executat.
  * La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible
    per la màquina.

L'objectiu de dividir el codi en dues fases és que el codi de la primera fase, el codi intermedi, sigui comú per a qualsevol processador, i que el codi generat en la segona fase sigui l'específic per a cada processador.

**La màquina virtual Java**

La màquina virtual Java, és l'entorn en què s'executen els programes Java. És un programa natiu, és a dir, executable en una plataforma específica, que és capaç d'interpretar i executar instruccions expressades en un codi de bytes que es generat pel compilador del llenguatge Java.
La màquina Java és una peça fonamental de la tecnologia Java. Se situa en un nivell superior al maquinari sobre el qual es vol executar l'aplicació i actua com un pont entre el codi bytes a executar el sistema.
El gran avantage de la JVM és que possibilita la portabilitat de l'aplicació a diferents plataformes i, així un programa Java escrit en un sistema operatiu Windows es potexecutar en altres sistemes operatius amb l'únic requeriment de disposar de la JVM per al sistema corresponent

[Torna a l'Índex](index.md)
