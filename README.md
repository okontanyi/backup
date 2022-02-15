# backup
cd /opt/scripts
vim backup.sh
#!/bin/bash
tar -czf /tmp/username.home.tar.gz
home/username
cd /tmp
ls -al
mkdir temp
mv username-home.tar.gz. temp/
cd temp
ls -la
tar -xvzf username-home.tar.gz
rm -rf temp
cd /opt/scripts/
vim backup.sh
chmod +x backup.sh
ls la /tmp
