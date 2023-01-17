# yii2-docker-nginx-fpm-mysql

- [Installation](#installation)

## Installation

You can set environment variables in the [`.env`](.env) file before initialization

``` sh
git clone https://github.com/w3lifer/yii2-docker-nginx-fpm-mysql yii2-app-basic
cd yii2-app-basic
make init
```

After installation the `.git` directory will be removed and the new repository will be initialized

Hence, you can add your remote `origin` to the newly created repository, commit and push the initial commit:

``` sh
git remote add origin git@github.com:<user>/<repo>
git add .
git commit -m 'initial commit'
git push -u origin master
```

To access the app, open http://localhost:801 in your favorite browser (see [`.env`](.env) file)
