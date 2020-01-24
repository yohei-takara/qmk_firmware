# buld

keymapからhexファイルの作成

```aidl
$ docker run -e keymap=my_keymap -e keyboard=ergodox_ez --rm -v $('pwd'):/qmk:rw edasque/qmk_firmware
```

作成されるhexファイルの場所

```aidl
$ qmk_firmware/.build/***.hex
```

# 書き込みツール

teensy

```aidl
$ brew cask install teensy
```
