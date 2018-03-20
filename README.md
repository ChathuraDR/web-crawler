# web-crawler

## Install phantomjs
Navigate over to the [phantomjs website](http://phantomjs.org/download.html "phantomjs download link") to the installation area.Download the zip file.

  - $ `bunzip2 phantomjs-x.x.x.tar.bz2`
  - $ `tar xvf phantomjs-x.x.x.tar`
  - $ `sudo cp -r phantomjs-x.x.x/ /opt/`
  - $ `cd /opt/phantomjs-x.x.x`
  
  - $ `sudo ln -sf ``pwd``/bin/phantomjs /usr/local/bin/phantomjs`

## Install casperjs
Casper depends on phantomjs, like jquery built on javascript.

  - $ `git clone git://github.com/casperjs/casperjs.git`.
  - $ `mv casperjs /opt/casperjs`
  - $ `cd /opt/casperjs`
  - $ `sudo ln -sf ``pwd``/bin/casperjs /usr/local/bin/casperjs`


