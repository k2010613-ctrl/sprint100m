# 100m 11秒台チャレンジ

40歳から100m 11秒台を目指す練習アプリ（PWA）。

## ファイル
- index.html … アプリ本体
- manifest.json … ホーム画面用の設定
- sw.js … オフライン用
- icon.png / icon-192.png … アイコン

## 公開手順（スマホのSafariでOK）
1. GitHubで New repository → 名前 `sprint100m`・Public → Create
2. 「uploading an existing file」から上の6ファイルをアップ → Commit changes
3. Settings → Pages → Branch を `main` / `(root)` → Save
4. 1〜2分後に https://k2010613-ctrl.github.io/sprint100m/ を開く
5. Safariの共有ボタン →「ホーム画面に追加」

## 更新の仕方
1. index.html を差し替えて Commit
2. sw.js の `sprint100m-v1` の数字を1つ上げて Commit
3. アプリを2回開き直すと新しい版になる

## 注意
- 記録はスマホ内に保存。設定の「ファイルに書き出し」でたまにバックアップ
- 同じURLのままなら更新しても記録は消えない
