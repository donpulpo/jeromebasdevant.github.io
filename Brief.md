Build a single-page website for jeromebasdevant.com — my personal AI leadership advisory practice. It will be deployed as a GitHub Pages site.

The full website copy is in `content/Website Copy v2.md` (paste or place your markdown there). The hero photo is at `assets/jerome-basdevant.jpg`.

**Structure:** The copy has clear sections — follow them as the page structure: Hero → The Problem → What Changes When I Show Up → How I Work (three engagement tiers) → Track Record → Why Me → Principles → Fit → Let's Talk. Use the hero photo prominently in the top section.

**The photo and its tone:** Professional headshot on a warm beige/sand background. Blue-grey blazer, open collar, arms crossed — approachable authority. Confident but not corporate. The site's entire visual identity should feel like an extension of this photo: warm, grounded, direct.

**Design direction:**

- This is a person, not a firm. The design should feel like meeting someone sharp over coffee, not browsing a McKinsey landing page.
- Palette: warm sand/beige (`#E8DED1` range) as a background tone, slate/charcoal for text, and the blue-grey from the blazer (`#6B7B8D` range) as an accent. Use sparingly — the warmth does the work.
- Typography: Google Fonts — a serif with character for headings (e.g. DM Serif Display, Playfair Display), a clean sans for body (e.g. Inter, DM Sans). The type should feel like someone who writes well, not someone who hired a branding agency.
- Generous whitespace. Let the copy breathe — it's the main asset.
- The proof points (25 years, 2 SaaS platforms, etc.) should feel like a quiet flex, not a dashboard. Think inline or a simple horizontal row, not big flashy counters.
- The three engagement tiers (Diagnostic / Strategy / Embedded) should read as distinct cards or blocks with clear visual separation.

**Technical constraints:**

- Single HTML file with inline CSS. No build step, no frameworks, no React.
- Mobile-first, fully responsive.
- Semantic HTML, good heading hierarchy, proper alt text.
- Fast-loading — Google Fonts and the image are the only external dependencies.
- The CTA at the bottom is a mailto link to [jerome.basdevant@gmail.com](mailto:jerome.basdevant@gmail.com).
- Include a minimal favicon setup if easy.

**What to avoid:**

- No hamburger menus, no sticky navbars, no parallax, no animations beyond subtle hover states.
- No testimonials section, no blog section, no newsletter signup.
- Don't soften the copy — it's deliberately direct. Keep "what to kill" and "AI theatre" as-is.
- No stock illustrations or decorative SVGs. The photo and the typography do the visual work.
- No dark mode. The warm palette is the identity.