# 广州租房市场监测分析平台
> 大数据课程项目，基于Python爬虫采集广州租房数据，进行清洗、可视化分析

## 项目介绍
本项目采集广州各区租房房源信息，对租金、户型、面积、区位等数据进行清洗与统计可视化，分析广州租房市场分布特征，实现租房市场监测。

## 技术栈
- 采集：Python、requests、BeautifulSoup
- 数据存储：MySQL
- 数据分析：Pandas、NumPy
- 可视化：Matplotlib、Pyecharts
- 版本管理：Git + GitHub

## 目录结构
```
guangzhou-rent-analysis/
├── data/                # 原始数据、清洗后csv文件
├── spider/              # 爬虫代码
├── analysis/            # 数据分析&可视化脚本
├── sql/                 # 建表SQL
├── README.md
```

## 使用步骤
1. 克隆仓库
```bash
git clone https://github.com/Yx-Yvonne/guangzhou-rent-analysis.git
```
2. 安装依赖
```bash
pip install requests pandas pyecharts pymysql
```
3.运行爬虫采集数据
4.数据清洗，存入 MySQL
5.执行分析脚本，生成图表

预期分析内容：
广州各区平均租金对比
租金和房屋面积相关性分析
热门户型分布统计
房源区域热力图
