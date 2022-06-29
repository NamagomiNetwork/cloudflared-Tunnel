# cloudflared-Tunnel

このイメージはcloudflared tunnel を建てるイメージです

## 設定してほしい変数

- `TUNNEL_NAME`
    - cloudflaredのトンネル名を指定してください
- `CLOUDFLARED_HOSTNAME`
    - ここにリモートドメイン(アクセスするドメイン)を入れてください
    - 例: `grafana.nabr2730.com`
- `CLOUDFLARED_SERVICE`
    - ローカルの接続先を指定してください
    - 例: `http://argocd-server.argocd` , `http://192.168.2.1`