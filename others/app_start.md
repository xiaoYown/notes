#### 首要准备:

- 项目二级目录

```
目的: 方便过网关二级目录项目部署

统一管理:
所有使用二级目录的请求, 均来源于同一个文件. 统一修改文件, 配置位置: 可导入最终打包的配置文件.

分散管理: 所有请求需使用二级目录封装
- 异步请求
- 带请求标签
- 文件上传依赖
- 封装全局 url 转换函数
- open|location.replace|location.href 跳转封装
```

- 接口代理
- UI 库选择
- axios 封装
- 接口统一管理, 接口统一封装
- 项目主题色
- 样式预编译语言: less/sass/stylus
- 生成前端最终文件 nginx 配置
- 项目公共依赖分离
- 开发规范

- 体验规范

```
- 点击请求, 需有按钮 loading 状态
- 加载请求, 加载部分使用 skeleton|spin 表示加载状态
- UI 销毁前, pending 状态请求需主动取消
- 请求失败状态处理
- 尽量避免弹窗展示处理结果(体验不佳)
- 接口请求测试页面(保证所有接口返回 200, 处理结果不为协议报错)
```

#### 次要准备:

- 国际化
- 首屏骨架屏
- 若是后台管理页, 需固定布局
- mock