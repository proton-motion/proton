# 项目目标

一个C++原生的执行引擎，适配Spark-SQL,Flink-SQL等大数据计算引擎API，通过向量化，缓存，SIMD等优化手段，大幅度提升这些大数据计算引擎的计算性能。支持各种列存文件，例如Parquet，ORC等。
兼容当前各种数据湖方案的API，同时重点优化ACID，Upsert等场景
# 一期计划
## 指令向量优化
## 基于Nvme SSD的缓存策略
