# Jenkins on Heroku


### step 0 - clone

```bash
    https://github.com/erickferreir4/jenkins_heroku.git
```

### step 1 - install heroku

```bash
    curl https://cli-assets.heroku.com/install.sh | sh
```

### step 2

```bash
    heroku login
```

### step 3

```bash
    heroku create app-name --buildpack heroku/java
```

### step 4 - git

```bash
    git init
    git add .
    git commit -m""
    git push heroku master
```

### step 5

```bash
    heroku git:remote -a app-name
```

### step 6

```bash
    heroku ps:scale web=1
```

### step 7

```bash
    heroku open
```

### step 8 - password admin

```bash
     heroku logs --app app-name
```
### step 9

```bash
    copy passwd
```
