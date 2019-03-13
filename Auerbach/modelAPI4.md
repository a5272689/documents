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
	"name": "测试模型",
	"field": "testmodel",
	"classify_id": 10000,
	"namefields": ["c"],
	"uniqfields": ["c"],
	"fields": [{
		"field": "base_info",
		"formtype": "map",
		"name": "基础信息",
		"not_delete": true,
		"child_fields": [{
			"field": "a",
			"formtype": "radio",
			"ismust": false,
			"labels": [{
				"field": "1",
				"label": "单选1"
			}],
			"name": "单选框",
			"valtype": "string"
		}, {
			"field": "b",
			"formtype": "checkbox",
			"ismust": false,
			"labels": [{
				"field": "1",
				"label": "多选1"
			}, {
				"field": "2",
				"label": "多选2"
			}],
			"name": "多选框",
			"valtype": "stringlist"
		}, {
			"field": "c",
			"formtype": "input",
			"ismust": false,
			"name": "输入框",
			"valtype": "string"
		}, {
			"field": "d",
			"formtype": "text",
			"ismust": false,
			"name": "文本框",
			"valtype": "string"
		}, {
			"field": "e",
			"formtype": "inputnumber",
			"ismust": false,
			"name": "计数器",
			"valtype": "number"
		}, {
			"field": "f",
			"formtype": "select",
			"ismust": false,
			"labels": [{
				"field": "1",
				"label": "选择1"
			}, {
				"field": "2",
				"label": "选择2"
			}],
			"multiple": false,
			"name": "选择器",
			"valtype": "string"
		}, {
			"field": "g",
			"formtype": "switch",
			"ismust": false,
			"name": "开关",
			"valtype": "bool"
		}, {
			"field": "h",
			"formtype": "time",
			"ismust": false,
			"name": "时间",
			"valtype": "string"
		}, {
			"field": "i",
			"formtype": "date",
			"ismust": false,
			"name": "日期",
			"valtype": "string"
		}, {
			"field": "j",
			"formtype": "datetime",
			"ismust": false,
			"name": "时间日期",
			"valtype": "string"
		}]
	}, {
		"field": "fields2",
		"formtype": "list",
		"name": "列表组",
		"child_fields": [{
			"field": "jkjkl",
			"formtype": "checkbox",
			"ismust": false,
			"labels": [{
				"field": "11",
				"label": "aa"
			}, {
				"field": "22",
				"label": "bb"
			}],
			"name": "多选框组",
			"valtype": "stringlist"
		}, {
			"field": "dd",
			"formtype": "datetime",
			"ismust": false,
			"name": "时间日期2",
			"valtype": "string"
		}]
	}, {
		"field": "333",
		"formtype": "map",
		"name": "字段组",
		"child_fields": [{
			"field": "2",
			"formtype": "datetime",
			"ismust": false,
			"name": "时间日期3",
			"valtype": "string"
		}]
	}],
	"id": 10046
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
