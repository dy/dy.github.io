<style>
	body {
		margin: auto auto;
		background: ghostwhite;
		display: flex;
		flex-flow: row wrap;
		padding: 2rem 2rem;
		font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
		--black: #24292e;
		color: var(--black);

		&::before {
			content: '';
			position: fixed;
			top: 0;
			left: 0;
			right: 0;
			bottom: 0;
			pointer-events: none;
			background: radial-gradient(circle at var(--x, 50%) 0, white, transparent 54%);
			transition: background-position 0.05s;
		}

		.markdown-body, main {
			position: relative;

			h1, h2, h3 {

			}
			p {
				margin: 0;
				max-width: 82ch;
			}

			a {
				color: slategray;
				text-decoration-color: rgb(from currentColor r g b / 20%);
				text-underline-offset: .2em;
				text-decoration-line: underline;
			}
			a:hover {
				text-decoration-color: currentColor;
				color: var(--black);
			}


			header {
				width: 100%;
				display: flex;
				flex-direction: column;
				align-items: baseline;
				gap: 1rem;
				margin-bottom: 2rem;
				.github {
					margin-left: auto;
					color: inherit;
					text-decoration: none;
				}
			}

			article {
				figure {
					margin: 0
				}
			}

			ul {
				padding: 0;
				padding-left: 2ch;

				/* li::marker {
					content: "· ";
				} */
			}


			/* hide github h1 */
			h1:first-of-type {
				display: none;
			}
		}
	}
</style>


# Dmitry Iv.

Open-source enthousiast with focus on purpose-driven software, eclectic design, aesthetic DX, minimalism and performance.

<nav style="display: flex; gap: 1rem; margin-top: 1rem; align-items: center">
	<a href="https://github.com/dy" title="github">
		<svg xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 0 98 96"><path fill-rule="evenodd" clip-rule="evenodd" d="M48.854 0C21.839 0 0 22 0 49.217c0 21.756 13.993 40.172 33.405 46.69 2.427.49 3.316-1.059 3.316-2.362 0-1.141-.08-5.052-.08-9.127-13.59 2.934-16.42-5.867-16.42-5.867-2.184-5.704-5.42-7.17-5.42-7.17-4.448-3.015.324-3.015.324-3.015 4.934.326 7.523 5.052 7.523 5.052 4.367 7.496 11.404 5.378 14.235 4.074.404-3.178 1.699-5.378 3.074-6.6-10.839-1.141-22.243-5.378-22.243-24.283 0-5.378 1.94-9.778 5.014-13.2-.485-1.222-2.184-6.275.486-13.038 0 0 4.125-1.304 13.426 5.052a46.97 46.97 0 0 1 12.214-1.63c4.125 0 8.33.571 12.213 1.63 9.302-6.356 13.427-5.052 13.427-5.052 2.67 6.763.97 11.816.485 13.038 3.155 3.422 5.015 7.822 5.015 13.2 0 18.905-11.404 23.06-22.324 24.283 1.78 1.548 3.316 4.481 3.316 9.126 0 6.6-.08 11.897-.08 13.526 0 1.304.89 2.853 3.316 2.364 19.412-6.52 33.405-24.935 33.405-46.691C97.707 22 75.788 0 48.854 0z" fill="currentColor"/></svg>
	</a>

	<a href="https://x.com/dmitryiv_" title="x.com">
		<svg xmlns="http://www.w3.org/2000/svg" height="21" viewBox="0 0 1200 1227">
		<path d="M714.163 519.284L1160.89 0H1055.03L667.137 450.887L357.328 0H0L468.492 681.821L0 1226.37H105.866L515.491 750.218L842.672 1226.37H1200L714.137 519.284H714.163ZM569.165 687.828L521.697 619.934L144.011 79.6944H306.615L611.412 515.685L658.88 583.579L1055.08 1150.3H892.476L569.165 687.854V687.828Z" fill="currentColor"/>
		</svg>
	</a>
</nav>

## Technography

<!-- * [plyr]() - minimalistic audio player
* [piano-keyboard]() – in-browser piano
* [sruti]() – drone generator
* [metr]() – metronome / drum practice helper
* [wavearea]() – edit audio in textarea
* [piezo]() – prototype language for sound processing
* [jz]() – js subset compiling to WASM
* [watr]() – light & fast WASM compiler -->

* [sprae](/sprae) – aesthetic progressive enhancement framework
* [subscript](/subscript) – syntax parser / expression evaluator
* [wavefont](/wavefont) – font with bars as characters
* [linefont](/linefont) – font with lines as characters

<!-- ## Sonography

* [endless beginnings]()

* [govindam adi purusam]()
	* bossa version
	* minimal guitar version
	* chillhop version
	* translated verses

* [marketplace of love]()
	* lounge version

* [moonlight rite]()
	* jazzier version
	* fixed imagery

* Older works
	* My moms favorites
 -->

<!-- * [krishnized]()
* [web-being]() -->


<script src="//unpkg.com/sprae" prefix="data-js-"></script>
<div data-js-scope="x=0, y=0" data-js-fx="console.log(123123)" data-js-onmousemove.document="e => { x = e.clientX; y = e.clientY; }" data-js-style.root="{'--x': x + 'px', '--y': y + 'px'}"></div>

<script type="module">
console.log(123456)
</script>
