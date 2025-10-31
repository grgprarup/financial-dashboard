## 💰 Financial Dashboard — Starter Template

This is the starter template for a Financial Dashboard application built with Next.js (App Router). It provides the foundational code structure to help you build an interactive, data-driven financial management dashboard with modern web technologies.

The template includes a clean layout, reusable components, and routing setup — perfect for visualizing financial data, tracking expenses, monitoring revenue, and generating insights.

For more information and learning resources, check out the Next.js [documentation](https://nextjs.org/learn) on the official Next.js website.

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
