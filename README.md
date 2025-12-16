# TP1-BPM-BPEL
Modéliser des processus métier, avec Bonita Studio 
Déployer les processus sur le moteur de Workflow Bonita BPM Engine 
Exécuter et administrer ces processus en utilisant l'interface Web fournie.
### Réalisé par: 
 - Salmi Farah
 - Chennoufi Salma
 - Imassenda Salma
## Processus d'Achat Modélisé
On a modélisé un processus d'achat avec trois modes de paiement (CB, chèque, espèce) utilisant BPMN 2.0 dans Bonita Studio. Le processus inclut :

 - Un gateway XOR pour le choix du paiement

 - Trois branches distinctes avec conditions

 - Un sous-processus pour paiement CB

 - Des tâches humaines pour chaque étape

 - Validation de CIN pour chèque

 - Calcul de monnaie pour espèces

## Composants WSDL Extraits

À partir du fichier WSDL fourni :

### Nom du service web :

 - ReservationHotelService

 ### Méthodes fournies :

 - ChercherChambre 

 - ReserverChambre

### Messages d'entrée/sortie :

- Input: ChercherChambre / - Output: ChercherChambreResponse

- Input: ReserverChambre / - Output: ReserverChambreResponse

### Protocole de liaison :

- SOAP over HTTP 