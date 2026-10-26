# 렛미플라이 · 관극 기록장

一个可部署到 GitHub Pages 的静态网站。纯 HTML/CSS/JavaScript，无需安装依赖。

## 包含功能
- 自定义添加/编辑/删除演出日程与演员
- 按演员筛选出演场次
- 标记观剧记录、座位区域/排/座号、票种、备注
- 统计观剧次数、观剧日期、演员组合
- 导出 PNG 统计卡片
- JSON 备份与导入恢复
- 自动保存在当前浏览器的 localStorage

## 本地预览
双击 `index.html` 用现代浏览器打开即可。建议 Chrome、Safari 或 Edge。

## 发布到自己的网址（GitHub Pages）
1. 登录 GitHub，创建一个新的 repository，例如 `let-me-fly-tracker`。
2. 将解压后的 `index.html` 和 `README.md` 上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 里选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，点击 **Save**。
6. 等待一两分钟，页面会显示网址，通常形如 `https://你的用户名.github.io/let-me-fly-tracker/`。

## 重要提示
- 数据只保存在当前设备/浏览器。GitHub Pages 只托管网站，不会自动同步个人记录到云端。
- 更换手机、浏览器或清除网站数据前，请在“备份与设置”中导出 JSON。
- 导入 JSON 会替换当前数据；建议先备份。
- 网站目前不含真实演出排期。请在“出演日程”里添加你要记录的日期和演员；这避免误用过期或不准确的排期。
- 这是个人粉丝自制记录工具，与制作方无关联。请只上传自己有权使用的图片和素材。
