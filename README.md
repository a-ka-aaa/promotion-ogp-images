# promotion-ogp-images

**01｜プロモーションプロジェクト**で使う画像の**公開ホスティング用リポジトリ**です。

GitHubの `raw` URL はそのまま画像として配信されるため、

- LP・ファネルの **OGP画像**（リンクプレビュー）
- LINE・オープンチャットへ **投稿する画像**
- **管理シートに「この画像だよ」と貼るリンク**

に、このリポジトリのURLを使います。

## 使うときのルール

- **素材の正式な管理台帳は `a-ka-aaa/promotion-project` の `MATERIALS.md`** です。用途・状態・経緯はそちらが正本で、このREADMEは「何がどのファイル名で置いてあるか」の索引です。
- **公開リポジトリです。** URLを知っていれば誰でも見られるため、非公開の資料・個人情報を含む画像は置きません。
- **置いたファイルの名前は変えない・消さない。** 稼働中のOGP設定や、すでに配布したリンクが直接このURLを見ています。
  - 同じ用途で**中身だけ差し替える** → **同じファイル名に上書き**（URLが変わらない）
  - **別案・別バージョン** → **新しいファイル名で追加**し、採用したほうを `MATERIALS.md` で「採用」と記録する

## ファイル名の付け方

```
<企画>-<用途>[-<補足>].jpg
```

| 部分 | 使う値 | 意味 |
| :--- | :--- | :--- |
| 企画 | `2days` | 2DAYSライブセミナー |
| 企画 | `sm5` | 売れる自分を作る5日間セールスマインドプログラム |
| 用途 | `ogp` | リンクプレビュー用（OGP。推奨は1200×630） |
| 用途 | `cta` | 投稿用（次の動作を促す帯つき） |
| 用途 | `archive` | アーカイブ配信で使う画像 |
| 補足 | `day1` `day2` `2line` など | 同じ用途の中での区別 |

## 置いてある画像

| ファイル | 何用か | 使っている場所 | サイズ | 状態 |
| :--- | :--- | :--- | :--- | :--- |
| [`2days-ogp.jpg`](https://raw.githubusercontent.com/a-ka-aaa/promotion-ogp-images/main/2days-ogp.jpg) | 2DAYSライブセミナーLPのOGP画像 | 2DAYSライブセミナー申込ページ（`raw_html` 版3ページを含む）の `meta_og_image` | 3198×1555 | 本番 |
| [`sm5-program-ogp.jpg`](https://raw.githubusercontent.com/a-ka-aaa/promotion-ogp-images/main/sm5-program-ogp.jpg) | 5日間プログラムのタイトル画像（文字の追加なし） | OGP用・オープンチャットへの投稿用 | 1200×630 | 本番 |
| [`sm5-program-cta.jpg`](https://raw.githubusercontent.com/a-ka-aaa/promotion-ogp-images/main/sm5-program-cta.jpg) | 5日間プログラムのオプチャ投稿用（CTA帯つき・**採用**） | 9月回オープンチャットへの投稿 | 1731×1077 | 本番 |
| [`sm5-program-cta-2line.jpg`](https://raw.githubusercontent.com/a-ka-aaa/promotion-ogp-images/main/sm5-program-cta-2line.jpg) | 同上の**別案**（補足1行入り） | — | 1731×1119 | 未採用（保管） |
| [`2days-archive-day1.jpg`](https://raw.githubusercontent.com/a-ka-aaa/promotion-ogp-images/main/2days-archive-day1.jpg) | **Day1アーカイブの配信で使う画像**（「48時間限定公開」「アーカイブはこちらから ↓↓ ●●DAY1アーカイブ●● ↓↓」） | 参加者オープンチャットへ投稿（①投稿 → ②画像 → ③ノート共有 の順） | 1536×1024 | 本番 |
| [`2days-archive-day2.jpg`](https://raw.githubusercontent.com/a-ka-aaa/promotion-ogp-images/main/2days-archive-day2.jpg) | **Day2アーカイブの配信で使う画像**（同上のDAY2版） | 参加者オープンチャットへ投稿（①投稿 → ②画像 → ③ノート共有 の順） | 1536×1024 | 本番 |

リンクをそのまま貼ると画像として表示されます。管理シートに貼る場合も上のURLを使ってください。
