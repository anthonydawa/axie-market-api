# TMT-axe

## setup development environment

1. clone [application root](https://github.com/dwnfrc/TMT-axe).
```
git clone git@github.com:dwnfrc/TMT-axe.git tmt-axe
```
2. move to application root
```
cd tmt-axe
```

3. clone following application.
    1. [app](https://github.com/dwnfrc/TMT-axe.app)
        1. cd to /app.
        ```
        cd app
        ```
        2. clone [app](https://github.com/dwnfrc/TMT-axe.app).
        ```
        git clone git@github.com:dwnfrc/TMT-axe.app.git .
        ```
    2. [api](https://github.com/dwnfrc/TMT-axe.api)
        1. cd to /api
        ```
        cd api
        ```
        2. clone [api](https://github.com/dwnfrc/TMT-axe.api)
        ```
        git clone git@github.com:dwnfrc/TMT-axe.api.git .
        ```

at end of above process your directory structure should be same as following
```
 tmt-axe
    │
    ├──  api
    └──  app

```

## start application on local
1. run docker command at project root(tmt-axe).
```
docker compose up
```
