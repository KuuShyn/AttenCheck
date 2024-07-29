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

Pushing changes
```bash
git push -u origin master
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

Generate Prisma, Migrate and Seed
```bash
pnpm run prisma:generate

pnpm run migrate:dev

pnpm run seed
```
to run the server
```bash
pnpm run start:dev
```
