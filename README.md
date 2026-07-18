# Shea1992 用户主页站点

GitHub 用户主页仓库（`<username>.github.io`），托管在自定义域名 **www.ai-general.cn**。

## 作用

在此仓库配置自定义域名后，账户下所有项目站点（如 `ai-skill-kits`）会自动通过该域名访问：

| 类型 | URL |
|------|-----|
| 用户主页 | https://www.ai-general.cn |
| 项目站点 | https://www.ai-general.cn/ai-skill-kits/ |

## 文件说明

- `CNAME` — GitHub Pages 自定义域名记录（`www.ai-general.cn`）
- `index.html` — 主站首页（项目入口导航）

## DNS 配置（一次性，须在域名服务商完成）

```
类型:  CNAME
主机:  www
值:    shea1992.github.io
```

可选（apex 域名跳转到 www）：
```
类型:  A
主机:  @
值:    185.199.108.153
       185.199.109.153
       185.199.110.153
       185.199.111.153
```

完成后在 https://github.com/Shea1992/shea1992.github.io/settings/pages 启用 **Enforce HTTPS**。
