# jekyll-tailwind-template
WebVolta's website template for Jekyll, tailwindcss, Node.js, npm, and Yarn.

## Setup Development App

### Jekyll
To install Jekyll, you will need Ruby installed.  Install the bundle
```
bundle install
```
### Javascript
To setup the JS part of the app, you will need NodeJS and NPM installed.  Install yarn:
```
npm install yarn
```
and then to install the dependencies:
```
yarn
```
## Running Jekyll Serve
If you're not changing tailwind.config.js, you can run Jekyll normally:
```
jekyll serve
```
For local development.  If you intend to make changes to the tailwind.confi.js file, you can run jekyll
with an environment variable that skips caching which ignores the js file:
```
SKIP_CACHING_CSS=true jekyll serve
```
