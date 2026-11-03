# erp_accounts_frontend
# Machine Test Project – Frontend Setup

## 1. Prerequisites

Make sure you have installed:

- Node.js
- npm
- VS Code

## 2. Open the Frontend Project

Open VS Code terminal and navigate to the frontend folder.

```bash
cd frontend
```

If your terminal is already inside the frontend folder, skip this step.

## 3. Install Dependencies

```bash
npm install
```

## 4. Configure Backend API URL

Check whether your frontend uses a backend API.

If you have an API configuration file or `.env`, update the API URL for local development.

Example for Vite:

```env
VITE_API_URL=http://localhost:5000
```

Use this only if your frontend code reads `import.meta.env.VITE_API_URL`.

Restart the frontend after changing `.env`.

## 5. Run the Frontend

```bash
npm run dev
```

Open the URL displayed in your terminal, usually:

http://localhost:5173

## 6. Build the Frontend

To check whether the frontend builds successfully:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 7. Common Issues

- **npm not recognized:** Install Node.js and restart VS Code.
- **Module not found:** Run `npm install`.
- **Frontend not loading:** Check the terminal for errors.
- **API error / Network Error:** Ensure the backend is running and the API URL is correct.
- **Port already in use:** Use the alternative local URL shown by Vite.

## Quick Start – Every Time

```bash
cd frontend
npm run dev
```

If dependencies are not installed yet, run `npm install` first.
