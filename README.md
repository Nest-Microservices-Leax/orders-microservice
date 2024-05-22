# Orders MicroService

```
docker compose up -d
```

## Development steps

1. Clone repository
2. Create `.env` file based on file `.env.template`
3. Run database with `docker compose up -d`
4. Run Nast Server
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
5. Run project `npm run start:dev`