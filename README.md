# Hexo_Legaod_Blog
Legaod_Blog的Hexo文件


```bush
mkdir -p ./source/_posts
mkdir -p ./themes/butterfly
git clone -b mine https://github.com/Edge-coordinates/hexo-theme-butterfly.git ./themes/butterfly
git clone -b master https://github.com/jerryc127/hexo-theme-butterfly.git
git clone https://github.com/Edge-coordinates/Legaod_Blog.git ./source/_posts
git pull --ff-only

git fetch --all
git reset --hard origin/main
git pull
```