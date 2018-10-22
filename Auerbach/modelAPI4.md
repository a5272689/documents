# 1.4. 模型更新
**path:** /auerbach/api/v1/models                   
**method:** PUT
#### 请求头：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| Content-Type      | 否 | application/json |
#### 请求体：
```
{
    "id": 10002,
	"classify_id": 10002,
	"field": "testmodel3",
	"fields": [{
		"name": "测试字段1",
		"field": "testField1",
		"valtype": "keyword",
		"unit": ""
	}],
	"mapping": {
		"testField1": {
			"type": "keyword"
		}
	},
	"name": "测试模型3",
	"namefields": ["testField1"],
	"show_fields": ["testField1"],
	"uniqfields": ["testField1"],
}
```
#### 参数：
#### 返回值：
```
{
    "result": true,
    "info": ""
}
```
