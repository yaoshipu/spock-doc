---
title: 获取服务组模板
taxonomy:
    category: docs
---

* **URL:**

    `/api/templates/stacks/:stackName`

* **Method:**

    `GET`

* **URL Params:**

    `None`

* **Data Params:**

    `None`

* **Success Response:**

	**Code:** `200`

	**Content:** 
	
	```
	{
		"stack_name": "stack-1",
		"internal": false,
		"services": [
			{
			"service_name": "service-1",
			"image": {
				"name": "service-1",
				"tag": "test"
			},
			"unit_type": "1U1G",
			"command": [
				"ls"
			],
			"config_paths": [
				"/disk1"
			],
			"volume_args": [
				{
				"unit_type": "SSD1_10G",
				"mount_path": "/disk1"
				}
			],
			"access_point": {
				"type": "domain",
				"proto": "",
				"ap_ports": [],
				"backend_ports": [
				25000
				]
			},
			"test": {
				"command": "",
				"result_path": ""
			}
			}
		],
		"init_scripts": [
			{
			"service_name": "service-1",
			"commands": []
			}
		]
	}
	```	

* **Error Response:**

	**Code:** `612`
  	
  	**Content:** `{ "message" : "Get Template Error", "code": "612", "description": "error details"}`