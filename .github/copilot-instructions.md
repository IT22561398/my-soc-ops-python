## 🛠️ Mandatory Development Checklist

- [ ] Lint: python -m uv run ruff check .
- [ ] Build/Sync: python -m uv sync
- [ ] Test: python -m uv run pytest
- [ ] Start: python -m uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
- [ ] Open http://localhost:8000 in a full browser (never use VS Code Simple Browser)

---

## Workspace Conventions

- **Frontend**: Use custom CSS utilities from app/static/css/app.css. Avoid generic, “AI slop” design—be creative and context-specific.
- **Docs**: Main guides in README.md and workshop/. Contributing info in CONTRIBUTING.md.
- **General**: Never use the Simple Browser. Always link to docs, don’t duplicate.
- **Agent Customization**: No workspace-instructions.md—follow these conventions and loaded instructions.

---

## Design Guide

- **Theme**: Professional, corporate, clean blue with glassmorphism and chrome accents.
- **Background**: Use a deep blue gradient with a subtle diagonal pattern overlay for depth.
- **Cards/Containers**: Apply glassmorphism (frosted glass effect) with strong blur, soft borders, and gentle shadows. Use `.corp-card` and `.corp-glass` classes.
- **Typography**: Use the Inter font (or Segoe UI/Roboto/Open Sans fallback) for a modern, premium look. Headings use `.corp-heading`, subheadings use `.corp-subheading`.
- **Buttons**: Use animated blue gradients, soft drop shadows, and gentle hover/active effects. Use `.corp-btn` for all primary actions.
- **Accents**: Use chrome/metallic gradients only for highlights or accent borders, not as main backgrounds.
- **Spacing**: Favor generous padding, margin, and whitespace for a clean, uncluttered layout.
- **Hierarchy**: Use color, size, and shadow to create clear visual hierarchy and focus.
- **Accessibility**: Ensure color contrast is high, text is legible, and interactive elements are clearly indicated.
- **No AI Slop**: Avoid generic, default, or “AI” aesthetics. Every element should feel intentional and tailored to the app’s context.
- **Responsiveness**: All layouts and components must look great on both desktop and mobile.

See `app/static/css/corporate.css` for implementation details and utility classes.
