# claude-spark-morph

复刻 Claude 生成 / 思考状态下的 12 射线橙色星芒（Starburst / Spark）补间动画。

纯原生 SVG + JavaScript，无任何三方库依赖。

## 特性

- **测绘插值**：包含 8 组关键帧，12 根射线在角度与长度上平滑补间，呈现短射线顺时针环形游走效果。
- **轻量原生**：核心绘制逻辑仅约 40 行原生 JS，由 `requestAnimationFrame` 驱动（周期 1.6 秒）。
- **无障碍兼容**：自动响应系统的 `prefers-reduced-motion` 设置，开启减弱动画时自动停留在首帧。

## 使用方式

直接用浏览器打开 `index.html` 即可运行查看。

核心数据与动画代码位于文件底部的 `<script>` 标签内，可直接提取移植到 React / Vue 或任意 Web 页面中作为 Loading / Thinking 指示器。

## License

[MIT](LICENSE)
