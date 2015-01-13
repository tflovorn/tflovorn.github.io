My Github pages site, constructed with [Jekyll](https://github.com/jekyll/jekyll) and [Poole](https://github.com/poole/poole).

To build locally on Mint 17:

sudo apt-get install ruby ruby-dev
sudo gem install bundler
bundle install

wget https://github.com/poole/poole/archive/v1.1.0.tar.gz
tar -xvzf v1.1.0.tar.gz
mv poole-1.1.0/* .
mv poole-1.1.0/.gitignore .
rmdir poole-1.1.0
rm v1.1.0.tar.gz
