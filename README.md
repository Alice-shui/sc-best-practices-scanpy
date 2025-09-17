# sc-best-practices-scanpy  
单细胞 RNA-seq 最佳实践全流程（Python/Scanpy | 2025 更新）

&gt; 基于 Luecken & Theis 2019 综述的完整实现，含公开数据自动下载、质控、归一化、批次校正、聚类、注释、轨迹、差异表达、功能富集、GRN 推断等模块。

## 🚀 一键运行
```bash
# 1. 克隆你自己的仓库
git clone https://github.com/YOUR_GITHUB/sc-best-practices-scanpy.git
cd sc-best-practices-scanpy

# 2. 新建环境
conda env create -f environment.yml
conda activate sc-best-practices

# 3. 启动 Jupyter
jupyter lab notebooks/00-full-pipeline.ipynb
