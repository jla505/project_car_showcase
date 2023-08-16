# Cartopia 

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/jla505/firechat">
    <img src="public/logo192.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Chat App</h3>

  <p align="center">
    A live chat app built with React and Firebase
    <br />
    <a href="https://github.com/jla505/firechat"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/jla505/firechat/issues">Report Bug</a>
    ·
    <a href="https://github.com/jla505/firechat/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)
[![Product Name Screen Shot][product-screenshot2]](https://example.com)
[![Product Name Screen Shot][product-screenshot3]](https://example.com)

A web chat app built with React and Firebase utilizes the powerful features of both technologies to create a real-time messaging application. Here's a description of how such an app could be constructed:

1. User Authentication: The app would include user authentication functionality using Firebase Authentication. Users would be able to sign up, log in, and log out using social logins such as Google.

2. Real-time Database: Firebase Realtime Database is used as the backend database for storing and synchronizing chat messages in real time. These NoSQL databases would allow for efficient, scalable, and synchronized storage of chat messages between users.

3. React Components: The app's user interface would be built using React components. The main components include a chat room component that displays the messages and an input component for users to enter new messages.

4. Real-time Messaging: Using Firebase's real-time capabilities, the app would update the chat interface in real time as new messages are sent or received. When a user sends a message, it would be instantly displayed in the chat room for all participants. 

5. Toggle dark / light theme

6. Create and delete private chats

7. Create, manage, leave and delete public chats

8. Responsive design

By combining the power of React for building interactive user interfaces and Firebase for real-time data synchronization, authentication, and database management, a web chat app can be created that provides a seamless and responsive messaging experience for users.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![React][React.js]][React-url]
* [![Firebase][Firebase.com]][Firebase-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at Google Firestore 
2. Clone the repo
   ```sh
   git clone git@github.com:jla505/firechat.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `.env`
   ```js
   REACT_APP_API_KEY={apiKey}
   REACT_APP_API_KEY={apiKey}
   REACT_APP_AUTH_DOMAIN={authDomain}
   REACT_APP_PROJECT_ID={projectId}
   REACT_APP_STORAGE_BUCKET={storageBucket}
   REACT_APP_MESSAGING_SENDER_ID={senderId}
   REACT_APP_APP_ID={appId}
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this web app to chat with others or experiment with the code!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/jla505/firechat/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@_jimbojl](https://twitter.com/_jimbojl) - jinwoodjin@gmail.com

Project Link: [https://github.com/jla505/firechat](https://github.com/jla505/firechat)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jin-liang/
[product-screenshot]: public/Screenshot1.png
[product-screenshot2]: public/Screenshot2.png
[product-screenshot3]: public/Screenshot3.png
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Firebase.com]: https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase
[Firebase-url]: https://firebase.google.com/?gad=1&gclid=Cj0KCQjw2eilBhCCARIsAG0Pf8t2asDzDpbc8faGmt2duOrqyMrAMkVL1_EE-ZOY6xe_90xF_6nNgUoaAkuaEALw_wcB&gclsrc=aw.ds