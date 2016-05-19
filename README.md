# フロントエンド層

- HTML
    - HTML5 ◯
- HTMLテンプレート言語
    - erb ◯
    - haml ◯
    - slim ◎
- CSS
- CSS 記法
    - BEM ◎
    - SMACC ◯
    - など
- CSS 拡張言語
    - scss ◯
    - sass ◯
    - less ◯
- CSS フレームワーク
    - bootstrap ◯
    - foundation ☓
    - など
- JavaScript
    - ES2015 ◯
    - CoffeeScript ◯
- JavaScript フレームワーク
    - React.js ◎
    - Vue.js ☓
    - Angular.js ☓
    - などなど
- UI/UX
- Analytics
  - Google Analytics △
  - など

# ミドルウェア層

- DB
    - MySQL ◎
    - PostgreSQL △
- WebServer(リバースプロキシ)
    - Apache △
    - nginx ◯
- AppServer
    - unicorn △
    - puma △
    - passenger △
- nosql
    - memcache △
    - redis ☓
    - mongodb ☓
- Paas
    - heroku △
    - google app engine ☓

# アプリケーション層

- HTTP1.1
    - ステータスコード
    - 主要なヘッダ
        - Cookies
        - Cache
        - など
- HTTP2
- SSL
  - 適用や証明書の種類、取得方法など
  - Let's Encrypt
- Ruby
    - メタプログラミング ◯
    - など
- Rails
    - Rack △
    - Asset Pipeline △
    - spring △
    - パフォーマンス △
        - N+1
        - キャッシュ
    - など。たくさんありすぎ
- SQL
- test
    - RSpec ◯
    - minitest ☓
    - capybara ☓
    - polgergeist / capybara-webkit ☓
- CI
    - Jenkins ☓
    - CircleCI ◯
    - TravisCI ☓
    - コードメトリクス
        - codeclimate ☓
        - houndci ☓
        - coverall ☓
        - など
- 認証
  - Devise ◯
  - Sorcery ☓
  - など
- 認可
  - CanCanCan △
  - Pundit ☓
  - など
- API
  - JSON API ◯
  - versioning x
  - documentation △
  - など
- i18n

# インフラ層

- Iaas
    - AWS △
    - さくら △
    - DigitalOcean x
- 仮想環境
    - Vagrant △
    - Docker x
    - Packer x
- プロビジョニング
    - ansible △
    - Chef x
    - Itamae x
- デプロイ
    - capistrano ◯
- エラー監視
    - zabbix x
    - nagiox x
    - airbrake △
- ログ
    - fluentd △
    - treasure data x
    - big query x
- ロードバランサ △
- キャッシュ △
- DNS △
- linux
    - プロセス △
    - スレッド △
    - ソケット △
- テスト
  - serverspec x

# 設計

- オブジェクト指向 ◯
- デザインパターン △
- マイクロサービス設計 △
- API設計 ◯
- DBスキーマ設計 ◯

# 全体にまたがるもの

- Security
    - XSS △
    - SQL Injection △
    - など
- Git ◯
- GitHub ◯
- 情報共有
    - Slack ◯
    - Qiita::Team ◯
    - esa.io △
    - Confluence ◯
- Gem開発 x
- performance tuning x
  - 計測
  - 調査
  - 改善

# その他

- 社内コミュニケーション ◯
- 社外コミュニケーション
    - 勉強会の参加、発表 △
    - ブログ △
    - OSS活動 △
- mobile application
    - iOS △
    - Android x
- 他言語
    - Go x
    - Erlang x
    - Elixir x
    - Haskell x
    - など
