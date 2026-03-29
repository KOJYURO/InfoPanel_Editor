# infoPanel Editer

Discord bot for generating 7 Days to Die XUi XML and returning downloadable files in Discord.

## Bot Brief (BB)

infoPanel Editer generates `xui.xml` and `windows.xml` from slash command input.
It is intended for simple distribution use where operators want a fixed export path and immediate XML download from Discord.

### Key Features
- Generate `xui.xml` and `windows.xml` from Discord
- Save output to a fixed XUi directory
- Return generated XML as Discord attachments
- Keep a simple sample set for redistribution

### How It Works
- `/xui_download`: Keep Sample XML structure and edit only localization strings
- Save `xui.xml` and `windows.xml` to the fixed XUi directory under WhiteRiverChallenges
- Return `xui.xml`, `windows.xml`, and `Localization.txt` as attachments

### Good to Know
- Output path is fixed by design
- Generated files overwrite the current fixed-path files
- Distribution samples are bundled under `Sample/`
   
---

## 日本語

7 Days to Die の XUi XML を Discord から生成し、添付ファイルとしてダウンロードできる配布向け Bot です。

## Bot Brief (BB)

infoPanel Editer は、スラッシュコマンド入力から `xui.xml` と `windows.xml` を生成します。
固定保存先へ上書きしつつ、Discord 添付としてそのまま取得できる、配布向けの最小構成を目的にしています。

### 主な機能
- Discord から `xui.xml` / `windows.xml` を生成
- WhiteRiverChallenges 配下の固定 XUi ディレクトリへ保存
- XML を Discord 添付として返却
- 再配布しやすい `Sample/` 一式を同梱

### 動作フロー
- `/xui_download`: `Sample/` 構成を維持し、文字列のみ編集
- `xui.xml` と `windows.xml` を固定保存先へ上書き
- 実行者へ `xui.xml` / `windows.xml` / `Localization.txt` を添付返却

### 補足
- 出力先は仕様として固定です
- 固定保存先の XML は毎回上書きされます
- 配布用サンプルは `Sample/` に含めています
