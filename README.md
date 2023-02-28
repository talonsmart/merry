# Merry - ATS System Core in Node and React

This is an ATS system written in Node, Express on the server and React + Tailwind on the frontend with Docker containerization.

Its source code was reworked into the internal ATS system for CSAT Solutions. Although that is proprietary, the base it uses and all common functions are open for your own usage and is continuously updated.

## How to use

### Create the Database

1. Duplicate `env.example` and `.env.test.example` and rename to `.env` and `.env.test`
2. run `docker-compose up -d`

```bash
docker-compose up -d # start running containers
docker-compose down # shut-down running containers
docker-compose ps # list the current running containers
```

Then, just start it through NPM.

1. `npm run dev`
2. open `127.0.0.1:3000`

---

Created by Talon Smart
