# starting-with-electron

This repository is a starting point for creating desktop apps with Electron, React and Tailwind and it was based on [Electron Forge](https://www.electronforge.io/).

## Running

- Clone the repository

```bash
# Using GitHub CLI
gh repo clone gabe-frasz/starting-with-electron <directory>

# Using git
git clone https://github.com/gabe-frasz/c6r.git <directory>
```

- Install the dependencies

```bash
npm install
```

- Run dev mode

```bash
npm run dev
```

> If you're having trouble trying to run electron on WSL, [this article](https://gist.github.com/caseywatts/9700b402b6b51d1d6af9f0b206739770) worked for me.

## Files

### `App.tsx`

Main component of the app.

### `index.html`

HTML file where React will render.

### `index.tsx`

File where React creates the root.

### `styles/input.css`

Tailwind CSS input.

### `styles/index.css`

Tailwind CSS output.

### `main.ts`, `preload.ts` and `renderer.ts`

Electron base files.

> For further information about development with Electron, checkout the [official documentation](https://www.electronjs.org/docs/latest/).
