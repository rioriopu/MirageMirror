# Mirage Mirror

FFXIV (Dalamud) 用のミラプリ管理プラグインです。

> dev1 リリース版。動作確認・フィードバック歓迎。

## インストール

1. XIVLauncher (Dalamud) で `/xlsettings` を開く
2. **「実験的」(Experimental)** タブを開く
3. **「カスタムプラグインリポジトリ」** に下記 URL を追加して **「保存」**:
   ```
   https://raw.githubusercontent.com/rioriopu/MirageMirror/main/repo.json
   ```
4. プラグインインストーラを開き直す → **「Mirage Mirror (dev1)」** を検索 → インストール

## 使い方

- `/mmr` または `/miragemirror` でウィンドウを開閉
- ターゲットしてからウィンドウ右上の「対象を取り込む」で装備取り込み
- 取り込みタブで mirapri / Eorzea Collection の URL を貼り付けて取り込み
- 「着てみる」で自キャラに視覚プレビュー (Glamourer 方式、サーバ送信なし)

## 主な機能

| 機能 | 説明 |
|------|------|
| ターゲットスキャン | 他プレイヤー / 自キャラの装備を視覚から特定 |
| URL 取り込み | mirapri / Eorzea Collection からグラマー取り込み |
| ローカルプレビュー | サーバ送信なしの「着てみる」、ジョブ変更で自動解除 |
| プレート登録 | 取り込み結果をミラージュプレートへ書込み (試験機能) |
| 所持品判定 | バッグ / アーマリー / 装備中 / ドレッサー / キャビネット / リテイナー / カバン |
| 検索タブ | 全装備 + 全アイテムを多軸フィルタ + シリーズグループ化 |
| お気に入り | 構成を保存、武器の対象ジョブも自動表示 |
| Glamourer 連携 | base64 デザインコピー |

## 動作要件

- FFXIV (DX11) + Dalamud (API Level 15)
- .NET 10 ランタイム (Dalamud 同梱)

## サポート

- バグ報告 / 機能要望: [GitHub Issues](https://github.com/rioriopu/MirageMirror/issues)
- 設定タブからもコマンド一覧を確認できます

## ライセンス

(配布元で記載)

---

*このリポジトリには配布用のメタデータのみが含まれます。ソースコードは別リポジトリで管理しています。*
