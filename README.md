# Setting-up-tmux

.tmux.confをコピーする

.bashrcをコピーする

デフォルトで行番号表示させたい場合は、.vimrcを
設定しておく。

$ vi ~/.vimrc

" 行番号を表示

set number

[WSL2上のUbuntuで最初にする作業まとめ](https://qiita.com/nab/items/18b5b6092ae0fc31a457)

Wi-Fiネットワークアダプタの共有を有効にする。[【WSL2】WSL2でUbuntuを動かしたらハマった件（sudo apt-get updateできない）](https://qiita.com/riraosan/items/3b036367d6d9f4e6b52a)

設定　＞　ネットワークとインターネット　＞　ネットワークの詳細設定　＞　ネットワークアダプターオプションの詳細　＞　どれか選ぶ　＞　プロパティ　＞　共有　＞　チェックをつける

sudo apt update

sudo apt upgrade

git のuser.name とuser.email を設定する

git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

Tmux Weatherを用意する

git clone https://github.com/aaronpowell/tmux-weather ~/clone/path

うまく行かないときは，-c http.proxy="" -c https.proxy="" をつける

ステータスバーにbandwidth を表示する

apt-get install gawk net-tools coreutils

下のバーにGitの情報を表示

git clone https://github.com/arl/tmux-gitbar.git ~/.tmux-gitbar

ステータスラインにカレントディレクトリを表示する[tmuxのペインのステータスラインにgitのブランチとかディレクトリとか表示する(プロンプトはもう古い)](https://qiita.com/arks22/items/db8eb6a14223ce29219a)

