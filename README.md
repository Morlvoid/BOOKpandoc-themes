# BOOKpandoc-themes：假装出书主题库



项目介绍：本项目为假装出书（BOOKpandoc）的css主题库，你可以上传你创作的css主题或下载他人创作的css主题使用。



### 1. 如何提交主题

- **方式一：Pull Request**
  贡献者将主题文件夹（含 `.css`、`preview.png`、`info.json`）放在 `themes/` 下，提交 PR。
  你审核后合并，PR 合并即表示主题上线。

- **方式二：仅提交设计稿**
  如果不会写 CSS代码，可以将设计稿（图片）放到 `drafts/` 下，并在 PR 中说明。
  其他开发者看到后，可以选择将其实现为完整主题并提交 PR（可以注明原设计作者）。

- **方式三：若不会使用Github，请提交邮箱**

  邮箱地址：morlvoid@qq.com 

### 2. PR 模板（.github/PULL_REQUEST_TEMPLATE.md）

```markdown
## 主题名称
[填写主题名称]

## 主题类型
- [ ] 完整主题（包含 .css 和预览图）
- [ ] 设计稿（仅图片，供参考）

## 主题描述
[简要描述主题风格]

## 版权声明
本人保证该主题不侵犯任何第三方知识产权，并同意以 [MIT 许可证] 开源。

## 预览图
（可粘贴图片链接）
```

## 3.info.json 示例

```json
{
  "name": "纸质小说风",
  "author": "你的名字",
  "version": "1.0",
  "description": "模拟纸质书籍的阅读体验，带书封、版权页",
  "tags": ["纸质", "小说", "怀旧"],
  "preview": "preview.png",
  "date": "2025-03-27"
}
```

## 4.目录结构

```bash
BOOKpandoc-themes/
├── README.md                 # 仓库说明、贡献指南
├── LICENSE                   # 与主项目一致的许可证
├── themes/                   # 主题存放目录
│   ├── theme-name-1/
│   │   ├── theme.css         # 主题样式文件
│   │   ├── preview.png       # 预览图（推荐 800x600）
│   │   └── info.json         # 主题元信息
│   ├── theme-name-2/
│   │   ├── theme.css
│   │   ├── preview.png
│   │   └── info.json
│   └── ...
├── drafts/                   # 未完成的设计稿存放区（可选）
│   ├── concept-name/
│   │   └── mockup.png        # 设计图，供开发者参考
│   └── ...
└── .github/
    └── PULL_REQUEST_TEMPLATE.md   # PR 模板
```

