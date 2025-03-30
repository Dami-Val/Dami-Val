<div align="right">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Source+Code+Pro&weight=700&duration=2000&pause=1000&color=FC3D21&width=435&lines=%F0%9F%8C%8C+Space+Data+Visualization+%F0%9F%94%AD;%F0%9F%8C%A0+NASA+APIs+Explorer+%F0%9F%8C%8E;%F0%9F%91%A8%E2%80%8D%F0%9F%9A%80+Interplanetary+Data+Hub+%F0%9F%94%AD;%F0%9F%9A%80+Discover+Our+Universe+%F0%9F%8C%8C" alt="Typing SVG" /></a><br>
<a href="https://github.com/Dami-Val/explorador-apod-nasa">
    <img src="https://img.shields.io/badge/React-19.1.0-blue?style=plastic&logo=react&logoColor=61DAFB&labelColor=20232A" alt="React Version" />
</a>
<a href="https://nasa-api-dami-val.vercel.app/">
    <img src="https://img.shields.io/badge/Live-Demo-FF4081?style=plastic&logo=vercel&logoColor=white&labelColor=20232A" alt="Live Demo" />
</a>
<img src="https://img.shields.io/badge/License-MIT-green?style=plastic&logo=license&labelColor=20232A" alt="License" />
<img src="https://img.shields.io/badge/NASA-APIs-0B3D91?style=plastic&logo=nasa&logoColor=white&labelColor=20232A" alt="NASA APIs" />
</div>

