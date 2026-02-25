# vibecoding-toolbox

一个用于存放和管理通过 Vibe Coding 生成的各种实用 Web 工具的集合项目。

## 项目介绍

vibecoding-toolbox 是一个工具集合项目，用于存放通过 AI 辅助开发（Vibe Coding）创建的各种实用 Web 应用。每个工具都是独立的 HTML 文件，可以直接在浏览器中运行，无需复杂的构建过程。

## 当前工具

### 1. 🧠 敏感指数测试 (sensitive-quiz.html)
- **功能**: 用于高度敏感群体的心理测试
- **特点**: 
  - 包含 48 道专业题目
  - 科学的评分系统
  - 详细的结果解释
- **评分范围**: 52-140 分

### 2. ✋ 手势控制应用 (gesture-control.html)
- **功能**: 通过摄像头识别手势与页面互动
- **特点**:
  - 支持 5 种手势识别
  - 实时摄像头预览
  - 直观的交互反馈
- **支持的手势**: 张开手掌、点赞、差评、剪刀手、握拳

## 使用方法

1. 克隆或下载本项目
2. 使用浏览器打开 `index.html` 文件
3. 从主页选择你想使用的工具
4. 或者直接在浏览器中打开对应的 HTML 文件

## 项目结构

```
vibecoding-toolbox/
├── index.html              # 主页 - 工具导航入口
├── sensitive-quiz.html    # 敏感指数测试
├── gesture-control.html   # 手势控制应用
└── README.md              # 项目说明文档
```

## 技术栈

- **HTML5**: 页面结构
- **CSS3**: 样式和动画
- **JavaScript**: 交互逻辑
- **MediaPipe**: 手势识别（手势控制应用）
- **localStorage**: 本地数据存储

## 开发说明

本项目采用 Vibe Coding 方式开发，即通过与 AI 对话协作生成代码。每个工具都是独立的，可以单独使用或扩展。

### 添加新工具

1. 创建新的 HTML 文件
2. 在 `index.html` 中添加工具卡片
3. 更新统计信息（如需要）

## 许可证

MIT License

## 贡献

欢迎通过 Vibe Coding 方式贡献新工具！
