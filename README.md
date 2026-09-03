# ScoreCutter

Browser-based manual cropping and cross-page composition for screen-ready sheet music images.

在页面上拖动上下边界，导出横向全宽的 PNG；支持 `4:3` / `16:9`、中心偏置（将图像块上下移动）、Enter 快捷导出，以及上一页和下一页的手动拼图。

## 使用

准备好曲谱页面的 PNG/JPG 图片后，打开 `manual_score_crop_ui.html`，选择图片文件夹：

1. 拖动两条蓝线选择上下边界。
2. 选择输出比例并调整中心偏置。
3. 点击“导出当前 PNG（Enter）”，或直接按 `Enter`。

点击“进入拼图”可把上一页和下一页的选区合并到同一张 PNG，并分别调整两块的偏置。

适用于扫描平整，谱表间距大的乐谱。
