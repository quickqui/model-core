# quick-qui/model-core

核心概念定义。

## 概念说明 - 

1. 模型（model） - 包含了必要信息的一个对象。其内容取决于其用途，在机制层面没有具体定义。
1. 模型定义（model define） - 
1. 模型验证（model validate） - 模型生成的过程中，可能有对模型或者模型的部分进验证的步骤，模型定义中有相关的约定。完成模型验证的逻辑是模型验证者（validator）。
1. 模型编织（model weave） - 模型生成的过程中，各个部分可以相互综合相互影响。这个步骤在模型定义中约定。完成模型编织的逻辑是模型编制者（weaver）。
2. 日志（log） - 模型生成的过程中会过程记录。称为日志。通过日志，模型描述者可以容易回溯和debug日志生成过程。验证的结果、编织的记录都使用这个机制。
