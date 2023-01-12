# 空白

## 建立空白分支

```shell
git checkout --orphan {name}
# e.g.
git checkout --orphan master
```

## 建立空白提交

```shell
git commit --allow-empty -m '{message}'
# e.g.
git commit --allow-empty -m 'chore: initial commit'
```
