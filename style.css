/* ═══════════════════════════════════════════════════════════════════════
   THE E-COMMERCE LEGACY — style.css
   Premium dark luxury design system
═══════════════════════════════════════════════════════════════════════ */

/* ── DESIGN TOKENS ────────────────────────────────────────────────── */
:root {
  /* Color */
  --c-bg:           #080810;
  --c-bg-mid:       #0d0d18;
  --c-surface:      #0f0f1a;
  --c-surface-2:    #141420;
  --c-surface-3:    #1a1a28;
  --c-border:       rgba(255,255,255,0.07);
  --c-border-gold:  rgba(180,145,55,0.3);
  --c-border-gold-bright: rgba(180,145,55,0.7);

  --c-gold:         #b49137;
  --c-gold-light:   #d4b05a;
  --c-gold-bright:  #e8c86e;
  --c-gold-dim:     rgba(180,145,55,0.15);
  --c-gold-glow:    rgba(180,145,55,0.08);

  --c-white:        #f2efe8;
  --c-white-dim:    rgba(242,239,232,0.7);
  --c-white-muted:  rgba(242,239,232,0.4);
  --c-white-faint:  rgba(242,239,232,0.15);

  --c-accent-green: #4ec97a;
  --c-accent-blue:  #4a8cff;

  /* Typography */
  --f-serif:   'Cormorant Garamond', Georgia, serif;
  --f-sans:    'DM Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;

  /* Spacing */
  --sp-xs:   0.5rem;
  --sp-sm:   1rem;
  --sp-md:   1.5rem;
  --sp-lg:   2.5rem;
  --sp-xl:   4rem;
  --sp-2xl:  6rem;
  --sp-3xl:  8rem;

  /* Radii */
  --r-sm:   6px;
  --r-md:   12px;
  --r-lg:   20px;
  --r-xl:   32px;

  /* Transitions */
  --ease-out-expo:   cubic-bezier(0.19, 1, 0.22, 1);
  --ease-in-out:     cubic-bezier(0.4, 0, 0.2, 1);
  --t-fast:  0.15s;
  --t-med:   0.35s;
  --t-slow:  0.6s;

  /* Shadows */
  --shadow-sm:   0 2px 12px rgba(0,0,0,0.4);
  --shadow-md:   0 8px 32px rgba(0,0,0,0.5);
  --shadow-lg:   0 20px 60px rgba(0,0,0,0.6);
  --shadow-gold: 0 0 40px rgba(180,145,55,0.12);
  --shadow-gold-intense: 0 0 60px rgba(180,145,55,0.2), 0 0 20px rgba(180,145,55,0.1);

  /* Layout */
  --max-w: 1200px;
  --max-w-md: 900px;
}

/* ── RESET & BASE ─────────────────────────────────────────────────── */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html {
  font-size: 16px;
  scroll-behavior: smooth;
  -webkit-text-size-adjust: 100%;
}

body {
  background-color: var(--c-bg);
  color: var(--c-white);
  font-family: var(--f-sans);
  font-weight: 400;
  line-height: 1.65;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  overflow-x: hidden;
}

img { display: block; max-width: 100%; height: auto; }
a { color: inherit; text-decoration: none; }
button { background: none; border: none; cursor: pointer; font: inherit; color: inherit; }
ul { list-style: none; }

/* ── TYPOGRAPHY UTILITIES ─────────────────────────────────────────── */
.section-eyebrow {
  display: flex;
  align-items: center;
  gap: 12px;
  font-family: var(--f-sans);
  font-size: 0.72rem;
  font-weight: 500;
  letter-spacing: 0.16em;
  text-transform: uppercase;
  color: var(--c-gold);
  margin-bottom: var(--sp-md);
}
.section-eyebrow__line {
  display: block;
  width: 28px;
  height: 1px;
  background: var(--c-gold);
  opacity: 0.7;
  flex-shrink: 0;
}
.section-heading {
  font-family: var(--f-serif);
  font-size: clamp(2.8rem, 5vw, 4.2rem);
  font-weight: 400;
  line-height: 1.08;
  letter-spacing: -0.02em;
  color: var(--c-white);
  margin-bottom: var(--sp-md);
}
.section-heading em {
  font-style: italic;
  color: var(--c-gold-light);
}
.section-sub {
  font-size: 1.05rem;
  color: var(--c-white-dim);
  max-width: 520px;
  line-height: 1.7;
}

/* ── SCROLL REVEAL BASE ───────────────────────────────────────────── */
.reveal {
  opacity: 0;
  transform: translateY(32px);
  transition: opacity 0.7s var(--ease-out-expo), transform 0.7s var(--ease-out-expo);
}
.reveal.is-visible {
  opacity: 1;
  transform: none;
}

