:root {
	--primary: #b758ff;
	--secondary: white;
	--background: white;
	--width: 1000px;
	--nav-break: 800px;
}

body {
	font-family: Roboto, -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
	font-weight: 400;
}

h1,
h2,
h3,
h4,
header {
	margin-block-end: 0.2em;
	font-family: Orbitron, Roboto, -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
	letter-spacing: .1em;
}

.social {
	fill: #b758ff;
}

.content-row {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
    gap: 1rem;
}

.rs-score .claim-inner a[href], rs-score .claim-inner a[href],
.rs-score .claim-inner a[href]:visited, rs-score .claim-inner a[href]:visited  {
    color: #fff;
    text-decoration: underline;
    font-weight: 400;
}