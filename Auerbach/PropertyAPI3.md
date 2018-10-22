# 1.1. 资产搜索
**path:** /auerbach/api/v1/searchproperty    
**method:** GET
#### 参数：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| query      | 否 | testfield:222 |
| index      | 是 | testmodel |
| sort      | 否 |  |
| order      | 否 |  |
| from      | 否 | 0 |
#### 返回值：
```
{
    "result": true,
    "info": "",
    "data": {
        "total": 1,
        "propertys": [
            {
                "id": "kRkUXmQBuPAr9qPqSpJW",
                "index": "testmodel",
                "data": {
                    "a": "22",
                    "b": "22",
                    "c": "22",
                    "d": "22",
                    "e": "22",
                    "f": "22",
                    "g": "22",
                    "h": "22",
                    "testfield": "222"
                }
            }
        ]
    }
}
```