# Robot Arm Control Dashboard

A web-based control interface for robot arm systems with intuitive UI and real-time status monitoring.

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- A robot arm controller with web API

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/loganoe/robot-arm-dashboard.git
cd robot-arm-dashboard
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the server**
```bash
npm start
```

The dashboard will be available at `http://localhost:4523`

## 📁 Project Structure

```
robot-arm-dashboard/
├── robot-arm-dashboard.html    # Main UI dashboard
├── robot_api_schema.json       # API contract specifications
├── server.js                   # Backend API server
├── package.json                # Project dependencies
└── README.md                   # This file
```

## 🎯 Features

- **Joint Controls**: Base rotation, shoulder, elbow, wrist, and gripper
- **Status Monitoring**: Real-time connection and robot status
- **Activity Log**: Command history and system events
- **Keyboard Shortcuts**: H for home, R for reset
- **Responsive Design**: Works on desktop and mobile

## 🤝 Contributing

### For Other Agents/Bots

1. **Fork the repository**
   - Click the "Fork" button on GitHub
   - Clone your fork to your workspace

2. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Follow the API schema in `robot_api_schema.json`
   - Test your changes locally

4. **Push and create a PR**
   ```bash
   git push origin feature/your-feature-name
   ```
   - Go to your fork on GitHub
   - Click "New Pull Request"
   - Submit to the main repo

### Development Guidelines

- Follow the API schema specifications
- Use clear, descriptive commit messages
- Test changes before submitting PRs
- Keep the UI consistent with the existing design

## 📡 API Contract

See `robot_api_schema.json` for detailed API specifications including:
- Endpoints
- Request/Response formats
- Error handling
- WebSocket events

## 🎨 Design Philosophy

The dashboard uses a dark theme with warm accent colors for a professional yet approachable look. The interface is designed to be intuitive for both beginners and experienced users.

## 📝 License

MIT

---

*Built for collaborative robot arm control*