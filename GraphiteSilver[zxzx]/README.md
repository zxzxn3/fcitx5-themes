# GraphiteSilver[zxzx]

基于 macOS-dark（原作者 thep0y）的深色微透明 Fcitx5 主题。

## 配色与尺寸

- 背景：`#28292B`，94% 不透明度，无描边。
- 选中背景：`#9A9B9D`；选中文字：`#1C1D1F`。
- 普通文字：`#E0E3E7`；菜单同步使用深色配色。
- 单行选中框高 36px、圆角半径 18px；外框高 44px、半径 22px。
- 选中框上下及左侧内缩 4px，使用匹配外框的模糊遮罩。

尺寸按 `Noto Fangsong KSS Rotated 13` 在 96 DPI 下的行高校准。改变字体、字号或使用多行内容后需重新检查圆弧比例。

## 使用与恢复

目录：`~/.local/share/fcitx5/themes/GraphiteSilver[zxzx]`。在经典用户界面中选择同名主题。
字体与主题选择在 Fcitx5 用户配置中，不包含在本仓库。

重载：`fcitx5-remote -r`。

在本主题目录内恢复统一仓库的 v1.0.0 版本（会覆盖主题文件的未提交修改）：

```sh
git restore --source=v1.0.0 -- theme.conf panel.svg panel-mask.svg highlight.svg
fcitx5-remote -r
```

## 同系列配色

- `WeChatGreen[zxzx]`
- `DustyRose[zxzx]`
- `GraphiteSilver[zxzx]`
