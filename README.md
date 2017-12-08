# Parallel-coordinate  

- 题目网站访问这里： [VAST challenge](http://vacommunity.org/ieeevpg/viscontest/2015/)  
- 演示网站：[zkid18.github.io](https://zkid18.github.io/data_visualization_project/)
- 简述：
> 给了美国高中生想去的专业、考试成绩、机构测评的符合程度、前两的转专业情况和最推荐的专业等，用可视化的方式展示这些专业流向、特征分布等

- 步骤：
1. 清洗数据、分析基本属性的分布  
2. 探索，选取chord和parallel coordinate的展示方式  
3. 针对 parallel coordinate ，首先根据出现次数resample到两千条数据，然后把符合程度（good-moderate-bad）映射到1-4（让数据符合正态分布）。对考试成绩ACTcat同样处理  

# 好处  
- 可以选取不同的维度  
- 随便组合就可以看出各种不同的分布和趋势  
  ![](https://github.com/qinshimeng18/Parallel-coordinate/blob/master/parallel.png)
  ![](https://github.com/qinshimeng18/Parallel-coordinate/blob/master/parallel_select.png)
