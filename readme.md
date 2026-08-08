# 🎓 安工大新生攻略

学长整理的安徽工业大学新生入学必看指南 · 非官方但走心

## 站点结构

| 文件 | 说明 |
|------|------|
| index.html | 首页：快速导航 + 速览 + 校史 + 官方入口 |
| prepare.html | 入学准备（证件/费用/资助/用品/信息渠道） |
| report.html | 报到流程（六步流程 + 交通指南） |
| military.html | 军训指南（物品清单/注意事项） |
| study.html | 学习攻略（教务/图书馆/保研/竞赛/奖学金） |
| plan.html | 大学规划（HR 视角四年规划） |
| colleges.html | 学院专业（14 个学院官网直达） |
| campus.html | 校区信息（佳山/秀山） |
| clubs.html | 校园生活（社团/食堂/住宿/体育） |
| tips.html | 学长忠告（10 条忠告/防骗/踩坑） |
| css/style.css | 全站共享样式 |

数据来源：安徽工业大学官网《学校简介》（数据截至 2026 年 4 月）、教务处、招生网、组织机构页。重要信息请以学校官方通知为准。

## 本地打开

直接双击 index.html，或在站点目录下运行：

```bash
python -m http.server 8000
# 访问 http://localhost:8000
```

## 部署到 GitHub Pages

### 方式一：命令行（需 GitHub Token）

```bash
git init
git add .
git commit -m "init: 安工大新生攻略"
git branch -M main
git remote add origin https://<你的TOKEN>@github.com/<用户名>/ahut-guide.git
git push -u origin main
```

推送后在 GitHub 仓库 Settings → Pages → Source 选择 `main` 分支即可，网址为：

```
https://<用户名>.github.io/ahut-guide/
```

### 方式二：网页拖拽（无需命令行）

1. 登录 GitHub → New repository 创建仓库（如 `ahut-guide`）
2. 仓库页面点 Add file → Upload files，把本站所有文件拖入上传
3. Settings → Pages → Source 选 `main` 分支 → Save

## 声明

⚠️ 本网站由热心学长个人制作，非学校官方平台。内容仅供参考，重要信息请以学校官方通知为准。
