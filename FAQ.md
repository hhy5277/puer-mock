# puer-mock FAQ

关于 puer-mock 使用过程中的常见问题答疑.

感谢 [@no13bus](https://github.com/no13bus) 在 v2ex 中找到我, 一起讨论了一些实际使用过程中的想法.

## puer-mock 的主要用途?

* mock server
* 生成假数据, 摆脱手工写 mock 数据的尴尬处境
* 在线接口文档
* 提高前后端的开发效率和沟通效率

## 接口由前端定还是后端定?

个人觉得接口由哪一方来定义是其次的, 反正前后端的接口是要双方协商的, 还会时不时地需要调整.

具体由哪一方来主导, 还得看公司的项目情况. 有后端主导的, 也有前端主导的. 但无论如何, 双方都需要参与进来, 接口绝对不是个单方职责, 需要多方共同推进.

PS: 我们这边由前端先定接口, 当然后端也会参与, 毕竟接口是要后端来实现的.

## 下一个阶段要做的是接口管理平台吗?

可以说 puer-mock 是以一个工具为切入点来推动前后端的工作效率. 能否成为一个平台还得看项目的发展情况吧, 毕竟工具使用时可以很灵活, 而平台则需要更加的全面, 更需要整体的推动, 因此不一定适合所有的公司和团队.

例如 [RAP](https://github.com/thx/RAP), 功能很强大, 属于平台级的, 相比 puer-mock 只需要在你的项目中添加一个接口配置文件就显得轻量多了, 对开发人员来说简单实用门槛很低, 才能促使他们将 puer-mock 运用到实际的项目中, 改进前后端的工作流程.