<!-- BEGIN:nextjs-agent-rules -->

# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

# Commit Message Conventions

All commits in this repository MUST follow the [Conventional Commits](https://www.conventionalcommits.org/) specification with a **required scope**:

```text
<type>(<scope>): <short summary in present tense>
```

### Allowed Types
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc.)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `build`: Changes that affect the build system or external dependencies
- `ci`: Changes to CI configuration files and scripts
- `chore`: Other changes that don't modify `src` or test files
- `revert`: Reverts a previous commit

### Scopes
The scope is **mandatory** and must be in `kebab-case`. Recommended scopes include:
- `app` (general application structure, layouts, root configs)
- `ui` (UI components, styling, themes)
- `api` (API routes, data fetching, backend services)
- `auth` (authentication and authorization logic)
- `lyrics` (lyrics parsing, fetching, and display features)
- `player` (audio/media player playback controls)
- `config` (project configuration, tooling, linters, git hooks)
- `deps` (dependency updates)
- Or any descriptive kebab-case feature/module scope (e.g., `search`, `playlist-card`).

### Examples
- `feat(lyrics): add synchronized lyric scrolling`
- `fix(player): resolve audio stutter on track change`
- `chore(config): configure commitlint and husky git hooks`
- `docs(readme): add installation guide for bun`
