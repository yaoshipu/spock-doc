---
title: 当前用户
taxonomy:
    category: docs
---

* **URL:**

    `/api/user/overview`

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
        "username": "yaoshipu",
        "title": "",
        "name": "yaoshipu",
        "nickname": "",
        "email": "yaoshipu@qiniu.com",
        "roles": [
            "staff"
        ],
        "disabled": false,
        "manager": "",
        "team": "",
        "mobile": "",
        "mobile2": "",
        "office": "",
        "join_at": "0001-01-01T00:00:00Z",
        "number": 0,
        "nation": "",
        "created_at": "0001-01-01T00:00:00Z",
        "updated_at": "2017-02-20T21:18:07.853+08:00",
        "last_active_ip": "127.0.0.1",
        "last_active_at": "2017-02-20T17:19:17.171+08:00",
        "parents": []
    }
    ```

* **Error Response:**

	**Code:** `500`
  	
  	**Content:** `{ "message" : "InvaInternal Error", "code": "500", "description": "error details"}`