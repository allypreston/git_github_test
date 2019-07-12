# h1 - Title

Text that is cool

## h2 Todo

- make a README.md file
- document how to:
  - how to track files on git
  - create a repo on Github
  - add a remote connection
  - push to Github

### h3 documentation
#### track files on git
To track files on git you need to
- initiate Git using [git init]
- add files to queue using [git add <file>]
- push the files using [git commit -m <message>]

#### create a repo on Github
To create a repository on Github you need to
- go onto Github
- open repositories on your profile
- click new repository
- name new repository

#### add a remote connection
To add a remote connection between your local on remote repositories you will need to
- link your ssh key by copying your public key to Github
- use the command [ssh -T git@github.com]. This will test that it is pushing to the correct location
- log in if prompted

#### push to Github
To push a commit to Github you will need to
- make a commit on the local repository
- use the command [git push <remote repository> <local repository>]
