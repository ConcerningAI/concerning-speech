# concerning-speech
Explore the problem of automatic speech recognition with open source tools and data sets.

## Installing on OS X
### Pre-requisites
* Install HomeBrew
* Use HomeBrew to install:
** git
** nvm
** flac

### Getting and configuring the repo
```sh
mkdir ConcerningAI
cd ConcerningAI
git clone git@github.com:ConcerningAI/concerning-speech.git speech
cd speech
nvm install $(cat .nvmrc)
nvm use $(cat .nvmrc)
```

### Adding the LibriVox files
```sh
cd ConcerningAI/speech
wget http://www.openslr.org/resources/12/dev-clean.tar.gz
tar -zxvf http://www.openslr.org/resources/12/dev-clean.tar.gz
rm dev-clean.tar.gz
```
