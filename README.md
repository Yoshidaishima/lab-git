# Git server

### Create new repo
ssh git@localhost -p 2222
mkdir /srv/git/your-repo.git
git-init --bare /srv/git/your-repo.git

### Use from git client example
git remote add origin ssh://git@rpi4.phy:2222/srv/git/test.git

### Sensitive data
- can be decrypted with gpg <file>

### Docs
(rockstorm)[https://hub.docker.com/r/rockstorm/git-server]
