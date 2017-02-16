## python環境の構築
### pythonを導入

- http://qiita.com/shizuma/items/027167c6257f1c9d2a6f
- http://12px.com/blog/2016/11/deeplearning/

```
$ brew install pyenv
$ brew install virtualenv
```

```
$ source ~/.zshrc
dyld: Library not loaded: /usr/local/opt/readline/lib/libreadline.6.dylib
  Referenced from: /usr/local/bin/bash
  Reason: image not found
dyld: Library not loaded: /usr/local/opt/readline/lib/libreadline.6.dylib
  Referenced from: /usr/local/bin/bash
  Reason: image not found
dyld: Library not loaded: /usr/local/opt/readline/lib/libreadline.6.dylib
  Referenced from: /usr/local/bin/bash
  Reason: image not found
```

readlineでエラー6系がなかったのでとりあえずリンク貼る

- http://qiita.com/kanpou_/items/0fe67e313c03e87277e7


```
$ ln -s /usr/local/opt/readline/lib/libhistory.dylib /usr/local/opt/readline/lib/libhistory.6.dylib
```

```
$ pyenv install 3.5.1
$ pyenv rehash
$ python --version
Python 3.5.1
```

### ライブラリを導入

```
$ pip install --upgrade pip
$ pip install numpy
$ pip install matplotlib
$ pip install pillow
```

## pythonを試す

