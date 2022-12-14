# GraphQL API with Subscription and Authentication

A starter template that will help you to build a GraphQL server with authentication and subscription using Node.js, Express, Prisma(Postgres DB), GraphQL, Apollo Server, JWT, and GraphQL Subscriptions.

## Setup

1. Change Dir

   ```bash
   cd my-project
   ```

2. Create a `.env` file in the root directory and add the following environment variables:

   ```bash
    DATABASE_URL="postgresql://postgres:admin@localhost:5432/chat?schema=public"
    ALGO="HS256"
    SECRET_KEY="test"
   ```

3. Install Dependencies

   ```bash
   yarn install
   ```

4. Run Redis

   ```bash
   docker-compose up -d
   ```

5. Run Dev Server

   ```bash
   yarn dev
   ```

6. Build and Run Production Server

   ```bash
   yarn build

   yarn start
   ```
