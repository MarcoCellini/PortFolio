<script>
	import punti from '$lib/images/punti.png';
</script>

<svelte:head>
	<title>Ed-Civica</title>
	<meta name="description" content="Spiegazione della materia" />
</svelte:head>

<body>
	<h1><b>EDUCAZIONE CIVICA</b></h1>
	
	<br />

	<h2 class="title"><b>CHE COS'E' L'EDUCAZIONE CIVICA</b></h2>

	<table>
		<tbody>
			<tr>
				<td>
					<p class="descrizione">
						Da settembre 2020 l'Educazione Civica è una disciplina trasversale che interessa tutti i
						gradi scolastici, a partire dalla scuola dell’Infanzia fino alla scuola secondaria di II
						grado.
						<br />L'insegnamento ruota intorno a tre nuclei tematici principali:
					</p>
				</td>

				<td>
					<img src={punti} alt="foto-scuola" class="foto-scuola" />
				</td>
			</tr>

			<tr>
				<td colspan="2">
					<p class="descrizione">
						Oltre a questi argomenti principali abbiamo trattato anche argomenti più vicini a noi
						come l'epidemia di Cocid-19 nel 2020, gli sbarchi di migranti e le loro storie tramite
						libri e testimonianze, come sono strutturati politicamente e legislativamente altri
						stati come la Gran Bretagna, ecc...
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</body>

<style>
	.title {
		text-align: left;
		font-family: 'Times New Roman', Times, serif;
		color: green;
	}

	h1 {
		font-size: 5rem;
	}

	h2 {
		font-size: 3rem;
	}

	.title {
		text-align: left;
		font-family: 'Times New Roman', Times, serif;
	}

	.descrizione {
		padding: 1%;
		font-family: 'Times New Roman', Times, serif;
		font-size: 1.3em;
	}
</style>
