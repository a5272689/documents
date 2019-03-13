# 2.2. 资产关系获取
**path:** /auerbach/api/v1/propertyrelations             
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
	"data": [{
		"id": 10315,
		"source_property_id": "5c2dc564884cdb381e83f8c5",
		"source_property_data": {
			"id": "5c2dc564884cdb381e83f8c5",
			"index": "redisinfo",
			"data": {
				"_id": "5c2dc564884cdb381e83f8c5",
				"configpath": "/home/redis",
				"datadirpath": "/home/redis",
				"env": "pro",
				"group": "order",
				"is_online": true,
				"logfilepath": "/home/redis",
				"master_slave": [{
					"masterhost": "common001",
					"slave2host": "common003",
					"slavehost": "common002"
				}, {
					"masterhost": "common003",
					"slave2host": "",
					"slavehost": "common002"
				}],
				"maxclients": "1000",
				"maxmemory": "8",
				"password": "123456",
				"port": "6379",
				"redis_type": "cluster",
				"redisname": "wxh-test",
				"region": "阿里云-华东1-可用区E",
				"slowlog": "10",
				"version": "3.2.3"
			}
		},
		"target_property_id": "AWLMioJTJBgdH4ikWgaR",
		"target_property_data": {
			"id": "AWLMioJTJBgdH4ikWgaR",
			"index": "server",
			"data": {
				"_id": "AWLMioJTJBgdH4ikWgaR",
				"alive": false,
				"disks": [],
				"hostname": "jenkins-dev.novalocal",
				"interfaces": [],
				"is_online": true
			}
		},
		"relation_id": 10010,
		"model_relation": {
			"id": 10010,
			"source_model_id": 10024,
			"target_model_id": 10000,
			"idescribe": "对应服务器",
			"term": "1ton"
		},
		"tags": "",
		"is_active": false,
		"user_code": "04141",
		"user_name": "黄金叠",
		"create_time": "2019-03-13T15:50:44+08:00",
		"update_time": "2019-03-13T15:50:44+08:00"
	}]
}
```