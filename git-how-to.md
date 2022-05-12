1) To create ssh keys pair you need to call:

ssh-keygen -t ed25519 -C "user_mail_address"
rename key files to make it more convinient

2) Open file .pub and copy it to the ssh keys section on GitHub

3) ssh-add .ssh/private_key

4) Use command git clone git@github.com:username/rep_name.git 