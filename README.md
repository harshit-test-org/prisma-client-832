## Introduction

Reproduction for https://github.com/prisma/prisma-client-js/issues/832


## Steps

1. Clone the repository and run yarn or npm
2. Replace creds in prisma/.env and run npx prisma migrate save --experimental&& npx prisma migrate up --experimental
3. Run npm run start


## Version

```
@prisma/cli          : 2.7.0-dev.2
Current platform     : darwin
Query Engine         : query-engine d1dd8a0508dfc82ae8bd83d91159e0ac807593ec (at node_modules/@prisma/cli/query-engine-darwin)
Migration Engine     : migration-engine-cli d1dd8a0508dfc82ae8bd83d91159e0ac807593ec (at node_modules/@prisma/cli/migration-engine-darwin)
Introspection Engine : introspection-core d1dd8a0508dfc82ae8bd83d91159e0ac807593ec (at node_modules/@prisma/cli/introspection-engine-darwin)
Format Binary        : prisma-fmt d1dd8a0508dfc82ae8bd83d91159e0ac807593ec (at node_modules/@prisma/cli/prisma-fmt-darwin)
Studio               : 0.272.0
```
