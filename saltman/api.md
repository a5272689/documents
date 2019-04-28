# 1.1 同步执行
**path:** /api/v1/salt/module/job/sync                  
**method:** POST
#### 请求头：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| Content-Type      | 否 | application/json |
#### 请求体：
```
{
	"tgt":"node006-dev.novalocal",
	"fun":"cmd.run",
	"args":["pwd"],
	"kwargs":{"cwd":"/tmp"}
}
```
#### 返回值：
```
{
	"info": "",
	"status": 10,
	"data": {
		"node006-dev.novalocal": {
			"result": true,
			"ret": "/tmp"
		}
	},
	"result": true
}
```
# 1.2 异步执行
**path:** /api/v1/salt/module/job/async  
**method:** POST
#### 请求头：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| Content-Type      | 否 | application/json |
#### 请求体：
```
{
	"tgt":"node006-dev.novalocal",
	"fun":"cmd.run",
	"args":["pwd"],
	"kwargs":{"cwd":"/tmp"}
}
```                
#### 返回值：
```
{
	"info": "",
	"data": {
		"jid": "20190428152658474918",
		"minions": ["node006-dev.novalocal"]
	},
	"result": true
}
```
# 1.3 异步结果获取
**path:** /api/v1/salt/module/job/async  
**method:** GET
#### 参数：
| 参数        | 是否必须           | 值示例  |
| ------------- |:-------------:| -----:|
| jid      | 是 | 20190428152658474918 |                
#### 返回值(成功返回)：
```
{
	"info": "",
	"status": 10,
	"data": {
		"node006-dev.novalocal": {
			"result": true,
			"ret": "/tmp"
		}
	},
	"result": true
}
```
#### 返回值(执行中)：
```
{
	"info": "",
	"status": 5,
	"result": true
}
```
#### 返回值(失败返回)：
```
{
	"info": "jid:20190428153022340381 does not exist",
	"status": 0,
	"result": false
}
```