# Clima-Daikin-Home-Hassistant
Package per Home Assistant per Climatizzatori DAIKIN 
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V1RWSFR)

PREMESSA:
Non ho trovato nessuna card soddisfacente per condizionatori, ne generica ne dedicata a Daikin e così ho deciso di crearne una personalizzata e adattabile a tutte le marche.
Ecco il risultato:

![Immagine 15-12-23 - 18 36](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7119e727-efc4-46da-9c8d-6bad87acf7ee)
![Immagine 15-12-23 - 18 36](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/159c3710-502c-4275-a3b8-0590982c964e)
![Immagine 15-12-23 - 18 35](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/7c1cecf0-48a4-4781-997f-eaf1b600c492)
![Immagine 15-12-23 - 18 35 (1)](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/75c1c80d-f8c0-446b-8dec-1590401cc15a)
![Immagine 15-12-23 - 18 35](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/d174c8ca-eac3-4f7b-85b2-93f2ef5bf5b6)
![Immagine 15-12-23 - 18 34](https://github.com/FedeL16/Clima-Daikin-Home-Hassistant/assets/141550943/a06b9b70-d2ce-498d-af78-4ad5a2a7c9fb)

PRE REQUISITI:

- Mushroom (HACS) si può usare anche altri tipi di grafica per le icone dei popup
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




