# TIPS / KNOWLEDGE / SHARING FOR THE WIN
Tips / information sharing / onboarding stuff for CfA

## Basics
* [Markdown intro](./markdown.md)
* [GIT intro](./git-intro.md) | [Setting up git on a ubuntu server](https://www.linux.com/learn/how-run-your-own-git-server)

## Blogging
### Jekyll
1. Create a new **blank** repo, use a reponame like [name-of-your-organisation]-blog
2. On your machine do a `git clone https://github.com/CodeforAustralia/[reponame].git` inside a folder of your choice
2. Create an orphaned `gh-pages` branch via `git checkout --orphan gh-pages`
3. Download a zip of the [jekyll-now](https://github.com/barryclark/jekyll-now) repo
4. On your machine, unzip the contents to the root of the folder that you cloned your repo to
5. `git add -A` then `git commit -m "Added jekyll-now."` then `git push origin gh-pages`. You will be prompted for username and password, use your own github account data, but make sure you are a contributor to codeforaustralia on GitHub first.
6. Your blog should be now available at http://codeforaustralia.github.io/[name-of-your-repo]
7. Map a domain / subdomain to your github.io url 👍🏽
8. Have a beer / wine / coffee and chill 🍻

## DigitalOcean
* [Adding a SSH Key](https://www.digitalocean.com/community/tutorials/how-to-use-ssh-keys-with-digitalocean-droplets)

## Dokku - heroku style deployments
* [Setting up dokku](https://www.andrewmunsell.com/blog/dokku-tutorial-digital-ocean/) | [Adding ssh key for dokku](https://www.digitalocean.com/community/questions/dokku-add-new-ssh-key)
* [Dokku docs](http://dokku.viewdocs.io/dokku~v0.4.2/application-deployment/)
* [Dokku deploying](http://dokku.viewdocs.io/dokku~v0.4.2/application-deployment/#deploying-to-subdomains)
* [Letsencrypt ssl](http://revelry.co/deploy-free-ssl-lets-encrypt-dokku/) | [Dokku SSL](http://morrisjobke.de/2016/02/21/Dokku-Easy-way-to-deploy-web-apps/)
* [Configure dokku nginx](http://dokku.viewdocs.io/dokku/nginx/#default-site)
* [dokku mongo](https://github.com/dokku/dokku-mongo) | [dokku + mongodb setup](https://gist.github.com/fizerkhan/029617fd75cdb167db7c)
* [dokku vm's < 1GB](http://dokku.viewdocs.io/dokku/advanced-installation/#vms-with-less-than-1gb-of-memory)

## Dev tools 
* [Astrum](http://astrum.nodividestudio.com/): document your web pattern library (think Bootstrap's doc webpage, but for your CSS)
* [Perftool](http://performance-tool.devbridge.com/): collect & display performance stats for your web project

## Design tools
* [colordrop.io](colordrop.io/): find nice colour palettes
* [Principal](http://principleformac.com/): animate prototypes 

## General tools
* [Gitify](http://gitify.io/): get Github notifications on Mac menubar
