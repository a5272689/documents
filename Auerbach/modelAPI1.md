# 1.1. 模型获取
**path:** /auerbach/api/v1/models
**method:** GET
#### 参数：
#### 返回值：
```
{
    "result": true,
    "info": "",
    "data": [
        {
            "id": 10000,
            "name": "测试模型",
            "field": "testmodel",
            "classify_id": 10002,
            "namefields": [
                "testfield"
            ],
            "uniqfields": [
                "testfield"
            ],
            "fields": [
                {
                    "field": "testfield",
                    "name": "测试字段",
                    "unit": "",
                    "valtype": "keyword"
                },
                {
                    "field": "a",
                    "name": "测试字段1",
                    "unit": "",
                    "valtype": "text"
                },
                {
                    "countfield": "t",
                    "countway": "count",
                    "field": "testfilegroup",
                    "fields": [
                        {
                            "field": "t",
                            "name": "t",
                            "unit": "",
                            "valtype": "long"
                        }
                    ],
                    "name": "测试字段zu1",
                    "valtype": "nested"
                }
            ],
            "show_fields": [
                "b",
                "c",
                "testfield",
                "a"
            ],
            "mapping": null
        }
    ]
}
```
