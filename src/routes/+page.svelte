<script lang="ts">
	import IMG_1 from "$lib/assets/speakers.jpg";
	import IMG_2 from "$lib/assets/second.jpg";
</script>



<nav>
	<div class="container nav-row">
		<a class="brand" href="#">
			<div class="mark">F</div>
			<div class="brand-name">Fox's Auto Sound - DEMO</div>
		</a>
		<div class="nav-links">
			<a href="#services">Services</a>
			<a href="#work">Work</a>
			<a href="#contact">Contact</a>
			<a href="#contact" class="btn btn-primary">Get a quote</a>
		</div>
	</div>
</nav>

<header class="hero">
	<div class="container hero-grid">
		<div>
			<span class="eyebrow"><span class="dot"></span>Car Audio Installation</span>
			<h1 class="display">Sound that <span class="accent">moves</span> with you.</h1>
			<p class="lede">Custom speaker installs, subwoofer setups, and full system builds, done right the first time. Local shop. Honest work.</p>
			<div class="hero-cta">
				<a href="#contact" class="btn btn-primary">Book an install</a>
				<a href="#work" class="btn btn-ghost">See recent work</a>
			</div>
			<div class="hero-meta">
				<div class="meta-item">
					<div class="meta-num">100+ yrs</div>
					<div class="meta-label">Experience</div>
				</div>
				<div class="meta-item">
					<div class="meta-num">All makes</div>
					<div class="meta-label">Cars &amp; trucks</div>
				</div>
				<div class="meta-item">
					<div class="meta-num">Same-day</div>
					<div class="meta-label">Quotes</div>
				</div>
			</div>
		</div>

		<div class="hero-visual">
			<div class="badge-float"><span class="pulse"></span>Booking now</div>
			<div class="speaker">
				<svg viewBox="0 0 200 200" fill="none" stroke="rgba(255,255,255,0.85)" stroke-width="1.5">
					<circle cx="100" cy="100" r="92" />
					<circle cx="100" cy="100" r="74" />
					<circle cx="100" cy="100" r="56" />
					<circle cx="100" cy="100" r="38" />
					<circle cx="100" cy="100" r="20" stroke="rgba(255,255,255,0.5)" />
					<circle cx="100" cy="100" r="6" fill="rgba(255,255,255,0.85)" stroke="none" />
					<circle cx="100" cy="100" r="106" stroke="rgba(255,255,255,0.25)" stroke-dasharray="2 6" />
				</svg>
			</div>
			<!-- <div class="hero-tag">// signal &rarr; clean &rarr; loud</div> -->
			<div class="hero-tag">clean & loud</div>
		</div>
	</div>
</header>

<section id="services">
	<div class="container">
		<div class="section-head">
			<div>
				<span class="eyebrow"><span class="dot"></span>What we do</span>
				<h2 class="display">Built for the way you drive.</h2>
			</div>
			<!-- <p>From a simple head-unit swap to a full system rebuild — every install is dialed in by ear, not by template.</p> -->
		</div>

		<div class="services">
			<article class="service-card">
				<div class="service-icon">
					<svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round">
						<circle cx="12" cy="12" r="9" />
						<circle cx="12" cy="12" r="5" />
						<circle cx="12" cy="12" r="1.5" fill="currentColor" />
					</svg>
				</div>
				<h3>Speaker installs</h3>
				<p>Door speakers, components, and tweeters fitted clean — no rattles, no compromises.</p>
			</article>
			<article class="service-card">
				<div class="service-icon">
					<svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
						<rect x="3" y="6" width="18" height="13" rx="2" />
						<path d="M7 19v2M17 19v2" />
						<circle cx="12" cy="12.5" r="3.5" />
					</svg>
				</div>
				<h3>Subwoofer boxes</h3>
				<p>Sealed and ported enclosures, custom-fit to your trunk, hatch, or behind the seat.</p>
			</article>
			<article class="service-card">
				<div class="service-icon">
					<svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
						<path d="M4 12h3l2-6 4 12 2-6h5" />
					</svg>
				</div>
				<h3>Amps &amp; wiring</h3>
				<p>Full system builds with proper gauge wiring, tuned amps, and zero electrical headaches.</p>
			</article>
		</div>
	</div>
