---
title: 查询Pipeline
taxonomy:
    category: docs
---

* **URL:**

    `/api/pipelines`

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
        "pipeline_name": "pipeline-1",
        "creator": "yaoshipu",
        "stack_name": "stack-1",
        "servive_name": "service-1",
        "test_stack": "test1",
        "test_service": "doratest",
        "test_env": "spock",
        "repo_owner": "yaoshipu",
        "repo_name": "aslan-platform",
        "run_build": true,
        "run_deploy": true,
        "run_test": true,
        "run_distribute": true,
        "updated": "2017-02-21T18:58:13.355+08:00",
        "enabled": true
    }
	```	

* **Error Response:**

	**Code:** `682`
  	
  	**Content:** `{ "message" : "Get Pipeline Error", "code": "682", "description": "error details"}`