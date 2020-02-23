# docker-compose-monitor

基本的な監視機能が動作する環境を構築。

## コンポーネントの構成

|項目             |内容                          |
|-----------------|------------------------------|
|prometheus       |メトリクスの収集および蓄積    |
|alertmanager     |アラート通知をおこなう        |
|blackbox-exporter|外形監視をおこなう            |
|node-exporter    |サーバリソースの収集をおこなう|
|grafana          |メトリクスの可視化をおこなう  |
|mailcatcher      |テスト用のSMTPサーバ          |
