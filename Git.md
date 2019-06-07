设置用户
git config --global user.name "lwd"
git config --global user.email "ldemo007@gmail.com"

设置密钥
ssh-keygen -t rsa -C "ldemo007@gmail.com"
C:\Users\ldemo\.ssh
id_rsa id_rsa.pub

登录github
setting->SSH and GPG keys
title=win10env
key=id_rsa.pub中的内容

验证ssh 
cmd #ssh git@github.com

