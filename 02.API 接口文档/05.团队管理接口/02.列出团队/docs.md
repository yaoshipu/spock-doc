---
title: 列出团队
taxonomy:
    category: docs
---

* **URL:**

    `/api/teams`

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
    [
        {
            "name": "CIA",
            "leader": "Json Bourne",
            "description": "agent",
            "creator": "yaoshipu",
            "updated_at": "2017-02-20T15:47:38.414+08:00"
        }
    ]
    ```

* **Error Response:**

	**Code:** `615`
  	
  	**Content:** `{ "message" : "List Team Error", "code": "615", "description": "error details"}`