# MangaRoll · 漫画时光卷 — Legal Docs

法律文档(隐私政策 / 用户协议)的源代码。通过 GitHub Pages 托管,自动获得 https URL,用于 App Store / 微信开放平台审核。

## 内容

| 文件 | 用途 | 部署后 URL |
|---|---|---|
| `index.md` | 首页导航 | `https://<USER>.github.io/<REPO>/` |
| `privacy.md` | 隐私政策(中英) | `https://<USER>.github.io/<REPO>/privacy/` |
| `terms.md` | 用户服务协议(中英) | `https://<USER>.github.io/<REPO>/terms/` |
| `_config.yml` | Jekyll 主题配置 | — |

## 部署到 GitHub Pages(5 分钟)

### 1. 在 GitHub 创建一个新 repo

- 仓库名建议: `mangaroll-legal` 或 `legal`
- 可以选 Private 或 Public,但 **Private repo 启用 Pages 需要 GitHub Pro 账号**,所以**强烈建议选 Public**
- 不要勾选 Add README(我们已有)

### 2. 推送代码

```bash
cd /Users/z77/Desktop/mangaroll-ios/mangaroll-legal
git init
git add .
git commit -m "init: privacy policy + terms of service"
git branch -M main
git remote add origin https://github.com/<你的用户名>/mangaroll-legal.git
git push -u origin main
```

### 3. 启用 Pages

在 GitHub 网页上:
- 进入 repo → Settings → Pages
- Source: **Deploy from a branch**
- Branch: `main` / `/ (root)`
- 点 **Save**
- 等 1–2 分钟,GitHub 会显示部署完成的 URL,例如:

  ```
  https://你的用户名.github.io/mangaroll-legal/
  ```

### 4. 验证

浏览器打开:

- `https://你的用户名.github.io/mangaroll-legal/privacy/`
- `https://你的用户名.github.io/mangaroll-legal/terms/`

确保两个 URL 都是 **https** 且能正常打开。

### 5. 把 URL 填入审核表单

| 平台 | 字段 | URL |
|---|---|---|
| App Store Connect | App 隐私 → 隐私政策网址 | `.../privacy/` |
| App Store Connect | App 信息 → 一般信息 → 隐私政策 URL | `.../privacy/` |
| App Store Connect | 用户服务协议(EULA,可选) | `.../terms/` |
| 微信开放平台 | 移动应用 → 隐私政策 URL | `.../privacy/` |

## 维护

修改文档后:

```bash
git add .
git commit -m "update: <说明>"
git push
```

GitHub Pages 会在 1–2 分钟内自动重新部署。

## 需要替换的字段

部署前请确认:

- [ ] 邮箱 `zooms@annauniv.edu` — 是你常用收邮件的地址(用户申诉、删数据请求都会发这里)
- [ ] 「上海市浦东新区人民法院」— 你想约定的诉讼管辖法院。如住址不在上海可改为常住地中级人民法院
- [ ] 价格 `¥30 / 月`、`¥198 / 年` — 与 App Store Connect 实际配置一致

如需修改,直接编辑 `privacy.md` 或 `terms.md`,然后 push。
