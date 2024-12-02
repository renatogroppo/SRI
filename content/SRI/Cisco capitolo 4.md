**

## 4.1.1

## Riassunto del Testo

Il testo discute l'importanza di stabilire una connessione fisica a una rete locale, sia essa cablata o wireless, prima di poter comunicare con dispositivi come stampanti o siti web.

## Tipi di Connessione

- Connessione Cablata: Utilizza cavi fisici per collegare dispositivi a uno switch, comune negli uffici aziendali. I dati vengono trasmessi tramite cavi Ethernet.
    
- Connessione Wireless: Utilizza onde radio per connettere laptop, tablet e smartphone a un punto di accesso o router wireless. Questa modalità è sempre più diffusa per i suoi vantaggi in termini di flessibilità.
    

## Componenti della Rete

Un punto di accesso wireless include:

- Antenne integrate
    
- Porte switch Ethernet
    
- Porta Internet
    

## Schede di Interfaccia di Rete (NIC)

Le NIC collegano i dispositivi alla rete:

- NIC Ethernet: Per connessioni cablate.
    
- NIC WLAN: Per connessioni wireless.
    

I dispositivi possono avere uno o entrambi i tipi di NIC. Ad esempio, una stampante può avere solo una NIC Ethernet e richiedere un cavo, mentre tablet e smartphone usano generalmente una NIC WLAN per la connessione wireless.

  

4.1.2

## Riassunto del Testo

Il livello fisico del modello OSI è responsabile del trasporto dei bit che compongono un frame dal livello di collegamento dati attraverso il supporto di rete. Questo livello riceve un frame completo, lo codifica in segnali elettrici, ottici o radio e lo trasmette sul supporto fisico.

## Funzionamento del Livello Fisico

- Codifica dei Frame: Il livello fisico accetta i frame e li trasforma in segnali, che vengono inviati uno alla volta sul supporto.
    
- Ricezione dei Segnali: Al nodo di destinazione, i segnali vengono recuperati, ripristinati come bit e passati al livello di collegamento dati come frame completo.
    

## Processo di Incapsulamento

Il testo menziona un esempio di incapsulamento, dove i bit vengono inviati sul supporto fisico, evidenziando l'importanza della codifica e della trasmissione dei dati in modo efficace. 

  
  

4.2.1

## Riassunto del Testo

Il livello fisico del modello OSI è fondamentale per il trasporto dei bit all'interno di una rete, gestendo la codifica dei frame e la loro trasmissione attraverso vari supporti fisici.

## Componenti del Livello Fisico

Il livello fisico comprende:

- Circuiti Elettronici: Componenti hardware per la trasmissione dei dati.
    
- Supporti: Cavi, fibre ottiche e onde radio.
    
- Connettori: Interfacce per collegare i dispositivi alla rete.
    

## Standardizzazione

Gli standard del livello fisico sono definiti da diverse organizzazioni, tra cui:

- ISO
    
- TIA/EIA
    
- ITU
    
- ANSI
    
- IEEE
    
- FCC (negli Stati Uniti)
    
- ETSI
    

Esistono anche gruppi regionali come CSA, CENELEC e JSA/JIS che sviluppano specifiche locali.

  

4.2..2

Componenti del livello fisico 

- Componenti fisici 
    
- Codifica
    
- segnalazioni
    

COMPONENTI FISICi

sono dispositivi hardware,i supporti, e connettori che trasmettono i segnali di bit. Componenti hardware come il NIC, interfacce e connettori, cavi,  sono tutti specificati nello standard del livello fisico

  
  

4.2.3

  

la codifica è un modo per convertire i dati in codice, la codifica è un modo per rappresentare informazioni digitali.

La codifica manchester: cioè 1 /0 (alte e bassa tensione ) viene utilizzata in Ethernet a 10 MBPS  

  

4.2.4

Segnalazione

il modo in cui i bit vengono rappresentati viene chiamato metodo di segnalazione. Gli standard del livello fisico devono definire quale tipo di segnale rappresenta un "1" e quale tipo di segnale rappresenta uno "0".(simile a morse) 

  

4.2.5

La larghezza di banda cioè la capacità con cui un supporto può trasportare dati.la larghezza di banda misura la quantità di dati che possono andare da un punto a un’altro in un periodo di tempo e viene misurata in kbps(kilobit al secondo), La larghezza di banda NON è la velocità di cui viaggiano i bit la la quantità di bit che viaggiano.Le proprietà dei supporti fisici, le tecnologie attuali e le leggi della fisica sono tutti fattori che influenzano la determinazione della larghezza di banda disponibile.

  

4.2.6

Per la misurazione della larghezza di banda servono: Lavenza, Throughput, Goodput.

- la latenza cioè il tempo per i dati ad arrivare da un punto ad un’altro. 
    
- Il throughput è la misura del trasferimento del bit in un periodo di tempo. IL throughput è solitamente minore alla larghezza di banda. Le cose che influenzano il throughput sono: la quantità di traffico il tipo di traffico
    
- Il Goodput è la stessa cosa del throughput ma dando un dato periodo di tempo. Il goodput è inferiore al throughput e alla larghezza di banda
    

  

4.3.0

4.3.1

Caratteristiche del cablaggio in rame: è il tipo di cablaggio più comune: esistono 3 tipi di cablaggio in rame:

Le reti utilizzano cablaggi in rame perchè sono economici,facili da installare ma la distanza di segnale non è elevata.

I dati vengono trasmessi via rame come impulsi elettrici.Per contrastare gli effetti negativi alcuni tipi di cavi in ​​rame sono avvolti in una schermatura metallica.

  

interferenza elettromagnetica (EMI) o interferenza a radiofrequenza (RFI) : i segnali EMI e RFI possono distorcere e corrompere i segnali dati trasportati dai supporti in rame.Per contrastare gli effetti negativi alcuni tipi di cavi in ​​rame presentano coppie di fili opposti intrecciati tra loro, il che annulla efficacemente la diafonia.

Diafonia - La diafonia è un disturbo causato dai campi elettrici Nei circuiti telefonici, la diafonia può causare l'ascolto di parte di un'altra conversazione vocale

  

Il rumore elettronico può essere limitato:

  

- Selezione del tipo o della categoria di cavi più adatti
    
- Progettare un'infrastruttura via cavo
    
- Utilizzo di tecniche di cablaggio che includano la corretta gestione e terminazione dei cavi
    
-   
    

4.3.2

I tre tipi di supporto di rame sono:

UTP

STP

cavo coassiale

  

4.3.3.

UTP (doppino intrecciato non schermato)

cioè il mezzo di rete più comune. Nella lan il cavo UTP è fatto con quattro coppie di fili.

  

4.3.4.

STP (doppino intrecciato schermato)

é una migliore protezione al rumore ma costa di più di quello UTP. IL cavo STP contrasta anche il EMI e RFI e la diafonia. è è difficile che ci siano intrecciature.

  

4.3.5.

Il cavo coassiale, Esistono diversi connettori utilizzati con il cavo coassiale BNC,tipo N e tipo F, il cavo coassiale viene utilizzato non spesso ma viene utilizzato:

- Installazioni wireless: I cavi coassiali collegano le antenne ai dispositivi wireless.
    
- Installazioni Internet via cavo - I provider di servizi via cavo forniscono connettività Internet ai propri clienti
    

**