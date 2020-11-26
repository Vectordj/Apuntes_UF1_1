# Apuntes_UF1_1

## Tipus de Software
N'hi han 3 tipus de software; de sistema, d'aplicació i de desenvolupament.  

## Relació Hardware-Software
**- Disc dur:** Emmagatzema arxius executables i de dades.  
**- Memòria RAM:** Emmagatzema temporalment el codi binari dels arxius executables i de dades.  
**- CPU:** Llegeix i executa instruccions emmagatzemades en la memòria RAM.  
**- Entrada i sortida:** Recogeix dades des de l'entrada.  

## Codi font, objecte i executable
- **Codi font:** Arxiu de text legible escrit en llenguatje de programació.
- **Codi objecte:** Arxiu binari no executable.
- **Codi executable:** Arxiu binari executable.

## Desenvolupament de Software
#### Fases principals
- Análisis
- Disseny
- Codificació
- Proves
- Manteniment

### Análisis
Es determina i defineix clarament les necessitats del client i s'especifica els requisits que ha de complir el software a desenvolupar.

### Disseny
Es descompon i organitza el sistema en elements components que poden ser desenvolupats per separat. També s'especifica la interrelació i funcionalitat dels elements components.

### Codificació
S'escriu el codi font de cada component.

### Proves
El principal objectiu de les proves és aconseguir que el programa funcioni incorrectament i que es descobreixin els defectes. Haurem de sometre al programa al màxim número de situacions diferents.

### Manteniment
Durant l'explotació del sistema software es necessari realitzar canvis ocasionals. Per això hi ha que refer part del treballa realitzat en les fases previes.

## Models de desenvolupament de Software
- Models clàssics (Model en cascada i model en V).
- Model de construcció de prototips.
- Models evolutius (Model en espiral i metodologies àgils).

### Model en cascada
Aquest model identifica les fases principals del desenvolupament software, les fases han de realitzar-se en l'ordre indicat. El resultat d'una fase és l'entrada de la següent fase.

### Model en V
Aquest model és una visió jerarquilitzada amb diferents nivells. Els nivells superiors indiquen una major abstracció, mentre que els enivells inferiors indiquen major nivell de detall. El resultat d'una fase és l' entrada de la següent fase.

### Prototips
Sovint els requisits no están especificats clarament perque no existia experiència prèvia i per omisió o falta de concreció de l'usuari/client.  
Es crea un prototip cudant la fase d'anàlisis i es provat per l'usuari/client per refinar els requisits del software a desenvolupar.  
  
Existeixen 2 tipus de prototips:  
- **Prototips ràpids**
  - El prototip pot estar desenvolupat utilitzant un altre llenguatje i/o eines.  
  - Finalment el prototip es rebutja.  
  
- **Prototips evolutius**
  - El prototip està dissenyat en el mateix llenguatje i eines del projecte.  
  - El prototip s'utilitza com base per desenvolupar el projecte.

### Model en espiral
L'activitat d'ingeneria correspon a les fases dels models clàssics(anàlisis, disseny, codificació, etc...).  
En l'activitat d'ingenieria es dóna gran importància a la reutilització de codi.

### Metodologies àgils
Es basa en el desenvolupament iteratiu i incremental, els requisits i solucions evolucionen amb el temps segons la necessitat del projecte.  

El treball és realitzat mitjançant  la colaboració d'equips auto-organitzats i multidisciplinaris, inmersos en un procès compartit de toma de decisions a curt plaç.  

Les metodologies més conegudes són: 
- Kanban
- Scrum
- XP (eXtreme Programming)

## Obtenció de codi executable
Tenim 2 opcions per obtenir codi binari executable. Mitjançant la compilació i la interpretació.  
- **Llenguatje compilat:** És necessari compilar cada vegada que el codi font es modifica, però a pesar d'això la seva execució és molt eficient.  
- **Llenguatje interpretat:** El seu codi font s'interpreta directament, pero al contrari que el llenguatje compilat, la execució d'aquest no és tan eficient.  

## Declaratius i imperatius
- **Declaratius:** Indiquen el resultat a obtenir sense especificar els passos que s'han seguit. Normalment son llenguatjes interpretats.
- **Imperatius:** Indiquen els passos a seguir per obtenir el resultat. Normalment son llenguatjes compilats.

## Evolució
- Codi binari
- Ensamblador
- Llenguatjes estructurats
- Llenguatjes orientats a objectes

## Criteris per la selecció d'un llenguatje
- Camp d'aplicació
- Experiència prèvia
- Eines de desenvolupament
- Documentació disponible
- Base d'usuaris
- Reutilització
- Portabilitat
- Imposició del client
