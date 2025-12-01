# Imagify Client

This app is built with React + Vite and includes Tailwind CSS plus additional UI helpers.

## Installing Dependencies

1. Install packages
   ```
   npm install
   ```
2. If you see build errors complaining about `react-toastify`, install it explicitly:
   ```
   npm install react-toastify
   ```

## Development

- `npm run dev` – start Vite dev server with hot reload.
- `npm run build` – create a production build.
- `npm run preview` – serve the production build locally.

## Configuration

Create a `.env` file (or `.env.local`) in the client directory if you want to point at a non-default API:

```
VITE_BACKEND_URL=http://localhost:4000
```

If the variable is omitted the app automatically falls back to `http://localhost:4000`.
