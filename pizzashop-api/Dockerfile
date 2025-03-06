FROM oven/bun:latest

WORKDIR /app

COPY . .

RUN bun install

CMD ["bun", "run", "src/db/migrate.ts", "&&", "bun", "run", "src/index.ts"]