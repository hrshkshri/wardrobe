# Wardrobe

A React Native application.

## Prerequisites

- Node.js >= 18
- npm or yarn
- React Native CLI
- Xcode (for iOS development)
- Android Studio (for Android development)

## Getting Started

### Installation

```bash
npm install
```

### Running the App

**iOS:**

```bash
npm run ios
```

**Android:**

```bash
npm run android
```

**Start Metro bundler:**

```bash
npm start
```

## Development

### Available Scripts

- `npm start` - Start Metro bundler
- `npm run android` - Run on Android
- `npm run ios` - Run on iOS
- `npm run lint` - Run ESLint
- `npm run lint:fix` - Fix ESLint errors
- `npm run format` - Format code with Prettier
- `npm run format:check` - Check code formatting
- `npm test` - Run tests

### Code Quality

This project uses:

- **ESLint** for code linting
- **Prettier** for code formatting
- **Husky** for Git hooks
- **lint-staged** for running linters on staged files

Pre-commit hooks will automatically lint and format your staged files.

## Project Structure

```
wardrobe/
├── App.tsx           # Main application component
├── index.js          # Entry point
├── package.json      # Dependencies and scripts
├── tsconfig.json     # TypeScript configuration
├── babel.config.js   # Babel configuration
├── metro.config.js   # Metro bundler configuration
├── .eslintrc.js      # ESLint configuration
├── .prettierrc       # Prettier configuration
└── .husky/           # Git hooks
```

## License

MIT
