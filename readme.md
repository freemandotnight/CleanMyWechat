# Clean My PC Wechat

![](https://markdown-pic-blackboxo.oss-cn-shanghai.aliyuncs.com/banner.png)

[![](https://img.shields.io/badge/platform-win64-lightgrey)](https://github.com/blackboxo/AutoDeleteFileOnPCWechat/releases) [![](https://img.shields.io/github/v/release/blackboxo/AutoDeleteFileOnPCWechat)](https://github.com/blackboxo/AutoDeleteFileOnPCWechat/releases) [![](https://img.shields.io/github/downloads/blackboxo/AutoDeleteFileOnPCWechat/total)](https://github.com/blackboxo/AutoDeleteFileOnPCWechat/releases)

自动删除 PC 端微信自动下载的大量文件、视频、图片等数据内容，解放一年几十 G 的空间占用。

该工具不会删除文字的聊天记录，请放心使用。请给个 **Star** 吧，非常感谢！

**现已经支持 Windows 系统中的所有微信版本。**

[国内地址 - 点击下载](
https://www.lanzoux.com/iamuhh1owmb)

[Github Release - 点击下载](
https://github.com/blackboxo/CleanMyWechat/releases/download/v2.0/CleanMyWechat.zip)

**碰到无法清理的，请记得勾选第一个选项，勾选后才会清理该账号下的内容。**

### [请我喝咖啡:coffee:](https://dun.mianbaoduo.com/@blackboxo)

## 特性
1. 自动识别微信账号，支持用户选择自定义路径；
2. 同时管理多个账号，保留配置参数，打开即用；
3. 自由设置想要删除的文件类型，包括图片类缓存、文件、图片、视频；
4. 自由设置需要删除的文件的距离时间，默认 365 天；
5. 删除后的文件放置在回收站中，检查后自行清空，防止删错需要的文件；
6. 支持删除进度的显示；

## 运行截图

![](https://markdown-pic-blackboxo.oss-cn-shanghai.aliyuncs.com/20200929151623.jpg)

## 微信现状

下载两年时间，微信一个软件就占用多达 33.5 G 存储空间。其中大部分都是与自己无关的各大群聊中的文件、视频、图片等内容，且很久以前的文件仍旧存在电脑中。

![](https://markdown-pic-blackboxo.oss-cn-shanghai.aliyuncs.com/20200213142805.png)

## 待改进

欢迎 PR！

- [ ] Bug：由于微信文件保存路径更改等导致的空配置文件 config.json 引起的闪退，可以考虑读取注册表，详见此 [Issue](https://github.com/blackboxo/CleanMyWechat/issues/45)
- [ ] 界面逻辑优化 [Issue](https://github.com/blackboxo/CleanMyWechat/issues/31)
- [ ] Mac 版本的开发，微信 Mac 版存在缓存大量占用问题
- [ ] 增加企业微信的支持
- [ ] Windows XP 系统的支持
- [ ] 有用户有每日定时删除的需求，考虑让应用开机自启动并常驻后台，或者“将选项变成参数加到快捷方式里运行自动执行”
- [ ] 增加应用打包后的签名
- [x] ~~自动识别出的多个微信账号的路径，让用户选择哪几个账号的需要删除，并记录参数~~
- [x] ~~更改为以天为单位~~
- [x] ~~增加多个微信路径的支持，支持保存路径~~
- [x] ~~支持 Microsoft Store 下载的微信 for Windows 版本~~
- [x] ~~支持 Microsoft Store 下载的微信 UWP 版本~~

其他需求详见 Issue

## 打包 EXE 方式

执行 pyinstaller -F -i images/icon.ico -w main.py， 会生成 dist 文件夹

将 images 文件夹拷贝到 dist 文件夹下，运行 dist/main.exe 即可执行。

## 致谢

[@mylittlefox](https://www.mylittlefox.art)：图标及 Banner 设计

[@Gears](https://refun.eu.org)：提供微信 for Windows 版本的文件目录树及测试支持

@SongJee：版本 1.1 的主要开发者，增加进度条，支持多个微信版本，自动识别路径

[@LenmoisLemon](https://github.com/LenmoisLemon)：版本 2.0 的主要开发者，全新 UI 设计，增加多用户配置

[@Louhwz](https://github.com/Louhwz)：版本 2.0 的主要开发者，增加多用户支持、多线程删除、自定义路径等

## 开发者

微博：@BlackBoXo

邮箱：bwu18@fudan.edu.cn

Blog：https://www.blackboxo.top/

## 项目 Star 数

[![Stargazers over time](https://starchart.cc/blackboxo/CleanMyWechat.svg)](https://starchart.cc/blackboxo/CleanMyWechat)
