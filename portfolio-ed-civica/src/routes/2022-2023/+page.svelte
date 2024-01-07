<script>
	import codF from '$lib/images/codF.png';
</script>

<svelte:head>
	<title>2022-2023</title>
	<meta name="description" content="Attivita' svolte nell'anno scolastico 2022-2023" />
</svelte:head>

<body>
	<h1><b>2022-2023</b></h1>
	<div>
		<h2 class="title" id="tpsi"><b>TPSI</b></h2>

		<p class="descrizione">
			Ad inizio anno abbiamo svolto un progetto interdisciplinare ideato dal docente di TPSI
			(Tecnologia per Progettazione di Sistemi Informatici) ovvero l'ideazione e la scrittura di un
			articolo per un blog.
			<br />L'articolo, dopo essere stato redatto, è stato corretto dalla docente di lettere e poi
			successivamente e stato scritto nel blog tramite il linguaggio <i>MarkDown</i>.
			<br />Più precisamente l'articolo che ho scritto io è
			<a
				href="https://prof.mancusoa.it/blog/arte-del-pc-e-tecniche-di-modding/"
				target="_blank"
				rel="noreferrer">questo</a
			>.
		</p>
	</div>

	<div class="lettere">
		<h2 class="title" id="lettere"><b>LETTERE</b></h2>

		<div class="slide-text">
			<p class="descrizione">
				Durante quest'anno accademico abbiamo proseguito e concluso il percorso intrapreso con
				Agende Rosse con la visione del film <i
					>"<a
						href="https://www.raiplay.it/programmi/lamafiauccidesolodestate"
						target="_blank"
						rel="noreferrer">La Magia uccide solo d'estate"</a
					></i
				>, gli incontri con gli attivisti e con il Sig. Ferdinando Domè, figlio di una vittima
				innocente nella strage di viale Lazio, avvenuta a Palermo nel dicembre del 1969.
				<br />
				Inoltre, sempre legato al percoso svolto con Agende Rosse, abbiamo realizzato una ricerca/presentazione
				su un personaggio che ha combattuto contro la mafia. Nel mio caso ho scelto Bruno Caccia.
			</p>

			<iframe
				src="https://docs.google.com/presentation/d/e/2PACX-1vSq1LLegXbF6AOk_7zwhORSUg5zx4Ma6v7x5O6FFTJKosxKfRTHpVe9tI5T4u6yKayAdJ2t5sUQUQJz/embed?start=false&loop=false&delayms=3000"
				frameborder="0"
				width="505"
				height="360"
				title="bruno-caccia-presentation"
				allowfullscreen="true"
				mozallowfullscreen="true"
				webkitallowfullscreen="true"
			/>
		</div>

		<div class="video-text">
			<iframe
				width="485"
				height="315"
				src="https://www.youtube.com/embed/JjV_6RxNlyY?si=Xd8fB-d_gTq6OuNg"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			/>

			<p class="descrizione">
				Per quanto riguarda le associazioni mafiose abbiamo anche assistito a due spettacoli
				teatrali riguardanti l'argomento che sono rispettivamente: <i>"Mare Addosso"</i> il quale
				racconta la vita di Peppino Impastato dal punto di vista della madre e
				<i>"Mi chiamo Rita Atria"</i>
				riguardante la storia di Rita Atria figlia di un importante boss mafioso la quale era riuscita
				a scappare dalla Sicilia grazie a Paolo Borsellino.
				<br />
				Ultimo, ma non per importanza, abbiamo partecipato ad un incontro online sulla 'Ndrangheta con
				il procuratore Gratteri, del quale vi lascio il video qui a fianco.
			</p>
		</div>

		<p class="descrizione">
			Nel corso di quest'anno scolastico abbiamo anche discusso sul tema della pena di morte nel
			corso della storia e nei tempi moderni avvalorando la discussione dalla lettura del romanzo di
			Victor Hugo <i
				>"<a
					href="https://www.feltrinellieditore.it/opera/lultimo-giorno-di-un-condannato-1/"
					target="_blank"
					rel="noreferrer">L'ultimo giorno di un condannato</a
				>".</i
			><br />
			Oltre a questi temi molto importanti buona parte delle lezioni è stata dedicata alla conoscenza
			dei cosidetti <i>"Anni di Piombo"</i>, periodo a cavallo tra gli anni '60 e gli anni '80 in
			cui l'Italia fu afflitta da un terrorismo di stampo politico. Abbiamo anche avuto l'onore di
			incontrare Benedetta Tobagi, figlia di Walter Tobagi giornalista assassinato in un attentato
			dalla Brigata XXVIII marzo, la quale è l'autrice del libro
			<i
				>"<a
					href="https://www.einaudi.it/catalogo-libri/storia/storia-contemporanea/come-mi-batte-forte-il-tuo-cuore-benedetta-tobagi-9788806198886/"
					target="_blank"
					rel="noreferrer">Come mi batte forte il cuore</a
				>".</i
			>
		</p>
	</div>

	<div class="info slide-text">
		<div>
			<h2 class="title" id="info"><b>INFORMATICA</b></h2>
			<img src={codF} alt="codice-fiscale" />
		</div>

		<p class="descrizione">
			Per quanto riguarda la materia informatica durante il corso dell'anno abbiamo continuato
			l'apprendimento di conoscenza riguardanti la sicurrezza online e ci siamo occupati di capire
			il funzionamento del codice fiscale e degli algoritmi che vi stanno dietro.<br />Creando due
			applicazioni in grado di
			<a
				href="https://github.com/marcoce005/C-sharp/tree/main/CodiceFiscale"
				target="_blank"
				rel="noreferrer">generare il codice fiscale</a
			>
			date le informazioni dell'utente e
			<a
				href="https://github.com/marcoce005/C-sharp/tree/main/CodiceFiscaleReverse"
				target="_blank"
				rel="noreferrer">estrapolarle</a
			> dato un codice fiscale.
		</p>
	</div>
</body>

<style>
	#tpsi {
		color: var(--color-tpsi);
		text-align: center;
	}

	#lettere {
		color: var(--color-lettere);
		text-align: center;
	}

	#info {
		color: var(--color-info);
	}

	.info p {
		margin-top: 30%;
	}

	.video-text iframe {
		margin-top: 6%;
	}
</style>