</section>

<section id="work" class="work-section">
	<div class="container">
		<div class="section-head">
			<div>
				<span class="eyebrow"><span class="dot"></span>Recent installs</span>
				<h2 class="display">A look in the bay.</h2>
			</div>
			<!-- <p>Two recent builds straight from the shop. More on the way.</p> -->
		</div>

		<div class="work-grid">
			<article class="work-item">
				<div class="work-photo">
					<img src={IMG_1} alt="Two subwoofers installed">
					<!-- <div class="swap"> -->
					<!--   DROP PHOTO 01 -->
					<!--   <small>recommended 4:3, ~1600px wide</small> -->
					<!-- </div> -->
				</div>
				<div class="work-meta">
					<div>
						<h3>Trunk double subwoofer build</h3>
						<p>We install strong bass systems that look produce powerful bass.</p>
					</div>
					<span class="work-tag">Sub install</span>
				</div>
			</article>

			<article class="work-item">
				<div class="work-photo">
					<img src={IMG_2} alt="Two subwoofers installed">
				</div>
				<div class="work-meta">
					<div>
						<h3>Highest quality installation</h3>
						<p>We don't just slap in speakers - we do clean, professional installs.</p>
					</div>
					<span class="work-tag">Professionalism</span>
				</div>
			</article>
		</div>
	</div>
</section>

<section id="contact" class="cta">
	<div class="container">
		<div class="cta-card">
			<div>
				<h2>Ready to upgrade your ride?</h2>
				<p>Send us your car and what you're thinking — we'll come back with a same-day quote and a date for the install.</p>
				<a class="cta-phone" href="tel:+10000000000">
					<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
						<path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
					</svg>
					(519) 268-2906
				</a>
			</div>
			<div class="cta-actions">
				<a href="/cdn-cgi/l/email-protection#c6aea3aaaaa986a0a9beb5a7b3b2a9b5a9b3a8a2e8a5a9ab" class="btn btn-primary">Email the shop</a>
				<a target="_blank" href="https://maps.app.goo.gl/6jZ2DnN5eKrPLrFg8" class="btn btn-ghost">Find us on the map</a>
			</div>
		</div>
	</div>
</section>

<footer>
	<div class="container foot-row">
		<div>© 2026 Fox's Auto Sound</div>
		<div>BN</div>
		<div>Mon–Fri · 9am–6pm</div>
	</div>
</footer>


<style>
:root {
	--blue-900: oklch(0.28 0.13 255);
	--blue-700: oklch(0.42 0.18 255);
	--blue-600: oklch(0.52 0.20 255);
	--blue-500: oklch(0.62 0.19 255);
	--blue-50:  oklch(0.97 0.02 255);

	--ink: oklch(0.18 0.01 260);
	--ink-soft: oklch(0.42 0.01 260);
	--line: oklch(0.90 0.005 260);
	--paper: oklch(0.99 0.003 90);
	--paper-warm: oklch(0.97 0.006 80);

	--radius: 14px;
	--maxw: 1180px;
}
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; }
body {
	font-family: 'Inter', system-ui, sans-serif;
	color: var(--ink);
	background: var(--paper);
	-webkit-font-smoothing: antialiased;
	line-height: 1.5;
}
.display {
	font-family: 'Bricolage Grotesque', 'Inter', sans-serif;
	font-weight: 600;
	letter-spacing: -0.02em;
	line-height: 1.02;
}
.container {
	max-width: var(--maxw);
	margin: 0 auto;
	padding: 0 32px;
}

