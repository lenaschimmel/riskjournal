<!-- PROJECT LOGO -->
# RiskJournal

<!-- TABLE OF CONTENTS -->
## Table of Contents

- [RiskJournal](#riskjournal)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

This product is in very early development and **SHOULD NOT BE USED YET**.

RiskJournal consists of multiple repositories:
 * __riskjournal__ - This repository. General overview and a docker-compose config to run _riskjournal-server_ and _covid-incidence-germany_ together
 * __riskjournal-cli__ - A node.js command line application to track personal covid risk. Currently this combines the application logic and the interface, but it will be split into two repositories later.
 * __riskjournal-server__ - A simple server which lets multiple instances of _riskjournal-cli_ exchange data, and hosts incidence data that it gets from _covid-incidence-germany_
 * __covid-incidence-germany__ - Downloads the covid case statistics and computes the daily incidence for each district and age group

<!-- GETTING STARTED -->
## Getting Started

_To be defined_

### Prerequisites

* docker
* docker-compose

### Installation

1. Clone the repo
```sh
git clone git@github.com:lenaschimmel/riskjournal.git
```
2. Run the script…
```sh
./up.sh
```
3. …or run it manually
```sh
docker-compose build && docker-compose up -d && docker-compose logs -f
```

<!-- USAGE EXAMPLES -->
## Usage

_To be defined_


<!-- ROADMAP -->
## Roadmap

_To be defined_

See the [open issues](https://github.com/lenaschimmel/riskjournal/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

_To be defined_


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@lenaschimmel](https://twitter.com/lenaschimmel) - mail@lenaschimmel.de

Project Link: [https://github.com/lenaschimmel/riskjournal](https://github.com/lenaschimmel/riskjournal)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [microCOVID](https://github.com/microcovid/microcovid)
* [Readme template](https://github.com/othneildrew/Best-README-Template)
