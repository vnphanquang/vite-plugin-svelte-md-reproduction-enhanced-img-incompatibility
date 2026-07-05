# Reproduction for https://github.com/ota-meshi/vite-plugin-svelte-md/issues/149

## Steps

1. Install dependencies, pnpm is recommended:

    ```bash
    pnpm install
    ```

2. Start dev server:
    
    ```bash
    pnpm dev
    ```

3. Visit live site, typically at http://localhost:5173, observe that `enhanced:img` was not rendered correctly.


Code of interest is at `src/routes`;