/* ---------- NAV ---------- */
nav {
	position: sticky;
	top: 0;
	z-index: 10;
	background: color-mix(in oklch, var(--paper) 88%, transparent);
	backdrop-filter: blur(10px);
	border-bottom: 1px solid var(--line);
}
.nav-row {
	display: flex;
	align-items: center;
	justify-content: space-between;
	height: 68px;
}
.brand {
	display: flex;
	align-items: center;
	gap: 12px;
	text-decoration: none;
	color: var(--ink);
}
.mark {
	width: 36px; height: 36px;
	border-radius: 10px;
	background: var(--blue-600);
	display: grid; place-items: center;
	color: white;
	font-family: 'Bricolage Grotesque', sans-serif;
	font-weight: 700;
	font-size: 18px;
	box-shadow: 0 6px 18px -8px var(--blue-700);
	overflow: visible;
}
.brand-name {
	font-family: 'Bricolage Grotesque', sans-serif;
	font-weight: 600;
	font-size: 18px;
	letter-spacing: -0.01em;
}
.nav-links {
	display: flex;
	gap: 32px;
	align-items: center;
}
.nav-links a:not(.btn-primary) {
	color: var(--ink-soft);
	text-decoration: none;
	font-size: 14px;
	font-weight: 500;
}
.nav-links a:hover { color: var(--blue-600); }
.btn {
	display: inline-flex;
	align-items: center;
	gap: 8px;
	padding: 11px 18px;
	border-radius: 10px;
	font-weight: 600;
	font-size: 14px;
	text-decoration: none;
	border: 1px solid transparent;
	cursor: pointer;
	transition: transform 0.12s ease, background 0.12s ease, box-shadow 0.12s ease;
	font-family: inherit;
}
.btn-primary {
	background: var(--blue-600);
	color: white;
	box-shadow: 0 8px 22px -10px var(--blue-700);
	white-space: nowrap;
}
.btn-primary:hover { background: var(--blue-700); transform: translateY(-1px); }
.btn-ghost {
	background: transparent;
	color: var(--ink);
	border: 1px solid var(--line);
}
.btn-ghost:hover { border-color: var(--blue-600); color: var(--blue-600); }

/* ---------- HERO ---------- */
.hero {
	padding: 88px 0 72px;
	position: relative;
	overflow: hidden;
}
.hero-grid {
	display: grid;
	grid-template-columns: 1.15fr 1fr;
	gap: 64px;
	align-items: center;
}
.eyebrow {
	display: inline-flex;
	align-items: center;
	gap: 8px;
	font-size: 12px;
	font-weight: 600;
	letter-spacing: 0.08em;
	text-transform: uppercase;
	color: var(--blue-700);
	background: var(--blue-50);
	padding: 6px 12px;
	border-radius: 999px;
}
.eyebrow .dot {
	width: 6px; height: 6px;
	background: var(--blue-600);
	border-radius: 50%;
}
h1 {
	font-size: clamp(44px, 5.5vw, 72px);
	margin: 20px 0 20px;
	text-wrap: balance;
}
h1 .accent { color: var(--blue-600); }
.lede {
	font-size: 18px;
	color: var(--ink-soft);
	max-width: 480px;
	text-wrap: pretty;
}
.hero-cta {
	margin-top: 32px;
	display: flex;
	gap: 12px;
	flex-wrap: wrap;
}
.hero-meta {
	margin-top: 40px;
	display: flex;
	gap: 28px;
	flex-wrap: wrap;
}
.meta-item {
	display: flex;
	flex-direction: column;
	gap: 2px;
}
.meta-num {
	font-family: 'Bricolage Grotesque', sans-serif;
	font-weight: 600;
	font-size: 24px;
	color: var(--ink);
	letter-spacing: -0.02em;
}
.meta-label {
	font-size: 12px;
	color: var(--ink-soft);
	font-weight: 500;
}

