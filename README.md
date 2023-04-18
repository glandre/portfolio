# portfolio
Geraldo's Professional Portfolio - https://geraldolandre.com

### Deployment instructions:

On the server:
```sh
# cd to the website enclosing folder
cd /var/www/geraldolandre.com/

# move existing folder
mv html html-old
```

On the development machine:
```sh
# Transfer files to the server
scp -rp html/ geraldo@geraldolandre.com:/var/www/geraldolandre.com
```
