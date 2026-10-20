# Trinity

An interactive 3D tribute to Laylow's album *Trinity*: the record floats in a field of green sparkles, follows your cursor and flips over on click, under glitch and scanline effects.

**[Live demo → trinity.thibaut-lefrancois.com](https://trinity.thibaut-lefrancois.com)**

## Features

- Textured 3D disc with an intro animation, hover outline and click-to-flip (front/back covers)
- Camera that follows the pointer with damping
- Glitch and scanline post-processing
- Loading screen with progress bar and sound design
- Responsive disc size on mobile

## Stack

- [React](https://react.dev) + [Vite](https://vite.dev)
- [Three.js](https://threejs.org) via [@react-three/fiber](https://r3f.docs.pmnd.rs) and [drei](https://drei.docs.pmnd.rs)
- [@react-three/postprocessing](https://react-postprocessing.docs.pmnd.rs)
- [GSAP](https://gsap.com) and [Motion](https://motion.dev) for animations
- [Zustand](https://zustand.docs.pmnd.rs) for state
- [Tailwind CSS](https://tailwindcss.com)

## Getting started

```bash
git clone https://github.com/thibautlfr/trinity.git
cd trinity
npm install
npm run dev
```

The app runs at http://localhost:5173.

| Script            | Description                       |
| ----------------- | --------------------------------- |
| `npm run dev`     | Start the dev server              |
| `npm run build`   | Build for production into `dist/` |
| `npm run preview` | Preview the production build      |
| `npm run lint`    | Lint with ESLint                  |

Add `#debug` to the URL to show the performance monitor.

## Author

Thibaut Lefrançois ([GitHub](https://github.com/thibautlfr) · [LinkedIn](https://www.linkedin.com/in/thibaut-lefrancois/))

*Trinity* artwork belongs to Laylow. This is a non-commercial fan project.
