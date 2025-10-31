A meteorological data visualization application built with React, TypeScript, and Supabase.

## Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (version 18 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **bun** (optional, faster alternative)

## Installation Steps

### 1. Copy the Project
Copy all project files to your target computer.

### 2. Install Dependencies
Open a terminal in the project directory and run:

```bash
npm install
```

Or if you're using bun:
```bash
bun install
```

## Running the Application

### Development Mode
To run the application in development mode with hot reload:

```bash
npm run dev
```

The application will be available at: `http://localhost:8080`

### Production Build
To create an optimized production build:

```bash
npm run build
```

The build output will be in the `dist` folder.

### Preview Production Build
To preview the production build locally:

```bash
npm run preview
```

Or with bun:
```bash
bun run preview
```

## Project Structure

```
├── src/
│   ├── components/       # React components
│   ├── pages/           # Page components
│   ├── hooks/           # Custom React hooks
│   ├── services/        # API services
│   ├── integrations/    # Supabase integration
│   └── lib/             # Utility functions
├── supabase/            # Supabase configuration and functions
└── public/              # Static assets
```

## Key Features

- 📊 Interactive meteorological data charts
- 🗺️ Leaflet map integration
- 📈 Temperature, humidity, rainfall, and solar radiation visualizations
- 🔐 User authentication with Supabase
- 📱 Responsive design
- 📥 CSV data import functionality
- 📄 PDF export capabilities

## Technologies Used

- **React 18** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool
- **Tailwind CSS** - Styling
- **Supabase** - Backend & authentication
- **Recharts** - Data visualization
- **Leaflet** - Maps
- **React Router** - Routing

### Build Errors
If you encounter build errors:
1. Delete `node_modules` folder
2. Delete `package-lock.json` (or `bun.lockb`)
3. Run `npm install` (or `bun install`) again
