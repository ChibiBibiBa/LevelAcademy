<script lang="ts">
	import {
		faFacebook,
		faTwitter,
		faYoutube,
		faInstagram
	} from '@fortawesome/free-brands-svg-icons';
	import { FontAwesomeIcon } from '@fortawesome/svelte-fontawesome';
</script>

<header>
	<div class="info">
		<div class="container">
			<ul class="socials">
				<li>
					<a href="https://www.facebook.com/levelacademymt">
						<FontAwesomeIcon icon={faFacebook}></FontAwesomeIcon></a
					>
				</li>
				<li></li>
				<li></li>
				<li></li>
				<li></li>
			</ul>
		</div>
	</div>
	<nav></nav>
</header>

<style>
	header {
		width: 100%;
		height: 125px;
		background-color: var(--background);
	}
	.info {
		width: 100%;
		height: 33%;
		border-bottom: solid 1px rgba(255, 255, 255, 0.2);
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.info .container {
		width: 85%;
		height: 50%;
		display: flex;
		justify-content: end;
		align-items: center;
	}
	.socials {
		width: 20%;
		height: 100%;
		color: white;
	}
	nav {
		width: 100%;
		height: 67%;
		position: sticky;
		top: 0;
		left: 0;
	}
</style>

