<script>
	import bio from '$lib/images/biologia.png';
</script>

<svelte:head>
	<title>2020-2021</title>
	<meta name="description" content="Attivit' svolte nell'anno scolastico 2020-2021" />
</svelte:head>

<body>
	<h1><b>2020-2021</b></h1>

	<table>
		<tbody>
			<tr>
				<td>
					<img src={bio} alt="mappa-covid" class="foto-bio" />
				</td>

				<td>&nbsp;</td>

				<td>
					<h2 class="title" id="biologia"><b>BIOLOGIA</b></h2>
					<p class="descrizione">
						Di Biologia durante l'anno scolastico 2020/2021 abbia approfondito un argomento in
						particolare: il Covid-19. Il Covid-19 è un virus che ha colpito tutto il mondo già
						dall'inizio del 2020 ed è tutt'ora presente (documento scritto il 3/1/21). Vi lascio il
						link di un sito dove vi è la statistica mondiale dell'epidemia:<br />
						<a
							href="https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6"
							target="_blank">Coronavirus Covid-19</a
						>
					</p>
				</td>
			</tr>
		</tbody>
	</table>

	<table>
		<tbody>
			<tr>
				<td>
					<h2 class="title" id="inglese"><b>INGLESE</b></h2>
					<p class="descrizione">
						D'altro canto di Inglese ci siamo soffermati sulla formazione del Parlamento inglese e
						sulla sua storia. Abbiamo anche studiato la differenza tra i vari poteri in capo alla
						Monarchia e al Parlamento.
						<br />Qui a destra e qui sotto vi lascio il video di presentazione di questi argomenti
					</p>
				</td>

				<td>&nbsp;</td>

				<td>
					<iframe
						width="560"
						height="315"
						src="https://www.youtube.com/embed/RAMbIz3Y2JA"
						title="YouTube video player"
						frameborder="0"
						allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
						allowfullscreen
					/>
				</td>
			</tr>
		</tbody>
	</table>

	<div>
		<div class="title" id="lettere">
			<h2><b>LETTERE</b></h2>
		</div>

		<p class="descrizione">
			A differenza di altre materie per Lettere durante l'anno scolastico abbiamo lavorato molto
			sulla migrazione in generale; abbiamo approfondito l' argomento tramite l'incontro con il
			dottor Pietro Bartolo, medico di Lampedusa, del quale abbiamo letto il libro "Le stelle di
			Lampedusa". Inoltre durante questa attività abbiamo avuto la possibilità di vedere un
			docu-film intitolato "Fuocoammare".
			<br />Qui sotto vi lascio:
		</p>

		<ul class="descrizione" id="elenco">
			<li>
				Il riassunto del libro e se volete potete comprarlo da
				<a
					href="https://www.google.com/url?q=https%3A%2F%2Fwww.amazon.it%2Fstelle-Lampedusa-storia-bambini-cercano%2Fdp%2F8804719249%2Fref%3Dtmm_pap_swatch_0%3F_encoding%3DUTF8%26qid%3D1609673253%26sr%3D8-1&sa=D&sntz=1&usg=AOvVaw396DyfL3tREj1j9yxywtAr"
					target="_blank">Amazon</a
				>.
			</li>
			<li>Le slide sulla storia delle migrazioni.</li>
			<li>L'incontro con il dottor Pietro Bartolo.</li>
			<li>
				<a
					href="https://www.google.com/url?q=https%3A%2F%2Fec.europa.eu%2Finfo%2Fstrategy%2Fpriorities-2019-2024%2Fpromoting-our-european-way-life%2Fstatistics-migration-europe_it&sa=D&sntz=1&usg=AOvVaw3MkOFzTPdQVvkCN5fX55tf"
					target="_blank"
					>Ed un sito dell'Unione Europea con le statistiche delle migrazioni nei vari paesi.</a
				>
			</li>
		</ul>
	</div>

	<table>
		<tbody>
			<tr>
				<td>
					<iframe
						src="https://docs.google.com/presentation/d/e/2PACX-1vR6wT4De5dhKt-wZBrTybzlRqoe8SWaIZbatmRHM5kukxSvydHDxxWlfTQxCCc2arkK9g5ZwAnAJpEO/embed?start=false&loop=false&delayms=3000"
						frameborder="0"
						allowfullscreen="true"
						mozallowfullscreen="true"
						webkitallowfullscreen="true"
						width="505"
						height="360"
					/>
				</td>

				<td>&nbsp;</td>

				<td>
					<iframe
						width="505"
						height="360"
						src="https://www.youtube.com/embed/eHEZwiyect4"
						title="L'Agnelli incontra il dottor Pietro Bartolo"
						frameborder="0"
						allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
						allowfullscreen
					/>
				</td>
			</tr>
		</tbody>
	</table>

	<br />

	<div class="riassunto">
		<center>
			<iframe
				src="https://docs.google.com/document/d/e/2PACX-1vSZym0B4an443owBw9z0jdBJjLgzZgHpLDfv-7fCyHekbE77Yxz1sRpRHGChucYRuVLMHr5CueIXiFg/pub?embedded=true"
				width="700"
				height="650"
			/>
		</center>
	</div>

	<br>

	
</body>

<style>
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
		padding: 2.3%;
		font-family: 'Times New Roman', Times, serif;
		font-size: 1.3em;
	}

	.foto-bio {
		width: 30rem;
	}

	#biologia {
		color: rgb(10, 122, 0);
	}

	#inglese {
		color: blue;
	}

	#lettere {
		color: orange;
		text-align: center;
	}

	#elenco {
		margin-top: 0px;
		padding: 2.5%;
	}
</style>
