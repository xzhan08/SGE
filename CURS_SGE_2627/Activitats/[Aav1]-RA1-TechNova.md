# Activitat 1 - Descripció completa de TechNova S.L.


## MÒDUL: Desenvolupament d'aplicacions multiplataforma

RA1: Identifica sistemes de planificació de recursos empresarials i de gestió de relacions amb clients (ERP-CRM) reconeixent-ne les característiques i verificant la configuració del sistema informàtic. 

## RECURSOS

 - Teoria RA1.

## CONDICIONS DE TREBALL

 - Treball individual.
 - Entregar al Moodle l'enllaç del github.
 - Github:
   - Continuar amb el repositori de l'activitat **Aav1.4**.
   - Crear una branca (al terminal) de nom **ra1** i ubicar-se a la branca (**git checkout ra1**)
   - Al acabar l'activitat, fusionar la branca **ra1** a la branca **main** del github.    

## AVALUACIÓ

 - Activitat avaluable amb nota de 0 a 100.
 - Entregar l'activitat a la data indicada.
 - Treballar a la branca **ra1**.
 - Entregar en format **.md** (markdown) amb la mateixa nomenclatura que el de l'activitat actual.

## ENUNCIAT

**Història de l’empresa:**

TechNova S.L. va ser fundada fa 8 anys a Barcelona per dos socis especialitzats en desenvolupament de programari. Van començar com una petita startup amb un comercial i dos desenvolupadors, oferint solucions digitals personalitzades per a petites empreses locals.

Gràcies a una estratègia de mercat basada en l’atenció al client, la flexibilitat tècnica i el posicionament digital, TechNova ha crescut de manera sostinguda. Actualment compta amb 45 empleats, distribuïts en cinc departaments:

* **RRHH** amb 4 empleats  
   Contractació, nòmines, gestió d’absències, formació interna  
* **Vendes** amb 6 empleats  
   Pressupostos, contractes, seguiment de clients, gestió comercial  
* **Màrqueting** amb 5 empleats  
   Campanyes digitals, xarxes socials, esdeveniments, posicionament de marca  
* **Desenvolupament** amb 25 empleats  
   Gestió de projectes, desenvolupament de programari, manteniment, resolució d’incidències  
* **Administració** amb 5 empleats  
   Comptabilitat, facturació, pagaments, relació amb proveïdors

**Serveis que ofereix:**

TechNova està especialitzada en el desenvolupament de programari a mida per a empreses. Els seus serveis inclouen:

* Consultoria tecnològica (anàlisi de necessitats i disseny de solucions digitals)  
* Desenvolupament d’aplicacions web i mòbils  
* Manteniment i suport tècnic post implementació

**Situació actual i principals problemes operatius:**

Tot i que TechNova ha crescut en nombre de clients i empleats, la seva infraestructura digital no ha evolucionat al mateix ritme. L’empresa continua utilitzant eines desconnectades i manuals per gestionar processos clau:

* RRHH utilitza fulls d’Excel per a nòmines i absències, sense traçabilitat ni control centralitzat.  
* Vendes gestiona pressupostos i contractes per correu electrònic i documents Word, cosa que genera duplicacions i pèrdua de versions.  
* Màrqueting no té connexió directa amb Vendes ni mètriques integrades, fet que dificulta mesurar l’impacte de les campanyes.  
* Desenvolupament utilitza Trello per als projectes, sense integració amb contractes ni facturació.  
* L’Administració treballa amb un programari comptable local que no es comunica amb altres departaments.

**1\. Anàlisi legal i comercial** (Escollir una opció):

- Tipus d’empresa:

[x] Societat Limitada (S.L.)  
[ ] Societat Anònima (S.A.)  
[ ] Altres: \_\_\_\_\_\_\_\_\_\_\_

**Justificació**: tal com indica el nom TechNova S.L.


- Classificació per mida:

[ ] Microempresa  
[x] Petita empresa  
[ ] Mitjana empresa  
[ ] Gran empresa

**Justificació**: ja que la empresa consta 45 empleats, perque una petita empresa es entre 10 i 49 treballadors.

- Tipus de servei:

[x] B2B  
[ ] B2C  
[ ] B2G

**Justificació**: Perque està especialitzada en el desenvolupament de programari a mida per a empreses.


---

**2\. Preguntes de diagnòstic**

1. Quines eines utilitza actualment TechNova per gestionar els seus processos?

**Resposta:** * RRHH utilitza fulls d’Excel, Vendes utilitzen documents Word, 
Desenvolupament utilitza Trello, l’Administració treballa amb un programari comptable local.

2. Quins problemes podrien sorgir per utilitzar eines no integrades?

**Resposta:** * Sense traçabilitat ni control centralitzat, genera duplicacions i pèrdua de versions, sense integració amb contractes ni facturació, les empreses no poden comunicar informacions entre ells...
  