[![NASA Explorer Banner](https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=1080&auto=format&fit=crop)](https://nasa-api-dami-val.vercel.app/)

# <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="35" /> Welcome to Explorador NASA!

A comprehensive dashboard for exploring NASA's various APIs, including APOD (Astronomy Picture of the Day), Mars Rover photos, EPIC (Earth Polychromatic Imaging Camera), NEO (Near-Earth Objects), and Exoplanet data. This application provides an intuitive interface to discover the wonders of space! 🚀✨

<p align="center">
  <a href="https://nasa-api-dami-val.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/✨ VISIT LIVE SITE ✨-0B3D91?style=for-the-badge&logo=vercel&logoColor=white" alt="Visit Live Site" width="300"/>
  </a>
</p>

## <img src="https://media.giphy.com/media/3oKIPic2BnoVZkRla8/giphy.gif" width="40"> Key Features

- 🌌 **APOD Explorer**: Discover the astronomy picture of the day with detailed explanations
- 🔴 **Mars Rover Photos**: Browse photos taken by Curiosity, Opportunity, and Spirit rovers
- 🌎 **EPIC Imagery**: View stunning images of Earth taken from the DSCOVR satellite
- ☄️ **NEO Tracker**: Monitor near-Earth objects and their approach details
- 🪐 **Exoplanet Database**: Explore planets outside our solar system with detailed properties

## 🚀 Live Demo & Screenshots

<p align="center">
  <a href="https://nasa-api-dami-val.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/🔭 EXPLORE THE UNIVERSE NOW-FC3D21?style=for-the-badge&logoColor=white" alt="Explore the Universe" width="350"/>
  </a>
</p>

### 📸 Screenshots

<table>
  <tr>
    <td><img src="https://via.placeholder.com/400x225?text=APOD+Explorer" alt="APOD Explorer"/></td>
    <td><img src="https://via.placeholder.com/400x225?text=Mars+Rover+Photos" alt="Mars Rover Photos"/></td>
  </tr>
  <tr>
    <td><img src="https://via.placeholder.com/400x225?text=EPIC+Earth+Images" alt="EPIC Earth Images"/></td>
    <td><img src="https://via.placeholder.com/400x225?text=NEO+Asteroid+Tracker" alt="NEO Asteroid Tracker"/></td>
  </tr>
</table>

> **Note**: Visit the [live site](https://nasa-api-dami-val.vercel.app/) for the full interactive experience!

## 💻 Technologies Used

<p align="center">
  <a href="">
    <img src="https://skillicons.dev/icons?i=react,js,html,css" />
  </a>
</p>

| 🛠️ Technology | ⚙️ Purpose |
|--------------|------------|
| React 19.1.0 | Frontend framework for building the user interface |
| JavaScript | Programming language for application logic |
| HTML/CSS | Markup and styling for the application |
| NASA APIs | Data sources for space-related information |
| Vercel | Hosting platform for the live deployment |

## <img src="https://media.giphy.com/media/LwBpQnYNGtqbQgvEO0/giphy.gif" width="40"> App Sections

| Section | Description |
|---------|-------------|
| 🌌 **APOD API** | Retrieves and displays NASA's Astronomy Picture of the Day, including images, descriptions, and historical archives. Supports searching by date range or specific dates. |
| 🔴 **Mars Rover** | Access photos taken by Mars rovers with filtering by camera type, sol (Martian day), or Earth date. Displays mission information and rover status. |
| 🌎 **EPIC** | Earth Polychromatic Imaging Camera provides full-disc imagery of Earth from the DSCOVR satellite at the L1 Lagrange point. Shows Earth's rotation through daily images. |
| ☄️ **NEO** | Near Earth Object Web Service tracks asteroids and comets that pass close to Earth. Provides orbital data, size estimates, and potential hazard information. |
| 🪐 **Exoplanet** | Access NASA's database of confirmed exoplanets with detailed information about their size, orbit, temperature, and potential habitability. |

## 📊 API Information

The application utilizes five key NASA APIs:

- **APOD API**: `https://api.nasa.gov/planetary/apod`
- **Mars Rover Photos API**: `https://api.nasa.gov/mars-photos/api/v1/rovers`
- **EPIC API**: `https://api.nasa.gov/EPIC/api`
- **NEO API**: `https://api.nasa.gov/neo/rest/v1`
- **Exoplanet Archive API**: `https://exoplanetarchive.ipac.caltech.edu/TAP/sync`

> **Note**: To use this application with full functionality, you'll need a NASA API key. You can obtain one for free at [api.nasa.gov](https://api.nasa.gov).

## 🚀 Installation and Usage

### 🌐 Online Access
The easiest way to use the application is through the [live site](https://nasa-api-dami-val.vercel.app/).

### 💻 Local Development

```bash
# Clone the repository
git clone https://github.com/Dami-Val/explorador-apod-nasa.git

# Navigate to the project directory
cd explorador-apod-nasa

# Install dependencies
npm install

# Create a .env file with your NASA API key
# REACT_APP_NASA_API_KEY=your_api_key_here

# Start the development server
npm start
```

After starting the server, open your browser and navigate to `http://localhost:3000` to use the application.

### 🔑 API Key
To use all features of this application, you'll need a NASA API key. Get yours for free at [api.nasa.gov](https://api.nasa.gov).

## <img src="https://media.giphy.com/media/QpyF0jsO26GWKTWctv/giphy.gif" width="40"> Implementation Details

This application is built with a modular architecture to ensure scalability and maintainability:

- **Component-Based Structure**: Each NASA API has its own dedicated set of components
- **Service Modules**: API interactions are abstracted into service modules
- **Responsive Design**: Adapts to various screen sizes for optimal user experience
- **Animated UI**: Smooth transitions and visual feedback enhance user engagement
- **Error Handling**: Robust error management for API connections and data processing

### 🧩 Project Structure

```
src/
├── components/
│   ├── apod/           # Astronomy Picture of the Day components
│   ├── rover/          # Mars Rover components
│   ├── epic/           # Earth Polychromatic Imaging Camera components
│   ├── neo/            # Near Earth Object components
│   ├── exoplanet/      # Exoplanet components
│   └── common/         # Shared components (Header, Footer, etc.)
├── services/           # API service modules
├── styles/             # CSS styles
└── utils/              # Utility functions
```

### 🔍 Key Features in Detail

- **Interactive Date Selection**: Choose specific dates or date ranges for APOD and other time-based data
- **Dynamic Image Galleries**: Browse collections of space imagery with fluid navigation
- **Data Visualizations**: View asteroid approaches, exoplanet statistics, and other space data
- **Comprehensive Filtering**: Filter Mars rover photos by camera, sol, and more
- **Responsive Layout**: Enjoy the application on any device from desktop to mobile

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- NASA for providing open APIs to access space data
- React community for the powerful frontend framework
- Vercel for the excellent hosting platform
- [Damian Valencia](https://github.com/Dami-Val) for creating and maintaining this project
- All stargazers and followers who support this project

## <img src="https://media.giphy.com/media/VdoIFLsMIlwzfKD520/giphy.gif" width="40"> Contact & Support

📢 Have questions, suggestions, or want to contribute? Feel free to reach out! 🚀

<p align="center">
  <a href="https://github.com/Dami-Val">
    <img src="https://img.shields.io/badge/-GitHub-010409?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:damival.32@gmail.com">
    <img src="https://img.shields.io/badge/-Email-c4211f?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/damian-valencia">
    <img src="https://img.shields.io/badge/-LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

<p align="center">
  <a href="https://nasa-api-dami-val.vercel.app/">
    <img src="https://img.shields.io/badge/Explore the Cosmos-0B3D91?style=for-the-badge&logo=nasa&logoColor=white" alt="Explore the Cosmos" />
  </a>
</p>

<div align="center">
  <img src="https://github.com/Dami-Val.png" width="150" height="150" style="border-radius:50%; border: 3px solid #FC3D21;" alt="Damian Valencia"/>
  
  <h3>About the Creator</h3>
  
  <p>
    <a href="https://github.com/Dami-Val">
      <img src="https://readme-typing-svg.herokuapp.com?font=Source+Code+Pro&size=18&duration=2000&pause=1000&color=0B3D91&center=true&vCenter=true&width=435&lines=Software+Engineering+Student;Space+Enthusiast;NASA+APIs+Explorer;Web+Developer" alt="Typing SVG" />
    </a>
  </p>

  <p>I'm Damian Valencia, a Software Engineering student passionate about space exploration and web development. This project combines my love for astronomy with my programming skills.</p>
  
  <a href="https://github.com/Dami-Val">
    <img src="https://img.shields.io/github/followers/Dami-Val?style=social" alt="Follow on GitHub" />
  </a>
  
  <p>
    <img src="https://komarev.com/ghpvc/?username=Dami-Val&color=0B3D91&style=flat-square&label=Profile+Views" alt="Profile Views" />
  </p>
  
  <p align="center">
    <sub>Made with ❤️ and 🔭 by Damian Valencia</sub>
  </p>
  
  <p align="center">
    <img src="https://raw.githubusercontent.com/Dami-Val/Dami-Val/output/github-contribution-grid-snake-dark.svg" alt="GitHub Snake" width="80%" />
  </p>
</div>
