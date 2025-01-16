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


## 建立空白訊息提交

```shell
git commit --allow-empty-message
```


## 推送到多個 remote

```shell
git remote set-url --add --push {倉庫} {目標}
```
