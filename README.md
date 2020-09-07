## What am I?
⭐ A Nuxt boilerplate project for 2020.  Enhanced with built in support for PWA, GZip, mobile-first (i.e. SASS MQ), unit testing and more.  

## Preview
[Click here to see a live version](https://nuxt-202x.herokuapp.com/)

## Complete walkthrough on how to deploy to Heroku
[Click here to see a tutorial on how to deploy to Heroku in 10 easy steps](https://jyn-labs-2020.herokuapp.com/blog/2020/SEP/7/how_to_deploy_a_nuxt_site_on_heroku_in_10_easy_steps)

## Core technologies
- [Nuxt 2.x](https://nuxtjs.org/) 
- [Vue 2.x](https://vuejs.org/) 
- [Vuex 3.x](https://github.com/vuejs/vuex)
- [Jest](https://jestjs.io/)
- [Sass MQ](https://github.com/sass-mq/sass-mq) 
- ES6/7 support (via Babel) 

## Install instructions:
```sh
$ git clone https://github.com/allenRoyston/nuxt-202x.git
$ cd nuxt-202x
$ npm install 
$ npm run dev
$ // open browser at http://localhost:1234
```

## Blog Automation:
To generate the links that the blog section will use, use the command:
```sh
$ npm run create:all
```
This will generate a JSON schema the Blog.vue component will utilize to automatically display your latest links.  It can be found in static/JSON.  If you wish to tweak the JSON structure, you can alter the code in node/buildBlog.js

## Auto deployment
If you have this repo in Github, you can run this command to automatically add and push for you.  It will also automatically update your link/blog pages.
```sh
$ npm run git
```

## Unit testing
Make sure Jest is installed globally before running unit tests.
``` sh
$ npm install jest -g
$ npm run test
```

