# shinyaaa.github.io

This is the website of Shinya Kato.

## Version
- Hugo 0.128.0
- Anatole v1.16.2 (Hugo theme)

## Setup
### Create repository
Create a repository named `shinyaaa.github.io` on GitHub.
Set up GitHub Actions Workflow:
- Go to Settings -> Code and automation -> Pages -> Build and deployment -> Source
- Select GitHub Actions -> Hugo

### Start Hugo project
Run the following commands to start a new Hugo project and set up the Anatole theme:
```
git clone https://github.com/shinyaaa/shinyaaa.github.io.git
hugo new site shinyaaa.github.io --force
cd shinyaaa.github.io
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
cd themes/ananke
git switch v1.16.2
cp -a . ../../
```

### Deploy
Just push the main branch.
```
git push origin main
```
