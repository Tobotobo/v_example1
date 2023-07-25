# v_example1

## 環境
```
> v --version
V 0.4.0 3a91a5e
```

## インストール
https://github.com/vlang/v
```
git clone https://github.com/vlang/v
cd v
./make.exe
```

## 実行
```
v init
v run src/main.v
v run src/fizz_buzz.v
```

## コンパイル
```
v src/main.v
v src/fizz_buzz.v
```

## V UI
https://github.com/vlang/ui
```
v install ui
v src/v_ui_example1.v
```
※0.0.4
- 一部マージンが効いていない。
- 全体的にボケがある。
- 日本語が文字化け
- IME非対応


## V-WebUI
https://github.com/webui-dev/v-webui
```
v install https://github.com/webui-dev/v-webui
v src/v_webui_example1.v
```
※2.3.0
- ビルドしようとするとエラー
  ```
  > v src/v_webui_example1.v
  builder error: 'tlhelp32.h' not found
  ```
