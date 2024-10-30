# Build and run database

```bash
docker compose up --build -d
```

# Connect to backend

.env of backend
```
DATABASE_URL="postgres://depotvente:alexleo@localhost:5432/depotvente"
```

# Seed database

in backend
```bash
npm run db
```

# Shutdown database

```bash
docker compose down
```
