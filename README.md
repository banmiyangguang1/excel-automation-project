# Excel自动化处理项目

这是一个使用Python和openpyxl库自动化处理Excel文件的示例项目。

## 项目描述

本项目包含一个Python脚本，用于自动创建包含今日利好公司公告的Excel文件。

## 文件结构

- `create_excel.py` - 主要的Python脚本，用于创建Excel文件
- `今日利好公司公告.csv` - 原始数据文件，包含利好公司公告信息
- `今日利好公司公告.xlsx` - 生成的Excel文件（运行脚本后生成）

## 功能特点

- 使用openpyxl库创建Excel工作簿
- 自动添加表头和数据行
- 支持中文内容处理
- 生成格式化的Excel文件

## 使用方法

1. 确保已安装Python和openpyxl库
2. 运行 `python create_excel.py`
3. 查看生成的Excel文件

## 依赖库

- openpyxl

## 作者

sun

## 许可证

MIT License