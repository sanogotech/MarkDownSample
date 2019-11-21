# MarkDownSample

### How-to
To set up the *** :
```
git clone https://github.com/user/projet.git
cd projet
mvn  clean  install 
```

### Visualization
```
+-------------+    +-------------+    +-------------+
|             |    |             |    /             /
|             |    |             |    /             /
|  Gitlab     |    |  Gitlab     |    /  Gitlab CI  /
|             +--> |  CI-Runner  +--> /  Container  /
|             |    |             |    /             /
|             |    |             |    /             /
+------+------+    +------+------+    +------+------+
+------|------------------|------------------|------+
|                      Docker                       |
+---------------------------------------------------+
```
