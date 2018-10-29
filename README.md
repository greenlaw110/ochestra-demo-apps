# ACT Framework Demo Applications

Notice: 
-------

All of the demo apps in this repo are split to standalone repos, and moved to <https://github.com/act-gallery>.

Usage:
-------

To start in dev mode:

```bash
cd /path/to/a/app
mvn clean compile exec:exec
```

To start in prod mode:

```bash
cd /path/to/a/app
mvn clean package
cd target/dist
unzip *.zip
./start
```
