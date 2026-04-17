# AI Chat School & Business Platform

An AI-powered chat application with two distinct modules:
- **School Module**: Peer-reviewed academic answers
- **Business Module**: Calendar integration and Microsoft app connectivity (Word, PowerPoint, Excel, etc.)

## Tech Stack

- **Frontend**: React.js with TypeScript
- **Backend**: Node.js with Express
- **APIs**: Microsoft Graph API
- **Database**: MongoDB (optional, configure as needed)
- **Authentication**: OAuth 2.0 (Microsoft)

## Project Structure

```
ai-chat-school-business/
├── frontend/                 # React application
├── backend/                  # Node.js/Express server
├── docs/                     # Documentation
├── .github/                  # GitHub workflows
└── docker-compose.yml        # Docker configuration
```

## Getting Started

### Prerequisites
- Node.js 16+
- npm or yarn
- Microsoft Azure account (for Graph API)

### Installation

1. Clone the repository
```bash
git clone https://github.com/Jrodblank130324/ai-chat-school-business.git
cd ai-chat-school-business
```

2. Install frontend dependencies
```bash
cd frontend
npm install
```

3. Install backend dependencies
```bash
cd ../backend
npm install
```

4. Set up environment variables (see .env.example files)

### Running Locally

**Backend:**
```bash
cd backend
npm run dev
```

**Frontend:**
```bash
cd frontend
npm start
```

## Features

### School Module
- AI-powered Q&A
- Peer review system
- Answer rating and feedback
- Academic integrity checks

### Business Module
- Calendar integration (Microsoft Outlook)
- Microsoft Word document creation/editing
- PowerPoint presentation management
- Excel spreadsheet integration
- Real-time collaboration

## API Documentation

See `/docs/API.md` for detailed endpoint documentation.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

MIT License - see LICENSE file for details

## Support

For issues and feature requests, please use the GitHub Issues page.
