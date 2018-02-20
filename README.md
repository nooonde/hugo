### Install Homebrew on Mac
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Install HUGO on Mac
`brew install hugo`

### Install HUGO on Linux
`snap install hugo`

### ADD /docs Folder to config.toml
`publishDir = "docs"`

### Change baseURL to your GitHub Pages
`baseURL = "https://xxxx.github.io/xxxx/"`

### Generate Site with Terminal-Command
`hugo`

### Delete /public Folder if necessary
`rm public -r`

### GIT Initialize and Push all (ignore .gitignore)
```
git init
git remote add origin https://github.com/nooonde/hugo.git
git add --all
git commit -m "Initial commit"
git push -u origin master
```

### GIT Pull
`git pull origin master`

### GIT Push
```
git add .
git commit -m "First Upload"
git push origin master
```

### On GitHub go to your repository - Settings - GitHub Pages - Source - master branch /docs folder

### Dont forget to generate the Site before another GIT Push
`hugo`
