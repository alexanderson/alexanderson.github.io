# alexanderson.github.io

The repo for my personal GitHub Pages site. Mainly for hosting my digital CV.

The site is a static react app instantiated with `create-react-app`.

## Build

The site is built using `yarn build`. 

On push to `master`, GitHub actions perform this build and push the resulting 
`build` directory to `gh-pages` branch which is then served as a GitHub Pages
site.
