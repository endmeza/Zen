<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">Developer's Portfolio <33</h1>

  <p align="center">
    It is a personal static website/portfolio template hosted with GitHub Pages, built to showcase my recent projects.
    <br />
    <strong>Site URL / Demo » </strong>
    <a href="https://endmeza.github.io/portfolio"> endmeza.github.io/portfolio</a>
    <br />
    <br />
    <a href="https://endmeza.com">About Me</a>
    ·
    <a href="https://github.com/endmeza/portfolio/issues">Report Bug</a>
    ·
    <a href="https://github.com/endmeza/portfolio/issues">Request Feature</a>
  </p>
</p>

[![GitHub forks](https://img.shields.io/github/forks/endmeza/portfolio?style=for-the-badge)](https://github.com/endmeza/portfolio/network)
[![GitHub license](https://img.shields.io/github/license/endmeza/portfolio?style=for-the-badge)](https://github.com/endmeza/portfolio/blob/master/LICENSE)
[![Twitter Follow](https://img.shields.io/twitter/follow/endmeza?color=ffcc66&logo=twitter&logoColor=ffffff&style=for-the-badge)](https://twitter.com/endmeza)
[![Node Version](https://img.shields.io/static/v1?label=Node&message=16.16.0&color=026e00&style=for-the-badge)](https://nodejs.org)
[![npm Version](https://img.shields.io/static/v1?label=npm&message=8.11.0&color=cb0000&style=for-the-badge)](https://nodejs.org)


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#setup">Setup</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
# About The Project

[![Product Name Screen Shot](/READMEdocs/front-image.gif)](https://example.com)





<!-- GETTING STARTED -->
# Getting Started

Building your own personal website from this project can take as little as 30 minutes. Follow the setup instructions below. Please feel free to reach out to me by filing an [issue](https://github.com/hashirshoaeb/portfolio/issues) or emailing me at hashirshoaeb@gmail.com for help configuring your project.

## Prerequisites

You should have [Nodejs](https://nodejs.org/en/) and [Git](https://git-scm.com/downloads) installed on your PC. You should also own a GitHub account.

## Setup

1. Fork this repoistory and clone it to your local machine.
    ```sh
      git clone https://github.com/<your-username>/portfolio.git
    ``` 

2. Edit the [config/config.js](https://github.com/hashirshoaeb/portfolio/blob/main/config/config.js) file. Replace [config/profile.png](https://github.com/hashirshoaeb/portfolio/blob/main/config/profile.png) with your image. 
    >Note: You need to rename your image file as `profile.png`.

3. Run following scripts in terminal/command prompt to install dependencies.
    ```sh
      npm install
      npm run build
    ```
## Testing

1. To test on your local server, run the following command:
    ```sh
      npm run dev
    ```

2. Open the browser to http://localhost:3000/

## Deployment

If it works locally, you can deploy your project to GitHub Pages. GitHub Pages provides two types of free domains, `<username>.github.io` and `<username>.github.io/<repository>`. You can choose the one that suits your needs. You can learn more about domain types from [here](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#types-of-github-pages-sites).

### Deploy to \<your-username>.github.io/portfolio

Simply you just need to commit and push your changes to github. And [GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/introduction-to-github-actions#overview) will take care of the deployment. Your site will be available at `https://<your-username>.github.io/portfolio`

### Deploy to \<your-username>.github.io

Create a new repository with your username as `<your-username>.github.io`. And let the following command do the job for you.

```sh
  npm run predeploy
  node scripts/pages.js <your-username> master
```

Your site will be available at `https://<your-username>.github.io`

>Note: You need to replace `<your-username>` with your username. To add CNAME for custom domain, see [scripts/cname.js](https://github.com/hashirshoaeb/portfolio/blob/main/scripts/cname.js)



<!-- CONTRIBUTING -->
# Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contribution you make would be **appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
# License

Distributed under the `MIT` License. See [LICENSE](https://github.com/hashirshoaeb/portfolio/blob/main/LICENSE) for more information.
