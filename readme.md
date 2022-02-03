# TMT-axe

## setup development environment

1. clone [application root](https://github.com/dwnfrc/TMT-axe).
```
git clone https://github.com/dwnfrc/TMT-axe tmt-axe
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
        git clone https://github.com/dwnfrc/TMT-axe.app.git app
        ```

at end of above process your directory structure should be same as following
```
 tmt-axe
    │
    └──  app
```

## start application on local
1. run docker command at project root(tmt-axe).
```
docker compose up
```
