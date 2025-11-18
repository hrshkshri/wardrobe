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
yarn install
```

### Running the App

**iOS:**

```bash
yarn ios
```

**Android:**

```bash
yarn android
```

**Start Metro bundler:**

```bash
yarn start
```

## Development

### Available Scripts

- `yarn start` - Start Metro bundler
- `yarn android` - Run on Android
- `yarn ios` - Run on iOS
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors
- `yarn format` - Format code with Prettier
- `yarn format:check` - Check code formatting
- `yarn test` - Run tests

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
