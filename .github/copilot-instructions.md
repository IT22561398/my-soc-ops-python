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
