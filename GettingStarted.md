#Steps


1. signup at github.com
2. create repo
3. mkdir ~/gitstuff
4. cd ~/gitstuff
5. mkdir yourrepo
6. cd yourrepo
7. git init
8. follow steps to merge new repo with github
9. sudo chown -R yourusername ../*
10. create Gemfile : https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

    source 'https://rubygems.org'
    gem 'github-pages', group: :jekyll_plugins

11. bundle install
12. copy in jekyll template
13. edit baseurl to be blank "" in config.yml
    baseurl:
14. jekyll serve -w
15. open browser and go to localhost:4000
