# PyCharm + CodeBuddy 接入 Hy3：IDE 内 AI 辅助 Python 学习指南

## 适用场景
面向在 PyCharm 中编写 Python 的高中生，通过 CodeBuddy 插件调用腾讯混元 Hy3 模型，
在 IDE 内直接获得代码解释、优化建议、Bug 修复等辅助，形成"写代码 → 问 Hy3 → 学知识点"的闭环。

## 前置条件
- PyCharm（Professional 或 Community 均可）
- CodeBuddy 插件（JetBrains 市场搜索 CodeBuddy 安装，或官网下载 .zip 手动安装）
- 有 CodeBuddy 会员/激活权限（Hy3 限免至 2026年8月31日，文本调用不消耗额外费用）

## 操作步骤

### 1. 安装 CodeBuddy 插件
PyCharm → Settings → Plugins → Marketplace → 搜 "CodeBuddy" → Install → Restart IDE。
（注：若 Marketplace 搜不到，可前往 CodeBuddy 官网下载 JetBrains 插件 .zip 文件，
通过 Settings → Plugins → 齿轮图标 → Install Plugin from Disk 手动安装。）

### 2. 在 PyCharm 中切换到 Hy3 模型
方式A：点击底部状态栏的 CodeBuddy 图标 → 选择 "Change Completions Model" → 选 Hy3
方式B：Cmd+Shift+P 打开命令面板 → 搜 "CodeBuddy: Change Completions Model" → 选 Hy3
（模型选择器也可在对话框左下角直接切换）

### 3. 提交代码优化需求
在 CodeBuddy 对话窗口中，粘贴 Python 代码并发送需求，例如：
"我是高中生，正在学 Python 字典，请帮我优化这段词频统计代码，
要求忽略大小写、过滤标点，并解释你改了哪些地方。"

### 4. 查看 Hy3 的优化结果
Hy3 会返回优化后的代码及逐行解释（如 lower() 方法、正则表达式过滤、
collections.Counter 等高阶用法）。

## 学习心得
通过 PyCharm + CodeBuddy + Hy3 的组合，我发现 IDE 内 AI 辅助编程的优势在于：
有时写的文件比较长，而且有些基础知识会遗忘，不知道该怎么办。如果一条条复制了，再去问别的AI很麻烦，可以直接在pycharm中安装，
切换hy3模型，让他直接在排查中就可以对我的代码进行更改，也会解释缘由，省去了很多步骤，节省了时间
  - WorkBuddy 更适合"任务型"场景（如让 AI 完成一个完整的文本处理任务）
  - PyCharm + CodeBuddy + Hy3 更适合"开发型"场景（如在写代码的过程中实时获得辅助）
- **限免福利**：Hy3 在 CodeBuddy 限免至 2026年8月31日，文本调用零成本，
  这对预算有限的学生党非常友好

## 注意事项
- Hy3 限免至 2026年8月31日，期间文本调用不消耗额外积分
- Hy3 是纯文本模型，不具备图像、视频等多模态能力
- 当晚 23:00 至次日 8:00 资源相对宽裕，建议错峰使用以获得更好的响应速度
- 当日资源繁忙时会进入排队，页面会提示重置时间后恢复<img width="803" height="452" alt="截屏2026-08-12 19 14 01" src="https://github.com/user-attachments/assets/635a2e04-1f41-497b-a54b-ae42626cd115" />
<img width="754" height="406" alt="截屏2026-08-12 19 15 55" src="https://github.com/user-attachments/assets/2d9df0e2-7574-4d28-8e1a-e6441ca7dd71" />
<img width="778" height="391" alt="截屏2026-08-12 19 15 23" src="https://github.com/user-attachments/assets/8647da0c-c60b-41ec-b228-c52721ecb299" />
<img width="772" height="414" alt="截屏2026-08-12 19 14 37" src="https://github.com/user-attachments/assets/4d089649-b210-4325-a91c-0a9b2f2493ba" />

<img width="783" height="422" alt="截屏2026-08-12 19 12 38" src="https://github.com/user-attachments/assets/c7377290-5155-4833-8612-1d79c8d05096" />
