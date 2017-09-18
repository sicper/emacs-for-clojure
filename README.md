# 专为 Clojure 初学者准备的 Emacs 开发环境

> Mac/Linux/Windows 均支持🍺

Emacs 新手可参考 [this introductory tutorial](http://www.braveclojure.com/basic-emacs/) !

## 安装

1. 下载最新的 [Emacs](https://www.gnu.org/s/emacs/)
2. 删除 `~/.emacs` or `~/.emacs.d` 如果它们存在的话. (Windows 路径为`C:\Users\{username}\AppData\Roaming\.emacs.d`）。
3. 下载[本库](https://github.com/sicper/emacs-for-clojure/archive/master.zip)， 将里面的文件放入步骤2 创建的目录里面。这时的目录结构：
    ```
    $ tree ~/.emacs.d
    /home/vagrant/.emacs.d
    ├── customizations
    │   ├── editing.el
    │   ├── elisp-editing.el
    │   ├── misc.el
    │   ├── navigation.el
    │   ├── setup-clojure.el
    │   ├── setup-js.el
    │   ├── shell-integration.el
    │   └── ui.el
    ├── init.el
    ├── profiles.clj
    ├── README.md
    └── themes
        ├── color-theme-tomorrow.el
        ├── tomorrow-night-blue-theme.el
        ├── tomorrow-night-bright-theme.el
        ├── tomorrow-night-eighties-theme.el
        ├── tomorrow-night-theme.el
        ├── tomorrow-theme.el
        └── zenburn-theme.el

    2 directories, 18 files
    ```
4. 下载Clojure构建工具 [lein](https://leiningen.org/)，并把它添加到 PATH 里面
5. 把本项目的 `profiles.clj` 移动到 `~/.lein`下（Windows 路径：`C:\Users\{username}\.lein`），如果该文件不存在需要先提前创建
6. 开启 Emacs，这时会去下载第三方库，等安装完后，Clojure 开发环境就好了！Enjoy！

## 说明

1. 如有任何安装问题，请提 [issue](https://github.com/sicper/emacs-for-clojure/issues)，本库的目的就是为初学者提供一个可在三大主流操作系统上完美运行的 Clojure 开发环境！
2. 本库 Fork 自 [flyingmachine](https://github.com/flyingmachine/emacs-for-clojure)，由衷感谢！
3. Clojure 学习交流 QQ 群：119845407。