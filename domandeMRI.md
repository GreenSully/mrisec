1)Illustrare in maniera sintetica i problemi dei recommender systems di tipo content-based.

<br><br>
		**many of the same /overspecialization** := rischio di raccomandazioni ripetitive con scarsa novelty/serendipity per via della sovraspecializzazione del recommender
		<br>
		**new user** := non conosco i gusti del nuovo utente quindi non so cosa raccomandargli
		<br>
		**limited content analisys** := un item potrebbe essere descritto in generale senza fare menzione delle feature più importanti, che potrebbe portare a raccomandare l'item quando non dovrebbe o proprio a non essere mai raccomandato
<br><br><br>
2)Illustrare in maniera sintetica i problemi dei recommender systems di tipo collaborativo.

<br><br>
		**matrice sparsa per i rating** := difficile trovare dei vicini
		se un utente non esprime preferenze non può avere raccomandazioni
		<br>
		**cold-start** := senza community non c'è modo di raccomandare (ma si possono usare altri approcci)
		<br>
		**new-user** := non può avere raccomandazioni
		<br>
		**new-item** := un nuovo item non ha preferenze di alcun utente e dunque non può essere raccomandato
		<br>
		**grey-sheep** := difficile trovare utenti simili significativi se un utente valuta in modo "intermedio" ogni item, non si sbilancia nel valutare.
		<br>
		**"canto delle sirene"(SEMERARO TRADEMARK)** := valutazioni false o organizzate alterano lo stato del sistema e influenzano le raccomandazioni
<br><br><br>
3)Descrivere le metriche di errore (MAE ed RMSE) utilizzate per la valutazione dell’accuratezza dei recommender systems.

<br><br>
	**MAE** := Mean Absolute Error, calcola la deviazione tra i rating predetti e i rating reali
<br>
	**RMSE** := Root Mean Square Error, come MAE ma penalizza deviazioni più grandi utilizzando il quadrato della differenza tra rating predetto e rating attuale

![](./img/mae_rmse.PNG)
<br><br><br>
4)Descrivere, commentando opportunamente, la funzione per il calcolo delle predizioni dei rating in un algoritmo di filtraggio collaborativo di tipo user-to-user.

5)Illustrare in maniera sintetica il problema della overspecialization (sovraspecializzazione) dei content-based recommender systems

6)Illustrare in maniera sintetica il problema del Cold-start nei recommender systems di tipo collaborativo

<br><br><br>
7)Descrivere in maniera sintetica i principi alla base del PageRank, focalizzando l’attenzione sulla formulazione ricorsiva basata sul “flow” model.

8)Descrivere in maniera sintetica i concetti fondamentali alla base del modello dei dati RDF, in particolare i concetti di risorsa, proprietà e statement.

<br><br>
	il modello dei dati RDF è basato su tre concetti:
	<br>
	 – **Risorse**: tutto ciò che viene descritto, ogni risorsa è identificata da un URI
	<br>
	 – **Proprietà**: una coppia attributo-valore che si vuole associare ad una risorsa, l'attributo è anch'esso identificato da un URI e il valore può essere un'altra risorsa o un tipo di dato primitivo (stringa, intero...)
	<br>
	 – **Asserzioni o statement**: l’associazione di una proprietà ad una risorsa, ci dice che “una risorsa (soggetto) ha un certo valore (oggetto) per una certa proprietà (predicato)”

<br><br><br>
9)Descrivere il problema dello spider trap nell’algoritmo PageRank e illustrare una possibile soluzione.

10)Descrivere i principali problemi dell’algoritmo PageRank e illustrare una possibile soluzione.

<br><br><br>
11)Descrivere in maniera sintetica il concetto di reificazione degli statement RDF.

<br><br>
	**reificazione** significa riduzione ad oggetto dell'asserzione. Si utilizza la reificazione per esprimere meta-informazioni su una meta-informazione. Quindi l'oggetto della tripla Soggetto-Proprietà-Oggetto diventa uno statement, quindi una tripla Soggetto-Proprietà-Oggetto.
	Dopo avere reificato l’asserzione si potranno esprimere ulteriori proprietà su di essa.

12)Descrivere in maniera sintetica i principi alla base del PageRank, focalizzando l’attenzione sulla formulazione basata su matrici di adiacenza stocastiche
