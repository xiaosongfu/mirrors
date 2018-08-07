### 快速开始

```
npm install docsify-cli -g

docsify init ./docs

docsify serve ./docs
```

### 同步方法

> 同步到服务器

```
~/dev/software/rclone/rclone-v1.42-osx-amd64/rclone sync /Volumes/macdata/xiaosongfu/dl-mirrors jdcloud:/root/app/dl-mirrors
```

> 同步到七牛云

```
~/dev/software/qshell-v2.1.8/qshell-darwin-x64 qupload2 -src-dir=/Volumes/macdata/xiaosongfu/dl-mirrors -bucket=dl-mirrors -thread-count=10 -check-exists -rescan-local -skip-file-prefixes=.DS_Store
```