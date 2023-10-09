<h2>Folder & File Structure</h2>

```sh
~/project on main
❯ tree --filelimit 10
  ├── index.html
  ├── node_modules [68 entries exceeds filelimit, not opening dir]
  ├── package.json
  ├── public
  │   └── vite.svg
  ├── src
  │   ├── counter.ts
  │   ├── main.ts
  │   ├── style.css
  │   ├── typescript.svg
  │   └── vite-env.d.ts
  ├── tsconfig.json
  ├── vite.config.js
  └── yarn.lock
```

- `index.html`: The HTML file that will be injected into the extension's popup.
- `node_modules`: The folder that contains all the dependencies.
- `package.json`: The file that contains all the dependencies.
- `public`: The folder that contains all the static assets.
- `src`: The folder that contains all the source code.
- `tsconfig.json`: The TypeScript configuration file.
- `vite.config.js`: The Vite configuration file.
- `yarn.lock`: The file that contains all the dependencies' versions.
