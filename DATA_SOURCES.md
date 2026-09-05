# 使用データとライセンス

取得記録の照合日: 2026-09-05（提供元の最新データを再取得した日ではありません）

## 交通データ

現在の公開サービスは、計算対象日 2026-08-04 の計算に、次の 29 個の
時刻表フィードを使用します。表示名は識別のためのものであり、各提供主体が
本サービスを運営、保証、推奨することを意味しません。

| 識別子 | 提供主体・サービス | 取得元 | ライセンス |
| --- | --- | --- | --- |
| `arakawa_sakura_bus` | 荒川区 さくら | [取得元メタデータ(JSON)][source-arakawa_sakura_bus] | CC BY 4.0 |
| `bunkyo_bguru` | 日立自動車交通 Bーぐる | [ODPTデータ詳細][source-bunkyo_bguru] | CC BY 4.0 |
| `chiyoda_kazaguruma` | 日立自動車交通 風ぐるま | [ODPTデータ詳細][source-chiyoda_kazaguruma] | CC BY 4.0 |
| `higashimurayama_green_bus` | 東村山市 グリーンバス | [ODPTデータ詳細][source-higashimurayama_green_bus] | CC BY 4.0 |
| `higashiyamato_chocobus` | 東大和市 ちょこバス | [ODPTデータ詳細][source-higashiyamato_chocobus] | CC0 1.0 |
| `katsushika_sakura_wagon` | 葛飾区 さくらワゴン | [取得元メタデータ(JSON)][source-katsushika_sakura_wagon] | CC BY 4.0 |
| `keisei_bus_chiba_west` | 京成バス千葉ウエスト | [ODPTデータ詳細][source-keisei_bus_chiba_west] | CC BY 4.0 |
| `kita_kbus` | 日立自動車交通 Kバス | [ODPTデータ詳細][source-kita_kbus] | CC BY 4.0 |
| `kiyose_kiyobus` | 清瀬市 きよバス | [ODPTデータ詳細][source-kiyose_kiyobus] | CC BY 4.0 |
| `kokubunji_bunbus` | 国分寺市 ぶんバス | [ODPTデータ詳細][source-kokubunji_bunbus] | CC BY 4.0 |
| `kozushima_village_bus` | 神津島村営バス | [取得元メタデータ(JSON)][source-kozushima_village_bus] | CC BY 4.0 |
| `kunitachi_aoyagikko` | 国立市 あおやぎっこ | [取得元メタデータ(JSON)][source-kunitachi_aoyagikko] | CC BY 4.0 |
| `machida_community_bus` | 町田市コミュニティバス | [ODPTデータ詳細][source-machida_community_bus] | CC0 1.0 |
| `minato_chiibus` | フジエクスプレス ちぃばす | [提供元GTFS案内][source-minato_chiibus] | CC BY 4.0 |
| `mir_tx` | 首都圏新都市鉄道 | [ODPTデータ詳細][source-mir_tx] | 公共交通オープンデータ基本ライセンス |
| `miyake_village_bus` | 三宅村営バス | [ODPTデータ詳細][source-miyake_village_bus] | CC BY 4.0 |
| `mizuho_community_bus` | 瑞穂町コミュニティバス | [取得元メタデータ(JSON)][source-mizuho_community_bus] | CC BY 4.0 |
| `nihon_chuo_bus` | 日本中央バス | [ODPTデータ詳細][source-nihon_chuo_bus] | CC BY 4.0 |
| `nishitokyo_hanabus` | 西東京市 はなバス | [ODPTデータ詳細][source-nishitokyo_hanabus] | CC BY 4.0 |
| `ogasawara_village_bus` | 小笠原村営バス | [取得元メタデータ(JSON)][source-ogasawara_village_bus] | CC BY 4.0 |
| `seibu_bus` | 西武バス・西武観光バス | [ODPTデータ詳細][source-seibu_bus] | 公共交通オープンデータ基本ライセンス |
| `shibuya_hachiko_bus` | 渋谷区 ハチ公バス | [公開メタデータ][source-shibuya_hachiko_bus] | CC BY |
| `tachikawa_kururin_bus` | 立川市 くるりんバス | [取得元メタデータ(JSON)][source-tachikawa_kururin_bus] | CC BY 4.0 |
| `taito_megurin` | 台東区 めぐりん | [ODPTデータ詳細][source-taito_megurin] | CC BY 4.0 |
| `tama_monorail` | 多摩都市モノレール | [ODPTデータ詳細][source-tama_monorail] | 公共交通オープンデータ基本ライセンス |
| `toei_bus` | 都営バス | [ODPTデータ詳細][source-toei_bus] | CC BY 4.0 |
| `toei_rail` | 東京都交通局 | [ODPTデータ詳細][source-toei_rail] | CC BY 4.0 |
| `tokyo_metro` | 東京メトロ | [ODPTデータ詳細][source-tokyo_metro] | 公共交通オープンデータ基本ライセンス |
| `twr_rinkai` | 東京臨海高速鉄道 | [ODPTデータ詳細][source-twr_rinkai] | 公共交通オープンデータ基本ライセンス |

