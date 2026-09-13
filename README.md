# 轻单 · 待办清单

无需安装依赖的中文个人待办应用。

## 如何运行

1. 安装 Node.js 18 或更新版本。
2. 在项目根目录打开终端。
3. 运行 `npm start` 启动项目。

也可以直接用浏览器打开 `dist/index.html`。

支持新增、编辑、完成、删除及撤销删除；截止日期、优先级、备注；今天、重要、已完成视图；搜索和排序；完成进度；手机和桌面布局。Ctrl/Cmd + K 聚焦搜索。

数据通过 localStorage 保存在当前浏览器和来源下，不含账号或云端同步。更换浏览器、地址或清除站点数据后不会保留原清单。初始清单为空，不混入演示任务。

文件：dist/index.html 页面结构；dist/styles.css 样式；dist/app.js 任务状态和交互；server.cjs 本地静态服务。`npm run check` 检查 JavaScript 语法。
