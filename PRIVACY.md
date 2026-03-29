# Privacy Policy / プライバシーポリシー

## EN

### 1. Scope
This policy applies to infoPanel Editer operations in Discord servers.

### 2. Data Processed
The bot may process:
- Guild and channel context needed to answer slash commands
- Slash command parameters used to generate XML
- Generated XML files written to the fixed output directory
- Runtime logs in terminal or service logs

### 3. Purpose
Data is used only to:
- Generate `xui.xml` and `windows.xml`
- Return generated files to the command invoker context
- Maintain stable operation and troubleshoot errors

### 4. Storage
- Generated files: `/root/Release/WhiteRiverChallenges/Config/XUi/`
- Sample files: `Sample/`
- Logs: terminal output or service logs

### 5. Sharing
Generated files are returned only within the Discord command context used to request them.
The bot does not intentionally share personal data with third parties.

### 6. Retention and Deletion
Generated files remain in the fixed output path until overwritten or manually deleted.
Discord-side message retention follows each server's own policy.

### 7. Security Notes
- Keep the bot token in environment variables or protected env files
- Limit command access to trusted roles or channels
- Back up production XML if the fixed output path is shared with live files

### 8. Contact
Use your own server support contact for privacy-related requests.

---

## JP

### 1. 適用範囲
本ポリシーは infoPanel Editer の Discord 運用に適用されます。

### 2. 処理する情報
本ボットは次の情報を処理する場合があります。
- スラッシュコマンド応答に必要なギルド/チャンネル文脈
- XML 生成に使うコマンド入力値
- 固定保存先に書き込まれる生成 XML
- ターミナルまたはサービスログ

### 3. 利用目的
情報は次の目的でのみ利用します。
- `xui.xml` と `windows.xml` の生成
- 実行コンテキストへの生成ファイル返却
- 安定運用と障害調査

### 4. 保存先
- 生成ファイル: `/root/Release/WhiteRiverChallenges/Config/XUi/`
- サンプルファイル: `Sample/`
- ログ: ターミナル出力またはサービスログ

### 5. 共有
生成ファイルは、要求を行った Discord コマンド文脈にのみ返却されます。
設計上、個人情報を第三者へ意図的に共有しません。

### 6. 保持期間と削除
生成ファイルは、次回上書きまたは手動削除まで固定保存先に残ります。
Discord 側の保持期間は各サーバー方針に従います。

### 7. セキュリティ注意
- Bot トークンは環境変数または保護された env ファイルで管理してください
- 実行権限は信頼できるロール/チャンネルへ限定してください
- 固定保存先が本番 XML と共有の場合は事前バックアップを推奨します

### 8. 連絡先
プライバシー関連の問い合わせは各運用サーバーの窓口で対応してください。