/* hero visual */
.hero-visual {
	position: relative;
	aspect-ratio: 4 / 5;
	border-radius: 20px;
	overflow: hidden;
	background: linear-gradient(135deg, var(--blue-700), var(--blue-900));
	box-shadow: 0 30px 60px -30px var(--blue-900);
}
.hero-visual::before {
	content: "";
	position: absolute; inset: 0;
	background-image:
		repeating-linear-gradient(45deg, transparent 0 18px, rgba(255,255,255,0.04) 18px 19px);
}
.speaker {
	position: absolute;
	inset: 0;
	display: grid; place-items: center;
}
.speaker svg { width: 70%; height: 70%; }
.hero-tag {
	position: absolute;
	left: 24px; bottom: 24px;
	font-family: 'JetBrains Mono', ui-monospace, monospace;
	font-size: 11px;
	color: rgba(255,255,255,0.7);
	letter-spacing: 0.05em;
}
.badge-float {
	position: absolute;
	top: 20px; right: 20px;
	background: rgba(255,255,255,0.95);
	color: var(--blue-700);
	padding: 8px 12px;
	border-radius: 999px;
	font-size: 12px;
	font-weight: 600;
	display: flex;
	align-items: center;
	gap: 6px;
}
.pulse {
	width: 8px; height: 8px;
	background: var(--blue-600);
	border-radius: 50%;
	box-shadow: 0 0 0 0 var(--blue-600);
	animation: pulse 1.8s infinite;
}
@keyframes pulse {
0% { box-shadow: 0 0 0 0 color-mix(in oklch, var(--blue-600) 50%, transparent); }
100% { box-shadow: 0 0 0 12px transparent; }
}

/* ---------- SERVICES ---------- */
section { padding: 72px 0; }
.section-head {
	margin-bottom: 40px;
	display: flex;
	align-items: end;
	justify-content: space-between;
	gap: 24px;
	flex-wrap: wrap;
}
.section-head h2 {
	font-size: clamp(32px, 3.5vw, 44px);
	margin: 8px 0 0;
}
.section-head p {
	color: var(--ink-soft);
	max-width: 380px;
	margin: 0;
	font-size: 15px;
}
.services {
	display: grid;
	grid-template-columns: repeat(3, 1fr);
	gap: 16px;
}
.service-card {
	padding: 28px;
	border: 1px solid var(--line);
	border-radius: var(--radius);
	background: var(--paper);
	transition: border-color 0.2s ease, transform 0.2s ease;
}
.service-card:hover {
	border-color: var(--blue-600);
	transform: translateY(-2px);
}
.service-icon {
	width: 44px; height: 44px;
	border-radius: 10px;
	background: var(--blue-50);
	color: var(--blue-700);
	display: grid; place-items: center;
	margin-bottom: 18px;
}
.service-card h3 {
	font-family: 'Bricolage Grotesque', sans-serif;
	font-size: 19px;
	margin: 0 0 6px;
	font-weight: 600;
	letter-spacing: -0.01em;
}
.service-card p {
	margin: 0;
	color: var(--ink-soft);
	font-size: 14px;
}

