this is a fork of https://github.com/hw431/github-actions-youtube-dl

[en]

# desc

Download videos from youtube and put it into release.

# How to use

Fork this repo and modify dl.conf as the url of videos you need download**s**. One url one line.

Notice: the disk space of your videos must less than 14GB.

# IMPORTANT

If you had downloaded all the videos, please remove releases, give github more space for others.

THANKS Github!

https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners#supported-runners-and-hardware-resources

[cn]

# 说明

使用 Github Actions 从 Youtube 下载视频并放到 Release

# 使用

Fork 这个仓库并将 dl.conf 修改为你需要下载的视频的 URL，一个 URL 占一行。

一次下载的视频总大小不得超过 14GB。

如果你只需要下载字幕，可以手动将 dl.conf 中的 `--write-auto-sub` 取消注释

# 注意

如果你已经下载完视频了，不要忘记把 realses 中的视频给删掉。请 *善意* 使用 Github 给出的免费空间。

# 鸣谢

- 感谢 Github 对 Action 和 Release 宽松的限制，使得本项目可以实现
- 感谢 Youtobe-dl 提供的下载器，使得我们可以使用 Youtobe-dl 去下载喜欢的视频
- 感谢 marvinpinto 提供的 workflow 脚本，使我可以便捷地上传多个 assets
- 感谢 Rar 提供的软件，使我简化了分卷压缩包的创建