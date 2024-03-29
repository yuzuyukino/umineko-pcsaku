# umineko-pcsaku
patch for translating Uminko Saku to Chinese

## Introduction

  该补丁用于将2019年10月4日发布的[海猫鸣泣之时咲](https://07th-expansion.net/umi_gensaku)中的两篇新内容《吾等的告白》以及《Last note of the Golden witch》翻译为简体中文，**并不包含本体游戏**。所以在使用补丁前你需要一份已安装的游戏资源，目前你可以在[这些店铺](https://07th-expansion.net/archives/4041)中购买正版copy.

## Credits

  除我以外，还有下面的个人或团体对该项目做出不可或缺的贡献（排名不分先后）：

  - [07th-mod](https://github.com/07th-mod/)：Ponscripter的开发和维护
  - linyueru8954，海喵鸣泣：《吾等的告白》文本的翻译
  - MMR六轩岛调查队：本体汉化补丁的assets帮我节省了大量的时间
  - [日不落汉化组](https://snsteam.club/)：对《Last note》翻译文本的授权
    - LUMI：翻译/润色
    - RAN：校对
  

## Instructions

  1. 在你的电脑上安装一份咲的本体游戏。
  2. 打开游戏安装目录。（默认路径为C:\Program Files (x86)\07th Expansion\uminekoSaku_Disc2\うみねこのなく頃に咲）
  3. 为将游戏默认字体更换为补丁使用的默认字体（黑体），你需要将游戏目录中的文件夹 `fonts` 以及字体文件 `default.ttf` 重命名为游戏无法识别的形式，如 `fonts_0` 和 `default_0.ttf`. 或者你也可以直接将这二者删除但我不推荐这样做，因为5.的缘故。
  4. 将你下载的补丁压缩包直接解压到游戏目录中（应包含有四项：bmp、0.utf、default.ttf、海猫鸣泣之时咲.exe），解压后你的游戏目录应是这个样子：
![aaa](https://github.com/yuzuyukino/umineko-pcsaku/assets/158812289/e6e3ae14-21b9-45d9-9bab-baaaf347a086)

  5. 若在安装补丁后你想要将游戏回退为日文原版，只需依次撤销上述4->3的步骤，即删除补丁文件，取消重命名等。
  6. 若你需要更换文本显示字体，请将你想要的字体文件重命名为 `default.ttf` 复制并替换到游戏目录中。
  7. 运行 `海猫鸣泣之时咲.exe` .（为避免可能的问题，请尽量右键选择以管理员身份运行）
  8. Enjoy! 
  
## Issues

  目前该补丁或者说Ponscripter引擎本身的一个bug是当你在游戏中查看历史文本时，backlog文本框会不自然地向左偏移一小段而不是居中，并且偏移的距离与你使用的字体有关。我只测试过黑体、宋体以及游戏自带的默认字体，三者偏移量：黑体>宋体>默认>0. 也就是说如果你将游戏字体更换为这三者以外的其他字体后有可能出现的问题是历史文本会超出窗口范围，**最坏的情况下游戏可能会崩溃**。如果你遇到了这个问题，请反馈你所使用的字体并尝试更换为其他字体。

  
  ![2](https://github.com/yuzuyukino/umineko-pcsaku/assets/158812289/ad913d42-f065-4303-9752-4083c193050d)
![1](https://github.com/yuzuyukino/umineko-pcsaku/assets/158812289/ea4b25b9-1446-4364-afe4-8ad02790b771)

