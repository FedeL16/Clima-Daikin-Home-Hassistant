
# Clima-Daikin-Home-Hassistant
Package per Home Assistant per Climatizzatori DAIKIN 
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V1RWSFR)


ENGLISH:

PREMISE:

I didn't find any satisfactory card for air conditioners, neither generic nor dedicated to Daikin and so I decided to create a personalized and adaptable one for all brands.

Here is the result:

![Immagine 15-12-23 - 18 36](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7119e727-efc4-46da-9c8d-6bad87acf7ee)
![Immagine 15-12-23 - 18 36](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/159c3710-502c-4275-a3b8-0590982c964e)
![Immagine 15-12-23 - 18 35](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7c1cecf0-48a4-4781-997f-eaf1b600c492)
![Immagine 15-12-23 - 18 35 (1)](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/75c1c80d-f8c0-446b-8dec-1590401cc15a)

![Immagine 15-12-23 - 18 34](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/a06b9b70-d2ce-498d-af78-4ad5a2a7c9fb)
![Immagine 16-12-23 - 01 09](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7284edc5-90da-4b9d-aaa2-2493763ed71c)

PRE REQUIREMENTS:

- Mushroom (HACS) you can also use other types of graphics for pop-up icons

- Honeycomb (HACS)

- Browser Mod (HACS)

- A LOT of patience

N.B. it's all customizable and adaptable to any climate or brand, but you'll have to be good at doing it by remembering to go to "developer tools->states->entity->name of your entity so you get all the hvac/preset/fan_mode/swing attributes, temperature and humidity sensors and so on, of your climate to be able to customize the entire package.

INSTALLATION:

The practice is always the usual one:

- creation of the part of sensors and scripts, either by package if you have enabled it, or by inserting into your files the sensors and scripts you have in your configuration, copying the clima_daikin.yaml file into the package folder, or copy its content related to the sensors into your sensor/template.yaml and the content inherent in the scripts in your script.yaml. Once this is done, replace with your entities the parts containing mine, so that you can have the new sensors/scripts customized for your climate. I remember that scripts can also be created one by one via interface.

PS for those who do not know the world of scripts well, they are nothing more than actions to be done by the system. A script can be composed of a set of actions or a single action. By creating a script you will therefore create an entity of that particular action (e.g. set the dehumidifier mode) so that by clicking that particular icon you can activate the script below and get what you want from your climate.

- upload of image files: inside your www folder inside the main root (config or homeassistant), create a sub folder that you will call daikin or choose the name yourself and insert inside all the image files I have attached

- RESTART HA

- Go to your favorite dashboard, add the card by manual card and copy the code from card.yaml (taking into account the name of the subfolder you have created in your WWW folder, because in case it is not daikin, you will have to change the path from which the images will be called up) and replace with your entities all the necessary parts of code and delete the parts that you do not need (for example if you do not have sensors in the windows you can directly delete the part of code not necessary).

If you have multiple Air Conditioners you will have to redo this procedure for each, except for uploading the images. REMEMBER both to change entities and to add a letter or a number to the various sensors / inputs / scripts etc, a bit like the appliance packages of the domhouse.it site (for those who installed it), also because I took a lot of inspiration to create the correct counters.

Ok now you should be operational have fun!

PS report me any error  in case you find any anomaly, I am neophyte and I can get lost in the lines of yaml.

If you appreciate this project, I would be grateful for your support through a simple coffee, so I can continue to create other content and keep those published up to date.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V1RWSFR)

##################################################################

ITALIANO:

PREMESSA:
Non ho trovato nessuna card soddisfacente per condizionatori, ne generica ne dedicata a Daikin e così ho deciso di crearne una personalizzata e adattabile a tutte le marche.
Ecco il risultato:

