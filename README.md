Port of [vite-plugin-cesium](https://github.com/nshen/vite-plugin-cesium) for React Router framework mode.

### Usage

```ts
// vite.config.ts
import reactRouterCesium from "vite-plugin-react-router-cesium";

export default defineConfig({
  plugins: [
    reactRouter(),
    tsconfigPaths(),
    reactRouterCesium(),
    // ...
  ],
  // ...
});
```

### Options

```ts
rebuildCesium?: boolean;
devMinifyCesium?: boolean;
cesiumBuildRootPath?: string;
cesiumBuildPath?: string;
cesiumBaseUrl?: string;
```
