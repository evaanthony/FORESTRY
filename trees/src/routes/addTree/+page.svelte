<svelte:head>
	<title>Add Trees</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>Add Trees</h1>
</div>
<div class="text-column">
	<form method="post">
		<div>
			<label>
				Tree Name :
				<input name="treeName" type="text">
			</label>
		</div><br>
		<div>
			<label>
				Tree Type :
				<input name="treeName" type="text">
			</label>
		</div><br>
		<div>
			<label>
				Tree Location :
				<input name="treeName" type="text">
			</label>
		</div><br>
		<div>
			<label>
				Tree Size :
				<input name="treeName" type="text">
			</label>
		</div><br><br>
		<div class="text-column">
			<button name="submit">Submit</button>
		</div>
	</form>
</div>
