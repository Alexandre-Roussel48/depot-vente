# Build database

```bash
docker build -t depot-vente .
```

# Run database

```bash
docker run -d depot-vente
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
