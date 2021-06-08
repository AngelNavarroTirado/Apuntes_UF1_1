# Apuntes_UF1_1

# Index

- **Introducció**
- **Cicle de vida del software**
- **Llenguatges de programació**


## Introducció

### Tipus de software

- **Software de sistema**: És el conjunt d'instruccions que permeten el maneig de la computadora (Sistemes operatius, drivers).
- **Software d'aplicació**: És un tipus de programari de computadora dissenyat per a realitzar un grup de funcions, tasques o activitats coordinades per al benefici de l'usuari (Suite ofimática, Navegador, Edició d'imatge, ...).
- **Software de desenvolupament**: És un tipus de programari de computadora dissenyat per a realitzar nou contingut (Editores, compiladores, interpretes, ...). 

### Relació HARDWARE-SOFTWARE

- **Disc dur**: Emmagatzema de manera permanent arxius executables i arxius de dades.
- **Memoria RAM**: Emmagatzema de manera temporal el codi binari dels arxius executables i els arxius de dades necessaris. 
- **CPU**: Llegeix i executa instruccions emmagatzemades en la memòria RAM, així com les dades necessàries.
- **E/S**: Reuneix noves dades des de l'entrada, es mostren els resultats, es llegeixen / guarden a un disc...

### Codis fonts, objectes i executables

- **Codi font**: Arxius de text legible escrit en un llenguatge de programació
- **Codi objecte**: Arxiu binari no executable.
- **Codi executables**: Arxiu binari executable.


## Cicle de vida del Software

### Enginyeria de Software

>Disciplina que estudia els principis i
>metodologias per el desenvolupament i 
>manteniment de sistemes software.

- La enginyeria de software és una de les branques de les ciències de la computació que estudia la creació de programari de confiança i de qualitat, basant-se en mètodes i tècniques d'enginyeria.

### Desenvolupament de Software

#### Fases principals

- **Anàlisis**
- **Disseny**
- **Codificació**
- **Proves**
- **Manteniment**

#### Anàlisi

En l’analisis és determina i defineix les caracteristiques i necessitats que el client vol pel programa.

#### Disseny

En el diseny descompondrem i organitzarem el sistema en elements per el desenvolupament individual.

#### Codificació

En la codificació s’escriu el codi font de cada component.

#### Proves

En les probes el objectiu sera probar el rendiment del software.

#### Manteniment

En el manteniment és l’apartat on és realizataran canvis ocasionals per la millora del software.

## MODELS DE DESENVOLUPAMENT DE SOFTWARE

- **Model clàssic**
  - **Model en cascada**
  - **Model en V**
- **Model de construcció de prototips**
- **Model evolutius o incrementals**
  - **Model en espiral**
  - **Metologia agil**
  
### Model en cascada

Té les següents característiques:
- Es el model més antic.
- Identifica les fases principals de desenvolupament programari.
- Les fases s'han de fer en l'ordre indicat.
- El resultat d'una fase és l'entrada de la següent fase.
- És un model bastant rígid que s'adapta malament a el canvi continu d'especificacions.
- Existeixen diferents variants amb més o menys quantitat d'activitats.

### Model en V

- Es un model molt semblant a el model en cascada.
- Visió jerarquitzada amb diferents nivells.
- Els nivells superiors indiquen major abstracció.
- Els nivells inferiors indiquen major nivell de detall.
- El resultat d'una fase és l'entrada de la següent fase.
- Existeixen diferents variants amb més o menys quantitat d'activitats.



### Model de construcció de prototips

En els prototips de tant en tant no estan especificats clarament per els següents motius:

- Per no existir experiència prèvia.
- Per omissió o falta de concreció de l'usuari / client.

Procés dels prototips:

- Es crea un prototip durant la fase d'anàlisi i és provat per l'usuari / client per refinar els requisits de programari a desenvolupar.
- Es repeteix el pas anterior les vegades necessàries.


Tipus de prototips:

- Prototips ràpids:
  - Prototip pot estar desenvolupat usant un altre llenguatge i / o eines
  - Finalment el prototip es rebutja.
- Prototips evolutius:
  -  El prototip està dissenyat en el mateix llenguatge i eines de el projecte.
  - El prototip es fa servir com a base per desenvolupar el projecte.



### **Model en espiral**

El model en espiral va ser desenvolupat per Boehm en 1988.

L'activitat d'enginyeria correspon a les fases dels models clàssics: anàlisi, disseny, codificació, proves i manteniment.

**Aplicat a la programació orientada a objectes:**

En l'activitat d'enginyeria es dóna gran importància a la reutilització de codi.


### **Metodologies àgils**

Les metodologies àgils són:

- Mètodes d'enginyeria de programari basats en el desenvolupament iteratiu i incremental.
- Els requisits i solucions evolucionen amb el temps segons la necessitat de el projecte.
- El treball és realitzat mitjançant la col·laboració d'equips auto-organitzats i multidisciplinaris, immersos en un procés compartit de presa de decisions a curt termini.
- Les metodologies més conegudes són:
  - Kanban 
  - Scrum
  - XP (eXtreme Programing)

En les metodologies àgils també podem trobar **Manifest pel Desenvolupament Àgiló**:

- **Individus i interaccions** sobre processos i eines.
- **Programari funcionant** sobre documentació extensiva.
- **Col·laboració amb el client** sobre negociació contractual.
- **Resposta davant el canvi** sobre seguir un pla.


#### **KANBAN**

KANBAN o dit d'un altre manera "sistemes de targetes", esta desenvolupat per Toyota per la industria de fabricants de productes.
Controla per demanda, la fabricació dels productes necessaris en la quantitat i temps necessaris.
I esta enfocat a lliurar el màxim valor per als clients, utilitzant els recursos justos.


#### **SCRUM**

**Conceptes** de scrum:

- Es un model de desenvolupament incremental.
- Fer interaccions regulars cada 2,3 o 4 setmanes.
- Al principi de cada iteració s'estableixen els seus objectius prioritzats (sprint backlog).
- A l'acabar cada iteració s'obté un lliurament parcial utilitzable pel client.
- Hi reunions diàries per tractar la marxa de l'esprint/projecte.

**Rols** Principals:

- **Product Owner**: Es la veu del client. Defineix criteris d'acceptació i assegura que es compleixin.

- **Scrum Màster:** Assegura que se segueix la metodologia Scrum. Motiva i facilita el treball de l'equip i ajudar a eliminar impediments que poden afectar al lliurament del producte. A més, s'encarrega de les tasques de mentoring i formació, coaching i de facilitar reunions i esdeveniments si cal.

- **Team:** Es l'equip de desenvolupament auto-organitzat i multifuncional que esta format entre 6 i 10 membres.


**Artefactes**

- **Product Backlog:** Llista ordenada amb els requisits del producte

- **Sprint Backlog:** Llista de requisits trets de l'backlog per al seu desenvolupament durant l'esprint

- **Increment:** Es l'estat del producte després de cada esprint

---

## **LLENGUATGES DE PROGRAMACIÓ**

### **Obtenció de codi executable**

Per obtenir codi binari executable tenim 2 opcions, per:
- Compilació
- interpretació


### **Procés de compilació / interpretació**

La compilació / interpretació de el codi font es porta a terme en dues fases:
- Anàlisi lèxic
- Anàlisi sintàctica

Si no hi ha errors, es genera el codi objecte corresponent.

Un codi font correctament escrit no vol dir que funcioni segons el desitjat.

No es realitza una anàlisi semàntic.



### **Llenguatges compilats**

Exemples: C, C++.

- **Principal avantatge:** Execució molt eficient.

- **Principal desavantatge:** Cal compilar cada vegada que el codi font és modificat.



### **Llenguatges Interpretats**

Exemples: PHP, Javascript.

- **Principal avantatge:** El codi font s'interpreta directament.

- **Principal desavantatge:** Execució menys eficient.


### **Javas**

Es un lleguatge de compilació he interpretació.

El codi font Java es compila i s'obté un codi binari intermedi denominat bytecode, després aquest bytecode s'interpreta per executar-lo.

Es pot considerar codi objecte però destinat a la màquina virtual de Java en lloc de codi objecte natiu.

- **Principal avantatge:** 
  - Estructurat i Orientat a Objectes
  - Relativament fàcil d'aprendre
  - Bona documentació i base d'usuaris

- **Principal desavantatge:**
  - Menys eficient que els llenguatges compilats


### **Tipus**

Els tipus es segons la forma en què operen:
- **Declaratius:** indiquem el resultat a obtenir sense especificar els passos.
- **Imperatius:** indiquem els passos a seguir per obtenir un resultat.

#### **Lenguajes declarativos** (Normalment són llenguatges interpretats):
- Lògics: Utilitzen regles. Ex: Prolog
- Funcionals: Utilitzen funcions. Ex: Lisp, Haskell
- Algebraics: Utilitzen sentències. Ex: SQL

#### **Lenguajes Imperatius** (Normalment són llenguatges interpretats):

- **Estructurats:** C
- **Orientats a objectes:** Java
- **Multiparadigma:** C++, Javascript

Els llenguatges orientats a objectes són també llenguatges estructurats.
Molts d'aquests llenguatges són compilats.

#### **Tipus: Segons el nivell d'abstracció**

Tipus de llenguatges segons nivell d'abstracció:
- Baix nivell: assemblador (codi maquina, comandes, etc..)
- Medi nivell: C
- Alt nivell: C ++, Java (són els que tenen que utilitzar un IDE para fer-ho)

---

### **EVOLUCIÓN**

- Codi binari
- Assemblador
- Llenguatges estructurats
- Llenguatges orientats a objectes

---

### **CRITERIS PER A LA SELECCIÓ D'UN LLENGUATGE**

- Camp d'aplicació
- Experiència prèvia
- Eines de desenvolupament
- Documentació disponible
- Base d'usuaris
- Reusabilitat
- Portabilitat
- Imposició de el client