3. Quins processos s’estan gestionant per separat en diversos departaments i podrien beneficiar-se d’una gestió integrada?  

**Resposta:** * s'en divideix en Consultoria tecnològica, Desenvolupament d’aplicacions web i mòbils, Manteniment i suport tècnic post implementació.
  
4. Quines conseqüències pot tenir aquesta situació si l’empresa continua creixent? 

**Resposta:** Augmentaren errors per la duplicacio manual dels empleats i la perdida d'informacio critica dels clients.
  
5. Quins processos haurien d’estar connectats per millorar l’eficiència?

**Resposta:** Deixant d'utilitzar eines fulls d’Excel, documents Word, Trello i un programari comptable local. Automatizant les nòmines.


---


**3\. Diagnòstic tècnic**

1. Quin model de servei al núvol seria més adequat per a TechNova?  
     
    [ ] IaaS  
    [ ] PaaS  
    [x] SaaS  
   

**Justificació**: És el més fàcil; pagues una subscripció a Internet i el proveïdor s'encarrega de mantenir el programa i els servidors.


2. Quina arquitectura d’ERP seria més adequada?  
     
    [ ] ERP de 2 capes (client-servidor)  
    [x] ERP de 3 capes (presentació, lògica, dades)  
   

**Justificació**: Perque es mes segur, escalable i robusta

---

**4\. Alternatives estratègiques**

1. És necessari implantar un ERP complet?

    [x] Sí  
    [ ] No

**Justificació**: perquè tots els departaments tenen problemes (Excel, Word, Trello) i necessiten estar connectats entre si.

2. Seria suficient implantar només un CRM?

 	[ ] Sí  
 	[x] No

**Justificació**:  perquè el CRM només serveix per a vendes i clients, i deixaria abandonats els problemes de nòmines i factures.

---


**5\. Respon de forma argumentada:**

1. Quin impacte tindria l’ERP en la cultura de l’empresa? 

**Resposta:**  L'empresa deixarà de treballar ailladament i passarà a una cultura transparent on tothom comparteix les dades en el mateix temps.
   
2. Quines resistències podrien sorgir i com es podrien gestionar?  

**Resposta:** Hi haurà por a perdre la feina; es fa explicant clarament el canvi.
  
3. Com justificaries la inversió davant la direcció?  

**Resposta:** Es justifica perquè s'estalviaran moltes hores de feina manual, s'eliminaran els errors de facturació i es vendrà més ràpid.
  
---

**6\. Test de seguiment – Indicadors clau (KPIs)**

1. Quin indicador reflecteix millor la millora en la gestió de factures després d’implantar l’ERP?  
     
    [ ] Nombre de clients nous al mes  
    [x] Reducció d’errors en facturació (%)  
    [ ] Temps mitjà de resposta a xarxes socials  
    [ ] Nombre de campanyes actives  
   

**Justificació**: Si el programa automatitza els càlculs, ara és veure que ja no es cometen errors humans en fer factures.

2. Si l’ERP connecta Vendes amb Desenvolupament, quin KPI seria més útil per mesurar-ne l’impacte?  
     
    [x] Projectes lliurats a temps (%)  
    [ ] Nombre de reunions internes  
    [ ] Taxa de conversió de leads  
    [ ] Cost mitjà per campanya  
   

**Justificació**: Com que els programadors veuen els contractes a l'acte, planifiquen millor i acaben els projectes quan toca.

3. Quin indicador ajuda a avaluar si RRHH gestiona millor les absències després de l’ERP?  
     
    [x] Absències registrades correctament (%)  
    [ ] Nombre d’empleats contractats  
    [ ] Temps mitjà de formació per empleat  
    [ ] Cost mensual de nòmines  
   

**Justificació**: Al deixar l'Excel manual, es mesura l'èxit veient que totes les baixes i vacances queden apuntades al sistema sense pèrdues.

4. Quin KPI reflecteix millor l’eficiència comercial després d’integrar CRM i ERP?  
     
    [x] Taxa de conversió de clients (%)  
    [ ] Nombre de correus enviats  
    [ ] Temps mitjà de càrrega del web  
    [ ] Nombre d’incidències tècniques  
   

**Justificació**: Amb el CRM i l'ERP units, l'equip comercial fa un millor seguiment i aconsegueix tancar més contractes amb èxit.

5. Quin indicador seria útil per justificar la inversió davant la direcció?  
     
    [x] Reducció d’errors, millora en lliuraments i augment de conversió  
    [ ] Nombre d’empleats que utilitzen l’ERP  
    [ ] Quantitat de mòduls contractats  
    [ ] Temps dedicat a formació  
   

**Justificació**: Els caps volen veure beneficis globals: menys errades, clients més contents i més vendes per recuperar els diners.
