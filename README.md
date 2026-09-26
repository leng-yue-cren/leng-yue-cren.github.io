# leng-yue-cren.github.io

这个仓库现在只做一件事：把旧地址跳转到新的作品集站点。

**作品集 → https://design.lengyue.xyz/**

## 为什么清空了原来的内容

- 原来的 `index.html` 是一个没有内容的空模板（不含任何作品图），已由新的自托管站点取代；
- 仓库里混着一套 AI agent 的配置文件（`SOUL.md` / `IDENTITY.md` / `USER.md` / `skills/` 等），
  这些属于本机配置，不应该公开在 GitHub 上，已全部移除；
- 移除前的完整副本保留在本机 `D:\com\homepage\_legacy-leng-yue-cren.github-io\`。

## 现在仓库里有什么

- `index.html` —— 一个极简跳转页（meta refresh + JS，带 canonical 指向新站）
- `README.md` —— 本说明

## 如果以后想彻底删掉这个仓库

```sh
gh repo delete leng-yue-cren/leng-yue-cren.github.io
```
