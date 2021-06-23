# TDD「出租车计费」

## 需求描述
根据里程数计算出租车费用

### 计价规则
- 不超过8公里时每公里0.8元
- 超过8公里则每公里加收50%长途费
- 停车等待时加收每分钟0.25元


## 要求
1. 戴好TDD的三顶帽子
2. 小步提交，Commit信息要表意


### 任务清单
Given 里程数为5，When 计算出租车费用，Then 费用为 4.0元

Given 里程数为10，When 计算出租车费用，Then 费用为 8.8元

Given 里程数为10，等待时间为10分钟， When 计算出租车费用，Then 费用为 11.3元

### 词汇表
车费：Taxi Fee
价格：Price
半价：Half Price
里程数：Mileage
长途费： Long trip fee
等待费：Waiting fee
