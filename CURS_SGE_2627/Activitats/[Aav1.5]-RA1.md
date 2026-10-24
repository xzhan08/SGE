# Activitat 1.5 — Documentació d'operacions i incidències

## MÒDUL: Desenvolupament d'aplicacions multiplataforma

RA1: Identifica sistemes de planificació de recursos empresarials i de gestió de relacions amb clients (ERP-CRM) reconeixent-ne les característiques i verificant la configuració del sistema informàtic. 

## RECURSOS

 - Teoria RA1

## CONDICIONS DE TREBALL

 - Treball individual
 - Entregar al Moodle l'enllaç del github
 - Github:
   - Continuar amb el repositori de l'activitat **Aav1.4**.
   - Treballar a la branca **ra1**.
   - Al acabar l'activitat, fusionar la branca **ra1** a la branca **main** del github.    

## AVALUACIÓ

 - Activitat avaluable amb **A** (Apte) o **NA** (No Apte).
 - Condicions per a **Apte**:
   - 100% de l'activitat demanada.
   - Entregar l'activitat a la data indicada.
   - Treballar amb branca i l'ús de commits.
 - Entregar en format **.md** (markdown) amb la mateixa nomenclatura que el de l'activitat actual.

## ENUNCIAT

Reprenent les comprovacions fetes a l'**activitat 1.4**:

## 1. Informe d'operacions realitzades

### Operació 1
* **Operació:** Verificació del Sistema Operatiu i l'espai lliure en disc.
* **Comanda/acció executada:** Comprovació de les propietats del sistema a Windows 11 i revisió de l'espai de l'unitat de disc principal (C:).
* **Resultat obtingut:** Windows 11 (versió 25H2) amb 239 GB d'espai lliure en disc. El sistema compleix amb els requisits d'emmagatzematge de sobres.
* **Data:** 24 d'octubre de 2026

### Operació 2
* **Operació:** Comprovació de la disponibilitat del port de connexió per defecte de PostgreSQL (5432).
* **Comanda/acció executada:** **tstat -ano | findstr 5432**
* **Resultat obtingut:** El port està lliure (la comanda no ha retornat cap línia de text ni procés actiu).
* **Data:** 24 d'octubre de 2026

### Operació 3
* **Operació:** Comprovació de la disponibilitat del port per defecte d'Odoo (8069).
* **Comanda/acció executada:** **tstat -ano | findstr 8069**
* **Resultat obtingut:** El port està lliure (sense cap servei escoltant en aquesta adreça), apte per a la futura instal·lació d'Odoo.
* **Data:** 24 d'octubre de 2026|

## 2. Documentació d'una incidència

* **Data i hora:** 24 d'octubre de 2026 a les 13:30 PM
* **Descripció del problema:** Durant les comprovacions d'entorn per a la instal·lació del sistema ERP, s'ha detectat que el sistema de gestió de bases de dades PostgreSQL no es troben instal·lats ni configurats al sistema operatiu.
* **Passos per reproduir-lo:**
  1. Obrir la línia de comandes (CMD).
  2. Executar la comanda per mirar la versió de Python: **python --version**.
  3. Executar la comanda per mirar la versió de PostgreSQL: **psql --version**.
* **Missatge d'error obtingut:** (Not found).
* **Causa detectada:** El sistema informàtic base (Windows 11) és una instal·lació neta o de treball general que encara no té configurat el programari ni l'entorn de desenvolupament necessari per allotjar Odoo.
* **Solució aplicada (o proposada):**
  * **Per a Python:** Descarregar l'instal·lador oficial executable des de la pàgina web de Python o instal·lar directament el paquet oficial des de la Microsoft Store。
  * **Per a PostgreSQL:** Descarregar l'instal·lador per a Windows des del lloc web oficial de PostgreSQL, seguir els passos de l'assistent d'instal·lació, configurar una contrasenya segura per a l'usuari principal (**postgres**) i verificar que el servei s'iniciï automàticament a Windows.