![Immagine 15-12-23 - 18 36](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7119e727-efc4-46da-9c8d-6bad87acf7ee)
![Immagine 15-12-23 - 18 36](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/159c3710-502c-4275-a3b8-0590982c964e)
![Immagine 15-12-23 - 18 35](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7c1cecf0-48a4-4781-997f-eaf1b600c492)
![Immagine 15-12-23 - 18 35 (1)](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/75c1c80d-f8c0-446b-8dec-1590401cc15a)

![Immagine 15-12-23 - 18 34](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/a06b9b70-d2ce-498d-af78-4ad5a2a7c9fb)
![Immagine 16-12-23 - 01 09](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7284edc5-90da-4b9d-aaa2-2493763ed71c)


PRE REQUISITI:

- Mushroom (HACS) si può usare anche altri tipi di grafica per le icone dei popup
- HoneyComb (HACS)
- Browser Mod (HACS)
- TANTA pazienza
N.B. è tutto personalizzabile e adattabile a qualsiasi clima o marca, ma dovrete essere bravi a farlo voi ricordandovi di andare in "strumenti per sviluppatori->stati->entità-> nomedellavostraentità così otterete tutti gli attributi hvac/preset/fan_mode/swing, sensori di temperatura e umidità e così via, dei vostri clima per poter appunto personalizzare l'intero package.

INSTALLAZIONE:

La prassi è sempre la solita:
- creazione della parte di sensori e script, sia tramite package se lo avete abilitato, sia inserendo nei vostri file dei sensori e degli script che avete nella vostra configurazione, copiando il file clima_daikin.yaml nella cartella package, oppure copiate il suo contenuto inerente ai sensori nel vostro sensor/template.yaml e il contenuto inerenete agli script nel vostro script.yaml. Una volta fatto questo sostituite con le vostre entità le parti contenenti le mie, affinchè possiate avere i nuovi sensori/script personalizzati per i vostri clima. Ricordo che gli script possono essere anche creati uno ad uno tramite interfaccia.
PS per chi non conoscesse bene il mondo degli script, non sono altro che azioni da far compiere al sistema. Uno script può essere composto da un insieme di azioni o da una singola azione. Creando uno script creerete, pertanto, una entità di quella determinata azione (ad esempio impostare la modalità deumidificatore) così che cliccando quella determinata icona potrete attivare lo script sottostante e ottenere quello che vorrete dai vostri clima.

- upload dei file di immagine: all'nterno della vostra cartella www dentro la root principale (config oppure homeassistant), create una sotto cartella che chiamerete daikin oppure scegliete voi il nome e inserite dentro tutti i file di immagine che ho allegato

- RIAVVIATE HA

- Andate nella vostra dashboard che preferite, aggiungete la card tramite card manuale e copiate il codice da card.yaml (tenendo conto del nome della sotto cartella che avete creato nella vostra cartella WWW, perchè nel caso non fosse daikin, dovrete modificare il percorso dal quale saranno richiamate le immagini) e sostituite con le vostre entità tutte le parti di codice necessarie ed eliminate le parti che non vi servono (ad esempio se non avete sensori alle finestre potete eliminare direttamente la parte di codice non necessaria).

Se avete più Climatizzatori dovrete rifare questa procedura per ciascuno, tranne l'upload delle immagini. RICORDATE sia di cambiare entità sia di aggiungre una lettera o un numero ai vari sensori/input/script ecc, un po per come accade per i package elettrodomestici del sito domhouse.it (per chi l'avesse installato), anche perchè ho preso molto spunto per creare i contatori corretti.

Ok ora dovreste essere operativi buon divertimento!

Ringrazio i ragazzi di Domhouse di avermi permesso di accedere ai contenuti e poterne usufruire per adattarli a questo piccolo progetto.

PS segnalatemi qualsiasi errore che potrebbe sfuggirmi nel caso trovaste qualsiasi anomalia, sono neofita e posso perdermi nelle righe di yaml.

Se apprezzi questo progetto, sarei grato del tuo supporto tramite un semplice caffè, cosi io posso continuare a creare altri contenuti e tenere aggiornati quelli pubblicati.


[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V1RWSFR)

##################################################################










