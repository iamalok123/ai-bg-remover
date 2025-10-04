# AI Background Remover

Remove image backgrounds instantly in your browser. This app provides a fast, intuitive experience for removing backgrounds from JPG, PNG, or WEBP images.

## Live Preview
[AI Background Remover](https://ai-bg-remover-nu.vercel.app/) 

### Features
- Drag & drop or click to upload images
- Supports JPG, PNG, and WEBP formats
- Instant background removal using AI
- Preview original and processed images side-by-side
- Download the processed image
- Process multiple images easily with a reset button
- Handles errors gracefully and shows processing status

### Tech Stack
- React 19 + Vite 7
- Tailwind CSS v4 (`@tailwindcss/vite` plugin)
- `@imgly/background-removal` for AI background removal

---

## Getting Started

### Prerequisites
- Node.js 18+
- npm 9+

### Install
```bash
npm install
```

### Run locally
```bash
npm run dev
```

### Build
```bash
npm run build
```

### Preview production build
```bash
npm run preview
```

---

## Configuration

### Tailwind CSS v4
- `vite.config.js` registers `@tailwindcss/vite`
- `src/index.css` imports Tailwind via `@import "tailwindcss";`

---

## Scripts
- dev: Start Vite dev server
- build: Build for production (outputs to `dist/`)
- preview: Preview production build
- lint: Run ESLint

---

## License
No license specified.
