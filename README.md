# Hamclock Docker

"HamClock is a kiosk-style application that provides real time space weather, radio propagation models, operating events and other information particularly useful to the radio amateur." (Source: Hamclock Website)

Goal of this repository is to build and run Hamclock inside Docker for ease of use.
Hamclock will be exposed as 

This repository does NOT contain any Hamclock source files as it's neither neccessary nor is the licensing clear. The files will be downloaded and compiled during `docker build`.

More information and documentation on the Hamclock Website:
[https://www.clearskyinstitute.com/ham/HamClock/](https://www.clearskyinstitute.com/ham/HamClock/)

## How to use
### Prerequisites
I assume that you're on some form of Linux/Unix system.
Docker and (optionally) Docker Compose are installed.

### Install/Usage
1. Check out this repository
2. Inside the repository run `docker-compose up -d`
3. Quickly open [http://localhost:8081](http://localhost:8081) and set up hamclock
4. Enjoy WB0OEW's hard work

### Advanced (Server/Cloud) usage
At this point I assume you have deeper knowledge on how to use Docker and potentially Kubernetes as well as reverse proxies, so I won't bother to explain the myriad of options on how to get it to run on remote infrastructure.

## Contributing
If you're interested in advancing this, please use the usual workflow of forking and creating a pullrequest.

## Future Plans
Customize Hamclock configuration via config file and writing the eeprom file as detailed on the website>user contrib>5.

Thanks to WB0OEW for his great ham radio tool!
73