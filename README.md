# TIPS / KNOWLEDGE / SHARING FOR THE WIN
Tips / information sharing / onboarding stuff for CfA

## Create a jekyll blog
1. Create a new **blank** repo, something like [name-of-your-organisation]-blog
2. On your machine do a `git clone https://github.com/CodeforAustralia/[reponame].git`
2. Create an orphaned `gh-pages` branch via `git checkout --orphan gh-pages`
3. Download a zip of the [jekyll-now](https://github.com/barryclark/jekyll-now) repo
4. On your machine, unzip the contents to the root of the folder that you cloned your repo to
5. `git add -A` then `git commit -m "Added jekyll-now."` then `git push origin gh-pages`. You will be prompted for username and password, use your own github account data, but make sure you are a contributor to codeforaustralia on GitHub first.
6. Your blog should be now available at http://codeforaustralia.github.io/[name-of-your-repo]
7. Map a domain / subdomain to your github.io url 👍🏽
8. Have a beer / wine / coffee and chill 🍻
