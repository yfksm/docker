# Docker for mac Ver 4.4.2 以降の場合の事前準備
```
vim ~/Library/Group\ Containers/group.com.docker/settings.json
```
で設定を開き
```
"deprecatedCgroupv1": true,
```
としてCgroupのv1を有効にする。
これによりsystemdが利用可能になる。
