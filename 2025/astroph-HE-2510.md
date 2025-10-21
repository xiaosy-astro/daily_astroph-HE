## Oct 21

### [Gradus.jl: spacetime-agnostic general relativistic ray-tracing for X-ray spectral modelling](https://arxiv.org/abs/2510.15049)

### Summary
Gradus.jl是一个用Julia编写的开源广义相对论光线追踪工具包，用于任意时空中的光谱建模，利用自动微分计算Christoffel符号和传播导数，支持计算Cunningham传递函数和含时间信息的传递函数形式，用于研究吸积盘反射模型。

#### Motivation

开发一个通用的广义相对论光线追踪工具包，用于光谱建模，特别是在任意时空中进行精确的光线追踪和导数传播，以支持高效的光谱模型计算和反射研究。

#### Method

使用Julia编程语言，利用前向模式自动微分计算Christoffel符号和传播导数，详细描述了相关数值方法，并通过测试和其他代码的比较验证模型。

#### Result

成功实现了不同iability用于最优计算Cunningham传递函数，描述了处理非零垂直高度吸积盘的方法，包括自遮挡处理，扩展了包含时间信息的传递函数形式，计算了高分辨率回波滞后光谱。

#### Conclusion
Gradus.jl提供了一个强大的工具，用于广义相对论光线追踪和光谱建模，特别是在处理吸积盘反射模型和计算时间相关效应方面表现出色。
