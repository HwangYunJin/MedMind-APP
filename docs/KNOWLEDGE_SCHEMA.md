# MedMind Knowledge Schema v0.1


## 1. Overview

MedMind uses a structured medical knowledge model
to transform medical knowledge into adaptive learning tasks.


核心目标：

医学知识
↓
知识节点
↓
学习任务
↓
用户掌握度



---

# 2. Entity Relationship


Disease

contains

Knowledge Nodes

Knowledge Nodes

connect through

Relations

Knowledge generates

Learning Tasks

Learning Tasks generate

Questions



---

# 3. Disease Entity


疾病实体。


Example:

COPD


Schema:

```json
{
"disease_id":"",
"name_cn":"",
"name_en":"",
"system":"",
"exam_priority":""
}
