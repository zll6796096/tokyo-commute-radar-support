# プライバシー

最終更新日: 2026-09-04

## 対象

この文書は、東京通勤レーダーの公開 Web サービスに適用されます。この公開
画面には、ユーザーアカウント、広告、利用状況分析タグ、またはブラウザの
永続ストレージを使って検索条件を保存する機能はありません。

## 入力と送信先

1. 住所または建物名を検索すると、入力文字列は東京通勤レーダーの API へ
   送信され、その API から OpenStreetMap Nominatim へ送信されます。
2. 候補を確定して到達圏を計算すると、候補の名称、住所、座標、到着時刻、
   通勤時間の上限が東京通勤レーダーの API へ送信されます。
3. 地図を表示すると、ブラウザは OpenStreetMap のタイルサーバーへ地図
   タイルを要求します。
4. 問い合わせリンクを開くと、GitHub へ移動します。

## 保存とログ

- 同じ住所検索の外部送信を減らすため、検索文字列と候補をサーバー
  プロセスのメモリ内にキャッシュする場合があります。このキャッシュは
  永続データベースではなく、プロセス終了時に失われます。
- 到達圏計算では確定後の座標を利用します。派生した経路結果は、座標や時刻
  などから生成したハッシュキーで、実行中のサーバー内にキャッシュされる
  場合があります。入力した住所文字列を経路キャッシュへ保存する設計では
  ありません。
- ホスティング事業者および外部サービスは、接続情報や要求 URL などの
  アクセスログを、それぞれの方針に基づいて処理する場合があります。
- 現時点で確認できない一律のログ保存期間は約束しません。

住所検索は URL のクエリとして API に送信され、Nominatim にも渡ります。
自宅住所、個人名、認証情報、その他の個人情報・機密情報を入力しないで
ください。Nominatim の方針も個人情報や機密情報を送信しないよう求めて
います。

## 外部サービス

- [OpenStreetMap Foundation Privacy Policy][osm-privacy]
- [Nominatim Usage Policy][nominatim-policy]
- [Google Privacy Policy][google-privacy]
- [GitHub General Privacy Statement][github-privacy]

GitHub Issues への投稿内容は公開され、投稿には GitHub アカウントが必要です。
問い合わせに住所、勤務先、認証情報を記載しないでください。

## お問い合わせ

このサービスのプライバシーに関する一般的な質問は、個人情報を含めずに
[お問い合わせフォーム][question-form] から開発者へお寄せください。
セキュリティ上の問題は [SECURITY.md](SECURITY.md) に従って非公開で報告して
ください。

[github-privacy]: https://docs.github.com/ja/site-policy/privacy-policies/github-general-privacy-statement
[google-privacy]: https://policies.google.com/privacy?hl=ja
[nominatim-policy]: https://operations.osmfoundation.org/policies/nominatim/
[osm-privacy]: https://osmfoundation.org/wiki/Privacy_Policy
[question-form]: https://github.com/zll6796096/tokyo-commute-radar-support/issues/new?template=question.yml
