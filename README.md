$ git clone git@github.com:cinsei/Instagram-Search.git
$ cd Instagram-Search
$ git symbolic-ref HEAD refs/heads/gh-pages
$ git clean -fdx
$ cp -a ~/work/* ./
$ git commit -a -m "initial commit"
$ git push origin gh-pages
