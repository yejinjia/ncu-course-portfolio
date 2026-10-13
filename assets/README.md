# assets —— 静态资源目录

这里存放**图片、流程图、演示 GIF、数据集说明**等不参与代码运行的文件，
方便主 `README.md` 和各周报告直接引用。

## 使用方式

1. 把文件拷进本目录，例如 `assets/ncu-logo.png`；
2. 在任意 Markdown 里用相对路径引用：

```markdown
<img src="assets/ncu-logo.png" alt="南昌大学校徽" width="120" />
```

或

```markdown
![流程图](assets/flow-week03.png)
```

## 建议

- 图片尽量压缩后再放进来（单张控制在 300 KB 以内），避免仓库变得臃肿；
- 文件名用小写英文 + 连字符，例如 `ncu-logo.png`、`week03-result.png`，避免中文和空格；
- 若想显示**南昌大学校徽**，可把它命名为 `ncu-logo.png` 放在本目录，再在主 `README.md` 顶部取消相关注释即可。
