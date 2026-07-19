# Projet Node JS l3

1. Backend

```bash
cd projet-node-back
# Create .env file
PORT=5000
FRONTEND_URI=http://localhost:3000

DB_HOST=localhost
DB_USER=root
DB_PORT=3306
DB_PASSWORD=root
DB_NAME=projet_node

npm install
npm run dev
```

2. Frontend

```bash
cd projet-node-front

# Create .env file
NEXT_PUBLIC_API_URL=http://localhost:5000
NODE_ENV=development

npm install
npm run dev
```
