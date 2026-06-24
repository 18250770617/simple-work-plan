# 📋 日程任务工具(vibe coding)

一个极简的 Vue 3 日程任务工具，用于记录与提醒,个人学习git与vibe coding项目。

## 功能

- ✅ 添加任务（标题 + 可选时间）
- ✅ 编辑 / 删除任务
- ✅ 勾选完成 / 恢复
- ✅ 筛选：全部 / 今天 / 指定日期 / 无日期
- ✅ 完成记录存档（可恢复或清空）
- ✅ 数据自动保存到浏览器本地

## 使用

直接用浏览器打开 `index.html` 即可（推荐用 VS Code Live Server 或 Python http.server）。

```bash
# 方式一：VS Code 右键 → Open with Live Server
# 方式二：Python
python -m http.server 3000
# 方式三：直接双击 index.html（部分浏览器可能需要 http 服务）
```

## 技术栈

- Vue 3（Options API，CDN 引入）
- 纯 CSS 样式，移动端适配
- localStorage 数据持久化
