# gpt_riskcontrol_helper

# 1, 项目背景

### 在银行信用风险管理中，客户的风险评级是重要的工作。一般来说，三个等级，具体的划分情况如下：
### 1、“高”风险等级：高风险等级的客户一般都有贷款逾期的记录，或者是名下账户有可疑的交易，并且在银行登记有违规行为；
### 2、“中”风险等级：除了高低两个风险等级以外的客户都属于这个等级。
### 3、“低”风险等级：低风险等级的客户在进行银行业务时循规蹈矩，并且没有不良记录，银行账户也比较正常，身份信息都是真实的；

# 2，实施方案
## 1、用户画像构建：利用规则提取客户交易特征，并结合客户身份信息、交易特征信息和外部风险信息，构建客户风险画像；
## 2、向量知识库构建：将一些评级规则和风控制度，进行向量化并导入知识库汇总；
## 3，建模和封装：利用Langchain和ChatGLM进行处理，构建对话系统，输入客户基本信息，输出评级结果和推荐。
