---
title: 删除产品模板
taxonomy:
    category: docs
---

- 需要管理员权限

* **URL:**

    `/api/templates/products/:productName`

* **Method:**

    `DELETE`

* **URL Params:**

    `None`

* **Data Params:**

    `None`

* **Success Response:**

	**Code:** `200`

* **Error Response:**

	**Code:** `613`
  	
  	**Content:** `{ "message" : "Delete Template Error", "code": "613", "description": "error details"}`