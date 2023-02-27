<!DOCTYPE html>
<html>
<head>
	<title>Aku Sayang Kamu</title>
	<link href="https://fonts.googleapis.com/css2?family=Handlee" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="container">
		<div class="header">
			<h1>Aku Sayang Kamu</h1>
		</div>
		<div class="content">
			<p>Percayalah bahwa aku mencintaimu selalu dan tidak akan pernah berubah.</p>
			<p>Kau adalah segalanya bagiku dan tidak akan pernah ada yang bisa menggantikanmu.</p>
			<p>Aku akan selalu ada untukmu dan bersamamu dalam segala hal.</p>
			<div class="heart"></div>
			<audio src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" controls></audio>
		</div>
		<div class="form">
			<h2>Kirim Pesan untukku</h2>
			<form id="message-form">
				<label for="name">Nama:</label>
				<input type="text" id="name" name="name" placeholder="Masukkan Nama Kamu">

				<label for="email">Email:</label>
				<input type="email" id="email" name="email" placeholder="Masukkan Email Kamu">

				<label for="message">Pesan:</label>
				<textarea id="message" name="message" placeholder="Tulis Pesan Kamu"></textarea>

				<input type="submit" value="Kirim">
			</form>
			<div id="status"></div>
		</div>
	</div>
	<script src="script.js"></script>
</body>
</html>
