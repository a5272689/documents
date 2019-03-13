# 2.1. 资产获取
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
		"total": 68,
		"propertys": [{
			"id": "AWLMioJTJBgdH4ikWgaR",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"disks\":[],\"hostname\":\"jenkins-dev.novalocal\",\"interfaces\":[],\"is_online\":true}",
				"_id": "AWLMioJTJBgdH4ikWgaR",
				"alive": false,
				"disks": [],
				"hostname": "jenkins-dev.novalocal",
				"interfaces": [],
				"is_online": true
			}
		}, {
			"id": "AWLMioLlJBgdH4ikWj0u",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"hostname\":\"bigdata003-dev.novalocal\"}",
				"_id": "AWLMioLlJBgdH4ikWj0u",
				"alive": false,
				"hostname": "bigdata003-dev.novalocal",
				"is_online": true
			}
		}, {
			"id": "AWLMioOIJBgdH4ikWnAl",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"hostname\":\"bigdata006-dev.novalocal\"}",
				"_id": "AWLMioOIJBgdH4ikWnAl",
				"alive": false,
				"hostname": "bigdata006-dev.novalocal",
				"is_online": true
			}
		}, {
			"id": "AWLMioPoJBgdH4ikWnja",
			"index": "server",
			"data": {
				"_data": "{\"alive\":true,\"biosversion\":\"1.9.1-5.el7\",\"cpuarch\":\"x86_64\",\"cpumodel\":\"Common KVM processor\",\"disks\":[{\"filesystem\":\"/dev/vda1\",\"path\":\"/\",\"total\":186.73364639282227},{\"filesystem\":\"tmpfs\",\"path\":\"/dev/shm\",\"total\":7.7884979248046875}],\"hostname\":\"app003-dev.novalocal\",\"interfaces\":[{\"hwaddr\":\"00:00:00:00:00:00\",\"ip\":\"127.0.0.1\",\"name\":\"lo\"},{\"hwaddr\":\"fa:16:3e:d5:08:16\",\"ip\":\"192.168.11.38\",\"name\":\"eth0\"}],\"kernel\":\"Linux\",\"kernelrelease\":\"2.6.32-504.el6.x86_64\",\"memtotal\":15950,\"numcpus\":8,\"os\":\"CentOS\",\"osarch\":\"x86_64\",\"osfamily\":\"RedHat\",\"osrelease\":\"6.8\",\"serialnumber\":\"9109ae38-066a-46eb-8058-4f8c492e52ae\",\"uuid\":\"ba5f32c8-09bb-4a67-a9ae-c2757a90f712\"}",
				"_id": "AWLMioPoJBgdH4ikWnja",
				"alive": true,
				"biosversion": "1.9.1-5.el7",
				"cpuarch": "x86_64",
				"cpumodel": "Common KVM processor",
				"disks": [{
					"filesystem": "/dev/vda1",
					"path": "/",
					"total": 186.73364639282227
				}, {
					"filesystem": "tmpfs",
					"path": "/dev/shm",
					"total": 7.7884979248046875
				}],
				"hostname": "app003-dev.novalocal",
				"interfaces": [{
					"hwaddr": "00:00:00:00:00:00",
					"ip": "127.0.0.1",
					"name": "lo"
				}, {
					"hwaddr": "fa:16:3e:d5:08:16",
					"ip": "192.168.11.38",
					"name": "eth0"
				}],
				"is_online": true,
				"kernel": "Linux",
				"kernelrelease": "2.6.32-504.el6.x86_64",
				"memtotal": 15950,
				"numcpus": 8,
				"os": "CentOS",
				"osarch": "x86_64",
				"osfamily": "RedHat",
				"osrelease": "6.8",
				"serialnumber": "9109ae38-066a-46eb-8058-4f8c492e52ae",
				"uuid": "ba5f32c8-09bb-4a67-a9ae-c2757a90f712"
			}
		}, {
			"id": "AWLMioQhJBgdH4ikWoTz",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"hostname\":\"app016-dev.novalocal\"}",
				"_id": "AWLMioQhJBgdH4ikWoTz",
				"alive": false,
				"hostname": "app016-dev.novalocal",
				"is_online": true
			}
		}, {
			"id": "AWLMioXWJBgdH4ikWu7d",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"hostname\":\"app017-dev.novalocal\"}",
				"_id": "AWLMioXWJBgdH4ikWu7d",
				"alive": false,
				"hostname": "app017-dev.novalocal",
				"is_online": true
			}
		}, {
			"id": "AWLMioXfJBgdH4ikWu7e",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"hostname\":\"app012-dev.novalocal\"}",
				"_id": "AWLMioXfJBgdH4ikWu7e",
				"alive": false,
				"hostname": "app012-dev.novalocal",
				"is_online": true
			}
		}, {
			"id": "AWLMioZPJBgdH4ikWv3E",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"hostname\":\"bigdata001-dev.novalocal\"}",
				"_id": "AWLMioZPJBgdH4ikWv3E",
				"alive": false,
				"hostname": "bigdata001-dev.novalocal",
				"is_online": true
			}
		}, {
			"id": "AWLMiodVJBgdH4ikWyER",
			"index": "server",
			"data": {
				"_data": "{\"alive\":true,\"biosversion\":\"1.9.1-5.el7_3.2\",\"cpuarch\":\"x86_64\",\"cpumodel\":\"Common KVM processor\",\"disks\":[{\"filesystem\":\"/dev/vda1\",\"path\":\"/\",\"total\":186.733642578125},{\"filesystem\":\"tmpfs\",\"path\":\"/dev/shm\",\"total\":7.7884979248046875}],\"hostname\":\"app006-dev.novalocal\",\"interfaces\":[{\"hwaddr\":\"00:00:00:00:00:00\",\"ip\":\"127.0.0.1\",\"name\":\"lo\"},{\"hwaddr\":\"fa:16:3e:8c:61:32\",\"ip\":\"192.168.11.54\",\"name\":\"eth0\"}],\"kernel\":\"Linux\",\"kernelrelease\":\"2.6.32-504.el6.x86_64\",\"memtotal\":15950,\"numcpus\":8,\"os\":\"CentOS\",\"osarch\":\"x86_64\",\"osfamily\":\"RedHat\",\"osrelease\":\"6.8\",\"serialnumber\":\"532065ce-bd08-47b7-a306-35a24633b20a\",\"uuid\":\"2f55b3a3-27e4-41ca-937b-69065bf211b1\"}",
				"_id": "AWLMiodVJBgdH4ikWyER",
				"alive": true,
				"biosversion": "1.9.1-5.el7_3.2",
				"cpuarch": "x86_64",
				"cpumodel": "Common KVM processor",
				"disks": [{
					"filesystem": "/dev/vda1",
					"path": "/",
					"total": 186.733642578125
				}, {
					"filesystem": "tmpfs",
					"path": "/dev/shm",
					"total": 7.7884979248046875
				}],
				"hostname": "app006-dev.novalocal",
				"interfaces": [{
					"hwaddr": "00:00:00:00:00:00",
					"ip": "127.0.0.1",
					"name": "lo"
				}, {
					"hwaddr": "fa:16:3e:8c:61:32",
					"ip": "192.168.11.54",
					"name": "eth0"
				}],
				"is_online": true,
				"kernel": "Linux",
				"kernelrelease": "2.6.32-504.el6.x86_64",
				"memtotal": 15950,
				"numcpus": 8,
				"os": "CentOS",
				"osarch": "x86_64",
				"osfamily": "RedHat",
				"osrelease": "6.8",
				"serialnumber": "532065ce-bd08-47b7-a306-35a24633b20a",
				"uuid": "2f55b3a3-27e4-41ca-937b-69065bf211b1"
			}
		}, {
			"id": "AWLMiolEJBgdH4ikWz3t",
			"index": "server",
			"data": {
				"_data": "{\"alive\":false,\"biosversion\":\"1.9.1-5.el7_3.2\",\"cpuarch\":\"x86_64\",\"cpumodel\":\"Common KVM processor\",\"disks\":[{\"filesystem\":\"/dev/vda1\",\"path\":\"/\",\"total\":186.733642578125},{\"filesystem\":\"tmpfs\",\"path\":\"/dev/shm\",\"total\":7.7884979248046875}],\"hostname\":\"app008-dev.novalocal\",\"interfaces\":[{\"hwaddr\":\"00:00:00:00:00:00\",\"ip\":\"127.0.0.1\",\"name\":\"lo\"},{\"hwaddr\":\"fa:16:3e:45:f4:60\",\"ip\":\"192.168.11.60\",\"name\":\"eth0\"}],\"kernel\":\"Linux\",\"kernelrelease\":\"2.6.32-504.el6.x86_64\",\"memtotal\":15950,\"numcpus\":8,\"os\":\"CentOS\",\"osarch\":\"x86_64\",\"osfamily\":\"RedHat\",\"osrelease\":\"6.8\",\"serialnumber\":\"28e79457-c114-4d25-8093-d01886abb70d\",\"uuid\":\"1f6e8519-4b94-4ef8-aa2f-b417bef6c47c\"}",
				"_id": "AWLMiolEJBgdH4ikWz3t",
				"alive": false,
				"biosversion": "1.9.1-5.el7_3.2",
				"cpuarch": "x86_64",
				"cpumodel": "Common KVM processor",
				"disks": [{
					"filesystem": "/dev/vda1",
					"path": "/",
					"total": 186.733642578125
				}, {
					"filesystem": "tmpfs",
					"path": "/dev/shm",
					"total": 7.7884979248046875
				}],
				"hostname": "app008-dev.novalocal",
				"interfaces": [{
					"hwaddr": "00:00:00:00:00:00",
					"ip": "127.0.0.1",
					"name": "lo"
				}, {
					"hwaddr": "fa:16:3e:45:f4:60",
					"ip": "192.168.11.60",
					"name": "eth0"
				}],
				"is_online": true,
				"kernel": "Linux",
				"kernelrelease": "2.6.32-504.el6.x86_64",
				"memtotal": 15950,
				"numcpus": 8,
				"os": "CentOS",
				"osarch": "x86_64",
				"osfamily": "RedHat",
				"osrelease": "6.8",
				"serialnumber": "28e79457-c114-4d25-8093-d01886abb70d",
				"uuid": "1f6e8519-4b94-4ef8-aa2f-b417bef6c47c"
			}
		}]
	}
}
```
#### 返回值带id：
```
{
	"result": true,
	"info": "",
	"data": {
		"id": "AWLMioJTJBgdH4ikWgaR",
		"index": "server",
		"data": {
			"_data": "{\"alive\":false,\"disks\":[],\"hostname\":\"jenkins-dev.novalocal\",\"interfaces\":[],\"is_online\":true}",
			"_id": "AWLMioJTJBgdH4ikWgaR",
			"alive": false,
			"disks": [],
			"hostname": "jenkins-dev.novalocal",
			"interfaces": [],
			"is_online": true
		}
	}
}
```