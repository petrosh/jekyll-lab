jekyll-lab
==========

jekyll playground on github-pages http://petrosh.github.io/jekyll-lab

deploying
---------

### build

- ```bundle install``` after adding gems in ```_config.yml```  
- ```bundle exec jekyll serve```

### mirriored on *gh-pages* branch

- ```git push -f origin master:gh-pages```  
- `git remote set-url origin git@github.com:petrosh/jekyll-lab.git` to avoid password input
