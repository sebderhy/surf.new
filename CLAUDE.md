# Surf Development Guidelines

## Build & Test Commands
- **Development**: `npm run dev` (Next.js + FastAPI)
- **Build**: `npm run build`
- **Lint**: `npm run lint`, `npm run lint:fix`
- **Test**: `npm run test`
- **Test specific file**: `npm run test:file -- path/to/file.test.tsx`
- **Test watch mode**: `npm run test:watch`
- **Python API dev**: `uv run python -m uvicorn api.index:app --reload`

## Code Style Guidelines
- **TypeScript**: Strict mode enabled with `tsconfig.json`
- **Formatting**: Prettier with 2-space indent, 100 char line width, double quotes
- **ESLint**: with Next.js, Prettier, and Tailwind plugins
- **Import ordering**: Required via `simple-import-sort` with specific grouping rules
- **Naming**: React components use PascalCase, files use camelCase
- **Commit messages**: Follow conventional commit format (feat, fix, chore, etc.)
- **React components**: Use functional components with hooks
- **CSS**: Tailwind with standard class ordering
- **Error handling**: Use try/catch blocks and proper error logging
- **API**: Python FastAPI with async function definitions