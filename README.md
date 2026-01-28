# Chronos Pomodoro

A modern Pomodoro timer built with React + TypeScript + Vite, featuring TailwindCSS for styling.

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or pnpm

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 🔧 Code Quality & Development Tools

This project is configured with industry-standard tools for maintaining high code quality:

### ESLint

Strict ESLint configuration with TypeScript type-checking enabled:
- Type-aware linting rules for TypeScript
- React Hooks best practices
- React Refresh for HMR
- Prettier integration for consistent formatting
- Automatic unused variable detection
- Enforced module imports best practices

**Commands:**
```bash
npm run lint          # Check for linting errors
npm run lint:fix      # Auto-fix linting errors
```

### Prettier

Code formatting with Prettier configured for:
- Single quotes for strings
- Semicolons enabled
- Trailing commas
- 100 character line width
- 2 space indentation
- Unix line endings (LF)

**Commands:**
```bash
npm run format        # Format all source files
npm run format:check  # Check if files are formatted
```

### TypeScript Configuration

Strict TypeScript settings with ES Module support:
- **Module System**: ESNext modules with bundler resolution
- **Target**: ES2022 for modern JavaScript features
- **Strict Mode**: Enabled with additional safety checks
- **Path Resolution**: Support for JSON imports and isolatedModules
- **Type Safety**: No implicit returns, unchecked indexed access protection

## 📁 Project Structure

```
chronos-pomodoro/
├── src/               # Source files
│   ├── App.tsx        # Main application component
│   ├── main.tsx       # Application entry point
│   └── index.css      # Global styles
├── .prettierrc        # Prettier configuration
├── .prettierignore    # Prettier ignore patterns
├── eslint.config.js   # ESLint configuration
├── tsconfig.json      # Base TypeScript config
├── tsconfig.app.json  # App TypeScript config
├── tsconfig.node.json # Node/build tools TypeScript config
└── vite.config.ts     # Vite configuration
```

## 🛠️ Technology Stack

- **React 19** - Modern React with latest features
- **TypeScript 5.9** - Type-safe JavaScript
- **Vite 7** - Fast build tool and dev server
- **TailwindCSS 4** - Utility-first CSS framework
- **ESLint 9** - Linting with flat config
- **Prettier 3** - Code formatting
