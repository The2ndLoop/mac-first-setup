# Mac購入後の初期設定
- iTerm2のインストール
- 入力関係の設定
- nodeのバージョン管理nのインスト

## iTerm2のインストール
capslockにcontrolを割り振り。
capslockとスペースで開くようにしている
[profile](./com.googlecode.iterm2)

## 入力関係の設定
全部設定した後、mac 再起動

### 長押しで英語が連続して打てるようにする
```sh
defaults write -g ApplePressAndHoldEnabled -bool true
```

### カーソルの速度変更
```sh
defaults write -g InitialKeyRepeat -int 10
defaults write -g  KeyRepeat -int 1.2
```

## Nodeのバージョン管理nのインスト
```sh
brew install n
```
