# Kaggle Titanic 泰坦尼克号生存预测

## 项目简介
这是我的 Kaggle 入门项目，使用逻辑回归预测泰坦尼克号乘客的生还情况。

## 最终成绩
- 线上得分：0.77990
- 使用模型：逻辑回归（带 StandardScaler 标准化）

## 主要步骤
1. 数据清洗与缺失值填充（按 Title 分组填充 Age）
2. 特征工程（Title 提取、FamilySize、Age*Pclass 交互特征）
3. 独热编码（Embarked、Title）
4. 交叉验证 + 网格搜索调参
5. 逻辑回归建模与预测

## 文件说明
- `ti.ipynb`：完整代码
