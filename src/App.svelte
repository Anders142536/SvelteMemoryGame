<script>
	import * as game from './game.js'
	
	let points = '10/10'

	function restart() {
		console.log('restarting')
	}

</script>

<div>
	<div class="header">
		<h1>Memory</h1>
		<div>
			<b>Points:</b>
			<p class='points' >{points}</p>
			<button on:click={restart}>Restart</button>
		</div>
	</div>
	<div class="board" >

	</div>
</div>

