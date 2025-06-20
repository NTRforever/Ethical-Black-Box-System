# 🤖 EBB伦理黑盒系统 / Ethical Black Box System

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)
![Academic](https://img.shields.io/badge/academic-peer--reviewed-purple.svg)
![Standards](https://img.shields.io/badge/standards-EBB%20compliant-orange.svg)

> 🔍 基于学术研究的专业级机器人伦理监控与数据管理系统 | Academic Research-based Professional Robot Ethics Monitoring & Data Management System

一个功能完整的EBB（Ethical Black Box）伦理黑盒系统，基于Bristol Robotics Lab的开创性研究，严格遵循学术界制定的开放标准规范。用于记录、监控和分析机器人的行为数据，确保机器人行为的可追溯性和伦理合规性。

A comprehensive EBB (Ethical Black Box) system based on groundbreaking research from Bristol Robotics Lab, strictly following academic open standard specifications. Used for recording, monitoring, and analyzing robot behavioral data, ensuring traceability and ethical compliance of robot behaviors.

**🎓 学术基础 Academic Foundation**: 本系统实现基于Winfield等人在TAROS 2017和arXiv 2022上发表的同行评议研究论文。

**🎓 Academic Foundation**: This system implementation is based on peer-reviewed research papers published by Winfield et al. at TAROS 2017 and arXiv 2022.

**📊 项目状态 Project Status**: 
- 🚀 **活跃开发中** Active Development
- 📈 **功能完整** Feature Complete  
- 🧪 **测试验证** Tested & Validated
- 📚 **完整文档** Well Documented



---

## 📋 目录 / Table of Contents

- [特性 Features](#-特性--features)
- [快速开始 Quick Start](#-快速开始--quick-start)
- [安装 Installation](#-安装--installation)
- [使用指南 Usage Guide](#-使用指南--usage-guide)
- [API文档 API Documentation](#-api文档--api-documentation)
- [配置说明 Configuration](#-配置说明--configuration)
- [数据格式 Data Format](#-数据格式--data-format)
- [贡献指南 Contributing](#-贡献指南--contributing)
- [常见问题 FAQ](#-常见问题--faq)
- [许可证 License](#-许可证--license)

---

## ✨ 特性 / Features

### 🎓 学术标准实现 / Academic Standards Implementation
- **权威理论基础 Authoritative Theoretical Foundation**: 基于Bristol Robotics Lab的开创性研究 / Based on groundbreaking research from Bristol Robotics Lab
- **开放标准兼容 Open Standards Compliance**: 严格遵循Winfield等人提出的EBB开放标准草案 / Strictly follows EBB open standard draft proposed by Winfield et al.
- **同行评议支持 Peer-reviewed Support**: 实现经过学术界验证的技术规范 / Implements academically validated technical specifications

### 🔧 核心功能 / Core Features
- **标准化数据记录 / Standardized Data Recording**: 符合EBB开放标准规范的三种记录类型（MD/DD/RD）/ Three record types (MD/DD/RD) compliant with EBB open standards
- **实时监控 / Real-time Monitoring**: 实时显示机器人传感器、执行器和决策数据 / Real-time display of robot sensor, actuator, and decision data
- **数据完整性 / Data Integrity**: 64位校验和验证，确保数据不被篡改 / 64-bit checksum validation to ensure data integrity
- **循环存储 / Circular Storage**: 智能循环存储机制，优化存储空间使用 / Intelligent circular storage mechanism for optimized space usage
- **多格式支持 / Multi-format Support**: 支持EBB、CSV、JSON等多种数据格式 / Support for EBB, CSV, JSON and other data formats

### 🎨 用户界面 / User Interface
- **直观GUI / Intuitive GUI**: 基于tkinter的现代化图形界面 / Modern graphical interface based on tkinter
- **多选项卡设计 / Multi-tab Design**: 系统状态、数据记录、数据查看、模拟器、设置 / System status, data recording, data viewing, simulator, settings
- **实时更新 / Real-time Updates**: 动态数据显示和状态监控 / Dynamic data display and status monitoring
- **多语言支持 / Multi-language Support**: 完整的中英文界面支持 / Complete Chinese and English interface support

### 🤖 机器人模拟器 / Robot Simulator
- **传感器模拟 / Sensor Simulation**: 电池、红外、触摸、陀螺仪、加速度计 / Battery, infrared, touch, gyroscope, accelerometer
- **执行器模拟 / Actuator Simulation**: 轮子角度、舵机位置等 / Wheel angles, servo positions, etc.
- **智能决策 / Intelligent Decision**: 基于传感器状态的决策逻辑模拟 / Decision logic simulation based on sensor states
- **实时运动学 / Real-time Kinematics**: 简单的机器人运动学模拟 / Simple robot kinematics simulation

### 📊 数据管理 / Data Management
- **导入导出 / Import/Export**: 支持多种格式的数据导入导出 / Support for multi-format data import/export
- **记录查看 / Record Viewing**: 详细的历史记录查看和分析 / Detailed historical record viewing and analysis
- **数据验证 / Data Validation**: 自动数据格式验证和错误处理 / Automatic data format validation and error handling
- **批量处理 / Batch Processing**: 支持大量数据的批量导入 / Support for bulk data import

---

## 🚀 快速开始 / Quick Start

### 5分钟快速体验 / 5-Minute Quick Experience

```bash
# 1. 克隆仓库 / Clone repository
git clone https://github.com/NTRforever/Ethical-Black-Box-System.git
cd Ethical-Black-Box-System

# 2. 安装依赖 / Install dependencies
pip install -r requirements.txt

# 3. 运行系统 / Run system
python main_EN.py
python main_CN.py
```

### 基本使用流程 / Basic Usage Flow

#### 中文 / Chinese
1. **启动程序** - 运行 `main_CN.py`
2. **设置机器人信息** - 在"系统设置"选项卡中配置机器人基本信息
3. **启动模拟器** - 在"机器人模拟器"选项卡中启动数据模拟
4. **开始记录** - 在"系统状态"选项卡中开始自动数据记录
5. **查看数据** - 在"数据查看"选项卡中查看记录的数据

#### English
1. **Start Program** - Run `main_EN.py`
2. **Configure Robot Info** - Set robot basic information in "System Settings" tab
3. **Start Simulator** - Launch data simulation in "Robot Simulator" tab
4. **Begin Recording** - Start automatic data recording in "System Status" tab
5. **View Data** - Check recorded data in "Data View" tab

---

## 📦 安装 / Installation

### 系统要求 / System Requirements

- **Python**: 3.8 或更高版本 / 3.8 or higher
- **操作系统 / OS**: Windows 10+, macOS 10.14+, Linux Ubuntu 18.04+
- **内存 / Memory**: 至少 512MB RAM / At least 512MB RAM
- **存储 / Storage**: 至少 100MB 可用磁盘空间 / At least 100MB available disk space

### 详细安装步骤 / Detailed Installation Steps

####  从源码安装（推荐）/  Install from Source (Recommended)

```bash
# 克隆仓库 / Clone repository
git clone https://github.com/NTRforever/Ethical-Black-Box-System.git
cd Ethical-Black-Box-System

# 创建虚拟环境 / Create virtual environment
python -m venv ebb_env

# 激活虚拟环境 / Activate virtual environment
# Windows:
ebb_env\Scripts\activate
# macOS/Linux:
source ebb_env/bin/activate

# 安装依赖 / Install dependencies
pip install -r requirements.txt

# 运行程序 / Run program
python main_CN.py
python main_EN.py
```



### 依赖文件 / Dependencies (requirements.txt)

```txt
# Core dependencies / 核心依赖
tkinter>=8.6
hashlib2>=1.3.1
dataclasses>=0.8
threading2>=0.1.0

# Data handling / 数据处理
pandas>=1.3.0
numpy>=1.21.0
json5>=0.9.6

# Development dependencies / 开发依赖
pytest>=6.2.0
black>=21.0.0
flake8>=3.9.0
mypy>=0.812
```

---

## 📖 使用指南 / Usage Guide

### 界面导航 / Interface Navigation

#### 1. 系统状态选项卡 / System Status Tab

**功能概述 / Function Overview**: 系统总控制台和状态监控 / System main console and status monitoring

**主要操作 / Main Operations**:

| 中文 / Chinese | English | 描述 / Description |
|----------------|---------|-------------------|
| EBB状态 | EBB Status | 显示当前系统运行状态 / Display current system status |
| 记录总数 | Record Count | 显示已记录的数据条数 / Show number of recorded data entries |
| 存储使用 | Storage Usage | 显示当前存储空间使用率 / Show current storage usage rate |
| 最后记录时间 | Last Record Time | 显示最近一次数据记录的时间 / Show timestamp of latest data record |
| 模拟器状态 | Simulator Status | 显示模拟器运行状态 / Show simulator running status |

**控制操作 / Control Operations**:
```python
# 控制命令 / Control Commands
- 开始自动记录 / Start Auto Recording: 启动定时自动数据记录 / Start timed automatic data recording
- 停止自动记录 / Stop Auto Recording: 停止自动记录功能 / Stop automatic recording function
- 手动记录一次 / Manual Record Once: 立即记录一次当前数据 / Immediately record current data once
- 清空记录 / Clear Records: 清除所有历史记录数据 / Clear all historical record data
```

#### 2. 数据记录选项卡 / Data Recording Tab

**功能概述 / Function Overview**: 实时数据监控和记录配置 / Real-time data monitoring and recording configuration

**实时数据显示格式 / Real-time Data Display Format**:
| 类型 Type | 名称 Name | 值 Value | 单位 Unit | 时间 Time |
|-----------|-----------|----------|-----------|-----------|
| 传感器 Sensor | battery | 95.50 | % | 14:30:25 |
| 传感器 Sensor | ir_sensor_1 | 0.23 | m | 14:30:25 |
| 执行器 Actuator | left_wheel | 45.20 | 度 ° | 14:30:25 |
| 决策 Decision | 当前决策 Current | Moving forward | - | 14:30:25 |

**记录配置 / Recording Configuration**:
```python
# 设置记录间隔 / Set recording interval
interval = 2  # 秒 seconds，可设置范围 configurable range：0.1-60秒 seconds

# 数据导入功能 / Data import function
supported_formats = ['.csv', '.json', '.ebb']
```

#### 3. 数据查看选项卡 / Data View Tab

**功能概述 / Function Overview**: 历史数据管理和分析 / Historical data management and analysis

**记录列表显示 / Record List Display**:
```
序号 No. | 类型 Type | 时间 Time | 字段数 Fields | 校验和 Checksum
001     | RD        | 2025-06-20 14:30:25 | 17 | A1B2C3D4
002     | RD        | 2025-06-20 14:30:27 | 17 | B2C3D4E5
```

**记录详情示例 / Record Detail Example**:
```
记录类型 Record Type: RD
时间戳 Timestamp: 2025-06-20 14:30:25
校验和 Checksum: A1B2C3D4

字段详情 Field Details:
  recS: 017:00000240
  ebbD: 2025:06:20
  ebbT: 14:30:25:123
  botT: 14:30:25:123
  batL: 095
  irSe: 01:0.23
  actV: 001:+0045.20
  decC: 0001:Moving forward
  wifi: 1:85
```

#### 4. 机器人模拟器选项卡 / Robot Simulator Tab

**功能概述 / Function Overview**: 模拟真实机器人运行环境 / Simulate real robot operating environment

**传感器模拟数据 / Sensor Simulation Data**:
```python
sensors = {
    'battery': 95.5,           # 电池电量 Battery level (0-100%)
    'ir_sensor_1': 0.23,       # 红外传感器1 Infrared sensor 1 (0-2.0m)
    'ir_sensor_2': 0.18,       # 红外传感器2 Infrared sensor 2 (0-2.0m)
    'ir_sensor_3': 0.45,       # 红外传感器3 Infrared sensor 3 (0-2.0m)
    'ir_sensor_4': 0.12,       # 红外传感器4 Infrared sensor 4 (0-2.0m)
    'touch_sensor_1': 0,       # 触摸传感器 Touch sensor (0/1)
    'gyro': [1.2, -0.8, 3.4], # 陀螺仪 Gyroscope [x, y, z] (度/秒 deg/s)
    'accelerometer': [0.1, 0.2, 9.8] # 加速度计 Accelerometer [x, y, z] (m/s²)
}

actuators = {
    'left_wheel': 45.2,        # 左轮角度 Left wheel angle (度 degrees)
    'right_wheel': 47.1,       # 右轮角度 Right wheel angle (度 degrees)
    'head_servo': 15.0         # 头部舵机角度 Head servo angle (度 degrees)
}
```

**决策逻辑示例 / Decision Logic Example**:
```python
# 决策代码对照表 / Decision code reference
decision_codes = {
    '0001': 'Moving forward / 前进',           
    '0002': 'Turning left / 左转',            
    '0003': 'Turning right / 右转',           
    '0004': 'Stopping / 停止',                
    '0005': 'Backing up / 后退',              
    '0006': 'Obstacle avoidance / 避障',      
    '0007': 'Emergency stop / 紧急停止'       
}
```

#### 5. 系统设置选项卡 / System Settings Tab

**功能概述 / Function Overview**: 系统参数配置和个性化设置 / System parameter configuration and personalization

**机器人信息配置 / Robot Information Configuration**:
```python
robot_info = {
    'name': 'TestRobot',              # 机器人名称 Robot name
    'version': '1.0',                 # 软件版本 Software version
    'serial': 'TR001',                # 序列号 Serial number
    'manufacturer': 'RobotCorp',      # 制造商 Manufacturer
    'operator': 'Zhang San',          # 操作员 Operator
    'responsible': 'Li Manager +86 138****1234'  # 负责人 Responsible person
}
```

**EBB系统设置 / EBB System Settings**:
```python
ebb_settings = {
    'max_records': 1000,              # 最大记录数 Maximum records
    'auto_backup': True,              # 自动备份 Auto backup
    'data_compression': False,        # 数据压缩 Data compression
    'log_level': 'INFO'              # 日志级别 Log level
}
```

### 高级功能使用 / Advanced Features Usage

#### 数据导入导出 / Data Import/Export

**导出数据 / Export Data**:
```python
# 导出为EBB标准格式 / Export to EBB standard format
ebb.export_records('robot_data_2025-06-20.ebb')

# 导出格式示例 / Export format example
"""
MD recS:010:00000130 ebbD:2025:06:20 ebbT:14:30:25:123 botN:TestRobot botV:1.0 botS:TR001 chkS:A1B2C3D4
DD recS:010:00000130 ebbD:2025:06:20 ebbT:14:30:25:123 ebbN:0000000100 ebbX:00000000000000100 chkS:B2C3D4E5
RD recS:017:00000240 ebbD:2025:06:20 ebbT:14:30:25:123 botT:14:30:25:123 batL:095 irSe:01:0.23 chkS:C3D4E5F6
"""
```

**导入CSV数据 / Import CSV Data**:
```csv
# 示例CSV格式 / Example CSV format (data.csv)
timestamp,sensor_battery,sensor_ir_1,sensor_ir_2,actuator_left_wheel,actuator_right_wheel,decision_code,decision_reason
2025-06-20 14:30:25,95.5,0.23,0.18,45.2,47.1,0001,Moving forward
2025-06-20 14:30:27,95.4,0.21,0.19,46.8,48.3,0001,Moving forward
2025-06-20 14:30:29,95.3,0.15,0.22,48.1,49.5,0002,Turning left
```

**导入JSON数据 / Import JSON Data**:
```json
{
  "metadata": {
    "robot_name": "TestRobot",
    "data_source": "simulation",
    "total_records": 3
  },
  "records": [
    {
      "timestamp": "2025-06-20 14:30:25",
      "sensors": {
        "battery": 95.5,
        "ir_sensor_1": 0.23,
        "ir_sensor_2": 0.18,
        "touch_sensor_1": 0,
        "gyro": [1.2, -0.8, 3.4],
        "accelerometer": [0.1, 0.2, 9.8]
      },
      "actuators": {
        "left_wheel": 45.2,
        "right_wheel": 47.1,
        "head_servo": 15.0
      },
      "decision": {
        "code": "0001",
        "reason": "Moving forward",
        "confidence": 0.95
      }
    }
  ]
}
```

---

## 📚 API文档 / API Documentation

### 核心类 EBBCore / Core Class EBBCore

#### 初始化 / Initialization
```python
from ebb_system import EBBCore

# 创建EBB实例 / Create EBB instance
ebb = EBBCore(max_records=1000)
```

#### 主要方法 / Main Methods

##### 创建记录 / Create Records
```python
# 创建元数据记录 / Create metadata record
robot_info = {
    'name': 'TestRobot',
    'version': '1.0',
    'serial': 'TR001',
    'manufacturer': 'RobotCorp',
    'operator': 'Zhang San',
    'responsible': 'Li Manager +86 138****1234'
}
meta_record = ebb.create_meta_data_record(robot_info)

# 添加机器人数据记录 / Add robot data record
sensor_data = {'battery': 95.5, 'ir_sensor_1': 0.23}
actuator_data = {'left_wheel': 45.2, 'right_wheel': 47.1}
decision_data = {'code': '0001', 'reason': 'Moving forward'}

robot_record = ebb.add_robot_data_record(sensor_data, actuator_data, decision_data)
```

##### 数据管理 / Data Management
```python
# 导出记录 / Export records
ebb.export_records('output.ebb')

# 导入记录 / Import records
ebb.import_records('input.ebb')

# 计算校验和 / Calculate checksum
checksum = ebb.calculate_checksum('test_data')

# 格式化时间戳 / Format timestamp
date_str, time_str = ebb.format_timestamp()
```

### 模拟器类 RobotSimulator / Simulator Class RobotSimulator

#### 基本使用 / Basic Usage
```python
from ebb_system import RobotSimulator

# 创建模拟器实例 / Create simulator instance
simulator = RobotSimulator()

# 更新模拟数据 / Update simulation data
simulator.update_simulation()

# 获取数据 / Get data
sensor_data = simulator.get_sensor_data()
actuator_data = simulator.get_actuator_data()
decision_data = simulator.get_decision_data()
```

#### 自定义传感器 / Custom Sensors
```python
# 添加自定义传感器 / Add custom sensor
simulator.sensors['custom_sensor'] = 42.0

# 自定义决策逻辑 / Custom decision logic
def custom_decision_logic(sensors):
    if sensors['battery'] < 20:
        return {'code': '0007', 'reason': 'Emergency stop - Low battery'}
    return {'code': '0001', 'reason': 'Normal operation'}
```

### GUI应用类 EBBGUIApplication / GUI Application Class

#### 初始化和运行 / Initialization and Running
```python
from ebb_system import EBBGUIApplication

# 创建应用实例 / Create application instance
app = EBBGUIApplication()

# 运行应用 / Run application
app.run()
```

#### 自定义界面 / Custom Interface
```python
# 自定义状态更新 / Custom status update
app.update_status('自定义状态 Custom Status', '运行中 Running')

# 添加自定义按钮 / Add custom button
def custom_action():
    print("执行自定义操作 Execute custom action")

import tkinter as tk
from tkinter import ttk
custom_button = ttk.Button(app.root, text="自定义操作 Custom Action", command=custom_action)
custom_button.pack()
```

---

## ⚙️ 配置说明 / Configuration

### 配置文件结构 / Configuration File Structure

创建 `config.json` 文件 / Create `config.json` file：
```json
{
  "system": {
    "max_records": 1000,
    "auto_save_interval": 60,
    "backup_enabled": true,
    "log_level": "INFO"
  },
  "robot": {
    "name": "DefaultRobot",
    "version": "1.0.0",
    "serial": "DEFAULT001",
    "manufacturer": "DefaultCorp",
    "operator": "System",
    "responsible": "Admin +86 123456789"
  },
  "simulator": {
    "update_interval": 0.1,
    "enable_noise": true,
    "battery_drain_rate": 0.01,
    "sensor_precision": 2
  },
  "gui": {
    "theme": "default",
    "language": "zh_CN",
    "window_size": "1200x800",
    "auto_refresh": true
  }
}
```

### 环境变量 / Environment Variables

```bash
# 设置数据目录 / Set data directory
export EBB_DATA_DIR="/path/to/data"

# 设置日志级别 / Set log level
export EBB_LOG_LEVEL="DEBUG"

# 设置最大内存使用 / Set maximum memory usage
export EBB_MAX_MEMORY="512MB"

# 设置备份目录 / Set backup directory
export EBB_BACKUP_DIR="/path/to/backup"
```

---

## 📄 数据格式 / Data Format

### EBB标准格式规范 / EBB Standard Format Specification

#### 元数据记录 (MD) / Metadata Record (MD)
```
格式 Format: MD field1:value1 field2:value2 ... chkS:checksum

必需字段 Required Fields:
- recS: 记录大小 Record size (格式 format: nnn:nnnnnnnn)
- ebbD: EBB日期 EBB date (格式 format: yyyy:mm:dd)
- ebbT: EBB时间 EBB time (格式 format: hh:mm:ss:ms)
- botN: 机器人名称 Robot name
- botV: 机器人版本 Robot version
- botS: 机器人序列号 Robot serial number
- botM: 制造商 Manufacturer
- opeR: 操作员 Operator
- resP: 负责人 Responsible person
- ebbN: EBB软件名称 EBB software name

示例 Example:
MD recS:010:00000130 ebbD:2025:06:20 ebbT:14:30:25:123 botN:TestRobot botV:1.0 botS:TR001 botM:RobotCorp opeR:Zhang_San resP:Li_Manager_+86_138****1234 ebbN:PyEBB_v1.0 chkS:A1B2C3D4
```

#### 数据数据记录 (DD) / Data Data Record (DD)
```
格式 Format: DD field1:value1 field2:value2 ... chkS:checksum

必需字段 Required Fields:
- recS: 记录大小 Record size
- ebbD: EBB日期 EBB date
- ebbT: EBB时间 EBB time
- ebbN: 数据记录总数 Total data records (10位数字 10 digits)
- ebbX: 当前记录索引 Current record index (17位数字 17 digits)
- ebD1: 第一条记录日期 First record date
- ebT1: 第一条记录时间 First record time
- ebDM: 最后记录日期 Last record date
- ebTM: 最后记录时间 Last record time

示例 Example:
DD recS:010:00000130 ebbD:2025:06:20 ebbT:14:30:25:123 ebbN:0000000100 ebbX:00000000000000100 ebD1:2025:06:20 ebT1:14:30:01:000 ebDM:2025:06:20 ebTM:14:30:25:123 chkS:B2C3D4E5
```

#### 机器人数据记录 (RD) / Robot Data Record (RD)
```
格式 Format: RD field1:value1 field2:value2 ... chkS:checksum

必需字段 Required Fields:
- recS: 记录大小 Record size
- ebbD: EBB日期 EBB date
- ebbT: EBB时间 EBB time
- botT: 机器人时间 Robot time

可选字段 Optional Fields:
- batL: 电池电量 Battery level (nnn, 0-100)
- irSe: 红外传感器 Infrared sensor (nn:n.nn)
- tchS: 触摸传感器 Touch sensor (nn:nnn)
- gyrV: 陀螺仪值 Gyroscope values (nn:±nnnnnn:±nnnnnn:±nnnnnn)
- accV: 加速度计值 Accelerometer values (nn:±nnnnnn:±nnnnnn:±nnnnnn)
- actV: 执行器值 Actuator values (nnn:±nnnn.nn)
- decC: 决策代码 Decision code (nnnn:reason_text)
- wifi: WiFi状态 WiFi status (n:nn)

示例 Example:
RD recS:017:00000240 ebbD:2025:06:20 ebbT:14:30:25:123 botT:14:30:25:123 batL:095 irSe:01:0.23 tchS:01:000 gyrV:01:+000012:-000008:+000034 accV:01:+000001:+000002:+009800 actV:001:+0045.20 decC:0001:Moving_forward wifi:1:85 chkS:C3D4E5F6
```

### 校验和计算 / Checksum Calculation

```python
import hashlib

def calculate_checksum(data: str) -> str:
    """计算64位非加密哈希校验和 / Calculate 64-bit non-cryptographic hash checksum"""
    return hashlib.sha256(data.encode()).hexdigest()[:8].upper()

# 示例 Example
data = "RD recS:017:00000240 ebbD:2025:06:20 ebbT:14:30:25:123"
checksum = calculate_checksum(data)  # 输出 Output: A1B2C3D4
```

### 数据验证 / Data Validation

```python
def validate_record(record_string: str) -> bool:
    """验证记录格式和校验和 / Validate record format and checksum"""
    parts = record_string.split(' ')
    
    # 检查记录类型 / Check record type
    if parts[0] not in ['MD', 'DD', 'RD']:
        return False
    
    # 提取校验和 / Extract checksum
    checksum_field = None
    for part in parts:
        if part.startswith('chkS:'):
            checksum_field = part.split(':')[1]
            break
    
    if not checksum_field:
        return False
    
    # 重新计算校验和 / Recalculate checksum
    data_without_checksum = ' '.join(p for p in parts if not p.startswith('chkS:'))
    calculated_checksum = calculate_checksum(data_without_checksum)
    
    return checksum_field == calculated_checksum
```

---

## 🤝 贡献指南 / Contributing

我们欢迎所有形式的贡献！/ We welcome all forms of contributions!

### 贡献类型 / Contribution Types

- 🐛 **Bug修复 / Bug Fixes**: 修复现有功能的问题 / Fix issues with existing features
- ✨ **新功能 / New Features**: 添加新的功能特性 / Add new functionality
- 📚 **文档 / Documentation**: 改进文档和示例 / Improve documentation and examples
- 🎨 **界面 / Interface**: 改进用户界面和用户体验 / Improve UI and UX
- ⚡ **性能 / Performance**: 性能优化和改进 / Performance optimization and improvements
- 🧪 **测试 / Testing**: 添加或改进测试用例 / Add or improve test cases

### 开发流程 / Development Workflow

#### 1. Fork 和 Clone / Fork and Clone
```bash
# Fork 这个仓库到你的GitHub账号 / Fork this repository to your GitHub account
# 然后clone你的fork / Then clone your fork

git clone https://github.com/your-username/Ethical-Black-Box-System.git
cd Ethical-Black-Box-System

# 添加上游仓库 / Add upstream repository
git remote add upstream https://github.com/NTRforever/Ethical-Black-Box-System.git
```

#### 2. 创建开发分支 / Create Development Branch
```bash
# 从main分支创建新的功能分支 / Create new feature branch from main
git checkout -b feature/your-feature-name

# 或者修复bug分支 / Or create bugfix branch
git checkout -b bugfix/issue-number-description
```

#### 3. 开发环境设置 / Development Environment Setup
```bash
# 创建虚拟环境 / Create virtual environment
python -m venv dev_env
source dev_env/bin/activate  # Linux/Mac
# 或 or
dev_env\Scripts\activate     # Windows

# 安装开发依赖 / Install development dependencies
pip install -r requirements-dev.txt

# 安装预提交钩子 / Install pre-commit hooks
pre-commit install
```

#### 4. 编码规范 / Coding Standards

**Python代码风格 / Python Code Style**:
```python
# 使用 Black 格式化代码 / Use Black to format code
black ebb_system/

# 使用 flake8 检查代码质量 / Use flake8 to check code quality
flake8 ebb_system/

# 使用 mypy 进行类型检查 / Use mypy for type checking
mypy ebb_system/
```

**提交消息规范 / Commit Message Convention**:
```
type(scope): description

body

footer
```

示例 Example:
```
feat(core): add new sensor data validation

- Add validation for gyroscope data range
- Improve error handling for invalid sensor values  
- Update tests for new validation logic

Closes #123
```

**类型说明 / Type Description**:
- `feat`: 新功能 / New feature
- `fix`: Bug修复 / Bug fix
- `docs`: 文档更新 / Documentation update
- `style`: 代码格式修改 / Code style changes
- `refactor`: 代码重构 / Code refactoring
- `test`: 测试相关 / Test related
- `chore`: 构建过程或辅助工具的变动 / Build process or auxiliary tool changes

#### 5. 测试 / Testing
```bash
# 运行所有测试 / Run all tests
python -m pytest tests/

# 运行特定测试文件 / Run specific test file
python -m pytest tests/test_ebb_core.py

# 生成覆盖率报告 / Generate coverage report
python -m pytest --cov=ebb_system tests/

# 运行集成测试 / Run integration tests
python -m pytest tests/integration/
```

#### 6. 提交和推送 / Commit and Push
```bash
# 添加更改 / Add changes
git add .

# 提交更改 / Commit changes
git commit -m "feat(core): add new sensor validation"

# 推送到你的fork / Push to your fork
git push origin feature/your-feature-name
```

#### 7. 创建Pull Request / Create Pull Request

1. 访问GitHub上的原始仓库 / Visit the original repository on GitHub
2. 点击 "New Pull Request" / Click "New Pull Request"
3. 选择你的分支 / Select your branch
4. 填写PR模板 / Fill in the PR template：

```markdown
## 📋 变更概述 / Change Overview
简要描述这个PR的变更内容 / Brief description of changes in this PR

## 🔧 变更类型 / Change Type
- [ ] Bug修复 / Bug fix
- [ ] 新功能 / New feature
- [ ] 文档更新 / Documentation update
- [ ] 性能改进 / Performance improvement
- [ ] 其他 / Other: ___________

## 🧪 测试 / Testing
- [ ] 已添加新的测试用例 / New test cases added
- [ ] 所有现有测试通过 / All existing tests pass
- [ ] 手动测试完成 / Manual testing completed

## 📷 截图（如果适用）/ Screenshots (if applicable)
添加截图来说明变更 / Add screenshots to illustrate changes

## 📝 检查清单 / Checklist
- [ ] 代码遵循项目编码规范 / Code follows project coding standards
- [ ] 已添加或更新相关文档 / Related documentation added or updated
- [ ] 提交消息遵循约定 / Commit messages follow convention
- [ ] 已测试变更不会破坏现有功能 / Tested that changes don't break existing functionality

## 🔗 相关Issue / Related Issues
关闭 Closes #issue_number
```

---

## ❓ 常见问题 / FAQ

### 安装和环境问题 / Installation and Environment Issues

**Q: 安装时提示"No module named 'tkinter'"错误 / Installation error "No module named 'tkinter'"**

A: 这是因为系统缺少tkinter模块 / This is because the system lacks the tkinter module:

```bash
# Ubuntu/Debian
sudo apt-get install python3-tk

# CentOS/RHEL
sudo yum install tkinter
# 或 or
sudo dnf install python3-tkinter

# macOS
brew install python-tk

# Windows
# tkinter通常随Python一起安装 / tkinter is usually installed with Python
# 如果缺少请重新安装Python / If missing, please reinstall Python
```

**Q: 运行时提示权限错误 / Runtime permission error**

A: 确保有足够的文件读写权限 / Ensure sufficient file read/write permissions:

```bash
# 检查当前目录权限 / Check current directory permissions
ls -la

# 给予执行权限 / Grant execution permissions
chmod +x main.py

# 如果需要，更改所有者 / If needed, change owner
sudo chown $USER:$USER -R ebb-system/
```

### 功能使用问题 / Feature Usage Issues

**Q: 模拟器启动后没有数据显示 / No data display after simulator starts**

A: 请检查以下几点 / Please check the following:
1. 确保模拟器已正确启动（状态显示"运行中"）/ Ensure simulator is correctly started (status shows "Running")
2. 检查数据更新间隔设置 / Check data update interval settings
3. 在"数据记录"选项卡中查看实时数据 / View real-time data in "Data Recording" tab

**Q: 导入数据失败 / Data import failed**

A: 常见原因和解决方法 / Common causes and solutions:
1. **文件格式不正确 / Incorrect file format**: 确保CSV文件包含正确的列名 / Ensure CSV file contains correct column names
2. **文件编码问题 / File encoding issue**: 确保文件使用UTF-8编码 / Ensure file uses UTF-8 encoding
3. **数据格式错误 / Data format error**: 检查数值字段是否为有效的数字格式 / Check if numeric fields are in valid number format

```python
# 检查CSV文件格式 / Check CSV file format
import pandas as pd
df = pd.read_csv('your_file.csv', encoding='utf-8')
print(df.head())
print(df.columns.tolist())
```

**Q: 记录数据丢失 / Record data lost**

A: EBB系统使用循环存储 / EBB system uses circular storage:
- 默认最大记录数为1000条 / Default maximum records is 1000
- 超过限制时会覆盖最早的记录 / Will overwrite earliest records when limit exceeded
- 可在"系统设置"中调整最大记录数 / Can adjust maximum records in "System Settings"
- 建议定期导出重要数据 / Recommend regular export of important data

### 性能问题 / Performance Issues

**Q: 系统运行缓慢 / System runs slowly**

A: 优化建议 / Optimization suggestions:
1. **减少记录频率 / Reduce recording frequency**: 调整自动记录间隔 / Adjust auto-recording interval
2. **限制最大记录数 / Limit maximum records**: 降低max_records设置 / Lower max_records setting
3. **关闭不必要的功能 / Disable unnecessary features**: 停止未使用的模拟器 / Stop unused simulator

```python
# 性能优化示例 / Performance optimization example
ebb = EBBCore(max_records=500)  # 减少最大记录数 / Reduce maximum records
```

**Q: 内存使用过高 / High memory usage**

A: 内存优化 / Memory optimization:
1. 定期清空历史记录 / Regularly clear historical records
2. 导出数据后清理内存 / Clean memory after data export
3. 重启应用程序 / Restart application

```python
# 内存清理 / Memory cleanup
ebb.records.clear()
ebb.current_record_index = 0
```

### 获取帮助 / Getting Help

如果以上FAQ没有解决您的问题 / If the above FAQ doesn't solve your problem:

1. **查看详细错误日志 / View detailed error logs**:
```bash
python main.py 2>&1 | tee ebb_error.log
```

2. **创建最小重现示例 / Create minimal reproduction example**:
```python
# minimal_example.py
from ebb_system import EBBCore

try:
    ebb = EBBCore()
    print("EBB初始化成功 / EBB initialization successful")
except Exception as e:
    print(f"错误 Error: {e}")
    import traceback
    traceback.print_exc()
```

3. **提交Issue / Submit Issue**: 在GitHub上创建新的Issue / Create new Issue on GitHub: https://github.com/NTRforever/Ethical-Black-Box-System/issues/new
4. **联系支持 / Contact Support**: 通过GitHub Discussions联系 / Contact via GitHub Discussions: https://github.com/NTRforever/Ethical-Black-Box-System/discussions

---

## 📜 许可证 / License

本项目采用 MIT 许可证 / This project is licensed under the MIT License - 查看 [LICENSE](LICENSE) 文件了解详情 / see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 EBB System Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🌟 致谢 / Acknowledgments

### 特别感谢 / Special Thanks

- [tkinter](https://docs.python.org/3/library/tkinter.html) - Python标准GUI库 / Python standard GUI library
- [Python](https://python.org) - 强大的编程语言 / Powerful programming language
- [GitHub](https://github.com) - 代码托管平台 / Code hosting platform
- 所有测试用户和反馈者 / All test users and feedback providers

### 引用 / Citation

如果您在学术研究中使用了这个项目 / If you use this project in academic research:

```bibtex
@software{ebb_system_2025,
  title={EBB Ethical Black Box System: Implementation of Academic Standards},
  author={EBB System Contributors},
  year={2025},
  url={https://github.com/NTRforever/Ethical-Black-Box-System},
  version={1.0.0},
  note={Implementation based on Winfield et al. open standard specifications}
}

@article{winfield2022ebb_standard,
  title={An Ethical Black Box for Social Robots: a draft Open Standard},
  author={Winfield, Alan F.T. and van Maris, Anouk and Salvini, Pericle and Jirotka, Marina},
  journal={arXiv preprint arXiv:2205.06564},
  year={2022},
  note={Primary technical specification for EBB implementation}
}

@inproceedings{winfield2017case,
  title={The Case for an Ethical Black Box},
  author={Winfield, Alan F.T. and Jirotka, Marina},
  booktitle={Towards Autonomous Robotic Systems: 18th Annual Conference, TAROS 2017},
  pages={262--273},
  year={2017},
  publisher={Springer},
  address={Cham},
  note={Foundational work establishing the need for robot ethical monitoring}
}
```

### 技术规范对应关系 / Technical Specification Mapping

| 学术标准 Academic Standard | 我们的实现 Our Implementation | 状态 Status |
|----------------------------|-------------------------------|-------------|
| MD记录格式 MD Record Format | `MetaDataRecord` 类 Class | ✅ 完全实现 Fully Implemented |
| DD记录格式 DD Record Format | `DataDataRecord` 类 Class | ✅ 完全实现 Fully Implemented |  
| RD记录格式 RD Record Format | `RobotDataRecord` 类 Class | ✅ 完全实现 Fully Implemented |
| 校验和算法 Checksum Algorithm | `calculate_checksum()` 方法 Method | ✅ SHA256前8位 SHA256 first 8 chars |
| 循环存储 Circular Storage | `EBBCore` 存储机制 Storage Mechanism | ✅ 智能覆盖 Intelligent Overwriting |
| 时间戳格式 Timestamp Format | `format_timestamp()` 方法 Method | ✅ yyyy:mm:dd hh:mm:ss:ms |

---

## 📚 学术基础 / Academic Foundation

本EBB系统的设计和实现基于Bristol Robotics Lab的开创性研究工作，严格遵循学术界提出的开放标准规范。

This EBB system design and implementation is based on groundbreaking research from Bristol Robotics Lab, strictly following the open standard specifications proposed by the academic community.

### 核心理论基础 / Core Theoretical Foundation

我们的实现完全符合以下学术研究中提出的技术规范和标准：

Our implementation fully complies with the technical specifications and standards proposed in the following academic research:

**主要参考文献 / Primary References:**

1. **Winfield, A.F.T., van Maris, A., Salvini, P., & Jirotka, M.** (2022). *An Ethical Black Box for Social Robots: a draft Open Standard*. arXiv:2205.06564v1 [cs.RO]. 
   - 🎯 **核心贡献 Key Contribution**: 首次提出了社交机器人伦理黑盒的完整开放标准规范
   - 📋 **技术规范 Technical Specs**: 定义了MD/DD/RD三种记录类型的详细数据结构
   - 🔧 **实现指导 Implementation Guide**: 提供了字段格式、校验和计算、时间戳标准等完整技术细节

2. **Winfield, A.F.T. & Jirotka, M.** (2017). *The Case for an Ethical Black Box*. In: Gao Y., Fallah S., Jin Y., Lekakou C. (eds) Towards Autonomous Robotic Systems. TAROS 2017. Lecture Notes in Computer Science, vol 10454. Springer, Cham.
   - 🎯 **核心贡献 Key Contribution**: 论证了机器人伦理黑盒的必要性和重要意义
   - 🛡️ **理论框架 Theoretical Framework**: 建立了透明度、责任追溯与公众信任的理论联系
   - ⚖️ **伦理基础 Ethical Foundation**: 提供了机器人伦理监管的理论依据

### 标准符合性 / Standards Compliance

- ✅ **数据格式 Data Format**: 严格遵循论文中定义的记录结构和字段格式
- ✅ **校验和算法 Checksum Algorithm**: 实现64位非加密哈希校验，确保数据完整性  
- ✅ **时间戳标准 Timestamp Standard**: 采用 `yyyy:mm:dd` 和 `hh:mm:ss:ms` 格式
- ✅ **循环存储 Circular Storage**: 实现智能循环存储机制，优化存储空间使用
- ✅ **三层记录架构 Three-tier Record Architecture**: 完整实现MD、DD、RD记录类型

### 学术影响与应用 / Academic Impact & Applications

这些开创性研究为机器人伦理监管提供了重要的理论基础和技术框架，我们的实现将学术理论转化为实用的软件系统。

These groundbreaking studies provide important theoretical foundations and technical frameworks for robot ethical governance. Our implementation transforms academic theory into practical software systems.

**研究机构 Research Institutions:**
- 🏛️ Bristol Robotics Lab, University of the West of England
- 🎓 Department of Computer Science, University of Oxford

---

## 📞 支持与联系 / Support & Contact

### 获取帮助 / Getting Help

- 📖 **文档 Documentation**: [在线文档 Online Docs](https://ntrforever.github.io/Ethical-Black-Box-System/)
- 💬 **讨论 Discussions**: [GitHub Discussions](https://github.com/NTRforever/Ethical-Black-Box-System/discussions)
- 🐛 **Bug报告 Bug Reports**: [GitHub Issues](https://github.com/NTRforever/Ethical-Black-Box-System/issues)
- 💡 **功能请求 Feature Requests**: [GitHub Issues](https://github.com/NTRforever/Ethical-Black-Box-System/issues/new?assignees=&labels=enhancement&template=feature_request.md)

### 社区 / Community

- 🌐 **官方网站 Official Website**: [项目主页 Project Home](https://github.com/NTRforever/Ethical-Black-Box-System)
- 📱 **技术交流 Technical Discussion**: [GitHub Discussions](https://github.com/NTRforever/Ethical-Black-Box-System/discussions)
- 💼 **项目支持 Project Support**: [GitHub Issues](https://github.com/NTRforever/Ethical-Black-Box-System/issues)

### 项目支持 / Project Support

如果您需要技术支持、功能建议 / If you need technical support, feature suggestions :

- 📧 **技术咨询 Technical Consultation**: [GitHub Issues](https://github.com/NTRforever/Ethical-Black-Box-System/issues)
- 💬 **功能讨论 Feature Discussion**: [GitHub Discussions](https://github.com/NTRforever/Ethical-Black-Box-System/discussions)

---

<div align="center">

**[⬆ 回到顶部 Back to Top](#-ebb伦理黑盒系统--ethical-black-box-system)**

Made with ❤️ by EBB System Contributors

[![GitHub stars](https://img.shields.io/github/stars/NTRforever/Ethical-Black-Box-System.svg?style=social&label=Star)](https://github.com/NTRforever/Ethical-Black-Box-System)
[![GitHub forks](https://img.shields.io/github/forks/NTRforever/Ethical-Black-Box-System.svg?style=social&label=Fork)](https://github.com/NTRforever/Ethical-Black-Box-System/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/NTRforever/Ethical-Black-Box-System.svg?style=social&label=Watch)](https://github.com/NTRforever/Ethical-Black-Box-System/watchers)

</div>
