# ios-Image-Study
## 学习IOS的图像处理
### 本节翻译了Core Image Programming Guide
<a href="https://developer.apple.com/library/archive/documentation/GraphicsImaging/Conceptual/CoreImaging/ci_intro/ci_intro.html#//apple_ref/doc/uid/TP30001185">原文地址</a>

> Core Image是一种图像处理和分析技术，旨在为静态和视频图像提供实时处理。 它使用GPU或CPU渲染路径，对Core Graphics，Core Video和Image I / O框架中的图像数据类型进行操作。 Core Image通过提供易于使用的应用程序编程接口（API）隐藏了低级图形处理的细节。 您不需要了解OpenGL，OpenGL ES或Metal的细节来充分利用GPU的强大功能，也无需了解Grand Central Dispatch（GCD）以获得多核处理的优势。 Core Image为您处理细节。
>
> Core Image一瞥
Core Image框架提供：

访问内置图像处理过滤器
特征检测功能
支持自动图像增强
将多个过滤器链接在一起以创建自定义效果的功能
支持创建在GPU上运行的自定义过滤器
基于反馈的图像处理功能
在macOS上，Core Image还提供了一种打包自定义过滤器以供其他应用程序使用的方法。
### Core Image高效且易于用于处理和分析图像
