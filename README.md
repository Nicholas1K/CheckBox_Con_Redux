Questo è il modo per gestire un CheckBox con React Native e il redux, prendendo l'elemento CheckBox all'interno di SceltaServizio 
(ho caricato l'intera pagina per potergli dare un contesto di utilizzo)
Per utilizzarlo basta installare la dipendenza '@react-native-community/checkbox', poi importare l'elemento import CheckBox from '@react-native-community/checkbox';
andare ad utilizzare l'elemento collegarlo al redux tramite i vari file store, action, actionCreator e reducer.
In fine all'interno del file dove il CheckBox viene utilizzato richiamarsi le funzioni scritte all'interno del actionCreator, copiare esattamente così com'è scritto
per avere un corretto utilizzo di un Checkbox che selezionando include l'elemento richiesto e deselezionandolo elimina l'elemento.
