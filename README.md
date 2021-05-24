 [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Stargazers][stars-shield]][stars-url]
  [![MIT License][license-shield]][license-url]
  [![Issues][issues-shield]][issues-url]
  [![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/SaswatM-62/Video-Call-Application-Frontend">
    <img src="images/video-call.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Video Call Application Frontend</h3>

  <p align="center">
    The Frontend of the video call application built using React.js and MaterialUI
    <br />
    <a href="https://vc-frontend-sm.netlify.app/">View Demo</a>
    ·
    <a href="https://github.com/SaswatM-62/Video-Call-Application-Frontend/issues">Report Bug</a>
    ·
    <a href="https://github.com/SaswatM-62/Video-Call-Application-Frontend/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://vc-frontend-sm.netlify.app/)

This project consists of the frontend of Video Call Application. The backend repository can be found here: [Backend](https://github.com/SaswatM-62/Video-Call-Application-Backend).  
The frontend is built using React.js and MaterialUI is used for the design. Socket-io.client library is used to allow the client to communicate to the server. The live video and audio of the clients are shared using simple-peer library.
To make a call from one client to another, a user id must shared using which the call can be made.
The backend server must be running before the running the client-side code for the application to work.
      
### Built With

The project is built with
* [React.js](https://reactjs.org/)
* [MaterialUI](https://material-ui.com/)

  

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

You need to have Node.js installed to run this application  
* How to install [Node.js](https://nodejs.org/en/)
* npm
  ```sh
  npm install npm@latest -g
  ```
  
  
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/SaswatM-62/Video-Call-Application-Frontend.git
   ```
2. Open the project folder in the terminal
   ```sh
   cd Video-Call-Application-Frontend
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
  
  
<!-- USAGE EXAMPLES -->
## Usage

Once you have completed the installation, you can run the development server locally by executing the following command in the terminal
   ```sh
   npm start
   ```
This will start the development server on port 3000.  
The connection to the backend is made in line number 7 of SocketContext.js in the src folder. The correct backend url must be specified for the application to work.

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/SaswatM-62/Video-Call-Application-Frontend/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.md` for more information.



<!-- CONTACT -->
## Contact

Saswat Mishra - [@TheSaswat](https://twitter.com/TheSaswat) - [LinkedIn][linkedin-url] - saswat.mish62@gmail.com

Project Link: [https://github.com/SaswatM-62/Video-Call-Application-Frontend](SaswatM-62/Video-Call-Application-Frontend)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [Font Awesome](https://fontawesome.com)
* [UXWing](https://uxwing.com/)
* [Unsplash](https://unsplash.com/)
* [socket.io-client](https://www.npmjs.com/package/socket.io-client)
* [react-copy-to-clipboard](https://www.npmjs.com/package/react-copy-to-clipboard)
* [simple-peer](https://www.npmjs.com/package/simple-peer)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/SaswatM-62/Video-Call-Application-Frontend?color=Green&style=for-the-badge
[contributors-url]: https://github.com/SaswatM-62/Video-Call-Application-Frontend/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/SaswatM-62/Video-Call-Application-Frontend?style=for-the-badge
[forks-url]: https://github.com/SaswatM-62/Video-Call-Application-Frontend/network/members
[stars-shield]: https://img.shields.io/github/stars/SaswatM-62/Video-Call-Application-Frontend?style=for-the-badge
[stars-url]: https://github.com/SaswatM-62/Video-Call-Application-Frontend/stargazers
[issues-shield]: https://img.shields.io/github/issues/SaswatM-62/Video-Call-Application-Frontend?style=for-the-badge
[issues-url]: https://github.com/SaswatM-62/Video-Call-Application-Frontend/issues
[license-shield]: https://img.shields.io/github/license/SaswatM-62/Video-Call-Application-Frontend?style=for-the-badge
[license-url]: https://github.com/SaswatM-62/Video-Call-Application-Frontend/blob/main/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/saswatmishra71
[product-screenshot]: images/screenshot.png