/* ---------- WORK ---------- */
.work-section {
	background: var(--paper-warm);
	border-top: 1px solid var(--line);
	border-bottom: 1px solid var(--line);
}
.work-grid {
	display: grid;
	grid-template-columns: 1fr 1fr;
	gap: 24px;
}
.work-item {
	border-radius: var(--radius);
	overflow: hidden;
	background: var(--paper);
	border: 1px solid var(--line);
}
.work-photo {
	/* aspect-ratio: 4 / 3; */
	position: relative;
	background:
		repeating-linear-gradient(135deg,
		oklch(0.93 0.01 260) 0 14px,
		oklch(0.95 0.008 260) 14px 28px);
	display: grid;
	place-items: center;
	color: oklch(0.45 0.01 260);
	font-family: 'JetBrains Mono', ui-monospace, monospace;
	font-size: 12px;
	letter-spacing: 0.04em;
}
.work-photo .swap {
	text-align: center;
	padding: 16px 22px;
	border: 1px dashed oklch(0.7 0.01 260);
	border-radius: 8px;
	background: rgba(255,255,255,0.6);
}
.work-photo .swap small {
	display: block;
	font-size: 10px;
	margin-top: 4px;
	opacity: 0.7;
}
.work-photo img {
	width: 100%;
	max-height: 400px;
	height: 100%;
	object-fit: cover;
}
.work-meta {
	padding: 22px 24px 24px;
	display: flex;
	justify-content: space-between;
	align-items: flex-start;
	gap: 16px;
}
.work-meta h3 {
	font-family: 'Bricolage Grotesque', sans-serif;
	font-size: 20px;
	margin: 0 0 4px;
	font-weight: 600;
	letter-spacing: -0.01em;
}
.work-meta p {
	margin: 0;
	color: var(--ink-soft);
	font-size: 14px;
}
.work-tag {
	font-size: 11px;
	font-weight: 600;
	color: var(--blue-700);
	background: var(--blue-50);
	padding: 5px 10px;
	border-radius: 999px;
	white-space: nowrap;
	flex-shrink: 0;
}

/* ---------- CTA ---------- */
.cta {
	padding: 72px 0;
}
.cta-card {
	background: linear-gradient(135deg, var(--blue-700), var(--blue-900));
	border-radius: 20px;
	padding: 56px 48px;
	color: white;
	display: grid;
	grid-template-columns: 1.4fr 1fr;
	gap: 32px;
	align-items: center;
	position: relative;
	overflow: hidden;
}
.cta-card::before {
	content: "";
	position: absolute;
	right: -80px; top: -80px;
	width: 320px; height: 320px;
	border-radius: 50%;
	background: radial-gradient(circle, color-mix(in oklch, var(--blue-500) 60%, transparent), transparent 70%);
}
.cta-card h2 {
	font-family: 'Bricolage Grotesque', sans-serif;
	font-size: clamp(28px, 3vw, 38px);
	margin: 0 0 12px;
	font-weight: 600;
	letter-spacing: -0.02em;
	text-wrap: balance;
}
.cta-card p {
	margin: 0;
	color: rgba(255,255,255,0.78);
	font-size: 16px;
	max-width: 480px;
}
.cta-actions {
	display: flex;
	flex-direction: column;
	gap: 10px;
	position: relative;
	z-index: 1;
}
.cta-actions .btn-primary {
	background: white;
	color: var(--blue-700);
	box-shadow: 0 12px 30px -12px rgba(0,0,0,0.4);
}
.cta-actions .btn-primary:hover { background: var(--blue-50); }
.cta-actions .btn-ghost {
	border-color: rgba(255,255,255,0.3);
	color: white;
}
.cta-actions .btn-ghost:hover { border-color: white; color: white; }
.cta-phone {
	font-family: 'Bricolage Grotesque', sans-serif;
	font-weight: 600;
	font-size: 22px;
	color: white;
	text-decoration: none;
	display: flex;
	align-items: center;
	gap: 10px;
	margin-top: 4px;
}

/* ---------- FOOTER ---------- */
footer {
	padding: 36px 0 48px;
	border-top: 1px solid var(--line);
	color: var(--ink-soft);
	font-size: 13px;
}
.foot-row {
	display: flex;
	justify-content: space-between;
	align-items: center;
	flex-wrap: wrap;
	gap: 16px;
}

/* ---------- responsive ---------- */
@media (max-width: 880px) {
	.hero { padding: 56px 0 48px; }
	.hero-grid { grid-template-columns: 1fr; gap: 40px; }
	.hero-visual { max-width: 380px; }
	.services { grid-template-columns: 1fr; }
	.work-grid { grid-template-columns: 1fr; }
	.cta-card { grid-template-columns: 1fr; padding: 40px 28px; }
	.nav-links a:not(.btn) { display: none; }
	section { padding: 56px 0; }
	.nav-row { padding: 40px 12px; }
}
</style>
