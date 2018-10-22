# 1.1. 资产获取
**path:** /auerbach/api/v1/propertys
**method:** GET
#### 参数：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| id      | 否 | kRkUXmQBuPAr9qPqSpJW |
| index      | 是 | testmodel |
#### 返回值不带id：
```
{
    "result": true,
    "info": "",
    "data": {
        "total": 3,
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
            },
            {
                "id": "jM8j4GQBxzUSjpe3yp8o",
                "index": "testmodel",
                "data": {
                    "a": "22",
                    "testfield": "1",
                    "testfilegroup": [
                        {
                            "t": "1",
                            "t2": "a"
                        },
                        {
                            "t": "4",
                            "t2": "b"
                        }
                    ]
                }
            },
            {
                "id": "jc8j4GQBxzUSjpe305_m",
                "index": "testmodel",
                "data": {
                    "a": "2",
                    "testfield": "2",
                    "testfilegroup": [
                        {
                            "t": "2",
                            "t2": "b"
                        }
                    ]
                }
            }
        ]
    }
}
```
#### 返回值带id：
```
{
    "result": true,
    "info": "",
    "data": {
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
}
```