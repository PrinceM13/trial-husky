# Next.js 15 Project

This is a [Next.js 15](https://nextjs.org) project.

## 📦 Getting Started (Development)

Start the local development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🛠️ Build and Run (Production)

### 1. Build the application:

```bash
npm run build
# or
yarn build
# or
pnpm build
```

### 2. Start the production server:

```bash
npm start
# or
yarn start
# or
pnpm start
```

This will run the app on [http://localhost:3000](http://localhost:3000)

---

## 🐳 Docker

### 1. Build Docker image

```bash
docker build -t your-app-name:latest .
```

### 2. Run Docker container

```bash
docker run -p 3000:3000 your-app-name:latest
```

> Ensure port `3000` is not already in use on your machine.

---

## 📁 Project Structure (Simplified)

```
.
├── src/
│ ├── app/ # Next.js app directory (entry point)
│ └── styles/ # Global styles
├── public/ # Static assets
├── .env.local # Local environment variables
├── Dockerfile # Docker config
├── next.config.js # Next.js config
├── package.json
└── README.md
```

---

## 🥪 Environment Variables

Create a `.env.local` file to store environment-specific values. Example:

```
PORT=3000
NEXT_PUBLIC_API_URL=https://api.example.com
```

---

## 📄 License

MIT
