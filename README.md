# cloud-config-for-coresos

## 使い方

1. ダウンロード

```bash
$ wget https://raw.githubusercontent.com/YujiAzama/cloud-config-for-coresos/master/cloud-config.yaml
```

2. 環境に合わせて修正する

3. インストール

```bash
$ sudo coreos-install -d /dev/sda -C stable -c cloud-config.yaml
```