/* ═══════════════════════════════════════════════════════════════════
   NAVIGATION
═══════════════════════════════════════════════════════════════════ */
.nav {
  position: fixed;
  top: 0; left: 0; right: 0;
  z-index: 1000;
  padding: 0;
  transition: background var(--t-slow) var(--ease-out-expo),
              border-color var(--t-slow) var(--ease-out-expo),
              backdrop-filter var(--t-slow);
}
.nav.is-scrolled {
  background: rgba(8, 8, 16, 0.85);
  backdrop-filter: blur(24px) saturate(1.5);
  -webkit-backdrop-filter: blur(24px) saturate(1.5);
  border-bottom: 1px solid var(--c-border);
}
.nav__inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  max-width: var(--max-w);
  margin: 0 auto;
  padding: 0 2rem;
  height: 68px;
}
.nav__logo {
  display: flex;
  align-items: center;
  gap: 10px;
}
.nav__logo-mark {
  width: 34px;
  height: 34px;
  background: linear-gradient(135deg, var(--c-gold), var(--c-gold-dim));
  border: 1px solid var(--c-border-gold);
  border-radius: var(--r-sm);
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--f-serif);
  font-size: 0.9rem;
  font-weight: 600;
  color: var(--c-gold-bright);
}
.nav__logo-text {
  font-size: 0.88rem;
  font-weight: 500;
  color: var(--c-white-dim);
  letter-spacing: 0.02em;
}
.nav__right {
  display: flex;
  align-items: center;
  gap: 2rem;
}
.nav__link {
  font-size: 0.88rem;
  font-weight: 400;
  color: var(--c-white-muted);
  letter-spacing: 0.03em;
  transition: color var(--t-fast);
}
.nav__link:hover { color: var(--c-white); }
.nav__cta {
  font-size: 0.82rem;
  font-weight: 500;
  letter-spacing: 0.04em;
  padding: 9px 20px;
  background: var(--c-gold-dim);
  border: 1px solid var(--c-border-gold);
  border-radius: 40px;
  color: var(--c-gold-bright);
  transition: background var(--t-med), border-color var(--t-med), color var(--t-med), box-shadow var(--t-med);
}
.nav__cta:hover {
  background: rgba(180,145,55,0.22);
  border-color: var(--c-border-gold-bright);
  box-shadow: var(--shadow-gold);
  color: var(--c-gold-bright);
}
.nav__hamburger {
  display: none;
  flex-direction: column;
  gap: 5px;
  padding: 4px;
}
.nav__hamburger span {
  display: block;
  width: 22px;
  height: 1.5px;
  background: var(--c-white-dim);
  border-radius: 2px;
  transition: all var(--t-fast);
}
.nav__mobile {
  display: none;
  flex-direction: column;
  gap: 0;
  padding: 0 2rem 1.5rem;
  border-top: 1px solid var(--c-border);
}
.nav__mobile.is-open { display: flex; }
.nav__mobile-link {
  padding: 0.9rem 0;
  font-size: 0.95rem;
  color: var(--c-white-dim);
  border-bottom: 1px solid var(--c-border);
  transition: color var(--t-fast);
}
.nav__mobile-link:hover { color: var(--c-white); }
.nav__mobile-cta {
  margin-top: 1rem;
  padding: 0.9rem 1.2rem;
  background: var(--c-gold-dim);
  border: 1px solid var(--c-border-gold);
  border-radius: var(--r-md);
  color: var(--c-gold-bright);
  text-align: center;
  font-weight: 500;
}

/* ═══════════════════════════════════════════════════════════════════
   BUTTON STYLES
═══════════════════════════════════════════════════════════════════ */
.btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-family: var(--f-sans);
  font-size: 0.88rem;
  font-weight: 500;
  letter-spacing: 0.04em;
  padding: 14px 28px;
  border-radius: 50px;
  cursor: pointer;
  transition: all var(--t-med) var(--ease-out-expo);
  white-space: nowrap;
}
.btn--primary {
  background: linear-gradient(135deg, var(--c-gold), #9a7a2a);
  color: #0a0800;
  border: 1px solid transparent;
  box-shadow: 0 4px 24px rgba(180,145,55,0.2);
}
.btn--primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 40px rgba(180,145,55,0.35);
  background: linear-gradient(135deg, var(--c-gold-bright), var(--c-gold));
}
.btn--primary:active { transform: translateY(0); }
.btn--primary svg { transition: transform var(--t-fast); }
.btn--primary:hover svg { transform: translateX(3px); }

.btn--ghost {
  background: transparent;
  color: var(--c-white-dim);
  border: 1px solid var(--c-border);
}
.btn--ghost:hover {
  border-color: var(--c-white-faint);
  color: var(--c-white);
  background: var(--c-white-faint);
  transform: translateY(-2px);
}

/* ═══════════════════════════════════════════════════════════════════
   HERO SECTION
═══════════════════════════════════════════════════════════════════ */
.hero {
  position: relative;
  min-height: 100svh;
  display: flex;
  flex-direction: column;
  padding-top: 68px;
  overflow: hidden;
}

/* Ambient background */
.hero__bg {
  position: absolute;
  inset: 0;
  z-index: 0;
  pointer-events: none;
}
.hero__bg-orb {
  position: absolute;
  border-radius: 50%;
  filter: blur(80px);
  animation: orb-float 12s ease-in-out infinite;
}
.hero__bg-orb--1 {
  width: 600px; height: 600px;
  top: -200px; right: -100px;
  background: radial-gradient(circle, rgba(180,145,55,0.08) 0%, transparent 70%);
  animation-duration: 14s;
}
.hero__bg-orb--2 {
  width: 400px; height: 400px;
  top: 40%; left: -100px;
  background: radial-gradient(circle, rgba(74,140,255,0.05) 0%, transparent 70%);
  animation-duration: 18s;
  animation-delay: -6s;
}
.hero__bg-orb--3 {
  width: 300px; height: 300px;
  bottom: 10%; right: 20%;
  background: radial-gradient(circle, rgba(180,145,55,0.05) 0%, transparent 70%);
  animation-duration: 10s;
  animation-delay: -3s;
}
@keyframes orb-float {
  0%, 100% { transform: translate(0, 0) scale(1); }
  33%       { transform: translate(20px, -30px) scale(1.05); }
  66%       { transform: translate(-15px, 20px) scale(0.97); }
}

.hero__bg-grid {
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(rgba(255,255,255,0.025) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.025) 1px, transparent 1px);
  background-size: 80px 80px;
  mask-image: radial-gradient(ellipse 80% 60% at 50% 40%, black 0%, transparent 100%);
  -webkit-mask-image: radial-gradient(ellipse 80% 60% at 50% 40%, black 0%, transparent 100%);
}
.hero__bg-noise {
  position: absolute;
  inset: 0;
  opacity: 0.025;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)'/%3E%3C/svg%3E");
  background-size: 200px 200px;
}

/* Hero inner layout */
.hero__inner {
  position: relative;
  z-index: 1;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
  max-width: var(--max-w);
  margin: 0 auto;
  padding: 5rem 2rem 4rem;
  flex: 1;
}

