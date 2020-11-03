<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
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
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Smart School </h3>

  <p align="center">
    This is an online platform for learning programming .
    <br />
    <a href="https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development">View Demo</a>
    ·
    <a href="https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/issues">Report Bug</a>
    ·
    <a href="https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

About me

### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [server](https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/server)
  * [Python 3.8](https://docs.python.org/release/3.8.6/)
  * [Virtual environment](https://www.enterprisedb.com/postgres-tutorials/how-use-postgresql-django)
  * [Django 3.1.2](https://docs.djangoproject.com/en/3.1/releases/3.1.2/)
  * [PostgreSQL 9.5.23](https://www.postgresql.org/docs/9.5/index.html)
  * [Bootstrap 4.5](https://getbootstrap.com)
  * [pip3](https://linuxize.com/post/how-to-install-pip-on-ubuntu-18.04/)
* [Client](https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/client)
  * [Node v8.9.4 or more recent version](https://nodejs.org/en/docs/)
  * [Bootstrap 4.5](https://getbootstrap.com)




<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

* __Server__

* Install python 3.8
```sh
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.8
sudo apt install python3.8-distutils
```


* Install  PostgreSQL
```sh
sudo apt update
sudo apt install postgresql postgresql-contrib

Connect PostgreSQL

sudo -u postgres psql

create database and user this commands

postgres=# create database 'name database';
postgres=# create user 'username' with password 'password';
postgres=# grant all privileges on database 'name database' to 'username';
```

* Install pip3

```sh
sudo apt-get update
sudo apt-get -y install python3-pip
```

* Install virtual environment
```sh
sudo apt-get install python3.8-venv
```

### Installation


1. Clone the repo
```sh
git clone https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/server
```
2. Go to the repository you just cloned
```sh
$cd Online_learning_platform/
```
3. Create virtual environment
```sh
python3 -m venv venv
```
4. Activate virtual environment
```sh
source venv/bin/activate
```
5. Install server dependencies
```sh
cd server/
pip3 install -r requirements.txt
```
5. Open .env file and save  your data
```sh
SECRET_KEY = SECRET_KEY
NAME = NAME
USER_NAME = USER_NAME
PASSWORD = PASSWORD
HOST = HOST
PORT = PORT
```


<!-- USAGE EXAMPLES -->
## Usage

## Insert database
```sh
open a new terminal
cd Online_learning_platform/
pg_restore -U <db_user> -d <db_name> -Fc db.dump>
```

## Migrate the database
```sh
python3.8 manage.py makemigrations
python3.8 manage.py migrate
```


## Create super user
```sh
python3.8 manage.py createsuperuser
after thi command you need insert user_name, password, email from command line
```


## Start server
```sh
python3.8 manage.py createsuperuser
after thi command you need insert user_name, password, email from command line
```

## Open result in browser
```sh
http://localhost:8000/
```

[![Product Name home page][product-homePage]](https://example.com)

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

<!-- 1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request -->



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development](https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/Instigate-Training-Center-11/Online_learning_platform/tree/development/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[product-homePage]: images/homePage.png
