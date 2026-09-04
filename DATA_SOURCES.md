# 使用データとライセンス

最終確認日: 2026-09-04

## 交通データ

現在の公開サービスは、代表的な平日 2026-08-04 の計算に、次の 29 個の
時刻表フィードを使用します。表示名は識別のためのものであり、各提供主体が
本サービスを運営、保証、推奨することを意味しません。

| 識別子 | 提供主体・サービス | 取得元 | ライセンス |
| --- | --- | --- | --- |
| `arakawa_sakura_bus` | 荒川区 さくら | [GTFS Data Repository][gtfs-repo] | CC BY 4.0 |
| `bunkyo_bguru` | 日立自動車交通 Bーぐる | [ODPT][odpt-catalog] | CC BY 4.0 |
| `chiyoda_kazaguruma` | 日立自動車交通 風ぐるま | [ODPT][odpt-catalog] | CC BY 4.0 |
| `higashimurayama_green_bus` | 東村山市 グリーンバス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `higashiyamato_chocobus` | 東大和市 ちょこバス | [ODPT][odpt-catalog] | CC0 1.0 |
| `katsushika_sakura_wagon` | 葛飾区 さくらワゴン | [GTFS Data Repository][gtfs-repo] | CC BY 4.0 |
| `keisei_bus_chiba_west` | 京成バス千葉ウエスト | [ODPT][odpt-catalog] | CC BY 4.0 |
| `kita_kbus` | 日立自動車交通 Kバス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `kiyose_kiyobus` | 清瀬市 きよバス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `kokubunji_bunbus` | 国分寺市 ぶんバス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `kozushima_village_bus` | 神津島村営バス | [GTFS Data Repository][gtfs-repo] | CC BY 4.0 |
| `kunitachi_aoyagikko` | 国立市 あおやぎっこ | [GTFS Data Repository][gtfs-repo] | CC BY 4.0 |
| `machida_community_bus` | 町田市コミュニティバス | [ODPT][odpt-catalog] | CC0 1.0 |
| `minato_chiibus` | フジエクスプレス ちぃばす | [公開 GTFS][chiibus-gtfs] | CC BY 4.0 |
| `mir_tx` | 首都圏新都市鉄道 | [ODPT][odpt-catalog] | 公共交通オープンデータ基本ライセンス |
| `miyake_village_bus` | 三宅村営バス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `mizuho_community_bus` | 瑞穂町コミュニティバス | [GTFS Data Repository][gtfs-repo] | CC BY 4.0 |
| `nihon_chuo_bus` | 日本中央バス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `nishitokyo_hanabus` | 西東京市 はなバス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `ogasawara_village_bus` | 小笠原村営バス | [GTFS Data Repository][gtfs-repo] | CC BY 4.0 |
| `seibu_bus` | 西武バス・西武観光バス | [ODPT][odpt-catalog] | 公共交通オープンデータ基本ライセンス |
| `shibuya_hachiko_bus` | 渋谷区 ハチ公バス | [公開 GTFS][shibuya-gtfs] | CC BY |
| `tachikawa_kururin_bus` | 立川市 くるりんバス | [GTFS Data Repository][gtfs-repo] | CC BY 4.0 |
| `taito_megurin` | 台東区 めぐりん | [ODPT][odpt-catalog] | CC BY 4.0 |
| `tama_monorail` | 多摩都市モノレール | [ODPT][odpt-catalog] | 公共交通オープンデータ基本ライセンス |
| `toei_bus` | 都営バス | [ODPT][odpt-catalog] | CC BY 4.0 |
| `toei_rail` | 東京都交通局 | [ODPT][odpt-catalog] | CC BY 4.0 |
| `tokyo_metro` | 東京メトロ | [ODPT][odpt-catalog] | 公共交通オープンデータ基本ライセンス |
| `twr_rinkai` | 東京臨海高速鉄道 | [ODPT][odpt-catalog] | 公共交通オープンデータ基本ライセンス |

ライセンス本文:

- [Creative Commons Attribution 4.0 International][cc-by-4]
- [Creative Commons CC0 1.0 Universal][cc0-1]
- [公共交通オープンデータ基本ライセンス][odpt-basic-license]

`shibuya_hachiko_bus` の公開メタデータは `CC BY` とだけ記載され、版数は
明記されていません。本表では版数を推定していません。詳細は
[ハチ公バスGTFS-JPデータの公開メタデータ][shibuya-metadata]を確認してください。

## 地図、住所検索、徒歩経路

- 地図表示: OpenStreetMap のラスタータイル。
- 住所・建物名検索: OpenStreetMap Nominatim。
- 徒歩ネットワーク: OpenStreetMap データから生成した経路グラフ。

OpenStreetMap データは Open Data Commons Open Database License の下で
提供されています。画面内にも `© OpenStreetMap contributors` の帰属表示を
行います。詳細は [OpenStreetMap Copyright and License][osm-copyright] と
[Nominatim Usage Policy][nominatim-policy] を確認してください。

## 加工と再配布の境界

本サービスは、公開交通データと OpenStreetMap データから、時刻表ベースの
到達圏、経路、250 m グリッド判定を生成します。リアルタイム運行情報、
東京全域の網羅性、または経路の完全性を保証しません。

この公開リポジトリには、チャレンジ限定データ、元の GTFS/GTFS-RT、ODPT
レスポンス、OTP グラフ、経路キャッシュ、生成済み到達圏データを掲載・再配布
しません。データ利用は、各提供元の利用条件、ライセンス、および
[公共交通オープンデータチャレンジ2026応募規約][challenge-rules] に従います。

[cc-by-4]: https://creativecommons.org/licenses/by/4.0/
[cc0-1]: https://creativecommons.org/publicdomain/zero/1.0/
[challenge-rules]: https://challenge2026.odpt.org/ja/entry.html
[chiibus-gtfs]: https://gtfs-jp.buskita.com/fxc/gtfs.zip
[gtfs-repo]: https://gtfs-data.jp/
[nominatim-policy]: https://operations.osmfoundation.org/policies/nominatim/
[odpt-basic-license]: https://developer.odpt.org/terms/data_basic_license.html
[odpt-catalog]: https://ckan.odpt.org/
[osm-copyright]: https://www.openstreetmap.org/copyright
[shibuya-metadata]: https://www.arcgis.com/home/item.html?id=185d0dbc980443b8b60e135349e2ae5e
[shibuya-gtfs]: https://www.arcgis.com/sharing/rest/content/items/185d0dbc980443b8b60e135349e2ae5e/data
