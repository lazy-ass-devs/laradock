# LazyAssDevs Laradock 

This is a forked repository of laradock. This project will install the dependencies needed in LazyAssDevs Backend projects.

Checkout their awesome project
- [Repository](https://github.com/laradock/laradock)
- [Docs](https://laradock.io/)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
- [Docker](https://www.docker.com/)

### Installing

Copy the envrionment file.
```
cp env-example .env
```
Setup your MySQL configuration after copying the environment file.

Install docker images that will be used in this project.
```
sudo docker-compose up -d
```

## Contributing
Follow these steps to orchestrate the projects
https://laradock.io/getting-started

Primarily, we will implement multiple projects
https://laradock.io/getting-started/#b-setup-for-multiple-projects

Update the [lazyassdevs-compose.yml](https://github.com/lazy-ass-devs/laradock/blob/master/lazyassdevs-compose.yml) file when you want to add docker images.
