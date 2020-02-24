## site

Source code of my personal website on Hugo

## Using
# Install Hugo
    sudo pacman -S hugo
# Make site
    hugo new site d351d3r
    cd d351d3r
    git init
# Add your theme
    git submodule add  https://github.com/naro143/hugo-coder-portfolio themes/coder-portfolio
    hugo server -D
    cd themes/coder-portfolio
    make
    
    cd ...
    hugo
# The finished site is collected in the "public" folder, and we will put it in a separate repository for creating a site
    cd public
    git init
    git remote add origin git@github.com:d351d3r/d351d3r.github.io.git
    git fetch origin
    git push -u origin master
    git add .
    git commit -m "first commit"
    git push -u origin master
