<script>
	import { Router, Link, Route } from 'svelte-routing';
	import Home from './Home.svelte';
	export let url = '';
	import About from './About.svelte';
	import Projects from './Projects.svelte';
</script>

<Router {url}>
	<div class="container">
		<div class="header">
			<span class="header__inner">
				<Link to="/" style="text-decoration:none">
					<div class="logo">
						<span class="logo__mark">&gt;</span>
						<span class="logo__text">PRANAV</span>
						<span class="logo__cursor" style="background-color:#0ff" />
					</div>
				</Link>
				<span class="header__right">
					<nav class="menu">
						<ul class="menu__inner">
							<li class="menu__items">
								<Link class="links" to="about/">About</Link>
							</li>
							<li class="menu__items">
								<Link class="links" to="skills/">Skills</Link>
							</li>
							<li class="menu__items">
								<Link class="links" to="projects/">Projects</Link>
							</li>
							<li class="menu__items">
								<Link class="links" to="workExperience/">WorkExperience</Link>
							</li>
						</ul>
					</nav>
					<span class="menu-trigger"
						><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"
							><path d="M0 0h24v24H0z" fill="none" /><path
								d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z"
							/></svg
						>
					</span>
				</span>
			</span>
		</div>
		<div>
			<Route path="/" component={Home} />
			<Route path="/about/" component={About} />
			<Route path="/projects/" component={Projects} />
		</div>
	</div>
</Router>

<style>
	.header {
		text-align: center;
		width: 100%;
    height: 4vh;
		margin: 0;
		background-color: rgb(35, 36, 37);
		color: rgb(169, 169, 179);
		font-family: 'Inter UI', -apple-system, BlinkMacSystemFont, 'Roboto',
			'Segoe UI', Helvetica, Arial, sans-serif;
		line-height: 1.54;
		text-rendering: optimizelegibility;
		font-feature-settings: 'liga', 'tnum', 'case', 'calt', 'zero', 'ss01',
			'locl';
		font-size: 1rem;
		letter-spacing: 0.06em;
	}
	@media (min-width: 640px) {
		.header {
			max-width: none;
		}
	}
	.header {
		display: flex;
		flex-direction: column;
		align-items: center;
    flex: 1 1 auto;
		justify-content: center;
		margin: 0px;
  }
	.header {
		background: rgb(27, 28, 29) none repeat scroll 0% 0%;
		display: flex;
		align-items: center;
		justify-content: center;
		position: relative;
		padding: 20px;
	}
	.header__inner {
		display: flex;
		align-items: center;
		justify-content: space-between;
		margin: 0px auto;
		width: 760px;
		max-width: 100%;
	}
	.logo {
		display: flex;
		align-items: center;
		text-decoration: none;
		font-weight: bold;
		font-family: monospace, monospace;
	}
	.logo__text {
		font-size: 1.125rem;
	}
	.logo__cursor {
		display: inline-block;
		width: 10px;
		height: 1rem;
		background: rgb(254, 81, 134) none repeat scroll 0% 0%;
		background-color: rgb(254, 81, 134);
		margin-left: 5px;
		border-radius: 1px;
		animation: 1s ease 0s infinite normal none running cursor;
	}
	.header__right {
		display: flex;
		flex-direction: row;
		align-items: center;
	}
	.menu {
		background: rgb(27, 28, 29) none repeat scroll 0% 0%;
	}
	.menu-trigger {
		width: 24px;
		height: 24px;
		fill: currentcolor;
		margin-left: 10px;
		cursor: pointer;
		display: none;
	}
	.menu__inner {
		display: flex;
		align-items: center;
		justify-content: flex-start;
		max-width: 100%;
		margin: 0px auto;
		padding: 0px 15px;
		font-size: 1rem;
		list-style: outside none none;
	}
  .container {
		overflow: hidden;
    height: 100vh;
    background-color: rgb(35, 36, 37);;
  }



</style>

