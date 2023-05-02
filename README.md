# FreeRTOS

Per dur a terme l'exercici, he utilitzat un Timer cada 10s. El seu callback, allibera el semàfor de tipus  binari, per a que la Tasca A l'ocupi i s'executi. 
La Tasca A imprimeix per pantalla i envia per una cua de 1 slot un valor random que serà utilitzat en la Tasca B. La Tasca B reb el valor de la cua i imprimeix per pantalla. 
