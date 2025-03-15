# AlbumQuest

**AlbumQuest** is a dynamic web application that enables users to search for albums by their favorite artists using the Spotify API. Built with modern web technologies, it offers a vibrant, festival-inspired user interface.

## Features

- **Artist Search**: Input an artist's name to retrieve their albums.
- **Album Display**: View album covers, titles, and release dates in a responsive grid.
- **Direct Links**: Access albums directly on Spotify.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Vite**: Fast development server and build tool.
- **React-Bootstrap**: Pre-styled components for responsive design.
- **Spotify API**: Fetches artist and album data.
- **CSS**: Custom styles for a festive theme.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/turjoy18/Spotify-Album-Finder.git
   cd Spotify-Album-Finder
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up Spotify API credentials**:

   - Create a `.env` file in the project root.
   - Add your Spotify Client ID and Secret:

     ```
     VITE_CLIENT_ID=your_spotify_client_id
     VITE_CLIENT_SECRET=your_spotify_client_secret
     ```

### Running the Application

Start the development server:

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser.

## Project Structure

- `src/`: Contains the main React components.
- `public/`: Static assets.
- `index.html`: Main HTML file.
- `App.jsx`: Core component handling search and display logic.
- `App.css`: Custom styles for the application.

## Key Components

- **App.jsx**: Manages state, handles API requests, and renders the UI.
- **App.css**: Defines the festive theme with vibrant colors and fonts.

## Styling and Theme

The application features a music festival vibe with:

- **Bright Colors**: Red, blue, and green splashes.
- **Festive Fonts**: 'Concert One' and 'Press Start 2P' from Google Fonts.
- **Responsive Layout**: Cards adjust to different screen sizes.

## API Integration

Utilizes the Spotify API to:

- Obtain an access token using client credentials.
- Search for artists based on user input.
- Fetch albums of the selected artist.

## Deployment

To build for production:

```bash
npm run build
```

Serve the contents of the `dist/` directory using your preferred hosting service.

## Acknowledgments

- [Spotify for Developers](https://developer.spotify.com/)
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [React-Bootstrap](https://react-bootstrap.github.io/)
- [Google Fonts](https://fonts.google.com/)

---

Feel free to explore and enhance AlbumQuest to suit your preferences! 
