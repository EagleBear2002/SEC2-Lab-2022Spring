# UC3-库存分析用例描述

| 项目     | UC3 库存分析                                                 |
| :-------- | :----------------------------------------------------------- |
| 参与者   | 库存管理人员，目标是了解并分析商品的库存信息，以辅助库存管理。 |
| 触发条件 | 库存管理人员需要了解库存情况                                 |
| 前置条件 | 库存管理人员必须已被识别和授权                               |
| 后置条件 | 如果库存管理人员要求，应该导出库存快照 Excel 文件            |
| 正常流程 | 1.0 库存查看<br/>    1.  库存管理人员输入起始日期和终止日期 <br/>    2. 系统统计并显示此时间段内的出/入库数量/金额/商品信息/分类信息/库存数量合计 |
| 扩展流程 | 1.1 库存盘点<br/>    1. 库存管理人员向系统请求库存盘点<br/>    2. 系统统计并显示当天的库存快照信息，包括当天的各种商品的名称，型号，库存数量，库存均价（商品的平均进价），批次批号，生产日期，并且显示行号, 并询问是否需要导出 Excel 文件。  <br/>    3. 库存管理人员根据提示选项进行选择是否导出 Excel 文件<br/>    4. 系统根据库存管理人员的选择导出 Excel 文件或结束本次库存盘点<br/>1.0-1a 库存管理人员输入不合法的起始日期和终止日期 (起始日期大于终止日期/起始日期大于当前日期)<br/>    1.系统拒绝查询并显示错误提示 <br/>1.0-1b 库存管理人员输入的起始日期到终止日期之间的数据不存在<br/>    1. 系统显示信息不存在提示<br/>    2. 库存管理人员根据实际情况判断是否需要上报维修系统 |
| 特殊需求 | 无                                                           |