ライセンス本文:

- [Creative Commons Attribution 4.0 International][cc-by-4]
- [Creative Commons CC0 1.0 Universal][cc0-1]
- [公共交通オープンデータ基本ライセンス][odpt-basic-license]

`shibuya_hachiko_bus` の公開メタデータは `CC BY` とだけ記載され、版数は
明記されていません。本表では版数を推定していません。詳細は
[ハチ公バスGTFS-JPデータの公開メタデータ][shibuya-metadata]を確認してください。

<a id="feed-acquisition"></a>

## 取得記録（公開版29フィード）

計算対象日は **2026-08-04**、実際の取得日時は
**2026-07-06 01:07:00–01:21:32 JST（日本標準時、UTC+09:00）** です。
2026-09-05 に公開 API の配布イメージに含まれる版の記録と照合しました。
取得日時は取得ログを秒単位で示し、秒未満を省略しています。提供元の更新日時や
現在の最新性を示すものではありません。現在の移動に使える最新時刻表を保証する
ものでもありません。

版識別子は、加工前に取得した元ファイルの SHA-256 の先頭12桁です。
取得元とライセンスは上の同じ識別子の行を参照してください。取得元リンクは
取得時の記録に基づく参照先であり、そのページの現在の内容や配布ファイルが
取得済みの版と同一であることを保証しません。ちぃばすのリンクは提供元の
GTFS 案内であり、当時のファイルそのものの個別掲載ページを確認したものではありません。

「calendar.txt 記録期間」は、取得した各フィードの calendar.txt に記録された
開始日の最小値から終了日の最大値です。期間中の毎日の運行や全路線の有効性を
保証せず、運行曜日と calendar_dates.txt の例外設定を併せて解釈する必要があります。
feed_info.txt を含む全体の期間とは区別しています。

| 識別子 | 取得日時（JST） | 版識別子（元ファイル） | calendar.txt 記録期間 |
| --- | --- | --- | --- |
| `arakawa_sakura_bus` | 2026-07-06 01:07:15 | `9d4336d0d393` | 2026-03-01–2027-02-28 |
| `bunkyo_bguru` | 2026-07-06 01:07:26 | `082a9e644364` | 2026-04-01–2027-12-31 |
| `chiyoda_kazaguruma` | 2026-07-06 01:07:27 | `186f739bdd1d` | 2026-06-02–2027-12-31 |
| `higashimurayama_green_bus` | 2026-07-06 01:07:16 | `5ee420e7c210` | 2026-04-01–2027-03-31 |
| `higashiyamato_chocobus` | 2026-07-06 01:07:25 | `81fb4c167718` | 2026-02-09–2027-03-31 |
| `katsushika_sakura_wagon` | 2026-07-06 01:07:17 | `fa07ecd375fa` | 2025-12-30–2026-12-29 |
| `keisei_bus_chiba_west` | 2026-07-06 01:07:08 | `0b5466a8a6e8` | 2026-04-01–2027-04-01 |
| `kita_kbus` | 2026-07-06 01:07:28 | `08644c63272c` | 2025-12-20–2026-12-31 |
| `kiyose_kiyobus` | 2026-07-06 01:07:29 | `a7b8601156df` | 2026-04-01–2027-03-31 |
| `kokubunji_bunbus` | 2026-07-06 01:07:21 | `68e4ccb129d9` | 2026-01-05–2027-06-30 |
| `kozushima_village_bus` | 2026-07-06 01:07:20 | `84a29423238c` | 2026-01-29–2027-01-28 |
| `kunitachi_aoyagikko` | 2026-07-06 01:07:10 | `5e856c939fa0` | 2026-01-13–2027-01-12 |
| `machida_community_bus` | 2026-07-06 01:07:23 | `49ef2114b70f` | 2020-12-01–2028-03-31 |
| `minato_chiibus` | 2026-07-06 01:07:11 | `f22c61878324` | 2026-04-01–2026-12-31 |
| `mir_tx` | 2026-07-06 01:21:12 | `66e478f35f58` | 2025-03-15–2026-12-31 |
| `miyake_village_bus` | 2026-07-06 01:07:31 | `636d327d9a4f` | 2025-09-29–2026-12-31 |
| `mizuho_community_bus` | 2026-07-06 01:07:18 | `72085b3cdb66` | 2024-10-01–2027-03-31 |
| `nihon_chuo_bus` | 2026-07-06 01:07:33 | `0454e6f0c591` | 2026-04-01–2027-03-31 |
| `nishitokyo_hanabus` | 2026-07-06 01:07:30 | `154f7f38860b` | 2026-04-01–2027-03-31 |
| `ogasawara_village_bus` | 2026-07-06 01:07:19 | `e576efcbcdb9` | 2026-02-10–2027-02-10 |
| `seibu_bus` | 2026-07-06 01:21:32 | `e38fe2712624` | 2026-07-01–2026-09-30 |
| `shibuya_hachiko_bus` | 2026-07-06 01:07:14 | `bded3256e593` | 2024-06-17–2030-03-31 |
| `tachikawa_kururin_bus` | 2026-07-06 01:07:24 | `101a2549fd92` | 2026-04-01–2027-03-31 |
| `taito_megurin` | 2026-07-06 01:07:12 | `b669ecdb7c52` | 2025-08-10–2026-12-31 |
| `tama_monorail` | 2026-07-06 01:21:13 | `cbe9a6ed3ae1` | 2025-03-15–2026-12-31 |
| `toei_bus` | 2026-07-06 01:07:06 | `6ee1f1c71fba` | 2026-07-05–2029-07-04 |
| `toei_rail` | 2026-07-06 01:07:00 | `2ff2c07c700e` | 2026-03-14–2026-12-31 |
| `tokyo_metro` | 2026-07-06 01:21:11 | `9a077f8ff182` | 2026-03-14–2026-12-31 |
| `twr_rinkai` | 2026-07-06 01:21:11 | `7b21ec23c76b` | 2026-03-14–2026-12-31 |

