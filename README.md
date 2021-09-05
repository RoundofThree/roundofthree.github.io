# Personal blog

Categories:

- General: tricks, notes for Kaggle...
- Labs: HackTheBox writeups, Kaggle competition code
- Research: vulnerabilities, patches, attack vectors...
- Whoami: skills, education, CV, HackTheBox and Leetcode profiles

## Commands 

- Create article
```sh
hugo new <path>.md
```

- Live server
```sh
# with drafts
hugo server -D -t terminal
# without drafts
hugo server -t terminal
```

- Build
```sh
hugo -D
```

## TODO
 
- [ ] Feature: convert any article to PDF. 
- [x] Feature: ToC. 
- [x] Feature: search by keywords.
- [x] Style: set root path to be whoami. 
- [ ] Change favicon.ico. I added the favicon to static/. ??????
- [ ] Add Github Actions workflow to publish to `gh-pages` branch. 

Built with Hugo. 