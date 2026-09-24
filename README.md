# Plain Voice

A quiet, typography-first WordPress theme designed for distraction-free reading, long-form writing, and architectural restraint. 

Deliberately minimal with zero JavaScript dependencies, **Plain Voice** treats the web browser as an extension of the printed page.

---

## Features

- **Typography-First Design:** Styled with fallback serif stacks (`Charter`, `Georgia`, `Cambria`) optimized for long-form legibility at `1.125rem`.
- **Zero JavaScript:** Built entirely on static CSS and PHP template functions for instant load times and complete simplicity.
- **Flat Layout Structure:** Direct top-to-bottom PHP template hierarchy without unnecessary nested template parts.
- **Accessibility Ready:** Includes standard keyboard navigation skip links, WCAG-compliant color contrast, and proper ARIA landmarks.
- **Single-Level Navigation:** Intentionally enforces a flat menu structure (`depth => 1`) to preserve simple site hierarchy.
- **Block Editor Support:** Enqueues the theme stylesheet directly into the WordPress block editor (`editor-styles`) so writing matches rendering.
- **Print & Reduced Motion Styles:** Built-in CSS media queries for printing clean pages and respecting user animation preferences.

---

## File Structure

```text
plain-voice/
├── style.css          # Theme metadata, design tokens, and core styling
├── functions.php      # Setup hooks, content width, excerpt rules, and asset enqueues
├── header.php         # Document head, site title, description, and primary menu
├── footer.php         # Content wrapper closing tags and colophon footer
├── index.php          # Main template fallback for index, archives, and search
├── single.php         # Single post view with category links and comment area
├── page.php           # Static page template
├── comments.php       # Comment list and response form structure
└── screenshot.png     # Theme preview thumbnail (1200×900 recommended)
