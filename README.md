# Jenkins on Heroku

```bash
1 - install heroku
    curl https://cli-assets.heroku.com/install.sh | sh
```

```bash
2 - heroku login
```

```bash
3 - heroku create app-name --buildpack heroku/java
```

```bash
8 - git
    git init
    git add .
    git commit -m""
    git push heroku master
```

```bash
6 - heroku git:remote -a app-name
```

```bash
9 - heroku ps:scale web=1
```

```bash
10 - heroku open
```

```bash
11 - passwd admin
     heroku logs --app app-name
```

```bash
12 - copy passwd
```