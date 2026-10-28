# Multiplayer Piano MIDI Player Plus

脚本基于 Andrew Larson 的 Multiplayer Piano MIDI Player 修改。

## 新增功能

- 底部控制栏添加了 MIDI 进度条。
- 支持拖动/点击进度条调整播放位置。
- 显示已播放时间 / 总长度，例如 `0:01 / 3:50`。
- 支持手动输入播放倍速。
- 支持手动输入弹奏力度倍率。
- 支持全局半音升降调，超出钢琴音域的音符会自动跳过。
- 支持大调/小调之间的调式转换，并保留经过音的半音偏移。

## 安装

1. 安装 Tampermonkey、Violentmonkey 或 Greasemonkey。
2. 新建用户脚本。
3. 把 `Multiplayer Piano - MIDI Player Plus.user.js` 的内容粘贴进去并保存。
4. 打开支持的 Multiplayer Piano 站点，例如 `https://multiplayerpiano.org/`。
5. 页面底部会多出 `MIDI Player` 的控制按钮。
