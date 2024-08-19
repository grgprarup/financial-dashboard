## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Development

### Install Dependencies

```bash
pnpm install
```

### Environment Variables
Copy the `.env.example` file to `.env` and update the values from database.

```env
POSTGRES_URL=
POSTGRES_PRISMA_URL=
POSTGRES_URL_NON_POOLING=
POSTGRES_USER=
POSTGRES_HOST=
POSTGRES_PASSWORD=
POSTGRES_DATABASE=
```

### Authentication Variables
Run the following command to generate a new secret key for the AUTH_SECRET token.

```bash
openssl rand -base64 32
```

Add the generated key to the `.env` file.

```env
AUTH_SECRET=
```

### Run the Development Server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
