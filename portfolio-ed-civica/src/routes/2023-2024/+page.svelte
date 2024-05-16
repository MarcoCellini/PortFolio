<svelte:head>
	<title>2023-2024</title>
	<meta name="description" content="Attivita' svolte nell'anno scolastico 2023-2024" />
</svelte:head>

<body>
	<h1><b>2023-2024</b></h1>

	<div class="inglese">
		<div class="slide-text">
			<div>
				<h2 class="title" id="inglese"><b>INGLESE</b></h2>
				<p class="descrizione">
					Nella prima parte dell'anno abbiamo approfondito le dinamiche dei social media e la loro
					grandissima diffusione nell'ultimo decennio.<br />Avendo un occhio di riguardo sulla
					dipendenza che essi creano alle persone al fine di mantenerli il più possibile incollati
					agli schermi.
				</p>
			</div>

			<iframe
				src="https://docs.google.com/presentation/d/e/2PACX-1vRK28j8v8AyQsMBmM7Z7r3_Fpe7iuEHH_ycoZzNbkLWu0FHHsvxI_nDtJPtsF4DL-D52VudKXu4fygr/embed?start=false&loop=false&delayms=3000"
				frameborder="0"
				width="505"
				height="360"
				allowfullscreen="true"
				mozallowfullscreen="true"
				webkitallowfullscreen="true"
				title="social-network-slides"
			/>
		</div>
	</div>

	<div class="lettere">
		<h2 class="title" id="lettere"><b>LETTERE</b></h2>

		<p class="descrizione">
			Buonaparte delle ore di educazione civica di quest'anno sono state dedicate alla
			sensibilizzazione sulla violenza contro le donne, tema che oramai portiamo avanti da tre anni.
			<br />
			L'altro argomento trattano durante queste ore è la prigionia nei campi di concentramento/sterminio
			in Germania negli anni '40, nei campi di lavoro Russi sotto la dittatura di Stalin e i laboratori
			sperimentali dei Giapponesi verso la fine degli anni '40.
		</p>
	</div>

	<div class="videos slide-text">
		<div class="video1">
			<iframe
				width="490"
				height="360"
				src="https://www.youtube.com/embed/uXQVgp7g0Xk?si=MCzroNf5Te-VT6kX"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			/>
		</div>
		<div class="video2">
			<iframe
				width="490"
				height="360"
				src="https://www.youtube.com/embed/6yXNjIq50Dw?si=NTY5c5ViEP71Fee9"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			/>
		</div>
		<div class="video3">
			<iframe
				width="490"
				height="360"
				src="https://www.youtube.com/embed/SKOP830ETKk?si=A5N1MNZnV_qmTeg8"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			/>
		</div>
	</div>

	<br />

	<p class="descrizione">
		Durante il corso dell'anno abbiamo anche trattato il tema della situazione carceraria italiana. <br
		/>
		Abbiamo avuto l'onore di incontranre l'attuale direttice della "Casa Circondariale Lorusso e Cotugno"
		di Torino la quale, insieme alla scrittice Serena Uccello, hanno redatto e pubblicato il libro "<i
			><a
				href="https://www.einaudi.it/catalogo-libri/problemi-contemporanei/senza-sbarre-cosima-buccoliero-9788806252793/"
				target="_blank"
				rel="noreferrer">Senza sbarre</a
			></i
		>".

		<br /><br />
		Nel corso dell'anno scolastico abbiamo avuto modo di affrontare temi anche difficili come la condizione
		manicomiale precedente alla legge Basaglia, grazie anche alla lettura del libro "<i
			><a href="https://www.rizzolilibri.it/libri/laltra-verita/" target="_blank" rel="noreferrer"
				>L'altra verità</a
			></i
		>". Tratto dall'esperienza personale della poetessa Alda Merini.
	</p>
</body>

<style>
	#inglese {
		color: var(--color-inglese);
		margin-top: 0px;
	}

	#lettere {
		text-align: center;
		color: var(--color-lettere);
	}

	.videos {
		grid-template-rows: 1fr 1fr;
		grid-template-areas: 'top1 top2' 'down down';
		column-gap: 1%;
		row-gap: 1%;
	}

	.video1 {
		grid-area: top1;
	}

	.video2 {
		grid-area: top2;
	}

	.video3 {
		grid-area: down;
		text-align: center;
	}
</style>
