# oby-2026-1206-fair

第14回 兵庫県私立小学校フェア（2026年12月6日）の入試広報用。

LPは作らず、go/ 中継ページから兵庫県私立小学校連合会の予約ページへ誘導する。

- 転送先：https://o-asako.com/hyogo-junior/

## URL

- 中継ページ：https://oby-kouhou.github.io/oby-2026-1206-fair/go/?s=（ソース名）

## 計測

- GA4計測ID：G-WG4L0SGNJJ（プロパティ 533276091）
- イベント：`go_relay`（source、event_name_jp `fair_1206`）
- 予約は連合会のフォームで完結するので、数えられるのはQR・リンクから来た人数まで。予約数は分からない

## ソース別パラメータ（go/?s=）

| s= の値 | 意味 |
|---------|------|
| winds11 | Winds From 11月号のQRから（2026/11作成） |
| test | テストアクセス（除外） |
