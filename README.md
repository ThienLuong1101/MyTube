#Youtube Clone 

# MyTube - YouTube Clone with Video Chat

A React-based YouTube clone application featuring video streaming, channel management, and real-time peer-to-peer video chat functionality. The application supports both light and dark themes for enhanced user experience.

## Features

### Core Functionality
- YouTube video streaming
- Channel browsing and management
- Video search capabilities
- Real-time peer-to-peer video chat
- Responsive design
- Dark/Light theme toggle

### Video Chat Features
- Real-time video conferencing
- Audio controls
- Camera controls
- Unique room ID generation
- Screen sharing capabilities
- Leave meeting functionality

## Technology Stack

- **Frontend Framework**: React.js
- **Routing**: React Router v6
- **UI Components**: Material-UI (MUI)
- **Video Player**: React Player
- **Real-time Communication**: Agora SDK
- **Styling**: CSS, Bootstrap
- **Theme Management**: next-themes
- **Icons**: Material Icons

## Prerequisites

Before running this application, make sure you have:
- Node.js (v14 or higher)
- npm or yarn package manager
- YouTube Data API key
- Agora SDK credentials

## Installation



**Install dependencies**
```bash
npm install
# or
yarn install
```


## Available Routes

- `/` - Home page with video feed
- `/video/:id` - Individual video page
- `/channel/:id` - Channel details page
- `/search/:searchTerm` - Search results page
- `/room/:roomId` - Video chat room

## Theme Configuration

The application supports both light and dark themes:

### Light Theme
```javascript
const lightTheme = {
  palette: {
    primary: {
      main: '#000000',
      contrastText: '#ffffff',
    },
    background: {
      default: '#ffffff',
    },
    text: {
      primary: '#000000',
    },
  },
}
```

### Dark Theme
```javascript
const darkTheme = {
  palette: {
    primary: {
      main: '#ffffff',
      contrastText: '#000000',
    },
    background: {
      default: '#000000',
    },
    text: {
      primary: '#ffffff',
    },
  },
}
```

## Running the Application

1. **Development mode**
```bash
npm start
# or
yarn start
```
The application will run on `http://localhost:3000`

2. **Build for production**
```bash
npm run build
# or
yarn build
```

## Video Chat Usage

1. Navigate to a video page
2. Click on the video chat button
3. Allow camera and microphone permissions
4. Share the room ID with other participants
5. Use the control panel to:
   - Toggle camera
   - Toggle microphone
   - Leave the meeting


Link to the website: https://66a31ad6bc7eee14b18871c5--deluxe-cucurucho-7f318f.netlify.app/

I give a credit to: https://www.youtube.com/watch?v=FHTbsZEJspU I learnt from him
