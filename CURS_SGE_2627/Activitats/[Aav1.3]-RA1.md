# Activitat 1.3 — Sistema operatiu i SGBD adequats per a un ERP-CRM

## MÒDUL: Desenvolupament d'aplicacions multiplataforma

RA1: Identifica sistemes de planificació de recursos empresarials i de gestió de relacions amb clients (ERP-CRM) reconeixent-ne les característiques i verificant la configuració del sistema informàtic. 

## RECURSOS

 - Teoria RA1

## CONDICIONS DE TREBALL

 - Treball individual
 - Entregar al Moodle l'enllaç del github
 - Github:
   - Continuar amb el repositori de l'activitat **Aav1.2**.
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

1. Per als següents sistemes ERP-CRM, ompliu una taula amb el **sistema operatiu compatible** i el **SGBD compatible** de cadascun (busqueu la informació a la documentació oficial de cada fabricant):

   * SAP S/4HANA (o SAP Business One)
   * Microsoft Dynamics 365
   * Odoo
   * SuiteCRM

   | Sistema | Sistema operatiu compatible | SGBD compatible |
   | :--- | :---- | :---- |
   | SAP ... | Linux (SUSE Linux Enterprise Server / Red Hat Enterprise Linux)|SAP HANA DB |
   | Microsoft Dynamics 365 |Windows Server  |Microsoft SQL Server |
   | Odoo | Linux (p. ex., Ubuntu, Debian), Windows, macOS| PostgreSQL|
   | SuiteCRM |Linux, Unix, macOS, Windows Server |MySQL o MariaDB|


2. Si **TechNova S.L.** (vegeu activitat 1) decidís instal·lar un ERP-CRM **on-premise** als seus propis servidors, tenint en compte que l'equip de Desenvolupament ja té coneixements de Linux, quina combinació de **sistema + sistema operatiu + SGBD** recomanaríeu? Justifiqueu-ho.

- Per a TechNova S.L. recomanem instal·lar Odoo sobre Linux (Ubuntu) amb la base de dades PostgreSQL. Com que l'equip de desenvolupament ja sap fer servir Linux, el muntatge serà molt més ràpid i no hauran d'aprendre des de zero. A més, tots aquests programes són de codi obert i gratuïts, llavors es pot estalvia haver de pagar llicències cares com les de Windows o Microsoft. És una combinació que funciona molt ràpid, és segura i es pot adaptar fàcilment.

3. Expliqueu, en 4-5 línies, què podria passar (a nivell tècnic i de suport) si s'intenta instal·lar un ERP-CRM amb un SGBD que **no** és oficialment compatible segons el fabricant.

- Si s'instal·la una base de dades no compatible, l'ERP pot tenir errors greus, pèrdua dades o deixar de funcionar perquè els programes no es podran comunicar bé. A més, el fabricant et traurà la garantia de forma immediata. Això significa que et quedaràs sense ajuda tècnica oficial i no rebràs les actualitzacions necessàries per protegir el teu sistema.