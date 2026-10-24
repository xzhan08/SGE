# Activitat 1.2 — Estudi comparatiu de sistemes ERP-CRM del mercat

## MÒDUL: Desenvolupament d'aplicacions multiplataforma

RA1: Identifica sistemes de planificació de recursos empresarials i de gestió de relacions amb clients (ERP-CRM) reconeixent-ne les característiques i verificant la configuració del sistema informàtic. 

## RECURSOS

 - Teoria RA1

## CONDICIONS DE TREBALL

 - Treball individual.
 - Entregar al Moodle l'enllaç del github.
 - Github:
   - Crear repositori de nom **sge_cognom**.
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

1. Escolliu **4 sistemes ERP-CRM reals** del mercat. Com a mínim un ha de ser de **codi obert** i un altre de **propietari/SaaS**.

   *Exemples orientatius (no és obligatori usar-los tots): SAP Business One, Microsoft Dynamics 365, Odoo, Salesforce, Oracle NetSuite, Sage 200, SuiteCRM, Zoho CRM, HubSpot CRM, Openbravo.*

2. Per a **cadascun** dels 4 sistemes, ompliu una fitxa amb aquesta informació:

   * **Nom i fabricant**
   * **Tipus de llicència** (propietària, codi obert, freemium, subscripció SaaS...)
   * **Model de desplegament** (on-premise, cloud, híbrid)
   * **Mida d'empresa a la qual s'orienta** (micro, petita, mitjana, gran)
   * **3 mòduls destacats**
   * **Un punt fort**
   * **Un punt feble**

3. Amb les 4 fitxes, elaboreu una **taula comparativa** (files = sistemes, columnes = els camps de l'apartat 2).

4. Tenint en compte el cas de **TechNova S.L.** (activitat 1 - descripció de l'empresa, departaments i problemes actuals), quin dels 4 sistemes recomanaríeu? Justifiqueu la resposta tenint en compte:

   * La mida de l'empresa (45 empleats).
   * El pressupost disponible (una PIME, no un gran compte).
   * Les necessitats concretes dels departaments (Vendes, Desenvolupament, RRHH, Administració, Màrqueting).


  ## RESPOSTA

### Fitxa 1: Odoo

* **Nom i fabricant**: Odoo (Odoo S.A.)
* **Tipus de llicència**: Codi obert (Llicència LGPLv3 per a l'edició Community) i subscripció comercial (edició Enterprise).
* **Model de desplegament**: Híbrid
* **Mida d'empresa a la qual s'orienta**: mitjana empresa.
* **3 mòduls destacats**: Gestió de Projectes, Facturació i Vendes.
* **Un punt fort**: molt modular, flexible i amb una millors relacions qualitat-preu del mercat gràcies al seu model d'aplicacions integrades.
* **Un punt feble**: La Community Edition és molt limitada pel que fa a les funcionalitats de comptabilitat i recursos humans.

### Fitxa 2: Microsoft Dynamics 365 (Business Central)

* **Nom i fabricant**: Microsoft Dynamics 365 Business Central (Microsoft)
* **Tipus de llicència**: SaaS (per usuari/mes).
* **Model de desplegament**: Principalment Cloud, tot i que permet opcions híbride.
* **Mida d'empresa a la qual s'orienta**: mitjana, gran empresa (tot i que tambe per a petites empreses en creixement).
* **3 mòduls destacats**: Gestió Financera avançada, Vendes i Màrqueting i Gestió de Projectes.
* **Un punt fort**: Integració nativa i total amb tot l'ecosistema de Microsoft (Office 365, Teams, Outlook, Power BI, Excel).
* **Un punt feble**: El cost de les llicències és elevat i la implantació sol requerir un partner certificat obligatori, augmentant els costos inicials.

### Fitxa 3: SuiteCRM

* **Nom i fabricant**: SuiteCRM (SalesAgility)
* **Tipus de llicència**: Codi obert complet (Llicència GPLv3).
* **Model de desplegament**: Principalment On-premise (servidor propi), tot i que es pot allotjar en núvols privats o contractar el seu servei cloud gestionat.
* **Mida d'empresa a la qual s'orienta**: Petita, mitjana i gran empresa que busqui un CRM potent sense pagar llicències per usuari.
* **3 mòduls destacats**: Gestió de Clients i Oportunitats, Automatització de Màrqueting i Atenció al Client.
* **Un punt fort**: No té costos de llicència per usuari; tens control absolut de les teves dades i codi que no te limitacions artificials.
* **Un punt feble**: És un CRM pur; no inclou mòduls d'ERP natius de manera que requereix integracions complexes amb altres sistemes.

### Fitxa 4: Salesforce (Customer 365 / Starter)

* **Nom i fabricant**: Salesforce Starter / Pro Suite (Salesforce Inc.)
* **Tipus de llicència**: Propietària estrictament per subscripció SaaS.
* **Model de desplegament**: 100% Cloud.
* **Mida d'empresa a la qual s'orienta**: Des de petites empreses fins a multinacionals i grans corporacions.
* **3 mòduls destacats**: Sales Cloud, Marketing Cloud i Service Cloud.
* **Un punt fort**: El CRM més potent, analític i utilitzat del món, amb una capacitat d'automatització i intel·ligència de vendes.
* **Un punt feble**: Cost molt elevat a mesura que es necessiten funcions avançades; a més, com passa amb SuiteCRM, està molt focalitzat en el client (CRM).

| Sistema ERP-CRM | Fabricant | Tipus de llicència | Model desplegament | Mida d'empresa | 3 mòduls destacats | Punt fort | Punt feble |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Odoo | Odoo S.A. | Codi obert / Subscripció | Híbrid (Cloud / On-premise) | Micro, Petita, Mitjana | Projectes, Comptabilitat, CRM-Vendes | Modularitat i excel·lent relació qualitat-preu. | La versió gratuïta requereix massa canvis manuals. |
| Microsoft Dynamics 365 | Microsoft | Propietària (SaaS) | Cloud | Mitjana, Gran | Gestió Financera, Vendes, Projectes | Integració absoluta amb Office 365 i Power BI. | Cost elevat i dependència estricta de partners. |
| SuiteCRM | SalesAgility | Codi obert (GPLv3) | On-premise / Cloud | Petita, Mitjana, Gran | Clients/Oportunitats, Màrqueting, Suport | Sense costos de llicència per usuari. | Manca de mòduls d'ERP interns (comptabilitat/RRHH). |
| Salesforce | Salesforce Inc. | Propietària (SaaS) | 100% Cloud | Petita, Mitjana, Gran | Sales Cloud, Marketing Cloud, Service Cloud | El CRM líder en automatització i vendes. | Preu molt elevat i no és un ERP de gestió comptable. |


### Recomanació i justificació per a TechNova S.L.

El sistema ideal per a TechNova S.L. és Odoo en la seva versió Enterprise. Recomano aquesta eina perquè encaixa molt amb una petita empresa de 45 treballadors. Opcions com Salesforce o Microsoft Dynamics són massa cares i complexes, mentre que SuiteCRM es queda curt perquè només serveix per a vendes i no inclou la gestió interna de l'empresa. El personal de vendes i màrqueting pot captar clients potencials, organitzar el procés de venda i enviar campanyes de correu des del mateix lloc. Per al departament d'administració inclou una gestió de factures, despeses i impostos adaptada directament a les lleis d'aquí. En resum, Odoo és la millor opció perquè unifica tota l'empresa de forma fàcil, estalvia haver de pagar diferents programes alhora i està preparat per si TechNova continua creixent en el futur.