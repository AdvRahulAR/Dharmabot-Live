
# Dharmabot Live

A real-time audio visualization application built with modern web technologies. This project combines 3D graphics and audio analysis to create an immersive visual experience.

## Features

- Real-time audio visualization using Three.js
- Custom shader implementations for visual effects
- Web Components architecture using Lit
- Integrated with Google's Generative AI

## Technologies Used

- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- [Three.js](https://threejs.org/) - 3D Graphics Library
- [Lit](https://lit.dev/) - Simple. Fast. Web Components.
- [TypeScript](https://www.typescriptlang.org/) - JavaScript with syntax for types
- [Google Generative AI](https://ai.google.dev/) - AI Integration

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn package manager
- Gemini API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AdvRahulAR/Dharmabot-Live.git
   cd Dharmabot-Live
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env.local` file in the root directory
   - Add your Gemini API key: `GEMINI_API_KEY=your_api_key_here`

### Development

To start the development server:

```bash
npm run dev
```

This will start the Vite development server, typically at `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## Project Structure

- `analyser.ts` - Audio analysis implementation
- `backdrop-shader.ts` - Shader implementation for background effects
- `sphere-shader.ts` - Shader implementation for sphere visualization
- `visual-3d.ts` - 3D visualization components
- `visual.ts` - Core visualization logic
- `utils.ts` - Utility functions
- `public/` - Static assets directory

## License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

Copyright (c) 2025, Rahul A R
