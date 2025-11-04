# GEMINI.md

This file provides a comprehensive overview of the project, its structure, and how to work with it.

## Project Overview

This is a web application built with the T3 stack, bootstrapped with `create-t3-app`. It's a full-stack application that uses:

-   **Framework**: [React](https://reactjs.org/)
-   **Bundler**: [Vite](https://vitejs.dev/)
-   **Language**: [TypeScript](https://www.typescriptlang.org/)
-   **Routing**: [TanStack Router](https://tanstack.com/router)
-   **Data Fetching**: [TanStack Query](https://tanstack.com/query)
-   **State Management**: [TanStack Store](https://tanstack.com/store)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/)
-   **UI Components**: [Shadcn](https://ui.shadcn.com/)
-   **Linting and Formatting**: [Biome](https://biomejs.dev/)
-   **Testing**: [Vitest](https://vitest.dev/)
-   **Package Manager**: [Bun](https://bun.sh/)

The project follows a file-based routing approach, where routes are defined as files in the `src/routes` directory.

## Building and Running

### Prerequisites

-   [Bun](https://bun.sh/)

### Installation

```bash
bun install
```

### Development

To start the development server, run:

```bash
bun run dev
```

This will start the development server on `http://localhost:3000`.

### Building for Production

To build the application for production, run:

```bash
bun run build
```

### Testing

To run the tests, run:

```bash
bun run test
```

### Linting and Formatting

To lint and format the code, you can use the following commands:

-   `bun run lint`: Lint the code.
-   `bun run format`: Format the code.
-   `bun run check`: Run both linting and formatting.

## Development Conventions

### Routing

The project uses file-based routing with TanStack Router. The routes are managed as files in the `src/routes` directory. The layout is defined in `src/routes/__root.tsx`.

### Data Fetching

Data fetching can be done using TanStack Query or the `loader` functionality built into TanStack Router.

### State Management

State management can be handled with TanStack Store.

### Demo Files

Files prefixed with `demo` in the `src/components`, `src/hooks`, and `src/data` directories can be safely deleted. They are provided as a starting point.
