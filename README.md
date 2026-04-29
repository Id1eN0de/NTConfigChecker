# NTConfigChecker

[![python](https://img.shields.io/badge/python-3.10+-blue?logo=python)](https://www.python.org/)
[![SQLModel](https://img.shields.io/badge/SQLModel-0.0.37-blue)](https://sqlmodel.tiangolo.com/)
[![PyQt6](https://img.shields.io/badge/PyQt6-6.4.2-blue)](https://www.riverbankcomputing.com/static/Docs/PyQt6/)
[![QFluentWidgets](https://img.shields.io/badge/QFluentWidgets-1.11.1-blue)](https://qfluentwidgets.com/zh/)

绿色环保，解压即撸


## 介绍
这是一个基于 Python 和 PyQt6构建的基于AI大模型的网络设备安全基线排查工具。旨在为网络管理员、网络安全员、网络安全督查人员提供了一套强大的工具，根据配置的基线检查内容，利用AI大模型能力自动分析网络设备配置信息，找出不合规项，并提出整改意见。

#### gitee地址：https://gitee.com/id1en0de/ntconfig-checker
#### github地址：https://github.com/Id1eN0de/NTConfigChecker

## 主要功能

- **配置检查**: 
  - 支持配置文件导入
  - 采用多线程机制（最大10线程）开展批量检测
  - 支持AI检测和脚本自动化检测模式切换（目前支持AI检测，脚本自动化检测还未整合）
  - 支持模型选择
  - 支持输出格式选择（默认为html)
- **基线库**: 
  - 检查基线库维护。
  - 通过维护检查内容（类似提示词），控制AI检查内容，从而更加精确地获得检查结果。
- **设置**: 
  - 检查结果保存路径设置
  - 调试模式开关
  - Syslog日志服务器设置
  - AI大模型设置


## 技术栈

- **后端**: Python 3.10+, SQLModel.
- **UI**: PyQt6, Jinja2 模板引擎, QFluentWidgets界面美化.
- **数据库**: sqlite

## 更新日志

### v1.2.1
* 增加主报告生成功能
* 修改部分bug

### v1.1.0
* 增加基线库导入导出功能
* 增加基线库模板，欢迎大家共同维护
* 修改部分bug

### v1.0.0

* 基础版本主要功能

## 界面展示

### 配置检查
<img width="827" height="598" alt="peizhi" src="https://github.com/user-attachments/assets/2a22845f-b775-4084-a173-72ae5f98f193" />


### 基线库
<img width="827" height="598" alt="jixian" src="https://github.com/user-attachments/assets/1888f265-7561-4f4e-9a34-55417d858cde" />



### 设置
<img width="827" height="598" alt="shezhi" src="https://github.com/user-attachments/assets/ebc02f6e-4a81-4cd7-8ec7-4550d14ac92c" />


### 日志
<img width="827" height="598" alt="rizhi" src="https://github.com/user-attachments/assets/219591ec-53af-40b7-b451-ebc9a39317db" />


### 主报告
<img width="827" height="2094" alt="baogao1" src="https://github.com/user-attachments/assets/d98964e9-b069-4ff6-b699-2da640ef047b" />

### 详细报告
<img width="827" height="2213" alt="baogao2" src="https://github.com/user-attachments/assets/f4f90da5-279d-411c-8697-585b41808df1" />



## 联系我们

欢迎提交建议和bug反馈。

邮箱：id1en0de@163.com

微信：Id1eN0de
<img width="528" height="680" alt="weixin" src="https://github.com/user-attachments/assets/a70d094f-3619-4d83-9644-ee4e60bb962b" />




肉身挂机  程序自驱
