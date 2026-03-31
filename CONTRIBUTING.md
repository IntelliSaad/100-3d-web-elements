# Contributing to 100+ 3D Web Elements

First off, thank you for considering contributing! 🎉

## How to Contribute

### 🐛 Report Bugs
Open an [issue](https://github.com/IntelliSaad/100-3d-web-elements/issues) with:
- A clear title and description
- Steps to reproduce the behavior
- The browser you're using
- Screenshots if applicable

### 💡 Suggest a New Component
Have an idea for a new 3D element? Open an issue with the `enhancement` label and describe:
- The interaction pattern (hover, scroll, click)
- The visual aesthetic you're imagining
- Reference links to similar designs (if any)

### 🔧 Submit a Pull Request
1. Fork the repository
2. Create your feature branch (`git checkout -b feat/amazing-component`)
3. Add your component in a new numbered folder (e.g., `101-your-component/`)
4. Commit your changes (`git commit -m 'Add amazing 3D component'`)
5. Push to the branch (`git push origin feat/amazing-component`)
6. Open a Pull Request

### 📐 Component Guidelines
- Each component must be **self-contained** in a single `.html` file
- Use **React** via ESM CDN imports (no build step)
- Use **Tailwind CSS** via CDN for styling
- Animations must be **hardware-accelerated** (`translate3d`, `scale3d`, `will-change`)
- Target **60fps** on an 8GB RAM machine

## Code of Conduct
Be respectful, constructive, and kind.
