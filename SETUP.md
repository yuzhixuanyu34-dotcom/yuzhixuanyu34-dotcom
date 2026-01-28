# GitHub Profile 配置指南

## 📋 已完成的美化

你的 GitHub Profile 已经添加了以下美化元素：

1. **动态打字效果** - 使用 readme-typing-svg
2. **访问量统计** - Profile views counter
3. **技能图标** - 使用 skillicons.dev
4. **GitHub 统计卡片** - 显示统计数据和常用语言
5. **连续贡献统计** - GitHub streak stats
6. **GitHub 奖杯** - 成就展示
7. **活动图表** - 贡献活动可视化
8. **贡献蛇蛇动画** - 吃掉你的贡献记录
9. **3D 贡献图** - 立体展示贡献
10. **名言卡片** - 随机编程名言

## 🚀 需要配置的功能

### 1. GitHub Actions 权限设置

为了让自动化工作流正常运行，需要配置 GitHub Actions 权限：

1. 进入仓库设置：`https://github.com/yuzhixuanyu34-dotcom/yuzhixuanyu34-dotcom/settings`
2. 找到 **Actions** → **General**
3. 在 **Workflow permissions** 部分，选择 **Read and write permissions**
4. 勾选 **Allow GitHub Actions to create and approve pull requests**
5. 点击 **Save**

### 2. WakaTime 代码统计（可选）

如果想显示每周代码统计，需要配置 WakaTime：

1. 注册 [WakaTime](https://wakatime.com/)
2. 获取你的 API Key
3. 在 VS Code 中安装 WakaTime 插件
4. 在 GitHub 仓库设置中添加 Secret：
   - 名称：`WAKATIME_API_KEY`
   - 值：你的 WakaTime API Key

### 3. Spotify 播放卡片（可选）

如果想显示最近在听的音乐：

1. Fork [novatorem](https://github.com/novatorem/novatorem) 仓库
2. 部署到 Vercel
3. 连接你的 Spotify 账号
4. 更新 README 中的链接

### 4. 更新联系方式

在 README 中更新以下内容为你的真实信息：

- CSDN 博客链接
- Bilibili 主页链接
- 其他社交媒体链接

## 📝 推送更新

完成配置后，将更改推送到 GitHub：

```bash
cd yuzhixuanyu34-dotcom
git add .
git commit -m "Update GitHub profile with beautiful README"
git push origin main
```

## 🎨 自定义主题

当前使用的主题是 `tokyonight`，你可以更改为其他主题：

- `radical`
- `merko`
- `gruvbox`
- `dark`
- `nord`
- `dracula`

只需在 README 中将 `theme=tokyonight` 替换为你喜欢的主题名称。

## 🔄 手动触发工作流

首次设置后，可以手动触发工作流：

1. 进入 **Actions** 标签页
2. 选择对应的工作流
3. 点击 **Run workflow**

## 📚 参考资源

- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [Skill Icons](https://github.com/tandpfun/skill-icons)
- [Snake Animation](https://github.com/Platane/snk)
- [3D Contribution](https://github.com/yoshi389111/github-profile-3d-contrib)

## 💡 提示

- 蛇蛇动画和 3D 贡献图会在每天自动更新
- 首次运行可能需要几分钟才能看到效果
- 如果图片无法显示，请检查 GitHub Actions 是否成功运行
- 确保仓库名称与你的用户名完全一致：`yuzhixuanyu34-dotcom`