/* Hero copy */
.hero__eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-size: 0.72rem;
  font-weight: 500;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--c-gold);
  margin-bottom: 1.5rem;
  opacity: 0;
  transform: translateY(16px);
}
.hero__eyebrow-dot {
  display: block;
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background: var(--c-gold);
  box-shadow: 0 0 8px var(--c-gold);
  animation: dot-pulse 2.5s ease-in-out infinite;
}
@keyframes dot-pulse {
  0%, 100% { box-shadow: 0 0 6px var(--c-gold); opacity: 1; }
  50%       { box-shadow: 0 0 14px var(--c-gold); opacity: 0.7; }
}

.hero__headline {
  font-family: var(--f-serif);
  font-size: clamp(3.5rem, 7vw, 5.8rem);
  font-weight: 400;
  line-height: 1.0;
  letter-spacing: -0.03em;
  color: var(--c-white);
  margin-bottom: 1.5rem;
  opacity: 0;
  transform: translateY(20px);
}
.hero__headline em {
  display: block;
  font-style: italic;
  color: var(--c-gold-light);
}

.hero__subheadline {
  font-size: 1.08rem;
  line-height: 1.75;
  color: var(--c-white-dim);
  max-width: 480px;
  margin-bottom: 2.5rem;
  opacity: 0;
  transform: translateY(20px);
}

.hero__meta {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  margin-bottom: 2.5rem;
  opacity: 0;
  transform: translateY(20px);
}
.hero__meta-item {
  display: flex;
  flex-direction: column;
  gap: 2px;
}
.hero__meta-num {
  font-family: var(--f-serif);
  font-size: 1.5rem;
  font-weight: 500;
  color: var(--c-gold-light);
  line-height: 1;
}
.hero__meta-label {
  font-size: 0.72rem;
  color: var(--c-white-muted);
  letter-spacing: 0.08em;
  text-transform: uppercase;
}
.hero__meta-divider {
  width: 1px;
  height: 32px;
  background: var(--c-border);
  flex-shrink: 0;
}

.hero__actions {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-bottom: 1.5rem;
  opacity: 0;
  transform: translateY(20px);
}

.hero__disclaimer {
  font-size: 0.78rem;
  color: var(--c-white-muted);
  opacity: 0;
}

/* Hero glass card */
.hero__card-wrap {
  position: relative;
  opacity: 0;
  transform: translateX(40px);
}
.hero__card {
  position: relative;
  background: rgba(15, 15, 26, 0.8);
  backdrop-filter: blur(32px) saturate(1.6);
  -webkit-backdrop-filter: blur(32px) saturate(1.6);
  border: 1px solid var(--c-border);
  border-top-color: rgba(255,255,255,0.1);
  border-radius: var(--r-xl);
  padding: 2rem;
  box-shadow: var(--shadow-lg), var(--shadow-gold);
  overflow: hidden;
}
.hero__card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 1px;
  background: linear-gradient(90deg, transparent, rgba(180,145,55,0.4), transparent);
}
.hero__card::after {
  content: '';
  position: absolute;
  inset: 0;
  border-radius: var(--r-xl);
  background: radial-gradient(ellipse 60% 40% at 70% 10%, rgba(180,145,55,0.05), transparent);
  pointer-events: none;
}

.hero__card-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1.75rem;
}
.hero__card-badge {
  font-size: 0.68rem;
  font-weight: 500;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--c-accent-green);
  background: rgba(78,201,122,0.1);
  border: 1px solid rgba(78,201,122,0.2);
  border-radius: 40px;
  padding: 4px 10px;
}
.hero__card-dots {
  display: flex;
  gap: 6px;
}
.hero__card-dots span {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--c-surface-3);
  border: 1px solid var(--c-border);
}

.hero__card-product {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 1.75rem;
  padding-bottom: 1.75rem;
  border-bottom: 1px solid var(--c-border);
}
.hero__card-product-icon {
  width: 48px;
  height: 48px;
  background: var(--c-surface-3);
  border: 1px solid var(--c-border-gold);
  border-radius: var(--r-md);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--c-gold);
  flex-shrink: 0;
}
.hero__card-product-name {
  font-family: var(--f-serif);
  font-size: 1.15rem;
  font-weight: 500;
  color: var(--c-white);
  line-height: 1.2;
}
.hero__card-product-by {
  font-size: 0.75rem;
  color: var(--c-white-muted);
  margin-top: 2px;
}

.hero__card-list {
  display: flex;
  flex-direction: column;
  gap: 12px;
  margin-bottom: 1.75rem;
  padding-bottom: 1.75rem;
  border-bottom: 1px solid var(--c-border);
}
.hero__card-item {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 0.9rem;
  color: var(--c-white-dim);
}
.hero__card-check {
  width: 20px;
  height: 20px;
  background: rgba(180,145,55,0.1);
  border: 1px solid var(--c-border-gold);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--c-gold);
  flex-shrink: 0;
}

.hero__card-price-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1rem;
}
.hero__card-price {
  display: flex;
  align-items: baseline;
  gap: 6px;
}
.hero__card-price-amount {
  font-family: var(--f-serif);
  font-size: 2rem;
  font-weight: 500;
  color: var(--c-gold-light);
  line-height: 1;
}
.hero__card-price-note {
  font-size: 0.78rem;
  color: var(--c-white-muted);
}
.hero__card-cta {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-size: 0.85rem;
  font-weight: 500;
  letter-spacing: 0.04em;
  padding: 11px 20px;
  background: linear-gradient(135deg, var(--c-gold), #9a7a2a);
  color: #050400;
  border-radius: 40px;
  transition: all var(--t-med) var(--ease-out-expo);
  box-shadow: 0 4px 20px rgba(180,145,55,0.2);
}
.hero__card-cta:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 32px rgba(180,145,55,0.35);
}

