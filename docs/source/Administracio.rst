Administració
=====

.. _Overview:


La secció d'Administració permet gestionar els usuaris que tenen accés a Systam. Es poden crear, editar, assignar rols als nous usuaris i també als existents.


Creació d'un nou usuari
----------------
Per a crear un usuari nou, simplement polsem el botó **[+]** que trobarem a la part superior del menú d'opcions i s'obrirà una nova finestra. A continuació, haurem d'emplenar les dades següents:

- **Codi**: Codi identificador per a l'usuari.
- **Nom** i **Cognoms**: Nom i cognoms del nou usuari.
- **Alias**: Pseudònim curt que identifiqui l'usuari.
- **RFID**: Codi RFID identificador per a l'usuari.
- **Adreça**: Adreça/domicili de l'usuari.
- **Població**: Població l'usuari.
- **Província**: Província de l'usuari.
- **País**: País de l'usuari.
- **Codi Postal**: Codi postal de l'usuari.
- **Rol de seguretat**: Rol de seguretat de l'usuari.
- **Tipus d'usuari**: Tipus d'usuari: *Usuari normal* o *Operari*.

A continuació podrem afegir una imatge i observacions que considerem importants sobre el nou usuari a donar d'alta. A més a més, de la zona horària i el format de data que emmagatzemi aquest perfil d'usuari. Això no obstant, el sistema ho estableix per defecte.

Com editar un usuari existent
----------------
Per a editar un usuari ja existent, primerament cercarem l'usuari per qualsevol dels camps superiors que volguem. **La cerca per cognom és la més útil en qualsevol cas.** Així doncs, un cop seleccionat l'usuari en farem clic damunt del **CODI**. A continuació s'obrirà una nova finestra amb tots els detalls de l'usuari, els quals els més crítics no podran modificar-se. Per a modificar el **codi, nom, cognom, alias, RFID, adreça, població o província** haurem de donar de baixa l'usuari i fer-ne un de nou. 

La finestra compta amb diferents pestanyes que ens permeten modificar diferents paràmetres de l'usuari:

+ **Dades generals**: Dades generals de l'usuari. Aquestes dades són les més importants quant a identificació de l'usuari.
+ **Detall de l'usuari**: En aquesta secció podrem seleccionar el tipus d'usuari i quin accés tenen, el grup d'usuaris i la prioritat com a usuari.
+ **Dades professionals**: Aquí podrem seleccionar el perfil professional, departament, secció i centre de cost.
+ **Localització alternativa**: Aquí podrem seleccionar l'adreça, població, província, país, codi postal.
+ **Dades de contacte**: Totes aquelles dades de contacte que formin part de l'usuari, aniran aquí. A més a més, es poden habilitar tota mena de notificacions de diferents tipus: tiquets, esdeveniments, actius, tracking i missatges emergents per a tenir l'usuari informat de cada situació.
+ **Càrrecs**: Aquí es poden assignar tots aquells càrrecs disponibles a l'usuari. Aquesta assignació permetrà a l'usuari tenir accés a diferents seccions de Systam. És important assignar els rols correctament. S'ha d'evitar donar rols d'administració i de comandaments a operaris.
+ **Configuració per a la creació de tiquets**: Podrem crear tíquets via correu electrònic. Per a fer això, podrem seleccionar el servei/actiu i el tipus de tiquet.
+ **Rols assignats**: En aquesta secció veurem els rols assignats que tenen els usuaris i a quines seccions poden accedir.

Configuració de dades de login
----------------
Aquí podrem modificar totes les dades de configuració del login de cada usuari. Una opció molt interessant és per a desbloquejar l'usuari, ja que alguns cops el compte es bloqueja per escriure malament la clau de pas. Podem modificar el següent.

+ **Codi**: Codi de l'usuari
+ **Tipus d'autenticació**: Tipus d'identificació, *local* o *ldap*. El tipus per defecte és *local*.
+ **Login**: Correu electrònic de l'usuari
+ **Nom**: Nom de l'usuari.
+ **Cognoms**: Cognom de l'usuari.
+ **Email**: Correu electrònic de l'usuari.
+ **Telèfon de contacte**: Telèfon de contacte de l'usuari.
+ **Bloquejar usuari**: Permet bloquejar i desbloquejar el compte de l'usuari. En el cas que un usuari no pugui entrar, s'ha de mirar aquesta secció si està bloquejada.
+ **Data d'expiració**: Data d'expiració de l'usuari.

Duplicat de permissos
----------------
Aquesta opció permet duplicar permissos d'un usuari i afegir-los a un altre. D'aquesta manera ens estalviarem temps en el moment de crear un usuari nou. Tot i així, es recomana que s'entrin manualment, ja que alguns usuaris podrien acabar tenint accés a seccions no permeses.
