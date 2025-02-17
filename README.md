# 宇浩渺AI探索

这是一个使用Hugo搭建的个人博客，专注于AI技术的探索与分享。

## 特点

- 使用Hugo静态站点生成器
- 采用Stack主题
- 支持文章搜索
- 响应式设计
- 支持暗色模式

## 本地开发

1. 克隆仓库：
```bash
git clone https://github.com/[你的GitHub用户名]/yangzai-blog.github.io.git
cd yangzai-blog.github.io
```

2. 安装Hugo（如果还没有安装）：
- Windows: `choco install hugo-extended`
- Mac: `brew install hugo`
- Linux: `sudo apt-get install hugo`

3. 启动本地服务器：
```bash
hugo server -D
```

4. 访问 http://localhost:1313 查看站点

## 添加新文章

```bash
hugo new content/post/your-post-name.md
```

## 部署

本站点通过GitHub Actions自动部署到GitHub Pages。
每次推送到main分支时会自动触发部署流程。

## 许可证

MIT 