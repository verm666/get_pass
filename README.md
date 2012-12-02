get_pass
========

Simple script for password management

How to use
----------

```bash
echo -e "facebook\t123456" > /tmp/pass
echo -e "my-root-password\t666666" >> /tmp/pass
gpg -c /tmp/pass
rm -f /tmp/pass
mv /tmp/pass.gpg ~/Dropbox/
get_pass
Password: 
0) facebook
1) my-root-password
Input number: 0
```

Your password in clipboard now!
