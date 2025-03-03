<footer class="layout-footer" style="display:flex">
	<div class="container">
		<div class="row align-items-center">
			<div class="col-lg-4">
				<a href="https://www.centbee.com/home">
					<img src="../assets/Centbee Logo Hori .png" alt="Centbee" />
				</a>
				<div style="margin-top: 1rem !important">
					<span class="footer-copyright">©2024 Centbee<br /> </span>
				</div>
			</div>
			<div class="col-lg-8">
				<nav class="footer-nav">
					<ul class="footer-menu">
						<li>
							<a href="/example">Home</a>
						</li>
						<li>
							<a href="/example">About</a>
						</li>
						<li>
							<a href="/example">Social</a>
						</li>
						<li>
							<a href="/example">Contact</a>
						</li>
						<li>
							<a href="/example">FAQs</a>
						</li>
					</ul>
					<ul class="footer-social">
						<li>
							<a href="/example">Home</a>
						</li>
						<li>
							<a href="/example">About</a>
						</li>
						<li>
							<a href="/example">Social</a>
						</li>
						<li>
							<a href="/example">Contact</a>
						</li>
						<li>
							<a href="/example">FAQs</a>
						</li>
					</ul>
				</nav>
			</div>
		</div>
	</div>
</footer>

<style>
	.layout-footer {
		background-color: #000000;
		color: #e2e924;
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
		padding: 2.5rem 0;
	}

	.container {
		width: 100%;
		padding-right: 15px;
		padding-left: 15px;
		margin-right: auto;
		margin-left: auto;
	}

	.row {
		display: -ms-flexbox;
		display: flex;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		margin-right: -15px;
		margin-left: -15px;
	}

	.align-items-center {
		-ms-flex-align: center !important;
		align-items: center !important;
	}

	.col-lg-4 {
		-ms-flex: 0 0 33.333333%;
		flex: 0 0 33.333333%;
		max-width: 33.333333%;
	}

	.col-lg-8 {
		-ms-flex: 0 0 66.666667%;
		flex: 0 0 66.666667%;
		max-width: 66.666667%;
	}

	.footer-nav {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-orient: vertical;
		-webkit-box-direction: normal;
		-ms-flex-direction: column;
		flex-direction: column;
	}

	.footer-menu,
	.footer-social {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		-webkit-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
		padding: 0;
		margin: 0;
		list-style: none;
	}

	.footer-menu a,
	.footer-social a {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		padding: 0.75rem 0.5rem;
		color: var(--color-white);
		white-space: nowrap;
	}
</style>
