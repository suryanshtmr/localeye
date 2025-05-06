
# LocalEye

LocalEye is a community-driven platform that enables citizens to report and track local civic issues in their neighborhoods. Users can report problems like potholes, streetlight failures, garbage dumps, and other civic issues with photos, descriptions, and precise location data.

## Features

- 📱 User-friendly interface for reporting issues
- 📍 Location-based issue tracking
- 📸 Photo upload support
- 🗺️ Interactive map view
- 🔍 Search and filter issues
- 👥 Community engagement
- 📊 Issue status tracking

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js + Express
- **Database**: MongoDB
- **Storage**: Cloudinary (for image storage)
- **Maps**: Google Maps API
- **Hosting**: Vercel (Frontend) + Render (Backend)

## Project Structure

```
localeye/
├── client/                 # Frontend React application
├── server/                 # Backend Node.js application
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- Google Maps API key
- Cloudinary account

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/localeye.git
cd localeye
```

2. Install frontend dependencies:
```bash
cd client
npm install
```

3. Install backend dependencies:
```bash
cd ../server
npm install
```

4. Set up environment variables:
   - Create `.env` files in both client and server directories
   - Add necessary API keys and configuration

5. Start the development servers:
   - Frontend: `cd client && npm start`
   - Backend: `cd server && npm run dev`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
