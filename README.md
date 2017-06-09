# 数据字典
## OA_WorkList(任务清单表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_ProjectName      | 任务名称                  | NVarChar(255)        | √            |
| 4                                        | F_Content          | 任务内容                  | NVarChar(255)        | √            |
| 5                                        | F_PlanID           | 项目名称  公司项目表ID    | NVarChar(255)        | √            |
| 6                                        | F_WorkHours        | 任务周期                  | NVarChar(255)        | √            |
| 7                                        | F_StartTime        | 起始时间                  | DateTime             | √            |
| 8                                        | F_EndTime          | 终止时间                  | DateTime             | √            |
| 9                                        | F_Create           | 创建人                    | NVarChar(255)        | √            |
| 10                                       | F_Duty             | 责任人                    | NVarChar(255)        | √            |
| 11                                       | F_Status           | 状态                      | NVarChar(255)        | √            |
| 12                                       | F_Reamark          | 备注                      | NVarChar(255)        | √            |
| 13                                       | F_Lev              | 优先级                    | NVarChar(255)        | √            |
| 14                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 15                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 16                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 17                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 18                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 19                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 20                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 21                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 22                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 23                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 24                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_WorkDaily(工作日报表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_Name             | 内容名称                  | NVarChar(255)        | √            |
| 4                                        | F_Content          | 工作内容                  | NVarChar(255)        | √            |
| 5                                        | F_DutyID           | 任务名称  任务名称ID      | NVarChar(255)        | √            |
| 6                                        | F_SuccessTime      | 完成时间                  | NVarChar(255)        | √            |
| 7                                        | F_RunMen           | 执行人                    | NVarChar(255)        | √            |
| 8                                        | F_ReviewMen        | 复核人                    | NVarChar(255)        | √            |
| 9                                        | F_Reamark          | 备注                      | NVarChar(255)        | √            |
| 10                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 11                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 12                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 13                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 14                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 15                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 16                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 17                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 18                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 19                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 20                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_WorkContent(工作内容表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_Name             | 内容名称                  | NVarChar(255)        | √            |
| 4                                        | F_Content          | 工作内容                  | NVarChar(255)        | √            |
| 5                                        | F_WLID             | 任务名称 任务ID           | NVarChar(255)        | √            |
| 6                                        | F_STime            | 完成时间                  | DateTime             | √            |
| 7                                        | F_RunMen           | 执行人                    | NVarChar(255)        | √            |
| 8                                        | F_ReviewMen        | 复核人                    | NVarChar(255)        | √            |
| 9                                        | F_Reamark          | 备注                      | NVarChar(255)        | √            |
| 10                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 11                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 12                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 13                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 14                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 15                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 16                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 17                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 18                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 19                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 20                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_Staff(公司职员)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Name             | 姓名                      | NVarChar(255)        | √            |
| 3                                        | F_Account          | 登录帐号                  | NVarChar(255)        | √            |
| 4                                        | F_Position         | 职务                      | NVarChar(255)        | √            |
| 5                                        | F_WageBase         | 工资基数                  | Decimal              | √            |
| 6                                        | F_Phone            | 手机                      | NVarChar(255)        | √            |
| 7                                        | F_QQNum            | QQ                        | NVarChar(255)        | √            |
| 8                                        | F_MailBox          | 邮箱                      | NVarChar(255)        | √            |
| 9                                        | F_IDCard           | 身份证号                  | NVarChar(255)        | √            |
| 10                                       | F_BankCard         | 银行卡号                  | NVarChar(255)        | √            |
| 11                                       | F_EntryTime        | 入职时间                  | DateTime             | √            |
| 12                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 13                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 14                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 15                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 16                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 17                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 18                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 19                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 20                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 21                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 22                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_ProjectDocPath(项目文档文件路径表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_ProDocID         | 项目文档表ID 项目文档名称 | NVarChar(255)        | √            |
| 3                                        | F_Name             | 文件路径                  | NVarChar(255)        | √            |
| 4                                        | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 5                                        | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 6                                        | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 7                                        | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 8                                        | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 9                                        | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 10                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 11                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 12                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 13                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 14                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_ProjectDoc(项目文档表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_Name             | 文档名称                  | NVarChar(255)        | √            |
| 4                                        | F_Describe         | 文档描述                  | NVarChar(255)        | √            |
| 5                                        | F_ProID            | 项目名称ID                | NVarChar(255)        | √            |
| 6                                        | F_DataType         | 资料类型                  | NVarChar(255)        | √            |
| 7                                        | F_DocFormat        | 文档格式                  | NVarChar(255)        | √            |
| 8                                        | F_Founder          | 创建人                    | NVarChar(255)        | √            |
| 9                                        | F_Reamark          | 备注                      | NVarChar(255)        | √            |
| 10                                       | F_Html             | 项目文档html              | NVarChar(2147483647) | √            |
| 11                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 12                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 13                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 14                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 15                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 16                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 17                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 18                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 19                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 20                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 21                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_CompanyProjectDes(公司项目描述表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_ProjectID        | 项目名称 项目名称ID       | NVarChar(255)        | √            |
| 4                                        | F_Title            | 描述标题                  | NVarChar(255)        | √            |
| 5                                        | F_Create           | 创建人                    | NVarChar(255)        | √            |
| 6                                        | F_Duty             | 责任人                    | NVarChar(255)        | √            |
| 7                                        | F_Client           | 客户                      | NVarChar(255)        | √            |
| 8                                        | F_Reamark          | 备注                      | NVarChar(255)        | √            |
| 9                                        | F_Content          | 描述内容                  | NVarChar(255)        | √            |
| 10                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 11                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 12                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 13                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 14                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 15                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 16                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 17                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 18                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 19                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 20                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_CompanyProject(公司项目表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_ProjectName      | 计划名称                  | NVarChar(255)        | √            |
| 4                                        | F_Content          | 计划内容                  | Decimal              | √            |
| 5                                        | F_PlanID           | 计划名称 公司计划表ID     | NVarChar(255)        | √            |
| 6                                        | F_WorkHours        | 项目周期                  | NVarChar(255)        | √            |
| 7                                        | F_PlanCharge       | 项目收费                  | NVarChar(255)        | √            |
| 8                                        | F_Profit           | 项目利润                  | Decimal              | √            |
| 9                                        | F_StartTime        | 起始时间                  | DateTime             | √            |
| 10                                       | F_EndTime          | 终止时间                  | DateTime             | √            |
| 11                                       | F_Create           | 创建人                    | NVarChar(255)        | √            |
| 12                                       | F_Duty             | 责任人                    | NVarChar(255)        | √            |
| 13                                       | F_Status           | 状态                      | NVarChar(255)        | √            |
| 14                                       | F_Reamark          | 备注                      | NVarChar(255)        | √            |
| 15                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 16                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 17                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 18                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 19                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 20                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 21                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 22                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 23                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 24                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 25                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_CompanyPlan(公司计划表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_PlanName         | 计划名称                  | NVarChar(255)        | √            |
| 4                                        | F_PlanContent      | 计划内容                  | Decimal              | √            |
| 5                                        | F_WorkHours        | 计划工时                  | NVarChar(255)        | √            |
| 6                                        | F_PlanCharge       | 计划收费                  | NVarChar(255)        | √            |
| 7                                        | F_Profit           | 计划利润                  | NVarChar(255)        | √            |
| 8                                        | F_StartTime        | 起始时间                  | Decimal              | √            |
| 9                                        | F_EndTime          | 终止时间                  | Decimal              | √            |
| 10                                       | F_Create           | 创建人                    | NVarChar(255)        | √            |
| 11                                       | F_Duty             | 责任人                    | NVarChar(255)        | √            |
| 12                                       | F_Status           | 状态                      | NVarChar(255)        | √            |
| 13                                       | F_Score            | 计划评分                  | NVarChar(255)        | √            |
| 14                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 15                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 16                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 17                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 18                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 19                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 20                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 21                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 22                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 23                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 24                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |


## OA_Client(客户清单表)

| 编号                                     | 字段列名           | 字段描述                  | 数据类型             | 是否允许为空 |
|------------------------------------------|--------------------|---------------------------|----------------------|--------------|
| 1                                        | F_Id               | 主键                      | NVarChar(255)        |              |
| 2                                        | F_Num              | 编号                      | NVarChar(255)        | √            |
| 3                                        | F_Name             | 客户名称                  | NVarChar(255)        | √            |
| 4                                        | F_Company          | 客户公司                  | NVarChar(255)        | √            |
| 5                                        | F_Phone            | 手机                      | NVarChar(255)        | √            |
| 6                                        | F_QQNum            | QQ                        | NVarChar(255)        | √            |
| 7                                        | F_MailBox          | 邮箱                      | DateTime             | √            |
| 8                                        | F_Position         | 职务                      | DateTime             | √            |
| 9                                        | F_Reamark          | 备注                      | NVarChar(255)        | √            |
| 10                                       | F_AddTime          | 责任人                    | DateTime             | √            |
| 11                                       | F_Address          | 公司地址                  | DateTime             | √            |
| 12                                       | F_CreatorUserId    | 创建人                    | NVarChar(255)        | √            |
| 13                                       | F_DeleteUserId     | 更新人                    | NVarChar(255)        | √            |
| 14                                       | F_LastModifyUserId | 修改人                    | NVarChar(255)        | √            |
| 15                                       | F_CreatorTime      | 创建日期                  | DateTime             | √            |
| 16                                       | F_LastModifyTime   | 更新日期                  | DateTime             | √            |
| 17                                       | F_DeleteTime       | 删除日期                  | DateTime             | √            |
| 18                                       | F_DeleteMark       | 删除标识                  | Bit(1)               | √            |
| 19                                       | F_Data1            | 备用字段1                 | NVarChar(255)        | √            |
| 20                                       | F_Data2            | 备用字段2                 | NVarChar(255)        | √            |
| 21                                       | F_Data3            | 备用字段3                 | NVarChar(255)        | √            |
| 22                                       | F_Data4            | 备用字段4                 | NVarChar(255)        | √            |
