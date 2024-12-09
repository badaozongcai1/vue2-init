# Vue 2 + Vite Template

A modern development setup for Vue 2 projects using Vite as the build tool. This template provides a minimal setup while maintaining high performance and developer experience.

## Features

- ⚡️ Lightning Fast HMR with [Vite](https://vitejs.dev/)
- 🎉 Vue 2.7
- 📦 Optimized Build Setup
- 🔧 Easy to Configure
- 🎨 Ready for CSS/SCSS

## Prerequisites

- Node.js version 14.0 or higher
- Package Manager (pnpm recommended)

## Package Manager

This template supports multiple package managers. We recommend using pnpm for its efficiency and disk space savings.

### Install your preferred package manager:

```bash
# Install pnpm (recommended)
npm install -g pnpm

# Or use npm (comes with Node.js)
# No additional installation needed

# Or install yarn
npm install -g yarn

# Or install bun
curl -fsSL https://bun.sh/install | bash
```

## Quick Start

1. Clone this repository:

```bash
git clone https://github.com/badaozongcai1/vue2-vite-template.git
cd vue2-vite-template
```

2. Install dependencies using your preferred package manager:

```bash
# Using pnpm (recommended)
pnpm install

# Using npm
npm install

# Using yarn
yarn install

# Using bun
bun install
```

3. Start development server:

```bash
# Using pnpm (recommended)
pnpm dev

# Using npm
npm run dev

# Using yarn
yarn dev

# Using bun
bun run dev
```

4. Build for production:

```bash
# Using pnpm (recommended)
pnpm build

# Using npm
npm run build

# Using yarn
yarn build

# Using bun
bun run build
```

## Project Structure

```
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── App.vue
│   └── main.js
├── index.html
├── package.json
└── vite.config.js
```

## Available Scripts

Using pnpm (recommended):

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview production build locally

Alternative commands:

```bash
# npm
npm run dev
npm run build
npm run preview

# yarn
yarn dev
yarn build
yarn preview

# bun
bun run dev
bun run build
bun run preview
```

## Extending the Template

### Adding Vue Router

```bash
# Using pnpm (recommended)
pnpm add vue-router@3

# Using npm
npm install vue-router@3

# Using yarn
yarn add vue-router@3

# Using bun
bun add vue-router@3
```

### Adding Vuex

```bash
# Using pnpm (recommended)
pnpm add vuex@3

# Using npm
npm install vuex@3

# Using yarn
yarn add vuex@3

# Using bun
bun add vuex@3
```

### Adding Axios

```bash
# Using pnpm (recommended)
pnpm add axios

# Using npm
npm install axios

# Using yarn
yarn add axios

# Using bun
bun add axios
```

## Configuration

The template uses Vite's default configuration with Vue 2 plugin. You can modify the configuration in `vite.config.js`:

```javascript
import { defineConfig } from "vite";
import vue2 from "@vitejs/plugin-vue2";

export default defineConfig({
  plugins: [vue2()],
  // Add your custom config here
});
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Vite](https://vitejs.dev/)
- [Vue 2](https://v2.vuejs.org/)
- [@vitejs/plugin-vue2](https://github.com/vitejs/vite-plugin-vue2)
