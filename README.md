# React + Vite

This template provides a minimal and optimized setup to run **React with Vite**, including Hot Module Replacement (HMR) and basic ESLint configuration.

## Official React Plugins

Two official plugins are currently supported:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react)  
  Uses **Babel** (or **oxc** when used with rolldown-vite) to enable Fast Refresh.

- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc)  
  Uses **SWC** for faster compilation and Fast Refresh support.

## React Compiler

The React Compiler is not enabled by default due to its impact on development and build performance.  
To enable it, refer to the official documentation:

https://react.dev/learn/react-compiler/installation

## Expanding ESLint Configuration

For production applications, it is recommended to use **TypeScript** with type-aware linting enabled.

Refer to the official TypeScript template for guidance on integrating:
- TypeScript
- `typescript-eslint`

Template link:  
https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts
