## 网站响应式设计

- src： 项目开发源码目录
- dist： 项目构建生产环境目录
- gulpfile.js：自动化构建配置文件

> 主要使用 **css3 媒体查询** 完成 pc & mobile 端适配：

```css
/**
 * 响应式样式：
 * 响应式的级别很高，rem 基于浏览器默认的 font-size，即 1rem = 16px
 * 响应式单位推荐使用 em，和 rem效果一样，但兼容性更好
 */
@media only screen and (max-width: 50em) {
  ...
}

@media only screen and (min-width: 30em) and (max-width: 50em) {
  ...
}

@media only screen and (max-width: 30em) {
  ...
}

```