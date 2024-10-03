# テスト用クラスターの設定用

## 適用方法

oc apply -k ./gitops/overlays/rhdp

gitops Operator のインストールが完了した後に以下を実行

oc apply -f app-of-apps.yaml