# Palama Campus Rides

Palama is a campus ride platform for students in Botswana, connecting passengers with local ride providers. Trips are limited to 65 km.

## Development

Requires Bun and Node.js.

```sh
git clone <this-repository-url>
cd <repository-name>
bun install
bun run dev
```

## Deploy to GitHub Pages

The GitHub Actions workflow builds and publishes the prerendered site. In the
repository settings, set **Pages > Build and deployment > Source** to **GitHub
Actions**. Pushes to `main` will deploy automatically.

The Pages build uses the repository path (`/palama/`) for assets and routes;
local development continues to use `/`.
