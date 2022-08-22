# Quick start 

## DO this only once 
Install dependencies
```
brew install hugo golang git
```

Clone repositories and link them to github pages 
```
git clone git@github-palsusto:veganpalsusto/starter-hugo-research-group.git palsusto-content-hugo
git submodule update --init --recursive
git submodule add -f -b main git@github-palsusto:veganpalsusto/veganpalsusto.github.io.git public
```

To run locally
```
hugo server
```

Then open a browser and go to `http://localhost:1313`
