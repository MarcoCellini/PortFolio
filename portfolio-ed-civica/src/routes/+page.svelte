<script>
	import scuola from '$lib/images/foto_scuola.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Pagina iniziale del sito" />
</svelte:head>

<body>
	<h1><b>EDUCAZIONE CIVICA</b></h1>

	<marquee class="name" align="middle" behavior="scroll" direction="left" scrolldelay="10">
		<p>Created by Marco Cellini 5° Computer Science</p>
	</marquee>

	<table>
		<tbody>
			<tr>
				<td colspan="3" class="title">
					<h2><b>MI PRESENTO</b></h2>
				</td>
			</tr>

			<tr>
				<td>
					<img src={scuola} alt="foto-scuola" class="foto-scuola" />
				</td>

				<td>&nbsp;</td>

				<td>
					<p class="descrizione">
						Mi chiamo Marco Cellini sono nato il 6 Settembre 2005 a Torino e frequento l'Istituto
						Internazionale Edoardo Agnelli che si trova in corso Unione Sovietica 312; per maggiori
						informazioni visionare il sito della scuola: <a
							href="https://agnelli.it/"
							target="_blank">Agnelli</a
						>.
						<br />Ho creato questo portfolio per raggruppare e successivamente pubblicare a tutti le
						attività che ho svolto di Educazione Civica durante i miei anni scolastici spero sia di
						aiuto non solo a me ma anche a tante altre persone che devono o dovranno intraprendere
						lo studio di questa materia.
						<br />Qui sotto vi lascio il video presentazione del mio istituto.
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</body>

<style>
	h1 {
		font-size: 5rem;
	}

	.name {
		color: black;
		font-size: 1.4rem;
	}

	h2 {
		font-size: 3rem;
	}

	.foto-scuola {
		width: 450px;
	}

	.descrizione {
		padding: 1%;
		font-family: 'Times New Roman', Times, serif;
		font-size: 1.1em;
	}

	.title {
		text-align: center;
		font-family: 'Times New Roman', Times, serif;
	}
</style>