## 基礎データに関するお知らせ

本サービスで使用する基礎データの正確性・完全性について、公共交通オープンデータセンター、公共交通オープンデータ協議会およびデータ提供者は責任を負いません。
本告知は [公共交通オープンデータ基本ライセンス][odpt-basic-license] 第10条第3項と
[開発者向けデータ利用ガイドライン][odpt-use-guideline] 3.1 に基づきます。
取得日時の表示については同ガイドライン 2.2.1 を参照してください。

本サービスはこれらの団体の公式サービスではありません。本サービスの開発・運営
および加工・表示内容は開発者の責任で行います。表示・操作については
[開発者のお問い合わせ窓口][question-form]へお寄せください。

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
到達圏、経路、250 m グリッド判定を生成します。経路グラフ用の処理では、
渋谷区の任意ファイルである translations.txt の除去、日本中央バスの空行除去を行っています。
上記の版識別子はこれらの処理前の元ファイルを識別します。リアルタイム運行情報、
東京全域の網羅性、または経路の完全性を保証しません。

この公開リポジトリには、チャレンジ限定データ、元の GTFS/GTFS-RT、ODPT
レスポンス、OTP グラフ、経路キャッシュ、生成済み到達圏データを掲載・再配布
しません。データ利用は、各提供元の利用条件、ライセンス、および
[公共交通オープンデータチャレンジ2026応募規約][challenge-rules] に従います。

[cc-by-4]: https://creativecommons.org/licenses/by/4.0/
[cc0-1]: https://creativecommons.org/publicdomain/zero/1.0/
[challenge-rules]: https://challenge2026.odpt.org/ja/entry.html
[nominatim-policy]: https://operations.osmfoundation.org/policies/nominatim/
[odpt-basic-license]: https://developer.odpt.org/terms/data_basic_license.html
[osm-copyright]: https://www.openstreetmap.org/copyright
[shibuya-metadata]: https://www.arcgis.com/home/item.html?id=185d0dbc980443b8b60e135349e2ae5e

