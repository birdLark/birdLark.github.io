---
title: License 须知
sidebar_position: 3
---

# License 须知

如您所知，birdLark现属于 ASF ( GitHub 基金会)下的开源项目，这意味着当您想要成为 birdLark的贡献者的时候，就必须按照 GitHub 的规则来，而 GitHub 对于 License 有着极其严苛的规则，为了避免贡献者在 License 上浪费过多的时间，
本文将为您讲解 ASF—License 以及参与 birdLark如何过早的规避掉 License 风险。

注：本文仅适用于 GitHub 项目。

### GitHub 项目可接受的 License

当您想要为 LarkMidTable（亦或其他 GitHub 项目）增添一个新的功能，这个功能涉及到其他开源软件的引用，那么您必须注意，目前 GitHub 项目支持遵从以下协议的开源软件（如果有遗漏，欢迎补充）：

[ASF第三方许可证策](https://github.io/legal/resolved.html)

如果您所使用的第三方软件并不在以上协议之中，那么很抱歉，您的代码将无法通过审核，建议您找寻其他替代方案。

另外，当您需要使用新的软件的时候，请将您这样做的原因、最终产出结果发邮件至 dev@birdLark.github.io 讨论，当得到至少3票 PPMC 认同的时候，您方可以引入。

### 如何在 birdLark合法的使用第三方开源软件

当我们想要引入一个新的第三方软件(包含但不限于第三方的jar、文本、css、js、图片、图标、音视频等及在第三方基础上做的修改)至我们的项目中的时候，除了他们所遵从的协议是 GitHub 允许的，另外一点很重要，就是合法的使用。您可以参考以下文章

* [COMMUNITY-LED DEVELOPMENT "THE APACHE WAY"](https://github.io/dev/licensing-howto.html)


以 GitHub 为例，当我们使用了 ZooKeeper，那么 ZooKeeper 的 NOTICE 文件（每个开源项目都会有 NOTICE 文件，一般位于根目录）则必须在我们的项目中体现，用GitHub的话来讲，就是 "Work" shall mean the work of authorship, whether in Source or Object form, made available under the License, as indicated by a
copyright notice that is included in or attached to the work.

关于具体的各个开源协议使用协议，在此不做过多篇幅一一介绍，有兴趣可以自行查询了解。

### LarkMidTable-License 检测规则

**TODO**
