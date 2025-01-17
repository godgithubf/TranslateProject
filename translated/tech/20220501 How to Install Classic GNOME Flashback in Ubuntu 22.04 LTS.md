[#]: subject: "How to Install Classic GNOME Flashback in Ubuntu 22.04 LTS"
[#]: via: "https://www.debugpoint.com/2022/05/gnome-classic-ubuntu-22-04/"
[#]: author: "Arindam https://www.debugpoint.com/author/admin1/"
[#]: collector: "lujun9972"
[#]: translator: "geekpi"
[#]: reviewer: " "
[#]: publisher: " "
[#]: url: " "

如何在 Ubuntu 22.04 LTS 中安装 Classic GNOME Flashback
======
关于如何在最新的 UBUNTU 22.04 LTS 中安装旧的 Classic GNOME Flashback 的快速指南。

[GNOME Flashback][1]（又名 classic GNOME）是旧 GNOME 3 shell 的一个分支，它使用早期 GNOME 2 技术的布局和原则。它的速度快如闪电，并且在设计上占用的 CPU 和系统资源非常少。因此，它非常适合可以追溯到几十年前的旧硬件。

随着带有现代 GNOME 42 的 [Ubuntu 22.04 LTS][2] 的发布，有必要寻找消耗很少系统资源的桌面环境选项。

此外，GNOME Flashback 很容易安装在现代 Ubuntu Linux 中，你仍然可以享受 Ubuntu 性能而不必担心 GNOME 42、GTK4、libadwaita 和其他东西。

### 在 Ubuntu 22.04 LTS 中下载并安装 Classic GNOME Flashback

按照以下步骤在 Ubuntu 22.04 LTS 中下载并安装经典 GNOME Flashback（Metacity）。

在 Ubuntu 22.04 LTS 中打开终端（CTRL+ALT+T）并运行以下命令。安装大小约为 61MB。

```

    sudo apt update

```

```

    sudo apt install gnome-session-flashback

```

![Install GNOME Classic Flashback Metacity in Ubuntu 22.04 LTS][3]

最后，安装完成后，退出。重新登录时，在登录选项中使用 GNOME Classic。

![Choose GNOME Classic while logging in][3]

### 经典 GNOME Flashback 的特点

首先，当你登录时，你将体验到传统的 GNOME 技术，该技术已被证明具有良好的生产力并且比今天的技术快得多。

在顶部有旧版面板，左侧是应用菜单，而系统托盘位于桌面的右上方。应用程序菜单显示所有已安装的应用和软件快捷方式，你可以在工作流程中轻松浏览。

此外，在右侧部分，系统托盘具有默认小部件，例如网络、音量控制、日期和时间以及关机菜单。

![Classic GNOME Flashback Metacity in Ubuntu 22.04 LTS][3]

底部面板包含打开的窗口和工作区切换器的应用列表。默认情况下，它为你提供四个工作区供你使用。

此外，你可以随时更改顶部面板的设置以自动隐藏、调整面板大小和背景颜色。

除此之外，你可以通过 ALT+Rigth 单击顶部面板添加任意数量的旧版小程序。

![Panel Context Menu][3]

![Add to panel widgets][3]

### GNOME Classic 的性能

首先，磁盘空间占用极小，即仅安装 61 MB。我的测试使用了大约 28% 的内存，其中大部分被其他进程占用。猜猜是谁？是的，是 snap-store 又名 Ubuntu 软件。

因此，总体而言，它非常轻巧，内存（仅 28 MB）和 CPU（0.1%）占用空间非常小。

![Performance of GNOME Classic in Ubuntu 22.04][3]

此外，假设你将其与同样使用相同技术的 Ubuntu MATE 进行比较。在这种情况下，它比 MATE 更轻量，因为你不需要任何额外的 MATE 应用及其用于通知、主题和其他补充资源的本机包。

### 结束语

我希望本指南在你决定在 Ubuntu 22.04 LTS Jammy Jellyfish 中安装 GNOME Classic 之前帮助你获得必要的信息。

* * *

我们带来最新的技术、软件新闻和重要的东西。通过 [Telegram][4]、[Twitter][5]、[YouTube][6] 和 [Facebook][7] 保持联系，不错过任何更新！


--------------------------------------------------------------------------------

via: https://www.debugpoint.com/2022/05/gnome-classic-ubuntu-22-04/

作者：[Arindam][a]
选题：[lujun9972][b]
译者：[geekpi](https://github.com/geekpi)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]: https://www.debugpoint.com/author/admin1/
[b]: https://github.com/lujun9972
[1]: https://wiki.archlinux.org/index.php/GNOME/Flashback
[2]: https://www.debugpoint.com/2022/01/ubuntu-22-04-lts/
[3]: data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7
[4]: https://t.me/debugpoint
[5]: https://twitter.com/DebugPoint
[6]: https://www.youtube.com/c/debugpoint?sub_confirmation=1
[7]: https://facebook.com/DebugPoint
