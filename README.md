## site

Source code of my personal website on Hugo

## Using
    hugo new site d351d3r
    cd d351d3r
    git init
    git submodule add  https://github.com/naro143/hugo-coder-portfolio themes/coder-portfolio
    hugo server -D
    cd themes/coder-portfolio
    make
    cd ...
    hugo
    cd public
    git init
    git remote add origin git@github.com:d351d3r/d351d3r.github.io.git
    git fetch origin
    git push -u origin master
    git add .
    git commit -m "first commit"
    git push -u origin master
