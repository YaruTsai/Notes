# IT Notes

# 露營網站開發
* Website：easy8.tw
* Website Admin: easy8.tw/admin
* Web Framework: Django
* Cloud: AWS
* README.md:
# This is easy8.tw site

EB KEY
```
Yarus-MacBook-Pro:djangoawseb yaru$ ls -al ~/.ssh/awsebkey
awsebkey      awsebkey.pub
```

Setup python virtual environment on on Mac
```
source ~/git/awscli/source/bin/activate
```

EB SSH
```
eb ssh
```

EB Django Path
```
cd /opt/python/current/app
```

Download the latest verion from AWS
```
eb labs download
```

SCP specific file, for example: db.sqlite3
```
(awscli) Yarus-MacBook-Pro:djangoawseb yaru$ scp -i ~/.ssh/awsebkey ec2-user@ec2-54-249-156-8.ap-northeast-1.compute.amazonaws.com:/opt/python/current/app/db.sqlite3 .
```
* 
* 
* 
