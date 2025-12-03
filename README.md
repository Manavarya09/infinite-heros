# Infinite Heroes

Infinite Heroes is a modern web application designed to showcase and explore a vast collection of heroes. Built with React and Vite, it offers a fast, interactive, and visually appealing experience for users.

## Features
- **Hero Catalog:** Browse an extensive list of heroes with detailed metadata.
- **API Key Integration:** Secure access to hero data via API key management.
- **Dynamic Loading Effects:** Enjoy smooth transitions and loading animations.
- **Responsive Design:** Optimized for desktop and mobile devices.
- **Panel Navigation:** Easily switch between different views and panels.

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Manavarya09/infinite-heros.git
   cd infinite-heros
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure
```
├── ApiKeyDialog.tsx      # API key input dialog component
├── App.tsx               # Main application component
├── Book.tsx              # Hero book/catalog component
├── index.css             # Global styles
├── index.html            # HTML entry point
├── index.tsx             # React entry point
├── LoadingFX.tsx         # Loading effects component
├── metadata.json         # Hero metadata
├── package.json          # Project dependencies and scripts
├── Panel.tsx             # Panel navigation component
├── README.md             # Project documentation
├── Setup.tsx             # Initial setup component
├── tsconfig.json         # TypeScript configuration
├── types.ts              # TypeScript types
├── useApiKey.ts          # Custom hook for API key management
├── vite.config.ts        # Vite configuration
```

## Usage
- **API Key:** On first launch, enter your API key to access hero data.
- **Navigation:** Use the panel to switch between hero catalog, details, and settings.
- **Search & Filter:** Quickly find heroes using search and filter options.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements and new features.

## License
This project is licensed under the MIT License.

## Author
- [Manavarya Singh](https://github.com/Manavarya09)

---

For more information, see the [metadata.json](./metadata.json) and explore the source code.
