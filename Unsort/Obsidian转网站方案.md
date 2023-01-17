# Obsidian推送到网站
quartz+obsidian可以完成推送到网站的过程。我们以后慢慢完善。
quartz+obsidian地址：https://forum-zh.obsidian.md/t/topic/8852
决定了，目前就是用obsidian来做笔记。后面自己写脚本进行配置。

[obsidian + github action方案](https://www.bilibili.com/video/BV18Y4y1H7Gu/?vd_source=64171f856db920efec690ac6c00f5cee)

全部使用wiki链接。后面转网站的时候，通过脚本、语法将wiki链接改为md链接。或者寻找是否支持wiki的hugo模板。

- [ ] 如何同步obsidian设置
- [ ] 如何同步仓库
- [ ] 如何设置图床


# 如何使用github进行同步
1. 在仓库根目录初始化git
2. 使用git连接上远程仓库
3. 在obsidian配置obsidian-git插件。插件会自动进行commit，并进行推送。
