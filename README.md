# Management

Interactive learning project for management fundamentals and decision-making.

> **Status:** Foundation v0.1. The current release provides the application shell and project infrastructure. Decision simulations, team/project scenarios, planning exercises, and risk tools are planned work.

**Live site:** https://inmersion-cs.github.io/Management/

## Learning focus

The project treats management as a set of choices made under constraints rather than a list of definitions. Planned areas include planning, organization, coordination, teams, projects, risk, decision-making, and evaluation of outcomes.

## Current implementation

The repository currently contains a React + TypeScript application shell with Management-specific routes and roadmap content, responsive keyboard-accessible navigation, automated type/lint/test/build checks, and GitHub Pages deployment.

## Roadmap

1. Planning
2. Organization
3. Decision making
4. Teams and risk
5. Interactive management scenarios

## Development

Node.js 22.13 or newer is required.

```bash
npm ci
npm run dev
```

Quality checks:

```bash
npm audit --audit-level=high
npm run typecheck
npm run lint
npm run test:run
npm run build
npm run format:check
```

## Contributing and accessibility

See [`CONTRIBUTING.md`](CONTRIBUTING.md). Keep feature claims accurate and preserve semantic HTML, keyboard operation, visible focus, touch-friendly controls, and reduced-motion behavior.

## License

MIT. See [`LICENSE`](LICENSE).
