# Hello World

課題の「受け取り，クローン，変更，コミット，提出，再提出」練習

1. 演習用PCのセットアップをする．<br>
別に配布した資料「0110_演習用PCのセットアップ.pdf」に従い「gitコマンドの個人設定」，
「git個人アクセストークンの取得」を済ませておく．

1. 課題を受け取る．

  - Teamsの投稿やメールで届いたリンクをクリックする．
  （初回はGitHub ClassroomとGitHubのアカウントを結びつける操作がある）
  - Webブラウザに表示された`Accept this assignment`ボタンをクリックする．
  - 自分専用の課題レポジトリがGitHub上に作成される．
  - 表示されたリンク`https://github.com/SysProIE4-20...`をクリックする．<br>
    （自分専用の課題レポジトリが見える）

2. GitHub上のレポジトリをローカルにコピーする．（クローン）

  - `[<> Code]`ボタンをクリックする．
  - 表示された候補から適切な方法を選ぶ．<br>
    （とりあえずは，URLの右にある![コピーボタン](button.png)をクリックしてURLをコピーする．）
  - ターミナルを開き適切なディレクトリに移動し次を実行する．<br>
    `$ mkdir SysPro` （初回だけ）<br>
    `$ cd SysPro`<br>
    `$ git clone ...`（`...`の部分に上でコピーしたURLをペーストする．）<br>
    `Username for ... : i20xxx`（Username には GitHub のアカウント名を入力する．）<br>
    `Password for ... : `（Password にはアクセストークンを入力する．）

3. 課題を完成する．（変更）

  - クローンしたレポジトリの中に移動し内容を確認する．<br>
    `$ ls`（クローンしたレポジトリを確認）<br>
    `$ cd <レポジトリのディレクトリ>`<br>
    `$ ls`（クローンしたレポジトリの中を確認）
  - レポジトリ内のファイルを変更して成果物を完成する．<br>
    今回は`hello.c`を完成して動作テストをする．<br>
    （「hello,world」を一行に表示するプログラムが完成できたらOK）

4. 変更を確定する．（コミット）<br>

  - ローカルレポジトリにコミットする．<br>
    `$ git commit -am "何か変更内容が分かるメッセージ"`

5. ローカルレポジトリの変更をGitHubに反映する．（提出）<br>
  `$ git push`（変更結果がアップロードされる）

6. 添削結果がメールなどで届いたら確認する．（再提出）

  - メールに書かれたコメントをよく読む．
  - 「合格」がもらえるまで「変更，コミット，提出」を繰り返す．<br>
    （変更はローカルなレポジトリに続けて下さい．_pullやcloneをしてはいけません_）
  - Webでレポジトリを見た時「Merge pull request」や「Close pull request」をしない．<br>
    （再提出しても教員に通知が行かないくなる）
