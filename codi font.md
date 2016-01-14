Per crear un programa el que es farà serà crear un arxiu i escriure a un fitxer 
el seguit d'instruccions que es vol que l'ordinador executi. Aquestes instruccions 
hauran de seguir unes pautes determinades en funció del llenguatge de programació
escollit. A més , haurien de seguir un ordre determinat que donarà sentit al programa
escrit. Per  començar n'hi haurà prou amb un editor de text simple.

Un cop s'ha acabat d'escriure el programa, el conjunt de fitxers de text resultants,
on es troben les instruccions, es diu que contenent **el codi font**. Aquest codi font 
pot ser des d'un nivell molt alt, molt a prop del llenguatge humà, fins a un de nivell
més baix, més proper al codi de les màquines, com ara el codi assemblador.

El procés anomenat **compilació** és la traducció del cdi font dels fitxers del programa
en fitxers en format binari que contenen les instruccions en un format que el processador
pot entendre. El cntingut d'aquests fitxers s'anomena **codi objecte**. El programa que fa
aquest procés s'anomena **compilador**.

El **codi objecte** és el codi font traduït (pel compilador) a codi màquina, però aquest
codig encara no pot ser executat per l'ordinador.

El **codi executable** és la traducció completa a codi màquina, duta a terme per l'enllaçador
(en anglès, *linker*). El codi executable és interpretat directament per l'ordinador.

L'**enllaçador** és l'encarregat d'inserir al codi objecte les funcions de les llibreries que
són necessàriues per al programa i de dur a terme el procés de muntatge generarnt un arxiu
executable.

Una **llibreria** és un col·lecció de codi predefinit que facilita la tasca del programador
a l'hora de codificar un programa.
