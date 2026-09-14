# 📦 我的 F-Droid 私人仓库

欢迎来我的个人 Android 应用分发站，所有 APK 通过 F-Droid 客户端自动更新。

## ✨ 仓库特色
- 📱 只放自用/精选 APK，持续维护
- 🔄 F-Droid 客户端一键添加、自动检测新版本
- ☁️ GitHub Actions 自动生成索引并部署到 GitHub Pages
- 🔐 仓库索引独立签名，客户端校验指纹

## 📲 如何在 F-Droid 添加本仓库
1. 打开 F-Droid → 设置 → 仓库/存储库 → ＋
2. 输入地址：
   https://xinxukong.github.io/F-Droid/repo
3. 确认添加并刷新即可看到应用

> 如果需要指纹方式，可后续在客户端查看本仓库指纹后分享给同事。

## 🗂 目录说明
- `repo/`：放 APK 文件，系统自动建索引
- `metadata/`：应用描述（首次构建后自动生成）
- `config.yml`：仓库名称、网址、签名配置
- `.github/workflows/build.yml`：自动构建部署脚本

## 🌸 访问量（Moe-Counter）
![Moe-Counter](https://count.getloli.com/get/@xinxukong-fdroid?theme=asoul)

想换风格把上面 `theme=asoul` 改成下面任意一个：
`moebooru` `3d-num` `ai-1` `booru-ffsr` `asoul` `random`

## ⚠️ 说明
本仓库仅供个人/小范围分发；APK 请使用已签名的 release 包。