.hero__card-fine {
  font-size: 0.72rem;
  color: var(--c-white-muted);
  text-align: center;
  letter-spacing: 0.04em;
}

.hero__card-glow {
  position: absolute;
  top: -80px; right: -80px;
  width: 260px; height: 260px;
  background: radial-gradient(circle, rgba(180,145,55,0.12) 0%, transparent 70%);
  filter: blur(40px);
  pointer-events: none;
  z-index: -1;
  animation: orb-float 10s ease-in-out infinite;
}

/* Hero scroll indicator */
.hero__scroll {
  position: absolute;
  bottom: 2rem;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
  z-index: 1;
}
.hero__scroll-line {
  width: 1px;
  height: 40px;
  background: linear-gradient(to bottom, transparent, var(--c-gold));
  animation: scroll-line 2s ease-in-out infinite;
}
@keyframes scroll-line {
  0%   { transform: scaleY(0); transform-origin: top; }
  50%  { transform: scaleY(1); transform-origin: top; }
  51%  { transform: scaleY(1); transform-origin: bottom; }
  100% { transform: scaleY(0); transform-origin: bottom; }
}
.hero__scroll span {
  font-size: 0.65rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--c-white-muted);
}

/* ═══════════════════════════════════════════════════════════════════
   SOCIAL PROOF STRIP
═══════════════════════════════════════════════════════════════════ */
.proof-strip {
  position: relative;
  z-index: 1;
  border-top: 1px solid var(--c-border);
  border-bottom: 1px solid var(--c-border);
  background: rgba(13,13,24,0.6);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  padding: 1.2rem 2rem;
}
.proof-strip__inner {
  max-width: var(--max-w);
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1rem 2rem;
}
.proof-strip__item {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 0.8rem;
  color: var(--c-white-muted);
  letter-spacing: 0.04em;
}
.proof-strip__item svg { color: var(--c-gold); flex-shrink: 0; }
.proof-strip__dot {
  width: 3px; height: 3px;
  border-radius: 50%;
  background: var(--c-border);
  flex-shrink: 0;
}

/* ═══════════════════════════════════════════════════════════════════
   RESULTS SECTION
═══════════════════════════════════════════════════════════════════ */
.results {
  padding: var(--sp-3xl) 2rem;
  position: relative;
}
.results__inner {
  max-width: var(--max-w);
  margin: 0 auto;
}
.results__header {
  margin-bottom: var(--sp-2xl);
}

/* Result cards */
.results__grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}

.result-card {
  background: var(--c-surface);
  border: 1px solid var(--c-border);
  border-radius: var(--r-xl);
  overflow: hidden;
  transition: transform var(--t-slow) var(--ease-out-expo),
              box-shadow var(--t-slow) var(--ease-out-expo),
              border-color var(--t-slow);
  cursor: default;
}
.result-card:hover {
  transform: translateY(-8px) scale(1.01);
  box-shadow: var(--shadow-lg), var(--shadow-gold);
  border-color: var(--c-border-gold);
}

.result-card__image-wrap {
  position: relative;
  overflow: hidden;
}
.result-card__image-frame {
  aspect-ratio: 16/9;
  overflow: hidden;
  position: relative;
}
.result-card__image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.8s var(--ease-out-expo);
  filter: brightness(0.9) saturate(1.1);
}
.result-card:hover .result-card__image {
  transform: scale(1.04);
}
.result-card__image-overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(
    to bottom,
    transparent 50%,
    rgba(8,8,16,0.7) 100%
  );
}
.result-card__image-label {
  position: absolute;
  top: 14px; right: 14px;
  font-size: 0.68rem;
  font-weight: 500;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--c-gold);
  background: rgba(8,8,16,0.7);
  border: 1px solid var(--c-border-gold);
  border-radius: 40px;
  padding: 4px 10px;
  backdrop-filter: blur(8px);
  -webkit-backdrop-filter: blur(8px);
}

.result-card__body {
  padding: 1.75rem;
}
.result-card__tag {
  display: inline-block;
  font-size: 0.68rem;
  font-weight: 500;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--c-gold);
  margin-bottom: 0.75rem;
}
.result-card__title {
  font-family: var(--f-serif);
  font-size: 1.5rem;
  font-weight: 500;
  color: var(--c-white);
  margin-bottom: 0.75rem;
  line-height: 1.2;
}
.result-card__desc {
  font-size: 0.9rem;
  color: var(--c-white-dim);
  line-height: 1.7;
  margin-bottom: 1.25rem;
}
.result-card__stat {
  display: flex;
  align-items: baseline;
  gap: 8px;
  padding-top: 1rem;
  border-top: 1px solid var(--c-border);
}
.result-card__stat-num {
  font-family: var(--f-serif);
  font-size: 1.6rem;
  font-weight: 500;
  color: var(--c-gold-light);
  line-height: 1;
}
.result-card__stat-label {
  font-size: 0.75rem;
  color: var(--c-white-muted);
  text-transform: uppercase;
  letter-spacing: 0.1em;
}

/* ═══════════════════════════════════════════════════════════════════
   FEATURES SECTION
═══════════════════════════════════════════════════════════════════ */
.features {
  position: relative;
  padding: var(--sp-3xl) 2rem;
  overflow: hidden;
}
.features__bg {
  position: absolute;
  inset: 0;
  pointer-events: none;
}
.features__bg-orb {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 700px; height: 500px;
  background: radial-gradient(ellipse, rgba(180,145,55,0.04) 0%, transparent 70%);
  filter: blur(60px);
}
.features__inner {
  position: relative;
  z-index: 1;
  max-width: var(--max-w);
  margin: 0 auto;
}
.features__header {
  margin-bottom: var(--sp-2xl);
}

.features__grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
}

