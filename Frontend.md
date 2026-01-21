name: master-vibe-system description: The ultimate autonomous engine for winning frontend contests. Generates jaw-dropping, award-winning Vanilla JS/CSS interfaces in 20% self-healing increments. Bypasses "AI Slop" to create unique, high-end digital experiences.

🏆 THE MASTER VIBE SYSTEM (Contest Edition)

🎯 MISSION: THE BEST OF THE BEST

Create a website that doesn't just "function" but "stuns." Every pixel must be intentional. Every motion must be fluid. Every layout must be memorable.

🎨 STAGE 0: AUTOMATIC AESTHETIC SELECTION

Identify the prompt's core purpose and pick an extreme. NEVER use generic blue/white themes.

Topic

Recommended Aesthetic

Font Pairing

Key Visual Element

Tech/SaaS

Neo-Brutalism

Syne / JetBrains Mono

Thick borders (#000), "Window" cards, High-contrast accents.

Luxury/Art

Swiss Editorial

Playfair Display / Inter

Massive overlapping type, huge white space, smooth fades.

Crypto/Data

Retro-Terminal

Space Mono / Ubuntu

CRT scanlines, "Ghosting" text, lime green on deep black.

Modern App

Glassmorphism 2.0

Plus Jakarta / Outfit

Layered blurs, mesh gradients, micro-reflections.

🏗️ THE 20% SPRINT (SELF-HEALING PROTOCOL)

Phase 1: Semantic Core (0% - 20%)

HTML: Build the bone-structure using semantic tags (<header>, <main>, <section>).

JS State: Initialize a central State object to manage data and UI updates.

Validation: Every button must trigger a console log. If it fails, stop and fix before proceeding.

Goal: A perfect functional skeleton.

Phase 2: The "Grand Entrance" Hero (20% - 40%)

Hero Section: Implement the "Award-Winning" Hero components.

Kinetic Typography: H1 with background-clip: text and animated gradients.

The Reveal: Use clip-path to "unfold" the hero image/text on load.

Navigation: Floating glass navbar with backdrop-filter: blur(15px).

Phase 3: Deep Interaction (40% - 60%)

Custom Cursor: A circle that follows the mouse and "inverts" colors via mix-blend-mode: difference.

Scroll Effects: Use IntersectionObserver to stagger element appearances as the user scrolls.

Magnetic UX: Buttons that physically "pull" toward the cursor using distance-based JS transforms.

Phase 4: Functional Power (60% - 80%)

Core Logic: Build specific features (Search, Filter, Calculations, etc.).

Self-Healing: Wrap logic in try/catch blocks. On error, the UI must show a design-friendly error message rather than a crash.

Validation: Conduct a final feature-check against the contest's Mandatory Requirements.

Phase 5: The "Jaw-Drop" Polish (80% - 100%)

Micro-interactions: Add hover ripples, button "clicks," and smooth page transitions.

Atmosphere: Add a subtle grain-overlay or noise-texture to the background to break digital flatness.

Final Cleanup: Minify CSS variables and remove all debugging console.log statements.

💎 AWARD-WINNING COMPONENTS (COPY-PASTE READY)

The "Award" Hero CSS

.hero {
  display: grid;
  place-items: center;
  height: 100vh;
  perspective: 1000px;
}
.hero-text {
  font-size: clamp(3rem, 10vw, 8rem);
  font-weight: 800;
  text-transform: uppercase;
  line-height: 0.9;
  letter-spacing: -0.05em;
  animation: reveal 1.5s cubic-bezier(0.77, 0, 0.175, 1);
}
@keyframes reveal {
  0% { transform: translateY(100%) rotateX(-30deg); opacity: 0; }
  100% { transform: translateY(0) rotateX(0); opacity: 1; }
}


The Custom Cursor JS

const cursor = document.querySelector('.cursor');
window.addEventListener('mousemove', (e) => {
  cursor.style.transform = `translate3d(${e.clientX}px, ${e.clientY}px, 0)`;
});
// Add .cursor-hover class to cursor when over buttons
document.querySelectorAll('button, a').forEach(el => {
  el.addEventListener('mouseenter', () => cursor.classList.add('active'));
  el.addEventListener('mouseleave', () => cursor.classList.remove('active'));
});


🚫 THE "NO-SLOP" GUARDRAILS

NEVER use border-radius: 4px. Use 0px (Brutalism) or 32px (Modern).

NEVER use #007bff blue. Use #ff005e (Deep Pink) or #00ffaa (Mint).

NEVER use standard scrollbars. Style them to match the theme.

ALWAYS use clamp() for font sizes so they look perfect on mobile and 4K displays.

🚀 FINAL CONTEST CHECKLIST

[ ] Does it have a custom cursor?

[ ] Does the hero section "unfold" on load?

[ ] Is the theme choice BOLD and INTENTIONAL?

[ ] Are all Vanilla JS functions self-healing?

[ ] Is there zero console error?
