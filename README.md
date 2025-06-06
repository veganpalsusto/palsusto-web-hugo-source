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

## Hugo server error

Sometimes you get some error, according to [this website](https://wowchemy.com/docs/hugo-tutorials/troubleshooting/#error-failed-to-resolve-output-format), 
you can try to do the following on your mac: 

```
sudo rm -rf $TMPDIR/hugo_cache/
```

## Updating modules

Consider going [here](https://github.com/HugoBlox/theme-research-group) and check the `go.mod` file to update the requirements of this one. 

## Deploy website 
First, build it to the `public` folder: 

```shell
hugo --minify
```
> ATTENTION! Always use `minify`

Then, go to the `public` folder and push the changes to the repository: 
```shell
cd public
git add .
git commit -m [commit_msg]
git push origin HEAD:main
```
