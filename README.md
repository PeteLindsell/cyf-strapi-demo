## Key things to note

This repository contains two packages

- Frontend built with Vite React
- Backend built with Strapi

## 🛠 Prerequisites

- Postgres for local development

## 🚀 Quick start

1. Create a Postgres database named `cyf`

2. Copy `/cms/.env.example` to `/cms/.env` and add database user details with access to `cyf` database created in step 1

3. Open frontend and backend folders in independent terminals

4. Install dependencies

```sh
npm install
```

5. Start the application in development mode

```sh
npm dev
```

If successfully you should find the following:

- Strapi CMS [localhost:1337/admin](http://localhost:1337/admin)
- Swagger docks [localhost:1337/documentation/v1.0.0](http://localhost:1337/documentation/v1.0.0)
- React frontend [localhost:3000](http://localhost:3000)
