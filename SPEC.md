# リスキリング診断【無料】あなたに向いたIT・データスキルが分かる - 技術仕様書

## 概要

**サービス名**: Reskilling Advisor
**バージョン**: 1.0.0
**更新日**: 2026-05-27
**URL**: https://appadaycreator.com/reskilling-advisor/

現職スキルと市場ニーズから最適な学び直しを診断。ITエンジニア・データサイエンス・DX人材への転換を提案。

## データ管理

- **ストレージ**: ブラウザ localStorage（外部API通信なし）
- **永続化**: ページ読み込み時に自動復元
- **クリア**: ブラウザのサイトデータ削除で初期化

## 技術スタック

- HTML5 / CSS3 / Vanilla JavaScript
- PWA対応（manifest.json / Service Worker）
- レスポンシブデザイン（モバイルファースト）

## 使い方

1. 記録したい項目を入力フォームに入力する
2. 「追加」または「記録」ボタンをクリックする
3. 記録一覧で過去のデータを確認する
4. グラフや集計で傾向を把握する
5. 継続的に記録して変化を追跡する

## よくある質問（FAQ）

**Q: リスキリング診断は無料で使えますか？**

はい、完全無料・登録不要でご利用いただけます。

**Q: 記録データはどこに保存されますか？**

ご使用のブラウザのローカルストレージに保存されます。他のデバイスとは共有されません。

**Q: ブラウザを閉じても記録は残りますか？**

はい、同じブラウザを使う限りデータは保持されます。

**Q: 記録を削除するにはどうすればいいですか？**

リセットボタン、またはブラウザのサイトデータをクリアすることで削除できます。

**Q: スマートフォンで利用できますか？**

はい、スマートフォン・タブレット・PCすべてでご利用いただけます。


## 関連サービス

- [睡眠の質チェッカー](https://appadaycreator.com/sleep-quality-checker/)
- [BMI・体重管理](https://appadaycreator.com/bmi-body-tracker/)
- [家計簿診断](https://appadaycreator.com/household-budget-analyzer/)

## テスト

| ファイル | フレームワーク | 概要 |
|---------|--------------|------|
| `tests/e2e/` | Playwright | 本番URL対象E2E（Jest対象外） |

## デプロイ

GitHub Pages（mainブランチ push → 自動デプロイ）

## ライセンス

MIT License
- 2026-05-29: PWA theme-color ブランドカラー統一 (#6366F1→#7c3aed) [improve_auto 横展開]
- 2026-05-29: P1〜P3 改善実装 [improve_auto] スキップリンク修正・twitter:meta head移動・window.onerror重複削除・saveReskillResult()バグ修正・ローディングスピナー改善・スコアバーチャート追加・LINEシェアボタン追加・使い方セクション修正
