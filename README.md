## Javier Maldonado Rivera CV

![preview](./public/javiermaldonadorivera-cv-preview.png)

## 📄 About

This project is refactored from the original [**dev-portfolio**](https://github.com/Smilesharks/dev-portfolio) project, thanks for his work.

## 🛠️ Stack

- [**Astro**](https://astro.build/) - The next-gen web framework.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with type syntax.

## 🚀 Getting Started

### 1. Use this Repo as an Astro Project Template

- I use [pnpm](https://pnpm.io/installation) as my package manager.

```bash
# Enable pnpm on MacOS, WSL & Linux:
corepack enable
corepack prepare pnpm@latest --activate
```

# Initialize the project
```bash
pnpm create astro@latest -- --template Smilesharks/dev-portfolio
```

### 2. Add Your Content:

Edit the `cv.json` file to create your own printable Portfolio/CV.

### 3. Launch the Development Server:

```bash
# Enjoy the results
pnpm dev
```
1. Open [**http://localhost:4321**](http://localhost:4321/) in your browser to view the result 🚀

### 4. Customisable colours:
Change the data-theme of `cv.json` and choose one of the colour themes defined in theme.css, red, blue, green, cyber and default, with its variants in dark mode, or create your own.

## 🧞 Commands

|     | Command         | Action                                                                       |
| :-- | :-------------- | :--------------------------------------------------------------------------- |
| ⚙️  | `dev` o `start` | Launches a local development server at `localhost:4321`.                   |
| ⚙️  | `build`         | Checks for errors and creates a production build in `./dist/`. |
| ⚙️  | `preview`       | Local preview at `localhost:4321`                                       |