# provisioning-windows
Windowsのアプリを構成します。

## 使い方メモ
- 管理者権限で PowerShell を起動する。
  Windows キー + X -> A

```bash
# chocolatey がインストール済みか確認
choco -v

# インストール済みパッケージを確認
clist -lo

# package.config ファイル記載のパッケージをインストール
cinst packages.config -y

# インストール済みパッケージすべてをアップデート
cup all -y
```
