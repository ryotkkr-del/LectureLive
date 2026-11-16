# LectureLive

授業の音声を記録し、日本語のリアルタイム文字起こしをローカルに保存するWindowsアプリです。

## 現在の開発状況

v0.6.0のコードはアプリの配布ZIPに含まれています。GitHubリポジトリへの初回のソースコード登録は、ZIP内の `publish_to_github.bat` を実行します。

- 録音元：Windowsのマイク / PC内部音声（WASAPI）
- 記録：WAV、文字起こしTXT、復旧ログ
- 音声認識：faster-whisper（初回のモデル取得後はオフライン）
- 更新：GitHub Releasesに公開された新版を起動前に確認

**注意**：録音・認識のWindows実機および90分連続運用は未検証です。最初は短い試験録音で確認してください。

## 初回GitHub登録

1. LectureLive_v0.6.0.zipをPCに解凍する
2. Gitをインストールし、GitHubにログインする
3. `publish_to_github.bat` を実行し、差分を確認して `yes` と入力する
4. ソースコードが登録された後、GitHubのActionsから公開版を作成する

学内の録音許可やプライバシーを遵守してください。
