# React + TypeScript + Vite + shadcn/ui Starter

A modern, pre-configured starter template for React applications with TypeScript, Vite, shadcn/ui, and Tailwind CSS. This boilerplate saves you time setting up a new project with these technologies.

## ✨ Features

- ⚡️ **Vite** - Fast build tool and development server
- 🚀 **React 18** - Latest React with modern features
- 🦾 **TypeScript** - Type-safe development
- 🎨 **Tailwind CSS** - Utility-first CSS framework
- 📦 **shadcn/ui** - Beautifully designed components
- 📏 **ESLint** - Code linting and quality assurance
- 🔥 **Hot Module Replacement** - Instant feedback during development

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed on your system
- npm, yarn, or pnpm package manager

### Installation

1. Clone or download this template
2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

## 📁 Project Structure

```
├── public/          # Static assets
├── src/
│   ├── components/  # Reusable components
│   ├── lib/         # Utilities and configurations
│   ├── App.tsx      # Main application component
│   ├── main.tsx     # Application entry point
│   └── index.css    # Global styles
├── index.html       # HTML template
├── vite.config.ts   # Vite configuration
├── tsconfig.json    # TypeScript configuration
├── tailwind.config.js # Tailwind CSS configuration
├── components.json   # shadcn/ui configuration
└── eslint.config.js # ESLint configuration
```

## 🛠 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎨 Using shadcn/ui Components

This template comes pre-configured with shadcn/ui. To add new components:

1. Run the shadcn/ui add command:

   ```bash
   npx shadcn-ui@latest add [component-name]
   ```

2. Import and use the component in your code:

   ```tsx
   import { Button } from "@/components/ui/button"

   function MyComponent() {
     return <Button>Click me</Button>
   }
   ```

## 📦 Customization

### Adding Dependencies

Install additional packages as needed:

```bash
npm install [package-name]
```

### Styling

- **Global styles**: Edit `src/index.css`
- **Component styles**: Use Tailwind CSS classes directly in components
- **Custom Tailwind classes**: Modify `tailwind.config.js`

### Configuration Files

- **Vite**: `vite.config.ts`
- **TypeScript**: `tsconfig.json`
- **Tailwind CSS**: `tailwind.config.js`
- **ESLint**: `eslint.config.js`

## 🔧 ESLint Configuration

This template includes an expanded ESLint configuration with type-aware rules for better code quality. The configuration includes:

- TypeScript recommended rules
- Stylistic rules for consistent code style
- React-specific linting rules

To customize ESLint, edit the `eslint.config.js` file.

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory, ready for deployment.

### Deploy to Vercel, Netlify, etc.

Most platforms automatically detect Vite projects. Simply connect your repository and deploy.

## 🤝 Contributing

If you have suggestions for improving this starter template, feel free to create an issue or pull request.

## 📄 License

This project is open source and available under the MIT License.
