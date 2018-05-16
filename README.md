# About this repository
该仓库主要收录不同主题的技术文档，同时这些文档将作为个人Blog和知乎专栏的蓝本。
目前收录的技术文档主题包括：
* PyTorch
* SUMO

# About PyTorch
PyTorch是开源的Python科学计算及深度学习库，主要用于创建各种深度学习应用。PyTorch由Facebook AI研究小组开发，同时，Uber的Pyro概率编程组件也包含在内。
PyTorch最大的特点是动态计算图机制，这使得模型构建更加灵活，特别是在创建序列模型时极具优势。
目前，Caffe2源码已并入PyTorch，成为不逊于TensorFlow的强大深度学习研究和实现工具。

# About SUMO
SUMO是由德国宇航中心（DLR）交通系统研究所开发的免费、开源的交通仿真套件，可以从http://www.dlr.de/ts/en/desktopdefault.aspx/tabid-9883/16931_read-41000/ 下载SUMO的安装包、说明文档和源代码。SUMO支持Windows、Linux操作系统。

## SUMO功能介绍
* 微观仿真。可仿真的对象包括车辆、行人、公共交通等。支持多种交通模型。仿真路网的大小不受限制。
* 在线交互。通过TraCI可以实时与仿真场景进行双向交互。
* 可导入OpenStreetMap、VISUM、VISSIM路网。
* Veins套件包含了SUMO（交通仿真器）和OMNET++（网络仿真器），可以实现车联网环境下的交通仿真。

## SUMO与其他交通仿真软件的对比
SUMO与VISSIM等微观交通仿真软件相比，具有以下优点：
* 开源、免费；
* 灵活，可自定义几乎所有仿真环境要素，包括路网、交通流模型、仿真输出等；
* 并行的多场景仿真。

但也有以下尚待完善之处：
* GUI工具功能相对欠缺，大部分功能需要通过程序脚本实现；
* 仍处于开发完善阶段，部分功能尚不稳定。
