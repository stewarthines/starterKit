# Web Starter Kit
My little web starter kit. 

## About

## Figma Doc

## Using Jekyll
- In the `config.yml` add the BaseURL
- To start the server run `jekyll serve --watch --baseurl ""` 

## Using CodeKit
- I use [CodeKit3](https://codekitapp.com/) to compile my SCSS and refresh my browser.
- Focus on master.scss
  - compile this
  - create a src map
  - run autoprefixer
  - run libsass
- Don't commit the `config.codekit3` file to the repo. 
### CodeKit + Jekyll
- set CodeKit to use an external server
- in `config.yml` add `config.codekit3` to the list of excluded files. 
