# s3-website-playground

learn [s3-website](https://github.com/klaemo/s3-website) npm module

**usage session**

```sh
# install deps
npm install

# create static website
./node_modules/s3-website/s3-website.js create 

# deploy static website
com.brianpfeil.s3-website-playground.site01
./node_modules/s3-website/s3-website.js deploy

# view 
open http://com.brianpfeil.s3-website-playground.site01.s3-website-us-east-1.amazonaws.com

# NOTE: using `./node_modules/s3-website/s3-website.js` to avoid global install and
# doesn't work with `npx` because of https://www.evernote.com/l/AAH8gou8OCZKF6rfnqA2Tom3BU7c0xuFTM0B/image.png
```