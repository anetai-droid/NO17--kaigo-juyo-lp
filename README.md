# 介護事業者向け 重要事項説明動画DX ランディングページ

介護事業所向けの「重要事項説明動画制作サービス（重説動画DX）」のランディングページです。
運営指導対策・介護報酬の返還リスク回避を訴求し、申込フォームへ誘導します。

## デプロイ先

GitHub Pages（公開後に下記URLを実際のものへ更新してください）
https://anetai-droid.github.io/NO17--kaigo-juyo-lp/folder/index.html
## ディレクトリ構成

```
folder/
  index.html            … LP本体（HTML/Tailwind CDN/Vimeo埋め込み）
  1.png / 2.png         … ヒーロー候補画像
  main.webp / sub.webp  … 写真素材
  svc-*.png             … 写真ストリップ用素材
  index_original.html.bak … 旧版（障害福祉向け）バックアップ
wrangler.jsonc          … Cloudflare 用設定（任意）
```

## 構成（セクション）

ヒーロー → お悩み共感（CHECK）→ サービス紹介＋紹介動画（ABOUT）→ 写真ストリップ → 選ばれる3つの理由（FEATURES）→ 対応サービス（SERVICE）→ 料金（PRICE）→ 申込・相談フォーム（CONTACT）→ フッター

## メモ・TODO

- 申込フォームはオートビズ（`https://76auto.biz/nfja/responder.php` / `tno=63`）に送信。介護用の配信先がある場合は差し替え。
- 紹介動画は Vimeo（`video/1179456430`）を埋め込み。介護版の動画があれば差し替え。
- 特定商取引法・プライバシーポリシー・利用規約のリンクは現状 `fukushi-jigyousya.com` のもの。必要に応じて更新。
- NEWS（新着情報）はLPには不要のため未掲載。
