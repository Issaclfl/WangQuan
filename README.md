# 鎏金时刻 · 动态立绘（NFC 第三页）

暖金黄昏、光束斜落、金色尘埃流动。

- 与 `reze-live-portrait`（雨夜蕾塞）、`valley-live-portrait`（晴野）并列的第三个 NFC 页面
- 底图为 1745×859，右上角视频水印已用 cv2 inpaint 抹除
- 音乐：《幻昼》降调版，换歌直接覆盖 `assets/bgm.mp3`
- 竖屏整体旋转 90° 全景铺满（同前两页），横屏 cover 铺满
- 微微动态：发丝飘动（hair.png 叠层 ±1.6° + 底图已抹发防重影）+ 呼吸缩放 + 视差
- 流光尘埃 220 颗；按钮为「暂停」和「流光」（尘埃开关）
- **视频页**：`video.html` + `video.mp4`（9.3 秒循环短片，静音自动播放，点击开声音）
  - 立绘页：`https://issaclfl.github.io/WangQuan/`
  - 视频页（NFC 推荐写这个）：`https://issaclfl.github.io/WangQuan/video.html`

## 本地预览

```powershell
cd C:\Users\Lawson\Desktop\NFC\golden-live-portrait
python -m http.server 8091
```

## 发布

推到新仓库后开 GitHub Pages，NFC 写入：

```
https://issaclfl.github.io/<仓库名>/
```
