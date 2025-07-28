# KubernetesFeaturesDocs

## Principali features di Kubernetes (K8s)

K8s é compatibile con qualsiasi OCI Container Runtime è permette l'orchestrazione di cluster di container.

I PRO di K8s sono:

- Automazione della gestione dei container: K8s gestisce automaticamente la applicazioni conteinerizzate e rende la decisione di configurazione di risorse, network e istanze più semplice.

- Capacità rigenerative: K8s è in grado di effettuare in "self-repair" nel caso venisse individuato un container non funzionante, che comprende o sostituzione o riavvio

- Resilienza e scalabilità : Rispetto al Compose, K8s offre la possibilità di scalare e adattare il carico di lavoro in base alle necessità dell'applicativo. Per esempio Quindi si posso aumentare le istanze in esecuzione per soddisfare un eventuale aumento di richieste al server.

- Utilizzo delle risorse: Come diretta conseguenza all'automazione, K8s permette una diminuzione del carico di lavoro e quindi di redistribuire le risorse in modo ottimale.

- Portabilità e Flessibilità: funzionando in cloud  pubblici e privati e on-premise K8s è in grado di interfacciarsi con tutti i provider di infrastruture e poter migrare tra questi in modo semplice.


 I CONS di K8s:

 - Curva di apprendimento: K8s è più complesso di altri tools di container, infatti non è sempre adatto per applicazioni di piccole dimensioni. Imparare le API può essere un ostacolo in un primo momento.

 - Delay e risorse: Una conseguenza della scalabilità di K8s è la dimunuzione di performance e velocità di gestione dei container, più si aumenta la dimensione è più lento funzionerà il cluster di containers e più risorse saranno necessarie per il corretto funzionamento dei microservizi.

 - Sicurezza: Anche se K8s rappresenta una valida opzione per grandi aziende per gestire applicazioni e microserivizi, il fattore sicurezza rappresenta un punto fondamentale, in quanto se non isolato correttamente, un'app K8s può essere target di attacchi

 - Vendor Lock-In: se un'azienda configura il proprio progetto o vendor per essere compatibile con K8s, potrebbe essere difficoltoso trasferirsi su altre piattaforme con altri servizi che potrebbero non funzionare su altre.

Caso d'uso:

Un esempio di utilizzo di K8s è rivolto al Machine Learning e strumenti AI. La capacità di scalare risorse orizzonatalmente permette l'elaborazione di grandi moli di dati in più nodi, mantenendo il tempo di elaborazione relativamente, e il bilanciamento delle risorse, per esempio se si vuole indirizzare più capacità per addestrare l'IA o si vuole mettere in primo piano l'utilizzo tramite altri dispositivi.