.feature-card {
  position: relative;
  background: rgba(15,15,26,0.7);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border: 1px solid var(--c-border);
  border-radius: var(--r-lg);
  padding: 2rem;
  overflow: hidden;
  transition:
    transform var(--t-slow) var(--ease-out-expo),
    border-color var(--t-slow),
    box-shadow var(--t-slow);
  cursor: default;
}
.feature-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 1px;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.08), transparent);
}
.feature-card::after {
  content: '';
  position: absolute;
  bottom: -60px; left: 50%;
  transform: translateX(-50%);
  width: 120px; height: 120px;
  background: radial-gradient(circle, rgba(180,145,55,0.06), transparent);
  filter: blur(20px);
  opacity: 0;
  transition: opacity var(--t-slow);
  pointer-events: none;
}
.feature-card:hover {
  transform: translateY(-6px);
  border-color: var(--c-border-gold);
  box-shadow: 0 20px 60px rgba(0,0,0,0.4), var(--shadow-gold);
}
.feature-card:hover::after { opacity: 1; }

.feature-card--center {
  background: rgba(20,15,10,0.8);
}
.feature-card--center::before {
  background: linear-gradient(90deg, transparent, rgba(180,145,55,0.2), transparent);
}

.feature-card__icon-wrap {
  width: 52px; height: 52px;
  background: var(--c-surface-3);
  border: 1px solid var(--c-border);
  border-radius: var(--r-md);
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1.5rem;
  transition: border-color var(--t-med), transform var(--t-med);
}
.feature-card:hover .feature-card__icon-wrap {
  border-color: var(--c-border-gold);
  transform: scale(1.05);
}
.feature-card__icon { font-size: 1.4rem; line-height: 1; }

.feature-card__title {
  font-family: var(--f-serif);
  font-size: 1.45rem;
  font-weight: 500;
  color: var(--c-white);
  margin-bottom: 0.75rem;
  line-height: 1.2;
}
.feature-card__desc {
  font-size: 0.9rem;
  color: var(--c-white-dim);
  line-height: 1.7;
  flex: 1;
}
.feature-card__footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 1.75rem;
  padding-top: 1rem;
  border-top: 1px solid var(--c-border);
}
.feature-card__num {
  font-family: var(--f-serif);
  font-size: 0.75rem;
  color: var(--c-white-muted);
  letter-spacing: 0.08em;
}
.feature-card__arrow {
  color: var(--c-gold);
  opacity: 0;
  transform: translateX(-6px);
  transition: all var(--t-med) var(--ease-out-expo);
}
.feature-card:hover .feature-card__arrow {
  opacity: 1;
  transform: none;
}

/* ═══════════════════════════════════════════════════════════════════
   OFFER SECTION
═══════════════════════════════════════════════════════════════════ */
.offer {
  padding: var(--sp-3xl) 2rem;
  position: relative;
  border-top: 1px solid var(--c-border);
}
.offer__inner {
  max-width: var(--max-w);
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 5rem;
  align-items: center;
}

/* Offer left */
.offer__heading {
  font-family: var(--f-serif);
  font-size: clamp(2.8rem, 5vw, 4rem);
  font-weight: 400;
  line-height: 1.1;
  letter-spacing: -0.02em;
  color: var(--c-white);
  margin-bottom: 2.5rem;
}
.offer__heading em {
  font-style: italic;
  color: var(--c-gold-light);
}

.offer__list {
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
  margin-bottom: 2rem;
}
.offer__list-item {
  display: flex;
  align-items: flex-start;
  gap: 12px;
}
.offer__list-check {
  width: 22px;
  height: 22px;
  background: rgba(180,145,55,0.1);
  border: 1px solid var(--c-border-gold);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--c-gold);
  flex-shrink: 0;
  margin-top: 1px;
}
.offer__list-item strong {
  display: block;
  font-weight: 500;
  font-size: 0.95rem;
  color: var(--c-white);
  margin-bottom: 2px;
}
.offer__list-item span {
  font-size: 0.85rem;
  color: var(--c-white-muted);
  line-height: 1.6;
}

.offer__guarantee {
  font-size: 0.82rem;
  color: var(--c-white-muted);
  padding: 12px 16px;
  background: var(--c-surface-2);
  border: 1px solid var(--c-border);
  border-radius: var(--r-md);
  border-left: 2px solid var(--c-gold);
}

/* Offer card */
.offer__card {
  background: rgba(15,15,26,0.9);
  backdrop-filter: blur(32px);
  -webkit-backdrop-filter: blur(32px);
  border: 1px solid var(--c-border);
  border-top-color: rgba(255,255,255,0.1);
  border-radius: var(--r-xl);
  padding: 2rem;
  box-shadow: var(--shadow-lg), var(--shadow-gold);
  position: relative;
  overflow: hidden;
}
.offer__card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 1px;
  background: linear-gradient(90deg, transparent, rgba(180,145,55,0.5), transparent);
}

.offer__card-top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1.75rem;
  padding-bottom: 1.75rem;
  border-bottom: 1px solid var(--c-border);
}
.offer__card-product {
  display: flex;
  align-items: center;
  gap: 10px;
}
.offer__card-product-icon {
  width: 40px; height: 40px;
  background: var(--c-surface-3);
  border: 1px solid var(--c-border-gold);
  border-radius: var(--r-sm);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--c-gold);
  flex-shrink: 0;
}
.offer__card-product-name {
  font-family: var(--f-serif);
  font-size: 1rem;
  font-weight: 500;
  color: var(--c-white);
  line-height: 1.2;
}
.offer__card-product-author {
  font-size: 0.72rem;
  color: var(--c-white-muted);
  margin-top: 2px;
}
.offer__card-price-tag {
  font-family: var(--f-serif);
  font-size: 1.4rem;
  font-weight: 500;
  color: var(--c-gold-light);
  flex-shrink: 0;
}

