# MarkDownSample

### How-to
To set up the playground, do the following:
```
git clone https://github.com/rjongejan/gitlab-ci-playground.git
cd gitlab-ci-playground
ansible-playbook playbook.yml
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
