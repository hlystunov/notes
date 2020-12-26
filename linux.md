### SSH

`ssh-copy-id user@server` - copy keys to server

### UBUNTU

`xbacklight -set 100` - brightness change \
`sudo netstat -ltnp | grep ':80'` - applications listening port \
`ncdu` || `du -hs .` - directory size \
`jq` - JSON formatter \ 
`export $(cat ./X.env | xargs) &&  ./X -m` - export ENV \
`dpkg -I` - install .deb package \
`dd if=/dev/urandom of=/tmp/X.xxx bs=1M count=1` - generate files with specific size

### GIT

`git reset --hard HEAD~1` - back to previous commit \
`git push origin HEAD --force` - force push

### SECURITY

`host -t mx` - mail servers \
`nmap -sS -p- -PS80,22 -n -T4 -vvv --reason` - scan ports

### DOCKER 

`docker exec -it ... bash` - interactive container
