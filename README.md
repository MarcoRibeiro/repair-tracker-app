# Repair App Monorepo

Monorepo com:
- Next.js para frontend
- Nest.js para backend
- Turborepo para orquestração

## Scripts
```bash
pnpm install
pnpm dev       # inicia ambos os apps
pnpm build     # build completo
```

## Estrutura
- `apps/web`: Frontend com Next.js
- `apps/api`: Backend com Nest.js
- `packages/ui`: Componentes partilhados (opcional)