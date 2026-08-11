# scout.agent-best.net

株式会社エージェントベスト「スカウト代行サービス」LP（採用企業さま向け・B2B）。

- 公開URL: https://scout.agent-best.net/
- ホスティング: GitHub Pages（main / ルート）
- DNS: Squarespace管理（CNAME → agentbest.github.io）

## 構成

| ファイル | 役割 |
|---|---|
| `index.html` | LP本体。CSS/JS/アイコンをすべて内包した1ファイル構成（外部CDN依存なし） |
| `CNAME` | 独自ドメイン設定 |
| `.nojekyll` | GitHub PagesのJekyll処理を無効化 |

## お問い合わせフォーム

コーポレートサイト（https://www.agent-best.net/contact ）と**同一のGoogleフォーム**へ送信しています。
フォームIDとentry IDは `index.html` 末尾のスクリプト内に定義。項目は 会社名／お名前／メールアドレス／お問い合わせ内容 の4つで、
送信本文の末尾に「お問い合わせ元：スカウト代行LP」を自動付記して、どのLP経由かを判別できるようにしています。

日程調整ツール（Timerex）へは、フォーム送信後のサンクス画面からのみ案内しています（いきなり遷移させない方針）。

## 編集方法

`index.html` を直接編集して push すれば、数分でGitHub Pagesに反映されます。
