# turbo-pnpm-workspace-bug

### What
turborepo tries to build packages that are in node_modules when `pnpm-worspace.yaml` uses `packages/**` pattern

to test:
```bash
pnpm i
pnpm build
# see error as it tries to build vite utilities
```