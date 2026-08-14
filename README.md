# Management

Open-source interactive web learning environment for management fundamentals and decision-making.

> **Status:** Foundation v0.1. Decision simulations, team/project scenarios, planning exercises, and risk tools are roadmap items, not implemented features yet.

**Live site target:** https://inmersion-cs.github.io/Management/

## Why this project exists

Management concepts become more useful when they are applied to choices, constraints, people, resources, and consequences. This project will grow into a scenario-driven environment for that practice.

## Learning scope

Planned areas include management fundamentals, planning, organization, decision-making, coordination, teams, projects, risk, and reflective evaluation of choices.

## Current features

Foundation v0.1 supplies an accessible React + TypeScript shell, subject-specific routes and roadmap, dependency audit, tests, strict type checking, linting, production build, Pages automation, and open-source project files.

## Roadmap

1. Planning
2. Organization
3. Decision making
4. Teams and risk
5. Later: interactive management scenarios

## Development

Node.js 22.13+ is required.

```bash
npm ci
npm run dev
npm audit --audit-level=high
npm run typecheck
npm run lint
npm run test:run
npm run build
```

## Contributing and accessibility

See [`CONTRIBUTING.md`](CONTRIBUTING.md). Preserve semantic HTML, keyboard operation, visible focus, touch-friendly controls, reduced-motion behavior, and accurate feature claims.

## License

MIT. See [`LICENSE`](LICENSE).
