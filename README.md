# Healthcare Dashboard

A React-based healthcare dashboard application built with Vite, TypeScript, and Tailwind CSS.

## Prerequisites

- Node.js (version 18 or higher recommended)
- npm, yarn, or pnpm package manager

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd <project-directory>
```

2. Install dependencies:
```bash
npm install
```

Or if you're using yarn:
```bash
yarn install
```

Or if you're using pnpm:
```bash
pnpm install
```

## Running the Project

### Development Mode

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

### Build for Production

Create a production build:
```bash
npm run build
```

### Preview Production Build

Preview the production build locally:
```bash
npm run preview
```

## Project Structure

- `src/app/` - Main application components
- `src/app/components/` - React components including Dashboard, Login, Patient management
- `src/app/components/ui/` - Reusable UI components (shadcn/ui)
- `src/styles/` - CSS and styling files
- `src/app/data/` - Mock data and data management

## Technologies Used

- React 18
- Vite
- TypeScript
- Tailwind CSS
- Radix UI components
- Material-UI icons
- React Router
- Recharts for data visualization
