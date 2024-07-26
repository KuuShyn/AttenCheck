### When Cloning this repo

use the --recurse-submodules flag
```bash
git clone https://github.com/KuuShyn/AttenSys.git --recurse-submodules
```
Pulling changes
```bash
git pull --recurse-submodules
```
Updating Submodules
```bash
git submodule update --remote
```

&nbsp;
---

### For Frontend - Client

```bash
pnpm install
```
```bash
pnpm run dev
```

&nbsp;
---
### For Backend - Server
```node
pnpm install
```

Make sure you have docker installed.  
postgres is running on docker locally.
```bash
# to run
docker compose up -d 

# to stop
docker compose down 
```

Migrate Prisma Schemas and Seeds
```bash
pnpm run migrate:dev
```
to run the server
```bash
pnpm run start:dev
```
