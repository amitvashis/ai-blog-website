# AI-Powered Blog Website

A modern, responsive blog website built with React that displays AI-generated content based on trending topics.

## Features

- 🚀 Fast, responsive UI built with React and Tailwind CSS
- 📱 Mobile-first design approach
- 🔍 Search functionality
- 🔄 Trending posts section
- 📰 Category-based browsing
- 📊 Analytics integration ready
- 🌙 Accessibility compliant

## Technology Stack

- **Frontend Framework**: React.js
- **Routing**: React Router v6
- **HTTP Client**: Axios
- **Styling**: Tailwind CSS
- **State Management**: React Context + Hooks
- **Build Tool**: Vite

## Project Structure

```
src/
├── assets/            # Images, fonts, icons
├── components/        # Reusable UI components
│   ├── Button/
│   ├── Footer/
│   ├── Header/
│   └── PostCard/
├── pages/             # Route-level components
│   ├── Home/
│   ├── PostDetail/
│   └── NotFound/
├── services/          # API layer (Axios instances & endpoints)
├── hooks/             # Custom React hooks
├── context/           # React Context providers
├── styles/            # Global styles
└── utils/             # Helpers & type definitions
```

## Getting Started

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Installation

1. Clone the repository
   ```
   git clone https://github.com/amitvashis/ai-blog-website.git
   cd ai-blog-website
   ```

2. Install dependencies
   ```
   npm install
   # or
   yarn
   ```

3. Start the development server
   ```
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
VITE_API_URL=https://your-backend-api.com
```

## Build for Production

```
npm run build
# or
yarn build
```

The build artifacts will be stored in the `dist/` directory.

## Testing

```
npm run test
# or
yarn test
```

## Deployment

The project is set up to be easily deployed to Vercel or Netlify. Simply connect your GitHub repository to either service for continuous deployment.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Code Standards

- Follow ESLint and Prettier configurations
- Component files use PascalCase (e.g., `Button.jsx`)
- Utility and hook files use camelCase (e.g., `useAuth.js`)
- CSS follows BEM methodology or Tailwind's utility classes

## License

This project is licensed under the MIT License - see the LICENSE file for details.