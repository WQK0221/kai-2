# 简易计算器智能体

一个基于 HTML/CSS/JavaScript 构建的简易计算器应用。

## 功能特性

- ✅ **基础运算**：支持加法、减法、乘法、除法
- ✅ **小数点支持**：支持小数运算
- ✅ **百分比计算**：一键计算百分比
- ✅ **正负号切换**：快速切换正负值
- ✅ **历史记录**：显示当前运算表达式
- ✅ **错误处理**：除以零错误提示

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)

## 快速开始

### 在线访问

部署在 GitHub Pages：
https://wqk0221.github.io/kai-2/

### 本地运行

```bash
# 克隆仓库
git clone https://github.com/WQK0221/kai-2.git

# 进入目录
cd kai-2

# 使用 Python 启动本地服务器
python -m http.server 8000

# 访问 http://localhost:8000
```

## 项目结构

```
kai-2/
├── index.html    # 主页面（包含 HTML、CSS、JavaScript）
└── README.md     # 项目说明文档
```

## 按钮布局

| 功能 | 说明 |
|------|------|
| C | 清除显示 |
| ± | 切换正负号 |
| % | 百分比计算 |
| ÷ | 除法 |
| × | 乘法 |
| − | 减法 |
| + | 加法 |
| = | 等于 |

## 开发说明

计算器使用纯前端技术实现，无需后端支持。所有计算逻辑均在浏览器端执行。

## License

MIT License