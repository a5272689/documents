# 1.6. 模型关系新增
**path:** /auerbach/api/v1/modelrelations                   
**method:** POST
#### 请求头：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| Content-Type      | 否 | application/json |
#### 请求体：
```
{
	"idescribe": "运行",
	"source_model_id": 10000,
	"target_model_id": 10001,
	"term": "1to1"
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
