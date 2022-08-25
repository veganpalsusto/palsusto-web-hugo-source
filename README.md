# Quick start 

## DO this only once 
Install dependencies
```shell
brew install hugo golang git
```

Clone repositories and link them to github pages 
```
git clone git@github.com:veganpalsusto/palsusto-web-hugo-source.git palsusto-source-hugo
git submodule update --init --recursive
git submodule add -f -b main git@github.com:veganpalsusto/veganpalsusto.github.io.git public
```

To run locally
```shell
hugo server --disableFastRender 
```

Then open a browser and go to `http://localhost:1313`
