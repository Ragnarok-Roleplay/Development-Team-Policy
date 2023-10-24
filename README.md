<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Capttech/CPT_Anticheat">
    <img src="https://imgur.com/T97YTKa.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">CPT Development</h3>

  <p align="center">
    Developing everything from Websites to FiveM resources
    <br />
    <a href="https://capttechs-organization.gitbook.io/cpt-development/"><strong>Explore the docs �</strong></a>
    <br>
    <a href="https://phantom-fire-studios.tebex.io/"><strong>Tebex �</strong></a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about">About</a></li>
    <li><a href="#built-with">Built With</a></li>
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
## About

It is my passion to create well maintained resources that run low usage.

Here's why:
* I focus on the resource usgae to make sure everything runs smoothe
* I use Typescript to make sure everything is parsed properly
* All resources have their own built in discord bot for all logs and messages
* All resources have their own built in SQL clinet so each resource can get the information that they need.

Use the `ReadMe.md` to get started.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

We use the best coding method for wrighting well optimized resources.

* [![Javascript][Javascript.js]][Javascript-url]
* [![Typescript][Typescript.js]][Typescript-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Server CFG Settings
Add the following sets into your server.cfg file. These will need to be defined around the top of the server.cfg
```sh
set cpt_db_host localhost
set cpt_db_port 3306
set cpt_db_user "Username"
set cpt_db_password "Password"
set cpt_db_database qbcore

set cpt_discord_token Discord_Token
set cpt_discord_guild Discord_Guild
```
   

### Server CFG Start
Add the following in your server.cfg to start the resource in your server
```sh
ensure CPT_Anticheat
```

### Prerequisites
There are a few resources that are required. Those are listed below
* QB Core Framework 
    * qb-core
    * qb-menu
    * qb-input
* Polyzone
* XSound

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Purchase the resource at  [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

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

See the [open issues](https://github.com/Capttech/CPT_Anticheat/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

CPT Development - [Discord Server](https://discord.gg/7TrZhvGRGK)

GitHub Link: [https://github.com/Capttech?tab=repositories](https://github.com/Capttech)

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
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/Capttech/CPT_Anticheat/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/Capttech/CPT_Anticheat/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Capttech/CPT_Anticheat/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Capttech/CPT_Anticheat/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/Capttech/CPT_Anticheat/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/joseph-dunn-4198b3261/

[Javascript.js]: https://img.shields.io/badge/logo-javascript-blue?logo=javascript
[Javascript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[Typescript.js]: https://img.shields.io/badge/logo-javascript-blue?logo=typescript
[Typescript-url]: https://nextjs.org/
[JQuery.com]: https://img.shields.io/badge/logo-javascript-blue?logo=jquery
[JQuery-url]: https://jquery.com 

