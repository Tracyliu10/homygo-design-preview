# Homygo 服务页面设计预览

包含已确认的五张新服务图片；表单只演示，不发送或保存。

## 发布方法

1. 在 GitHub 创建 public 仓库，例如 homygo-design-preview。
2. 解压下载包，将包内文件上传到仓库最外层，不要只上传 ZIP，也不要嵌套在子目录中。index.html 必须在最外层。
3. 仓库 Settings → Pages → Source 选择 Deploy from a branch。
4. Branch 选择 main，目录选择 / (root)，点击 Save。
5. 等待发布完成，在同一页面查看正式网页链接。通常形式为 https://你的用户名.github.io/homygo-design-preview/。
6. 将 GitHub Pages 网页链接发送给设计公司，仓库链接只用于文件和 Issues 反馈。

## 文件

- index.html：五个可切换服务页面，图片和样式均内嵌。
- design-brief.html：可在浏览器阅读的中文设计说明。
- design-brief.md：可编辑的原始设计说明。
- .nojekyll：让 GitHub Pages 直接托管静态文件。
- robots.txt：请求搜索引擎不抓取；不提供访问限制。

注意：public 仓库及预览网页公开可访问。照片为 AI 生成示意图，不能作为团队实拍说明。原测试站不受影响。
