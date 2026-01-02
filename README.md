# 🎮 Pokédex

<div align="center">

**A Pokémon database application built with React and the PLC design system**

[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Rsbuild](https://img.shields.io/badge/Rsbuild-1.6-FF6B6B?logo=vite&logoColor=white)](https://rsbuild.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

</div>

---

## 🎯 Overview

**Pokédex** is a modern Pokémon database application built with React and the PLC design system. It provides a comprehensive interface for browsing, searching, and viewing detailed information about Pokémon from the Pokémon universe.

### ✨ Key Features

- 🔍 **Pokémon Search** - Search for Pokémon by name, type, or ID
- 📊 **Detailed Information** - View comprehensive Pokémon details
- 🎨 **Beautiful UI** - Modern glassmorphism design using PLC components
- 📱 **Responsive Design** - Works on desktop and mobile devices
- 🌙 **Dark Mode** - Built-in dark mode support
- 📋 **Pokémon List** - Browse all Pokémon with pagination
- 🎯 **Type Information** - View Pokémon types and weaknesses
- 📈 **Stats Display** - View base stats and abilities
- 🖼️ **Pokémon Images** - High-quality Pokémon artwork
- ⚡ **Fast Performance** - Optimized for speed

---

## 🚀 Quick Start

### Prerequisites

- **Node.js** >= 18.0.0
- **npm** >= 9.0.0

### Installation

```bash
# Clone the repository
git clone https://github.com/marius-patrik/portfolio.git
cd portfolio/pokedex

# Install dependencies
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Build

Build for production:

```bash
npm run build
```

### Preview

Preview the production build:

```bash
npm run preview
```

---

## 🛠️ Tech Stack

| Category | Technology | Version |
|----------|-----------|---------|
| **Framework** | React | 19.x |
| **Language** | TypeScript | 5.9.x |
| **Build Tool** | Rsbuild | 1.6.x |
| **Design System** | PLC Core | Latest |
| **Styling** | Tailwind CSS | 4.0.x |
| **Linting** | Biome | 2.3.x |

---

## 📁 Project Structure

```
pokedex/
├── src/
│   ├── components/      # React components
│   ├── App.tsx          # Main app component
│   ├── index.tsx        # Entry point
│   └── index.css        # Global styles
├── public/              # Static assets
├── rsbuild.config.ts    # Rsbuild configuration
├── tsconfig.json        # TypeScript configuration
├── biome.json           # Biome configuration
├── package.json         # Project dependencies
└── README.md            # This file
```

---

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Lint and fix code with Biome |

---

## 🎨 Features in Detail

### Pokémon Browsing

- **Pokémon List** - Browse all Pokémon with pagination
- **Search** - Search Pokémon by name or ID
- **Filter** - Filter by type, generation, or other criteria
- **Sort** - Sort Pokémon by various attributes

### Pokémon Details

- **Basic Info** - Name, ID, height, weight
- **Types** - Primary and secondary types
- **Stats** - Base stats (HP, Attack, Defense, etc.)
- **Abilities** - Pokémon abilities
- **Evolution** - Evolution chain information
- **Moves** - Learnable moves
- **Images** - Official artwork and sprites

### User Interface

- **Card View** - Pokémon displayed as cards
- **Detail View** - Comprehensive detail page
- **Responsive Layout** - Adapts to screen size
- **Smooth Animations** - Smooth transitions and animations

---

## 🔧 Configuration

### Rsbuild Configuration

The project uses Rsbuild for building. Configuration can be found in `rsbuild.config.ts`.

### TypeScript Configuration

TypeScript settings are defined in `tsconfig.json` with strict type checking enabled.

### Biome Configuration

Code formatting and linting rules are configured in `biome.json`.

---

## 📦 Dependencies

### Core Dependencies

- **react** ^19.2.3 - React library
- **react-dom** ^19.2.3 - React DOM renderer
- **plc-core** - PLC component library

### Development Dependencies

- **@rsbuild/core** ^1.6.14 - Build tool
- **@rsbuild/plugin-react** ^1.4.2 - React plugin for Rsbuild
- **@biomejs/biome** ^2.3.10 - Linter and formatter
- **typescript** ^5.9.3 - TypeScript compiler

---

## 🌐 API Integration

The application integrates with the [PokéAPI](https://pokeapi.co/) to fetch Pokémon data:

- **Pokémon List** - Fetch list of all Pokémon
- **Pokémon Details** - Fetch detailed information
- **Type Information** - Fetch type data
- **Evolution Chains** - Fetch evolution information

---

## 🚢 Deployment

### Build for Production

```bash
npm run build
```

The `dist/` folder contains the production build ready for deployment.

### Deploy to GitHub Pages

```bash
npm run deploy
```

---

## 🤝 Contributing

Contributions are welcome! When contributing:

1. Follow the existing code style
2. Add TypeScript types for all props
3. Include examples in documentation
4. Ensure components are accessible
5. Test in both light and dark modes

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🔗 Related Projects

- **[plc-core](../plc/plc-core/)** - Core component library
- **[plc-ui](../plc/plc-ui/)** - Desktop UI library
- **[plc-playground](../plc/plc-playground/)** - Component playground

---

## 🙏 Acknowledgments

- **PokéAPI** - Pokémon data API
- **The Pokémon Company** - Pokémon franchise

---

<div align="center">

**Built with ❤️ using PLC**

</div>
