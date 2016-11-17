# cloud-config-for-coresos

## 使い方

### ダウンロード

```bash
$ wget https://raw.githubusercontent.com/YujiAzama/cloud-config-for-coresos/master/cloud-config.yaml
```

### 環境に合わせて修正する

パスワードのハッシュ生成方法

```bash
$ openssl passwd -1
```

### インストール

```bash
$ sudo coreos-install -d /dev/sda -C stable -c cloud-config.yaml
```