/* Form elements */
.offer__card-form { display: flex; flex-direction: column; gap: 1rem; }
.offer__form-label {
  display: block;
  font-size: 0.78rem;
  font-weight: 500;
  color: var(--c-white-muted);
  letter-spacing: 0.06em;
  margin-bottom: 6px;
}
.offer__input-wrap { position: relative; }
.offer__input {
  width: 100%;
  background: var(--c-surface-2);
  border: 1px solid var(--c-border);
  border-radius: var(--r-md);
  padding: 12px 16px;
  font-family: var(--f-sans);
  font-size: 0.92rem;
  color: var(--c-white);
  outline: none;
  transition: border-color var(--t-fast), box-shadow var(--t-fast);
  -webkit-appearance: none;
}
.offer__input::placeholder { color: var(--c-white-muted); }
.offer__input:focus {
  border-color: var(--c-gold);
  box-shadow: 0 0 0 3px rgba(180,145,55,0.12);
}
.offer__input-focus-ring {
  position: absolute;
  inset: -2px;
  border-radius: calc(var(--r-md) + 2px);
  border: 2px solid var(--c-gold);
  opacity: 0;
  pointer-events: none;
  transition: opacity var(--t-fast);
}
.offer__input:focus ~ .offer__input-focus-ring { opacity: 0.4; }

.offer__submit {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  padding: 14px 24px;
  background: linear-gradient(135deg, var(--c-gold), #9a7a2a);
  color: #050400;
  font-family: var(--f-sans);
  font-size: 0.88rem;
  font-weight: 500;
  letter-spacing: 0.04em;
  border-radius: 50px;
  transition: all var(--t-med) var(--ease-out-expo);
  box-shadow: 0 4px 24px rgba(180,145,55,0.2);
  cursor: pointer;
}
.offer__submit:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 40px rgba(180,145,55,0.35);
  background: linear-gradient(135deg, var(--c-gold-bright), var(--c-gold));
}

.offer__card-trust {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  margin-top: 1.25rem;
  padding-top: 1.25rem;
  border-top: 1px solid var(--c-border);
}
.offer__trust-item {
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 0.72rem;
  color: var(--c-white-muted);
}
.offer__trust-item svg { color: var(--c-gold); flex-shrink: 0; }

/* ═══════════════════════════════════════════════════════════════════
   FOOTER
═══════════════════════════════════════════════════════════════════ */
.footer {
  border-top: 1px solid var(--c-border);
  padding: var(--sp-xl) 2rem var(--sp-lg);
  background: rgba(6,6,10,0.8);
}
.footer__inner {
  max-width: var(--max-w);
  margin: 0 auto;
}
.footer__top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 2rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid var(--c-border);
}
.footer__brand {
  display: flex;
  align-items: center;
  gap: 10px;
}
.footer__logo-mark {
  width: 32px; height: 32px;
  background: linear-gradient(135deg, var(--c-gold-dim), transparent);
  border: 1px solid var(--c-border-gold);
  border-radius: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--f-serif);
  font-size: 0.85rem;
  font-weight: 600;
  color: var(--c-gold);
}
.footer__logo-text {
  font-size: 0.85rem;
  color: var(--c-white-muted);
}
.footer__nav {
  display: flex;
  gap: 2rem;
}
.footer__link {
  font-size: 0.82rem;
  color: var(--c-white-muted);
  transition: color var(--t-fast);
}
.footer__link:hover { color: var(--c-white); }
.footer__bottom {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}
.footer__copy {
  font-size: 0.82rem;
  color: var(--c-white-muted);
}
.footer__disclaimer {
  font-size: 0.72rem;
  color: rgba(242,239,232,0.25);
  max-width: 600px;
  line-height: 1.6;
}

/* ═══════════════════════════════════════════════════════════════════
   CHECKOUT PAGE
═══════════════════════════════════════════════════════════════════ */
.checkout-page { min-height: 100svh; }

/* Checkout BG */
.co-bg {
  position: fixed;
  inset: 0;
  z-index: 0;
  pointer-events: none;
  overflow: hidden;
}
.co-bg__orb {
  position: absolute;
  border-radius: 50%;
  filter: blur(100px);
}
.co-bg__orb--1 {
  width: 500px; height: 500px;
  top: -100px; right: -100px;
  background: radial-gradient(circle, rgba(180,145,55,0.06), transparent 70%);
  animation: orb-float 16s ease-in-out infinite;
}
.co-bg__orb--2 {
  width: 400px; height: 400px;
  bottom: -50px; left: -50px;
  background: radial-gradient(circle, rgba(74,140,255,0.04), transparent 70%);
  animation: orb-float 20s ease-in-out infinite reverse;
}
.co-bg__noise {
  position: absolute;
  inset: 0;
  opacity: 0.02;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)'/%3E%3C/svg%3E");
}

/* Checkout header */
.co-header {
  position: relative;
  z-index: 10;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 2rem;
  height: 64px;
  border-bottom: 1px solid var(--c-border);
  background: rgba(8,8,16,0.7);
  backdrop-filter: blur(24px);
  -webkit-backdrop-filter: blur(24px);
}
.co-header__back {
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 0.82rem;
  color: var(--c-white-muted);
  transition: color var(--t-fast);
}
.co-header__back:hover { color: var(--c-white); }
.co-header__brand {
  display: flex;
  align-items: center;
  gap: 8px;
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
}
.co-header__logo-mark {
  width: 30px; height: 30px;
  background: var(--c-gold-dim);
  border: 1px solid var(--c-border-gold);
  border-radius: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--f-serif);
  font-size: 0.8rem;
  color: var(--c-gold-bright);
}
.co-header__logo-text {
  font-size: 0.82rem;
  color: var(--c-white-dim);
}
.co-header__secure {
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 0.72rem;
  color: var(--c-white-muted);
}
.co-header__secure svg { color: var(--c-accent-green); }

/* Checkout main layout */
.co-main {
  position: relative;
  z-index: 1;
  min-height: calc(100svh - 64px);
  display: flex;
  align-items: flex-start;
  padding: 3rem 2rem 4rem;
}
.co-layout {
  display: grid;
  grid-template-columns: 420px 1fr;
  gap: 3rem;
  max-width: 1000px;
  margin: 0 auto;
  width: 100%;
  align-items: start;
}

