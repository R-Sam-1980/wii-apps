# Nintendont

- 网址：https://github.com/FIX94/Nintendont
- 版本：6.504
- 时间：2026-04-09


## Nintendont 分支

### App 更新说明

github 尚未提供 App 打包下载，需要手动更新：

源项目 FIX94/Nintendont | 目标项目 R-Sam-1980/wii-apps
--- | ---
loader/loader.dol | apps/Nintendont/boot.dol
nintendont/icon.png | apps/Nintendont/icon.png
nintendont/meta.xml | apps/Nintendont/meta.xml

- FIX94 目前的做法是：每次修改了代码之后会重新编译生成 loader.dol
- R-Sam 对应的做法是：不定期检查 FIX94 是否有更新，替换完 .dol 文件之后，手动修改 meta.xml 里面的 version 和 release_date


### 频道安装文件

- wad\Nintendont 文件夹里的频道安装文件来自：https://wads.gabubu.xyz/wads
- 两个频道使用了不同的背景音乐，除此之外其他地方都一样
