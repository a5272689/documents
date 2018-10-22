# 1.1. 资产新增
**path:** /auerbach/api/v1/propertys    
**method:** POST
#### 请求头：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| Content-Type      | 否 | application/json |
#### 请求体：
```
{
  "index":"testmodel",
  "data":{
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
```
#### 参数：
#### 返回值：
```
{
    "result": true,
    "info": ""
}
```