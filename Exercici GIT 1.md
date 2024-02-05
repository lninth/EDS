# Exercici GIT 1: Creació i actualització de repositoris
## Lorenzo Cremonese

Indica els comandaments amb els quals resoldries els escenaris plantejats en els diferents exercicis.  

### Exercici 1

1. Crea un repositori nou amb el nom llibre i mostra el seu contingut.  
   mkdir llibre  
   cd llibre  
   git init  
   ls -a  

2. Configura Git definint el nom de l'usuari, el correu electrònic i activa l'exida en color. Mostra la configuració final.  
   git conifg --global user.name "lorenzo"  
   git config --global user.email "lorenzo.cremonese10@gmail.com"  
   git config color.ui true  
   git config --list

### Exercici 2

1. Comprova l'estat del repositori.  
   git status
2. Crea un fitxer índex.txt amb el següent contingut:
   > Capítol 1: Introducció a Git
   > 
   > Capítol 2: Fluxe de treball bàsic
   > 
   >  Capítol 3: Repositoris remots
   
   nano index.txt  
   git status  
   
3. Comprova de nou l'estat del repositori.   
   git status
   
4. Afegeix el fitxer a la zona d'intercanvi temporal.  
   git add .  
   
5. Torna a comprovar una vegada més l'estat del repositori.  
   git status  

### Exercici 3

Realitza un commit dels últims canvis amb el missatge "Afegit índex del llibre." i revisa l'estat del repositori.  
git commit -m "Afegit índex del libre"   
git status  

### Exercici 4

