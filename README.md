# React + TypeScript + Tailwind CSS Boilerplate

![License](https://img.shields.io/github/license/saminyasar004/react-ts-tailwind-boilerplate)
![Stars](https://img.shields.io/github/stars/saminyasar004/react-ts-tailwind-boilerplate)
![Forks](https://img.shields.io/github/forks/saminyasar004/react-ts-tailwind-boilerplate)

A modern, production-ready boilerplate for building React applications with speed and precision. This template comes pre-configured with the latest tools and best practices to help you jumpstart your next project.

## 🚀 Features

-   **[Vite](https://vitejs.dev/)**: Lightning-fast development server and optimized builds.
-   **[React](https://react.dev/)**: The library for web and native user interfaces.
-   **[TypeScript](https://www.typescriptlang.org/)**: Strongly typed JavaScript for better developer experience and fewer bugs.
-   **[Tailwind CSS v4](https://tailwindcss.com/)**: A utility-first CSS framework for rapidly building custom designs.
-   **[shadcn/ui](https://ui.shadcn.com/)**: Beautifully designed components built with Radix UI and Tailwind CSS.
-   **[TanStack Query](https://tanstack.com/query/latest)**: Powerful asynchronous state management.
-   **[React Router](https://reactrouter.com/)**: Declarative routing for React web applications.
-   **Dark Mode**: Fully integrated theme switching with `next-themes`.
-   **Linting & Formatting**: Pre-configured ESLint and Prettier for consistent code style.
-   **Path Aliases**: Clean imports using `@/` alias.

## 🛠️ Tech Stack

-   **Framework**: React 18
-   **Build Tool**: Vite 5
-   **Language**: TypeScript 5
-   **Styling**: Tailwind CSS 4 + tailwindcss-animate
-   **UI Components**: shadcn/ui (Radix UI)
-   **Routing**: React Router DOM 6
-   **State Management**: TanStack Query v5
-   **Forms**: React Hook Form + Zod
-   **Icons**: Lucide React

## 📦 Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

-   [Node.js](https://nodejs.org/) (v18 or higher)
-   [Yarn](https://yarnpkg.com/) (v1.22 or higher) or npm

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/saminyasar004/react-ts-tailwind-boilerplate.git
    cd react-ts-tailwind-boilerplate
    ```

2.  **Install dependencies:**

    ```bash
    yarn install
    # or
    npm install
    ```

3.  **Start the development server:**

    ```bash
    yarn dev
    # or
    npm run dev
    ```

    Open [http://localhost:8080](http://localhost:8080) (or the port shown in your terminal) to view it in the browser.

## 🏗️ Project Structure

```
react-ts-tailwind-boilerplate/
├── src/
│   ├── components/         # Reusable UI components
│   │   ├── ui/             # shadcn/ui primitives
│   │   ├── mode-toggle.tsx # Theme switcher
│   │   └── ...
│   ├── lib/                # Utility functions (cn, utils)
│   ├── pages/              # Page components (routed)
│   ├── hooks/              # Custom React hooks
│   ├── App.tsx             # Main application component
│   ├── main.tsx            # Entry point
│   └── index.css           # Global styles and Tailwind directives
├── public/                 # Static assets
├── .eslintrc.cjs           # ESLint configuration
├── tailwind.config.ts      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
├── vite.config.ts          # Vite configuration
└── package.json            # Project dependencies and scripts
```

## 🎨 Customization

### Tailwind Configuration

The Tailwind configuration is located in `tailwind.config.ts`. You can customize colors, fonts, and other theme values here.

### Components

This project uses [shadcn/ui](https://ui.shadcn.com/). You can add more components by running:

```bash
npx shadcn-ui@latest add [component-name]
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 👤 Author

**Samin Yasar**

-   GitHub: [@saminyasar004](https://github.com/saminyasar004)
-   Email: [yasarsamin57@gmail.com](mailto:yasarsamin57@gmail.com)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
