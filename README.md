# Projet - Système de vote

Un smart contract de vote peut être simple ou complexe, selon les exigences des élections que vous souhaitez soutenir. Le vote peut porter sur un petit nombre de propositions (ou de candidats) présélectionnées, ou sur un nombre potentiellement important de propositions suggérées de manière dynamique par les électeurs eux-mêmes.

Dans ce cadres, vous allez écrire un smart contract de vote pour une petite organisation. Les électeurs, que l'organisation connaît tous, sont inscrits sur une liste blanche (whitelist) grâce à leur adresse Ethereum, peuvent soumettre de nouvelles propositions lors d'une session d'enregistrement des propositions, et peuvent voter sur les propositions lors de la session de vote.

✔️ Le vote n'est pas secret pour les utilisateurs ajoutés à la Whitelist

✔️ Chaque électeur peut voir les votes des autres

✔️ Le gagnant est déterminé à la majorité simple

✔️ La proposition qui obtient le plus de voix l'emporte.

✔️ N'oubliez pas que votre code doit inspirer la confiance et faire en sorte de respecter les ordres déterminés!



👉 Le processus de vote : 

Voici le déroulement de l'ensemble du processus de vote :

1. L'administrateur du vote enregistre une liste blanche d'électeurs identifiés par leur adresse Ethereum.
2. L'administrateur du vote commence la session d'enregistrement de la proposition.
3. Les électeurs inscrits sont autorisés à enregistrer leurs propositions pendant que la session d'enregistrement est active.
4. L'administrateur de vote met fin à la session d'enregistrement des propositions.
5. L'administrateur du vote commence la session de vote.
6. Les électeurs inscrits votent pour leur proposition préférée.
7. L'administrateur du vote met fin à la session de vote.
8. L'administrateur du vote comptabilise les votes.
9. Tout le monde peut vérifier les derniers détails de la proposition gagnante.

...
 

