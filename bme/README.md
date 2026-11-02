# 生物医学工程（BME）

> 返回：[论文精读笔记总索引](../README.md)

## 本模块关注什么

把工程方法用在医学上的那类研究：**怎么测、怎么动、怎么进到体内去**。

具体的兴趣范围（按笔记里真正出现过的问题归纳，不是学科定义）：

- **生物传感**：压力 / 力 / 形状的测量，尤其是塞进导管、导丝、光纤那么细的空间里的测量
- **医疗机器人**：磁导航、软体机器人、腔内机器人、手术器械
- **生物材料**：刺激响应材料（光、磁、温度、pH）、水凝胶、液晶弹性体
- **能量与信号的传输**：光在光纤里怎么走、怎么在不同位置"分别控制"不同部件

## 已收录（6 篇）

| 论文 | 方向 | 笔记 |
| --- | --- | --- |
| Photoacoustic Triaxial Force Sensing via Integrated Polymer Waveguides for Ultra-Compact Robotic Surgical Instruments（IEEE/ASME TMech 2025, DOI 10.1109/TMECH.2025.3628300） | 光声三轴力传感 / 微创手术器械 | [查看](papers/photoacoustic-triaxial-force-sensing/photoacoustic-triaxial-force-sensing.md) |
| Iontronic tip-sensing guidewires（Nature Biomedical Engineering 2025, DOI 10.1038/s41551-025-01548-9） | 离子电子压力传感 / FFR 导丝 | [查看](papers/iontronic-tip-sensing-guidewires/iontronic-tip-sensing-guidewires.md) |
| Magnetic catheter robot with dynamic force feedback for stiffness identification and abnormality detection（Fundamental Research 2026, DOI 10.1016/j.fmre.2026.03.014） | 磁导航 / 力反馈 / 刚度识别 | [查看](papers/magnetic-catheter-robot-force-feedback/magnetic-catheter-robot-force-feedback.md) |
| Deep learning–enabled versatile shape perception for soft robots via single-ended multimode fiber（Science Advances 2026, DOI 10.1126/sciadv.aef6263） | 多模光纤散斑 / 形状感知 / 软体机器人 | [查看](papers/single-ended-multimode-fiber-shape-perception/single-ended-multimode-fiber-shape-perception.md) |
| Nature-Inspired Magnetic Cilia for Detection and Early Intervention of Vascular Stenosis（Advanced Materials 2026, DOI 10.1002/adma.202520941） | 磁控人工纤毛 / 血流动力学 / 无线磁传感 / ROS 响应递送 | [查看](papers/magnetic-cilia-vascular-stenosis/magnetic-cilia-vascular-stenosis.md) |
| Light-Actuated Fiber-Climbing Inchworm Robot Toward Endoluminal Navigation（Advanced Functional Materials 2026, DOI 10.1002/adfm.75627） | 液晶弹性体 / 侧发光光纤 / 尺蠖机器人 / 腔内导航 | [查看](papers/light-actuated-fiber-climbing-inchworm-robot/light-actuated-fiber-climbing-inchworm-robot.md) |

## 新增一篇 BME 笔记

1. 建目录 `bme/papers/<论文slug>/`，笔记文件与目录同名：`<论文slug>.md`
2. 自绘图放 `images/`；**论文原图**放 `images/paper-figures/`，并在那里写一份 `NOTICE.md`（出处、DOI、版权归属）
3. 论文原图的别名统一用 `fig<N>-<内容-短横线>.png`
4. 在上面「已收录」表里加一行，并把标题里的篇数改掉
