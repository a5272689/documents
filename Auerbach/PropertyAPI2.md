# 1.1. 资产关系获取
**path:** /api/v1/propertyrelations
**method:** GET
#### 参数：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| id      | 是 | kRkUXmQBuPAr9qPqSpJW |
| index      | 是 | testmodel |
#### 返回值：
```
{
    "result": true,
    "info": "",
    "data": [
        {
            "id": 10000,
            "source_property_id": "kRkUXmQBuPAr9qPqSpJW",
            "source_property_data": {
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
            },
            "target_property_id": "NNLFi2YBHhd-Km3cRrxv",
            "target_property_data": {
                "id": "NNLFi2YBHhd-Km3cRrxv",
                "index": "model2",
                "data": {
                    "testfield1": "test21"
                }
            },
            "relation_id": 10000,
            "tags": ""
        }
    ]
}
```