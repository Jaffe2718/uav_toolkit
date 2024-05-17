# UAV Toolkit 项目说明

![Stars](https://img.shields.io/github/stars/Jaffe2718/uav_toolkit?style=flat-square)
![Forks](https://img.shields.io/github/forks/Jaffe2718/uav_toolkit?style=flat-square)
![Issues](https://img.shields.io/github/issues/Jaffe2718/uav_toolkit?style=flat-square)
![Licence](https://img.shields.io/github/license/Jaffe2718/uav_toolkit?style=flat-square)

## 项目简介
该项目是一个可以在ArcGIS Pro中运行的Python工具箱[<sup>[1]</sup>](#R1)。
该Python工具箱包含一个基于Segment Anything[<sup>[2]</sup>](#R2)的图像分割工具，可以用于无人机图像的分割。

## 用户文档

- [安装和配置](docs/user/setup.md)
- [使用说明](docs/user/usage.md)
- [参数说明和调参指南](docs/user/params.md)

## 开发者文档

- [需求分析报告](docs/dev/requirements.md)
- [设计文档](docs/dev/design.md)
- [UML](docs/dev/uml.md)


## 引用和参考文献

<a name="R1" href="https://pro.arcgis.com/en/pro-app/latest/arcpy/geoprocessing_and_python/a-quick-tour-of-python-toolboxes.htm">[1]</a> What is a Python toolbox?—ArcGIS Pro | Documentation. (n.d.). Pro.arcgis.com. Retrieved May 16, 2024

<a name="R2" href="https://arxiv.org/abs/2304.02643">[2]</a> Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson, L., Xiao, T., Whitehead, S., Berg, A. C., Lo, W.-Y., Dollár, P., & Girshick, R. (2023). Segment Anything. ArXiv:2304.02643.