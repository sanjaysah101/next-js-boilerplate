# Next.js Boilerplate

A modern and well-structured Next.js boilerplate to kickstart your projects.

## Features

- ⚡ [Next.js](https://nextjs.org) for Static Site Generation and Server-side Rendering
- 🎨 Integrated with Tailwind CSS
- 📏 ESLint — Find and fix problems in your code
- 💖 Prettier — Code Formatter for consistent style
- 🐶 Husky — For running scripts before committing
- 🚓 Commit Lint — Make sure your commit messages follow the convention
- 🖌 Renovate — Keep your dependencies up to date
- 🚫 lint-staged — Run ESLint and Prettier against staged Git files
- 👷 PR Workflow — Run Type Check & Linters on Pull Requests
- ⚙️ EditorConfig - Maintain consistent coding styles across editors and IDEs

## Quick Start

### 1. Clone this repository

```bash
git clone https://github.com/yourusername/next-js-boilerplate.git
```

### 2. Install dependencies

```bash
pnpm install
```

### 3. Run the development server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```tree
.
├── public/          # Static files
├── src/
│   ├── app/        # App router pages
│   ├── components/ # React components
│   ├── lib/        # Library files
│   └── styles/     # Global styles
├── .eslintrc.js    # ESLint configuration
├── .prettierrc     # Prettier configuration
└── tsconfig.json   # TypeScript configuration
```

## Available Scripts

```shell
# Development
pnpm dev          # Start development server
pnpm build        # Build production bundle
pnpm start        # Start production server

# Code Quality
pnpm lint         # Run ESLint
pnpm format       # Format code with Prettier
pnpm type-check   # Run TypeScript compiler check

# Git Hooks
pnpm prepare      # Install Husky git hooks
```

## Environment Variables

```env
NEXT_PUBLIC_API_URL=your_api_url_here
```

## Commit Convention

This project uses [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Format: `<type>(<scope>): <subject>`

`<type>` includes:

- feat (new feature)
- fix (bug fix)
- docs (documentation)
- style (formatting, missing semicolons, etc)
- refactor (code change that neither fixes a bug nor adds a feature)
- test (adding tests)
- chore (maintain)

## VSCode Recommended Extensions

- ESLint
- Prettier
- Tailwind CSS IntelliSense
- PostCSS Language Support

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
