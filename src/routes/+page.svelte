<script>
	let darktheme = true;
</script>

<div data-bs-theme={darktheme ? 'dark' : 'light'}>
	<nav class="navbar main-bg">
		<div class="container-fluid">
			<h1 class="navbar-brand px-3 fs-3" style="font-family: 'Passions Conflict', cursive;">
				Synergy
			</h1>
			<div class="hstack ">
				<a
					href="https://github.com/SupremeDeity/itcprj_website"
					target="_blank"
					rel="noreferrer"
					class="mx-3 btn btn-secondary"><i class="bi bi-github" /></a
				>
				<div class="vr" />
				<button
					type="button"
					on:click={() => (darktheme = !darktheme)}
					class="mx-3 btn btn-secondary"><i class="bi bi-moon-stars" /></button
				>
			</div>
		</div>
	</nav>
	<div style="height:90vh" class="main-bg">
		<div
			class="row text-center position-absolute start-50 top-50 translate-middle user-select-none"
		>
			<h1 style="font-family: 'Passions Conflict', cursive; font-size:250px; ">Synergy</h1>
			<a
				href="#"
				target="_blank"
				rel="noreferrer"
				class="mx-3 my-3 p-3 btn btn-{darktheme
					? 'dark'
					: 'light'} border border-danger rounded-pill fs-5"
				style="font-family: 'Roboto';"
				><i class="bi bi-download mx-2" />
				Download For Windows
			</a>
		</div>
	</div>
	<div class="features container-fluid text-center p-3 user-select-none">
		<h2 class="text-dark">Features</h2>
		<div class="row row-col-3 m-3">
			<div class="col-sm-4">
				<div class="card text-center p-3">
					<div class="card-header text-muted"><i class="bi bi-server mx-2" /></div>
					<div class="card-body text-body">
						<h5 class="card-title">Server</h5>
						<p class="card-text">Create upto 10 community servers for free without any hassle.</p>
					</div>
				</div>
			</div>
			<div class="col-sm-4">
				<div class="card text-center p-3">
					<div class="card-header text-muted"><i class="bi bi-chat-fill mx-2" /></div>
					<div class="card-body text-body">
						<h5 class="card-title">Video & Voice</h5>
						<p class="card-text">Low latency voice & video chat to connect to your community.</p>
					</div>
				</div>
			</div>
			<div class="col-sm-4">
				<div class="card text-center p-3">
					<div class="card-header text-muted"><i class="bi bi-fullscreen mx-2" /></div>
					<div class="card-body text-body">
						<h5 class="card-title">Screen Sharing</h5>
						<p class="card-text">Screen share your adventures for all the world to see.</p>
					</div>
				</div>
			</div>
		</div>
		<div class="row row-col-3 m-3">
			<div class="col-sm-4">
				<div class="card text-center p-3">
					<div class="card-header text-muted"><i class="bi bi-emoji-kiss-fill mx-2" /></div>
					<div class="card-body text-body">
						<h5 class="card-title">Emojis & Stickers</h5>
						<p class="card-text">Level up your messages with the power of emojis and stickers.</p>
					</div>
				</div>
			</div>
			<div class="col-sm-4">
				<div class="card text-center p-3">
					<div class="card-header text-muted"><i class="bi bi-tools mx-2" /></div>
					<div class="card-body text-body">
						<h5 class="card-title">Moderation</h5>
						<p class="card-text">
							Built in moderation tools to ensure a healthy environment for your community.
						</p>
					</div>
				</div>
			</div>
			<div class="col-sm-4">
				<div class="card text-center p-3">
					<div class="card-header text-muted"><i class="bi bi-arrow-left-right mx-2" /></div>
					<div class="card-body text-body">
						<h5 class="card-title">Cross-platform</h5>
						<p class="card-text">Stay connected on your mobile or your computer.</p>
					</div>
				</div>
			</div>
		</div>
	</div>
	<footer class="footer text-center p-1 border border-start-0 border-end-0">
		<p class="my-1" style="font-family: Roboto;">Synergy&#8482; 2023</p>
	</footer>
</div>

<style>
	.main-bg {
		background: #556270; /* fallback for old browsers */
		background: -webkit-linear-gradient(
			to right,
			#ff6b6b,
			#556270
		); /* Chrome 10-25, Safari 5.1-6 */
		background: linear-gradient(
			to right,
			#ff6b6b,
			#556270
		); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
	}
	.features {
		height: 80vh;
	}
	.footer {
		color: var(--bs-light);
		background-color: var(--bs-dark);
	}
</style>
