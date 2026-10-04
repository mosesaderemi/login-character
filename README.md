# Login Character

An interactive login page featuring an animated SVG character that reacts to what the user does. It is a front-end showcase of expressive micro-interactions built with React, TypeScript and Motion.

## Behaviour

- The character's eyes follow the mouse pointer across the screen
- It blinks at random intervals
- When the password field is focused, the character shifts and lifts its eyes
- The show and hide password toggle makes the character look away or look back
- A wrong password makes the form shake, shows an inline error and gives the character a sad expression for a moment

## Demo Logic

This project demonstrates the interface only. There is no backend, and the sign-in button checks the typed value against a fixed demo password (`password`). Connect the button handler in `src/App.tsx` to a real authentication call to use it in an application.

## Tech Stack

| Area | Technology |
| --- | --- |
| Framework | React 19, TypeScript |
| Animation | Motion (`motion/react`) |
| Styling | Tailwind CSS 4 |
| Build tool | Vite |
| Linting | ESLint with typescript-eslint |

## Project Structure

```text
.
├── index.html
├── src
│   ├── App.tsx       Login form and animated character
│   ├── main.tsx
│   └── index.css
├── public
└── vite.config.ts
```

## Getting Started

```bash
git clone https://github.com/mosesaderemi/login-character.git
cd login-character
npm install
npm run dev
```

Open the address printed in the terminal, usually `http://localhost:5173`.

| Command | Description |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Type-check and create a production build |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint |

## Author

Aderemi Moses Timileyin
GitHub: [@mosesaderemi](https://github.com/mosesaderemi)
LinkedIn: [linkedin.com/in/mosesaderemi-6a70a5405](https://www.linkedin.com/in/mosesaderemi-6a70a5405)

## License

Released under the MIT License. See the `LICENSE` file for details.
