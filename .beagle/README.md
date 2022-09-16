# version

<!-- https://github.com/fatedier/kcp-go -->

```bash
git remote add upstream git@github.com:fatedier/kcp-go.git

git fetch upstream

git merge upstream/frp2
```

## dev

```bash
# 新建一个Tag
git tag v2.0.4-beagle.0

# 推送一个Tag ，-f 强制更新
git push -f origin v2.0.4-beagle.0

# 删除本地Tag
git tag -d v2.0.4-beagle.0
```

## realse

```bash
# 新建一个Tag
git tag v2.0.4-beagle

# 推送一个Tag ，-f 强制更新
git push -f origin v2.0.4-beagle

# 删除本地Tag
git tag -d v2.0.4-beagle
```

## debug

```bash
go vet ./...
```
