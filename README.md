
## Demo Website

Before anything else, make sure you have a working version of NodeJS and npm.

Install Hugo (`https://gohugo.io/installation/`). The easiest way on Linux is:

```
sudo snap install hugo
```

Clone this repository, then do:

```
git submodule update --init --recursive
npm install
```

To develop:
```
npm run dev
```

To build:
```
npm run build
```

To deploy:
```
npm run deploy
```