/* Order Summary */
.co-summary {
  background: var(--c-surface);
  border: 1px solid var(--c-border);
  border-radius: var(--r-xl);
  padding: 2rem;
  position: sticky;
  top: 90px;
}
.co-summary__product {
  display: flex;
  align-items: center;
  gap: 14px;
  margin-bottom: 1.5rem;
}
.co-summary__product-image {
  width: 56px; height: 56px;
  background: var(--c-surface-3);
  border: 1px solid var(--c-border-gold);
  border-radius: var(--r-md);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--c-gold);
  flex-shrink: 0;
}
.co-summary__product-name {
  font-family: var(--f-serif);
  font-size: 1.1rem;
  font-weight: 500;
  color: var(--c-white);
}
.co-summary__product-author {
  font-size: 0.78rem;
  color: var(--c-white-muted);
  margin-top: 2px;
}
.co-summary__product-type {
  font-size: 0.68rem;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--c-gold);
  margin-top: 3px;
}
.co-summary__divider {
  height: 1px;
  background: var(--c-border);
  margin: 1.25rem 0;
}
.co-summary__includes {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.co-summary__include-item {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 0.82rem;
  color: var(--c-white-dim);
}
.co-summary__include-item svg { color: var(--c-gold); flex-shrink: 0; }
.co-summary__totals {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.co-summary__line {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 0.85rem;
  color: var(--c-white-muted);
}
.co-summary__line--total {
  font-weight: 500;
  color: var(--c-white);
  font-size: 0.95rem;
  padding-top: 10px;
  border-top: 1px solid var(--c-border);
}
.co-summary__total-price {
  font-family: var(--f-serif);
  font-size: 1.3rem;
  color: var(--c-gold-light);
}
.co-summary__badge {
  margin-top: 1.25rem;
  padding: 12px;
  background: var(--c-surface-2);
  border-radius: var(--r-md);
  border: 1px solid var(--c-border);
}
.co-summary__badge-row {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}
.co-summary__badge-item {
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 0.72rem;
  color: var(--c-white-muted);
}
.co-summary__badge-item svg { color: var(--c-gold); flex-shrink: 0; }

/* Form section */
.co-form-section { display: flex; flex-direction: column; gap: 1.5rem; }
.co-form-card {
  background: rgba(15,15,26,0.9);
  backdrop-filter: blur(32px);
  -webkit-backdrop-filter: blur(32px);
  border: 1px solid var(--c-border);
  border-radius: var(--r-xl);
  padding: 2.5rem;
  position: relative;
  overflow: hidden;
}
.co-form-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 1px;
  background: linear-gradient(90deg, transparent, rgba(180,145,55,0.3), transparent);
}
.co-form-heading {
  font-family: var(--f-serif);
  font-size: 1.7rem;
  font-weight: 400;
  color: var(--c-white);
  margin-bottom: 4px;
}
.co-form-sub {
  font-size: 0.88rem;
  color: var(--c-white-muted);
  margin-bottom: 2rem;
}
.co-form { display: flex; flex-direction: column; gap: 1.75rem; }
.co-form-group { display: flex; flex-direction: column; gap: 1rem; }
.co-form-section-title {
  font-size: 0.75rem;
  font-weight: 500;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--c-white-muted);
  display: flex;
  align-items: center;
  gap: 8px;
}
.co-form-section-badge {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  font-size: 0.68rem;
  letter-spacing: 0.08em;
  color: var(--c-accent-green);
  background: rgba(78,201,122,0.08);
  border: 1px solid rgba(78,201,122,0.2);
  border-radius: 4px;
  padding: 2px 7px;
  font-weight: 400;
  text-transform: none;
}

/* Form fields */
.co-field-wrap { display: flex; flex-direction: column; gap: 6px; }
.co-field-label {
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 0.78rem;
  font-weight: 500;
  color: var(--c-white-muted);
  letter-spacing: 0.04em;
}
.co-field-help {
  display: flex;
  align-items: center;
  color: var(--c-white-muted);
  opacity: 0.5;
  transition: opacity var(--t-fast);
  cursor: help;
}
.co-field-help:hover { opacity: 1; }
.co-field-input-wrap {
  position: relative;
}
.co-field-input-wrap--card {
  display: flex;
  align-items: center;
}
.co-field-card-icon {
  position: absolute;
  left: 12px;
  color: var(--c-white-muted);
  pointer-events: none;
  z-index: 1;
}
.co-field-input--pad-card { padding-left: 48px !important; }
.co-field-input {
  width: 100%;
  background: var(--c-surface-2);
  border: 1px solid var(--c-border);
  border-radius: var(--r-md);
  padding: 13px 16px;
  font-family: var(--f-sans);
  font-size: 0.92rem;
  color: var(--c-white);
  outline: none;
  transition: border-color var(--t-fast), box-shadow var(--t-fast), background var(--t-fast);
  -webkit-appearance: none;
}
.co-field-input::placeholder { color: rgba(242,239,232,0.25); }
.co-field-input:focus {
  border-color: var(--c-gold);
  background: var(--c-surface-3);
  box-shadow: 0 0 0 3px rgba(180,145,55,0.1);
}
.co-field-input.is-invalid {
  border-color: #e55;
  box-shadow: 0 0 0 3px rgba(230,80,80,0.1);
}
.co-field-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}
.co-field-focus-ring {
  position: absolute;
  inset: -1px;
  border-radius: calc(var(--r-md) + 1px);
  border: 1px solid var(--c-gold);
  opacity: 0;
  pointer-events: none;
  transition: opacity var(--t-fast);
}

