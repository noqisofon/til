git subtree
=========================

submodule とは違うらしい。  
git clone する替わりにこう:

    % git subtree add --prefix ext/io-path https://github.com/scheme-gasket/scm-io-path.git

で、git pull する替わりにこう:

    % git subtree pull --prefix ext/io-path https://github.com/scheme-gasket/scm-io-path.git

これは git のステージ上に何かが乗っている時は失敗するので注意。


## 参照

- [git-subtree移行メモ](http://qiita.com/shogo82148/items/04b29b195dbbb373152f)
