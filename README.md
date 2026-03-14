# 3D Web Elements

Beautiful, interactive 3D web components with elastic animations and modern design.

## 🚀 Quick Start

Start a local server to view the components. You can use any of these methods:

### Using live-server (Recommended)
```bash
npx -y live-server --port=8000
```

### Using Python
```bash
python -m http.server 8000
```

### Using VS Code
Run the task "Start Dev Server" from the command palette (`Ctrl+Shift+P` → "Tasks: Run Task")

## 🌐 Access Your Components

Once the server is running, visit:
- **Main page:** http://localhost:8000/
- **Individual components:** http://localhost:8000/components/[component-name]/[file].html

### Available Components:
- **3D Button:** http://localhost:8000/components/01-3d-button/button.html
- **Elastic Toggle:** http://localhost:8000/components/02-elastic-toggle/toggle.html
- **Morphing Input:** http://localhost:8000/components/03-morphing-input/input.html
- **Magnetic Card:** http://localhost:8000/components/04-magnetic-card/card.html
- **Sculpted Progress:** http://localhost:8000/components/05-sculpted-progress/progress.html
- **Notification Block:** http://localhost:8000/components/06-notification-block/notification.html

## ✨ Features

- 🎨 **3D Components** - Realistic depth and animations using Three.js
- ⚡ **No Build Step** - Pure HTML/CSS/JavaScript
- 🎯 **Interactive** - Hover, click, and drag interactions
- 🌈 **Premium Design** - Vibrant colors and smooth animations

## 📁 Project Structure

```
3DWebElements/
├── components/
│   ├── 01-3d-button/
│   ├── 02-elastic-toggle/
│   ├── 03-morphing-input/
│   ├── 04-magnetic-card/
│   ├── 05-sculpted-progress/
│   └── 06-notification-block/
├── styles/
│   └── main.css
├── .vscode/
│   ├── tasks.json
│   └── launch.json
├── index.html
└── README.md
```

## 🛑 Stop Server

Press `Ctrl+C` in the terminal window to stop the dev server.
