<script>
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

		<p class="descrizione" />
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

	.slide-text,
	.video-text {
		display: grid;
		grid-template-columns: 1fr 1fr;
		column-gap: 3%;
	}

	.video-text iframe {
		margin-top: 6%;
	}
</style>
