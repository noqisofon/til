git subtree
=========================

submodule とは違うらしい。  
git clone する替わりにこう:

    % git subtree add --prefix ext/io-path https://github.com/scheme-gasket/scm-io-path.git

で、git pull する替わりにこう:

    % git subtree pull --prefix ext/io-path https://github.com/scheme-gasket/scm-io-path.git

