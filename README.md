# 🏡&nbsp; [rguyennot.github.io](https://rguyennot.github.io/resume)

[![View website](https://img.shields.io/badge/open%20site-rguyennot.github.io-green)](https://rguyennot.github.io/)
[![Hugo v0.8.4](https://img.shields.io/badge/hugo-v0.8.4-orange)](https://github.com/gohugoio/hugo)
[![Twitter Follow](https://img.shields.io/twitter/follow/rguyennot?label=Follow&style=social)](https://twitter.com/intent/user?screen_name=rguyennot)

Resume of [@rguyennot](https://github.com/rguyennot/resume), created and deployed using the following:

- [Hugo Extended](https://github.com/gohugoio/hugo)
- [Resume](https://github.com/jmousqueton/resume) - The customized Hugo template by [Julien Mousqueton](https://github.com/jmousqueton/resume)

## Demo 

You can see it in action on [devresume](https://themes.3rdwavemedia.com/demo/bs5/devresume/)

## 👍🏻 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## :cd:  Installation

- Create the Hugo project : `hugo init myresume.github.io`
- Go to your new hugo project : `cd myresume.github.io/`
- You can use JMousqueton's `config.toml` in this [repository](https://github.com/JMousqueton/Configuration-Hugo) : `wget https://github.com/JMousqueton/Configuration-Hugo/blob/main/jmousqueton.github.io/config.toml .`
- Add JMousqueton's theme : `cd myresume.github.io/themes ; git clone https://github.com/jmousqueton/resume`
- Edit the file [config.toml](config.toml) with your informations

## 💡 baseURL in config.toml
> WARNING : Unless this is present in your config.toml, your website won’t work !

Don’t forget to rename your **baseURL** in `config.toml` with the value [https://<USERNAME>.github.io]() for your user repository, or [https://<USERNAME>.github.io/<REPOSITORY_NAME>]() for a project repository.

## :rocket:  Running a local testing server

Run `hugo server -D` then open [http://localhost:1313/](http://localhost:1313/). Pages will live-refresh when source files are changed.  

## 🔥 Build and deploy

➡️ To build your site in the `public` folder(within the root of your project), execute the following hugo command : 

(you can stop hugo server with `ctrl+c` before build):  

```shell
hugo
```

➡️ To push the public/ directory to your github repository :   
```shell
cd public/
git remote add origin https://github.com/username/resume.git
git branch -M main
git add .
git commit -m "rebuilding my site $(date)"
git push -u origin main
```

➡️ Go to [https://USERNAME.github.io/<REPOSITORY_NAME>]() an voilà ! 

## 🙎🏻‍♂️ Author

**Rudy GUYENNOT**

## 📜 License

MIT 2.0
