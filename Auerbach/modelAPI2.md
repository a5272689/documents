# 1.1. 模型关系获取
**path:** /auerbach/api/v1/modelrelations                   
**method:** GET
#### 参数：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| id      | 是 | 10000 |
#### 返回值：
```
{
    "result": true,
    "info": "获取成功",
    "data": [
        {
            "id": 10000,
            "source_model_id": 10000,
            "target_model_id": 10001,
            "idescribe": "运行",
            "term": "1to1"
        }
    ]
}
```
