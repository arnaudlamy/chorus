# Ubuntu 14.04

## Packages to install
```bash
sudo apt-get install npm
sudo apt-get install bundler
sudo apt-get install compass-bootstrap-sass-plugin
sudo npm install -g grunt-cli
sudo gem install sass
```

Then in your git folder:

```bash
bundle install --path vendor/bundle
npm install
npm test
```