[odpt-use-guideline]: https://developer.odpt.org/terms/data_basic_use_guideline.html
[question-form]: https://github.com/zll6796096/tokyo-commute-radar-support/issues/new?template=question.yml
[source-arakawa_sakura_bus]: https://api.gtfs-data.jp/v2/organizations/arakawacity/feeds/sakura
[source-bunkyo_bguru]: https://ckan.odpt.org/dataset/hitachi_automobile_transportation_all_lines/resource/95ec7d40-73d9-4003-8d39-898421f5b689
[source-chiyoda_kazaguruma]: https://ckan.odpt.org/dataset/hitachi_automobile_transportation_chiyoda_alllines/resource/45cab9b6-8e6a-405e-812d-20503c622326
[source-higashimurayama_green_bus]: https://ckan.odpt.org/dataset/higashi_murayama_city_alllines/resource/4dfb1af9-c788-47f5-b959-c1b7f0d36352
[source-higashiyamato_chocobus]: https://ckan.odpt.org/dataset/higashiyamato_city_all_lines_cc0/resource/bb2a0ce5-4976-49b5-8d68-1f381ee94824
[source-katsushika_sakura_wagon]: https://api.gtfs-data.jp/v2/organizations/katsushikacity/feeds/sakura
[source-keisei_bus_chiba_west]: https://ckan.odpt.org/dataset/keisei_transit_bus_all_lines/resource/af855ba1-374e-4157-a80d-211a5c425d29
[source-kita_kbus]: https://ckan.odpt.org/dataset/hitachi_automobile_transportation_kita_all_lines/resource/b551e2d8-0ae1-4fb4-9a4d-aa8de7f3095c
[source-kiyose_kiyobus]: https://ckan.odpt.org/dataset/kiyose_city_kiyo_bus/resource/51906ad9-248c-433f-9f6b-5e4ae385dd3f
[source-kokubunji_bunbus]: https://ckan.odpt.org/dataset/kokubunji_city_kokubunji_city_bunbus/resource/32d11416-9ff2-4995-8bd5-d1d3ee194ba9
[source-kozushima_village_bus]: https://api.gtfs-data.jp/v2/organizations/kozushimavillage/feeds/kozushimavillagebus
[source-kunitachi_aoyagikko]: https://api.gtfs-data.jp/v2/organizations/kunitachicity/feeds/aoyagikko
[source-machida_community_bus]: https://ckan.odpt.org/dataset/machida_city_all_lines/resource/9bf04956-1203-40bc-8277-846f148f5530
[source-minato_chiibus]: https://bus.fujikyu.co.jp/rosen/gtfs
[source-mir_tx]: https://ckan.odpt.org/dataset/train-mir/resource/663ebc8f-6c0c-4151-b966-f97f5d9b148c
[source-miyake_village_bus]: https://ckan.odpt.org/dataset/miyake_vill_all_line/resource/f526db08-21ea-452c-b6ed-ea5758b3c44a
[source-mizuho_community_bus]: https://api.gtfs-data.jp/v2/organizations/mizuhotown/feeds/communitybus
[source-nihon_chuo_bus]: https://ckan.odpt.org/dataset/nippon_chuo_bus_maebashi_area/resource/a9811287-1b77-4f15-a61e-c73bad060521
[source-nishitokyo_hanabus]: https://ckan.odpt.org/dataset/nishitokyo_city_all_lines/resource/60f33768-4158-41b3-9a48-ed5786061e16
[source-ogasawara_village_bus]: https://api.gtfs-data.jp/v2/organizations/ogasawaravillage/feeds/o
[source-seibu_bus]: https://ckan.odpt.org/dataset/seibu_bus__b-bus_gtfs/resource/8a2d63ed-6023-42bf-ae34-1796c56f607f
[source-shibuya_hachiko_bus]: https://www.arcgis.com/home/item.html?id=185d0dbc980443b8b60e135349e2ae5e
[source-tachikawa_kururin_bus]: https://api.gtfs-data.jp/v2/organizations/tachikawacity/feeds/kururinbus
[source-taito_megurin]: https://ckan.odpt.org/dataset/tokyo_taito_city_megurin_ccby40/resource/6e882760-6ee0-4cb3-b3de-88c0c1819367
[source-tama_monorail]: https://ckan.odpt.org/dataset/train-tamamonorail/resource/c72cc2a7-f1d5-41cf-9fac-5545237fd425
[source-toei_bus]: https://ckan.odpt.org/dataset/b_bus_gtfs_jp-toei/resource/171a583d-4bf3-4f71-ae57-16f2140babda
[source-toei_rail]: https://ckan.odpt.org/dataset/train-toei/resource/35b68908-4558-47ae-bfa5-867e58544a1a
[source-tokyo_metro]: https://ckan.odpt.org/en/dataset/train-tokyometro/resource/d4f11962-1c5a-4316-9a16-7fb229c227ea
[source-twr_rinkai]: https://ckan.odpt.org/dataset/train-twr/resource/f1953807-47da-4540-94bd-26c391e5caef
