# SvenRogue 个人项目实验室主页更新说明

目标站点：SvenRogue — 个人项目实验室（原 Sites 项目，project_id: appgprj_6abbc9ac6e4c819188d0aa983c41e0d3）
主展示域名：https://svenrogue.top/#projects
对应已发布地址：https://svenrogue-lab.svenrogue.chatgpt.site

## 修改目标
仅在首页的「01 / SELECTED WORK」/「一些想法，已经上线。」区域的末尾，接在第 05 项「小喵掌机天气应用」之后新增第 06 项，保留首页的导航、Hero、其他五个项目、关于区和 Footer 不变。

新增项目：
- 编号：06 — SMART HOME / DOCUMENTATION
- 标题：SASWELL T19 中文说明书
- 类型：PDF / GitHub
- 文案：将 SASWELL T19 无线温控器英文说明书整理为完整中文版，涵盖 App 配网、RF 无线对码、定时编程及 STON 壁挂炉联动排障。非官方中文译本。
- 标签：SASWELL · STON · 智能家居
- 主 CTA「查看完整中文版 PDF」：
  https://github.com/SvenRogue/saswell/blob/main/SASWELL_T19WHB-7-RF-APP_%E5%AE%8C%E6%95%B4%E4%B8%AD%E6%96%87%E7%89%88.pdf
- 次 CTA「GitHub 仓库」：https://github.com/SvenRogue/saswell
- 可选「中文在线阅读」：
  https://github.com/SvenRogue/saswell/blob/main/SASWELL_T19WHB-7-RF-APP_%E5%AE%8C%E6%95%B4%E4%B8%AD%E6%96%87%E8%AF%B4%E6%98%8E%E4%B9%A6.md

## 界面和测试要求
1. 使用当前主页相同卡片结构、字体、配色、间距、悬浮状态和移动端断点。
2. 首页项目数「5 个公开项目」更新为「6 个公开项目」，卡片编号与视觉节奏保持一致。
3. 「作品」导航锚点及「探索我的项目」跳转仍指向 #projects。
4. 外链新标签打开，使用 rel="noopener noreferrer"。
5. 桌面端和移动端都确认卡片文字无溢出、按钮可操作。
6. 发布到**已有的 Sites 项目**，不新建替代站点、不改变自定义域名或访问控制。
7. 实际部署成功后访问两个站点链接，确认第 06 项可见，并验证 PDF 和 GitHub 链接。

现成卡片代码：[`homepage-card.html`](homepage-card.html)。其中的 class 是示意性名称，实际应融入当前 Sites 源码里的卡片组件或原有样式，**不要把独立 HTML 片段不加适配直接覆盖站点**。

状态：该更新说明与代码已放到 GitHub；原站点尚未重新发布。
