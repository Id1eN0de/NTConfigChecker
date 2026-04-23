# NTConfigChecker
绿色环保，解压即撸

## 介绍
这是一个基于 Python 和 PyQt6构建的基于AI大模型的网络设备安全基线排查工具。旨在为网络管理员、网络安全员、网络安全督查人员提供了一套强大的工具，根据配置的基线检查内容，利用AI大模型能力自动分析网络设备配置信息，找出不合规项，并提出整改意见。

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

#### v1.0.0

* 基础版本主要功能

## 界面展示

### 配置检查
<img width="827" height="598" alt="peizhi" src="https://github.com/user-attachments/assets/d82901b2-e1c5-45e5-8164-ce35465bfcab" />

### 基线库
<img width="827" height="598" alt="jixian" src="https://github.com/user-attachments/assets/37783a65-953d-4451-953b-3083b1ef48bd" />

### 设置
<img width="827" height="598" alt="shezhi" src="https://github.com/user-attachments/assets/debc42dc-76ba-422e-a823-942d7653e32c" />

### 日志
<img width="827" height="598" alt="rizhi" src="https://github.com/user-attachments/assets/059202b2-9d4d-45e2-b74f-ab2313435547" />


## 联系我们

欢迎提交建议和bug反馈。

邮箱：id1en0de@163.com

微信：Id1eN0de
<img width="827" height="598" alt="weixin" src="https://github.com/user-attachments/assets/fc2a5a56-145b-48e7-b72c-66ac96d1637d" />



肉身挂机  程序自驱
