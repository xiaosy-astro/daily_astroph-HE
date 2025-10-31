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


## Oct 24

### [Accretion with two-phase gas supply and its application in black hole X-ray binaries](https://arxiv.org/pdf/2510.19584)
### Summary
该论文研究黑洞X射线双星中同时包含冷热气体供应的吸积过程，分析盘与冕的相互作用，发现吸积几何结构和发射光谱强烈依赖于总气体供应率和冷热气体比例。
### Motivation
传统认为黑洞X射线双星的吸积由洛希瓣溢出或星风供应，分别形成几何薄盘或厚热吸积流。本文考虑更一般情况，即同时包含冷热气体供应，分别供给盘和冕。
### Method
采用半解析方法分析盘与冕之间的能量耦合和物质交换（冕凝结/盘蒸发过程）。
### Result
发现吸积几何结构和发射光谱取决于总气体供应率和冷热气体比例。在中等吸积率下，不同冷气体比例可产生多样的几何结构和光谱形状；高吸积率下内区总是盘主导；低吸积率下热流主导产生硬态光谱。通过比较MAXI观测数据，约束了吸积流粘滞参数为0.25-0.35。
### Conclusion
冷热气体混合供应的吸积模型能够解释中间态观测到的各种光谱，并预测了天鹅座X-1的硬度-强度相关性，为理解黑洞双星吸积过程提供了更全面的框架。


## Oct 30

### [Unveiling the soft X-ray source population towards the inner Galactic disk with XMM-Newton](https://arxiv.org/abs/2510.23814)
### Summary
使用XMM-Newton观测对eROSITA全天巡天(eRASS1)中探测到的微弱X射线源进行分类和表征，发现银盘区域主要被日冕源(74%)主导，提出硬度比阈值(HR > -0.2)来有效分离非日冕源，并估计约6%的银河脊X射线发射被分解为点源。
### Motivation
过去巡天灵敏度限制导致对微弱X射线源的理解不足，需要利用更深的XMM-Newton观测来分类和表征eRASS1探测到的银盘区域X射线源。
### Method
分析189个eRASS1源，结合X射线光谱拟合(0.2-10keV)和Gaia天体测量与测光数据，使用经验硬度比阈值(HR > -0.2)分离非日冕源，并通过叠加分类群体与银河脊X射线发射比较。
### Result
eRASS1银盘目录主要被日冕源(74%)主导，其中约8%为风驱动大质量星，18%为吸积致密天体；约6%的GRXE通量在0.5-2.0keV波段被分解为点源，软波段发射主要来自活跃星，硬波段通量主要来自X射线双星。
### Conclusion
eRASS1目录保留了不可忽视的致密天体群体，可以通过X射线颜色选择有效区分。


## Oct 31

### [BlazEr1: The eROSITA Blazar Catalog. Blazars and Blazar Candidates in the First eROSITA Survey](https://arxiv.org/abs/2510.25589)

### Summary
eROSITA首次全天X射线巡天（eRASS1）创建了包含5865个源的BlazEr1耀变体目录，其中2106个为确认耀变体，3668个源首次获得X射线数据，为耀变体研究提供了重要资源。

### Motivation
利用eROSITA首次X射线全天巡天的930000个源数据，进行详细的耀变体普查，填补X射线耀变体研究的空白。

### Method
从文献中收集耀变体和候选体列表，与eRASS1目录匹配，创建BlazEr1目录；对计数超过50的源获取X射线光谱特性，并收集从射电到伽马射线的多波段数据.

### Result
BlazEr1目录包含5865个源，其中2106个确认耀变体，3668个源首次获得X射线数据；整个样本的非耀变体污染率低于11%；提供了X射线光度、光子指数分布、多波段特性等耀变体群体特性。
### Conclusion
BlazEr1目录为耀变体研究提供了X射线探测的耀变体和候选体汇编，是未来利用eROSITA巡天研究X射线变异性和大样本耀变体能谱分布的重要起点。

### [Radiation-dominated polar emitting region of an accreting X-ray pulsar -- I. Polarization- and spectrum-dependent structure, and the emergent continuum](https://arxiv.org/abs/2510.25762)

### Summary
本文通过三维数值模拟研究了X射线脉冲星辐射主导的极区发射区域，考虑了多种物理过程对辐射转移和发射区域结构的影响。
### Motivation
研究X射线脉冲星极区发射区域的辐射转移过程，特别是考虑磁场散射、康普顿效应、偏振模式转换等多种物理机制对辐射谱形成的影响。
### Method
采用三维几何二维模型，使用自洽算法计算发射区域内的辐射转移和结构，考虑磁场依赖的散射截面、二阶体康普顿化、诱导康普顿散射、偏振模式转换、自由-自由过程、电子-质子碰撞产生的回旋辐射以及真实的吸积通道形状。
### Result
发现诱导康普顿效应在建立激波后区域电子温度中起重要作用；激波波内通过体加热机制获得比激波后区域更高的电子温度；在激波波内和上方通过体运动效应和热多普勒效应获得能量的光子负责形成偏振模式出射连续谱中的高能区域。
### Conclusion
该模型成功模拟了X射线脉冲星极区发射区域的复杂物理过程，揭示了诱导康普顿效应和体加热机制在温度分布和辐射谱形成中的关键作用。
