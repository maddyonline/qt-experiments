Getting Started with Qt
=========
This repository contains a gentle introduction to getting started with Qt 5 (primarily on Mac OS X).

Installation
--------------
```sh
git clone https://github.com/maddyonline/qt-experiments.git
cd qt-experiments/
echo "Just trying some git sanity check commands"
git status
git branch -a
git pull
git push
cd ..
mkdir build-qt-experiments
export PATH=/Users/"your-username"/Qt/5.3/clang_64/bin:$PATH
qmake ../qt-experiments/SecondApp.pro
make
open SecondApp.app
```
