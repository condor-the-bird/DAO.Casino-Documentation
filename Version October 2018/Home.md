
# DAO.Casino SDK et al.

New to DAO and want learn more about the protocol and its benefits? Navigate to the **About**... chapter.

Want to dive into details? Check the detailed **Documentation**. 

For a quick start, read below.

# DC Quick Start

## SDK Deployment

### Prerequisites 
- Docker: https://www.docker.com/products/docker-desktop
- Node.js v10: https://nodejs.org/en/

### Install CLIs
```
  sudo npm i -g truffle
  sudo npm i -g dc-cli
```

## Create Initial DApp

```bash
  dc-cli create daocasino/sdk ./myDapp
  cd ./myDapp
  dc-cli start
```

## Build Game

At game directory call:

```bash
  dc-cli build
  cd ./build
  zip -r game.zip ./
  # open .
```

Then send game.zip file to the platform.
