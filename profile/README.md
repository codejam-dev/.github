# CodeJam

A real-time collaborative coding platform for developers to code together, learn, and build projects in sync.

## 🚀 What is CodeJam?

CodeJam enables developers to write code together in real-time with live cursor tracking, integrated voice/video chat, and instant code execution. Think Google Docs meets VS Code.

## ⚡ Features

- **Real-time Collaboration** - Multiple developers coding simultaneously with conflict-free sync
- **Live Code Execution** - Run code directly in the browser with sandboxed environments
- **Video & Voice Chat** - Built-in communication without switching apps
- **Multi-language Support** - Python, JavaScript, Java, Go, and more
- **Session Management** - Create rooms, invite teammates, and manage permissions

## 🛠️ Tech Stack

- **Backend**: Spring Boot 3.x, WebSocket, Redis
- **Frontend**: React, Monaco Editor, WebRTC
- **Infrastructure**: Docker, Kubernetes, PostgreSQL
- **Real-time**: Operational Transforms / CRDT for conflict resolution

## 📦 Repositories

| Repository | Description | Status |
|------------|-------------|--------|
| [codejam-backend](link) | Spring Boot API & WebSocket server | 🚧 In Progress |
| [codejam-frontend](link) | React web application | 🚧 In Progress |
| [codejam-executor](link) | Sandboxed code execution service | 📋 Planned |
| [codejam-infra](link) | Docker Compose & K8s configs | 📋 Planned |

## 🏗️ Architecture
```
┌─────────────┐         ┌──────────────┐         ┌─────────────┐
│   Frontend  │◄───────►│   API Gateway │◄───────►│   Backend   │
│   (React)   │         │  (WebSocket)  │         │ (Spring Boot)│
└─────────────┘         └──────────────┘         └─────────────┘
                               │                         │
                               ▼                         ▼
                        ┌──────────────┐         ┌─────────────┐
                        │    Redis     │         │  PostgreSQL │
                        │   (Pub/Sub)  │         │   (State)   │
                        └──────────────┘         └─────────────┘
```

## 🚀 Quick Start
```bash
# Clone the backend
git clone https://github.com/codejam-org/codejam-backend.git
cd codejam-backend

# Run with Docker Compose
docker-compose up -d

# Backend runs on http://localhost:8080
# Frontend runs on http://localhost:3000
```

## 🤝 Contributing

We're actively building CodeJam and welcome contributions! 

1. Check out our [Contributing Guidelines](CONTRIBUTING.md)
2. Pick an issue labeled `good-first-issue`
3. Fork, code, and submit a PR

## 📋 Roadmap

- [x] Real-time text synchronization
- [x] WebSocket connection management
- [ ] Code execution engine
- [ ] Video/voice integration
- [ ] Syntax highlighting for 10+ languages
- [ ] Docker-based session isolation
- [ ] Authentication & user management
- [ ] Persistent session history

## 📄 License

MIT License - See [LICENSE](LICENSE) for details

## 🔗 Links

- **Documentation**: [Coming Soon]
- **Discord**: [Coming Soon]
- **Issues**: [Report bugs](https://github.com/codejam-org/codejam-backend/issues)

---

**Status**: 🚧 Active Development | Not Production Ready
