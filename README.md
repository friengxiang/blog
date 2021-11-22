作用：。

## github做图床容量是无限的吗？
一般每个仓库0.5-1G，不建议超1g，装满换仓库即可，总无限
单个仓库超过1G会有人工审核，发现图床直接封号，审核通过后的仓库总大小限制100G .

## 加速cdn
可能还有不少人不知道 GitHub 图床的正确用法吧？我来给大家科普下。

创建一个 GitHub 仓库作为图床仓库，上传提交图片到仓库中
在要使用 GitHub 图床图片的地方将链接换为 https://cdn.jsdelivr.net/gh/{user}/{repo}/图片路径
举个栗子，比如 GitHub 官方仓库 github/explore 下话题 github 图片原始路径是：https://github.com/github/explore/blob/master/topics/github/github.png 访问起来贼慢。

使用 jsDelivr 加速后的地址：https://cdn.jsdelivr.net/gh/github/explore/topics/github/github.png 访问速度飞起，享受 jsDelivr 提供的全球 CDN 加速。