/* Submit button */
.co-submit {
  width: 100%;
  padding: 16px 24px;
  background: linear-gradient(135deg, var(--c-gold), #9a7a2a);
  color: #050400;
  border-radius: 50px;
  font-family: var(--f-sans);
  font-weight: 500;
  font-size: 0.92rem;
  letter-spacing: 0.04em;
  cursor: pointer;
  transition: all var(--t-med) var(--ease-out-expo);
  box-shadow: 0 4px 28px rgba(180,145,55,0.2);
  border: none;
  position: relative;
  overflow: hidden;
  margin-top: 0.5rem;
}
.co-submit::before {
  content: '';
  position: absolute;
  inset: 0;
  background: rgba(255,255,255,0.15);
  transform: translateX(-100%) skewX(-12deg);
  transition: transform 0.6s var(--ease-out-expo);
}
.co-submit:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 44px rgba(180,145,55,0.4);
  background: linear-gradient(135deg, var(--c-gold-bright), var(--c-gold));
}
.co-submit:hover::before { transform: translateX(120%) skewX(-12deg); }
.co-submit:active { transform: translateY(0); }
.co-submit.is-loading { pointer-events: none; opacity: 0.8; }
.co-submit__inner {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  position: relative;
  z-index: 1;
}
.co-submit__loading { display: none; }
.co-submit.is-loading .co-submit__text { opacity: 0; }
.co-submit.is-loading .co-submit__icon { display: none; }
.co-submit.is-loading .co-submit__loading { display: flex; position: absolute; }
.co-submit__spinner {
  width: 20px; height: 20px;
  border: 2px solid rgba(0,0,0,0.2);
  border-top-color: #050400;
  border-radius: 50%;
  animation: spin 0.7s linear infinite;
}
@keyframes spin {
  to { transform: rotate(360deg); }
}

.co-form-legal {
  font-size: 0.72rem;
  color: var(--c-white-muted);
  line-height: 1.7;
  text-align: center;
}
.co-form-legal-link {
  color: var(--c-gold);
  border-bottom: 1px solid transparent;
  transition: border-color var(--t-fast);
}
.co-form-legal-link:hover { border-bottom-color: var(--c-gold); }

/* Trust row */
.co-trust-row {
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
  justify-content: center;
  padding: 0 1rem;
}
.co-trust-item {
  display: flex;
  align-items: center;
  gap: 7px;
  font-size: 0.75rem;
  color: var(--c-white-muted);
}
.co-trust-item svg { color: var(--c-gold); }

/* Success overlay */
.co-success {
  position: fixed;
  inset: 0;
  z-index: 1000;
  background: rgba(8,8,16,0.95);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 2rem;
}
.co-success[hidden] { display: none; }
.co-success__card {
  background: var(--c-surface);
  border: 1px solid var(--c-border-gold);
  border-radius: var(--r-xl);
  padding: 3rem;
  text-align: center;
  max-width: 440px;
  box-shadow: var(--shadow-lg), var(--shadow-gold-intense);
}
.co-success__icon {
  width: 72px; height: 72px;
  background: rgba(180,145,55,0.1);
  border: 1px solid var(--c-border-gold);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 1.5rem;
  color: var(--c-gold);
}
.co-success__heading {
  font-family: var(--f-serif);
  font-size: 2.5rem;
  font-weight: 400;
  color: var(--c-white);
  margin-bottom: 0.75rem;
}
.co-success__sub {
  font-size: 0.92rem;
  color: var(--c-white-dim);
  line-height: 1.7;
  margin-bottom: 2rem;
}
.co-success__cta {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 12px 24px;
  border: 1px solid var(--c-border);
  border-radius: 40px;
  font-size: 0.85rem;
  color: var(--c-white-dim);
  transition: all var(--t-med);
}
.co-success__cta:hover {
  border-color: var(--c-border-gold);
  color: var(--c-gold);
}

/* ═══════════════════════════════════════════════════════════════════
   RESPONSIVE — TABLET
═══════════════════════════════════════════════════════════════════ */
@media (max-width: 1100px) {
  .hero__inner {
    grid-template-columns: 1fr;
    gap: 3rem;
    padding: 4rem 2rem 3rem;
  }
  .hero__copy { max-width: 600px; }
  .hero__card-wrap { max-width: 480px; }
  .results__grid { grid-template-columns: 1fr; max-width: 600px; }
  .features__grid { grid-template-columns: 1fr 1fr; }
  .offer__inner { grid-template-columns: 1fr; gap: 3rem; }
  .co-layout { grid-template-columns: 1fr; max-width: 560px; }
  .co-summary { position: static; order: -1; }
}

@media (max-width: 768px) {
  :root {
    --sp-2xl: 4rem;
    --sp-3xl: 5rem;
  }
  .nav__right { display: none; }
  .nav__hamburger { display: flex; }
  .nav.mobile-open .nav__mobile { display: flex; }
  .features__grid { grid-template-columns: 1fr; }
  .hero__meta { flex-wrap: wrap; gap: 1rem; }
  .hero__actions { flex-direction: column; align-items: flex-start; }
  .co-main { padding: 2rem 1rem 3rem; }
  .co-form-card { padding: 1.75rem; }
  .co-field-row { grid-template-columns: 1fr; }
  .footer__top { flex-direction: column; gap: 1.5rem; align-items: flex-start; }
  .footer__nav { flex-wrap: wrap; gap: 1rem; }
  .proof-strip__dot { display: none; }
  .co-trust-row { gap: 1rem; }
}

@media (max-width: 480px) {
  .hero__headline { font-size: 3rem; }
  .section-heading { font-size: 2.4rem; }
  .offer__heading { font-size: 2.4rem; }
  .results__grid { grid-template-columns: 1fr; }
  .nav__inner { padding: 0 1.25rem; }
  .co-layout { max-width: 100%; }
}

/* ═══════════════════════════════════════════════════════════════════
   ULTRA-WIDE
═══════════════════════════════════════════════════════════════════ */
@media (min-width: 1600px) {
  :root { --max-w: 1360px; }
  .hero__headline { font-size: 6.5rem; }
}
