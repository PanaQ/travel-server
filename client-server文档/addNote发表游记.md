**简要描述** 
- addNote发表游记

**版本信息**
- 1.0

**请求URL** 
- `/note/addNote `

**参数** 

|参数名|必选|类型|说明|
|:---- |:---   |:---|:----- |
|title |是 | String | 游记title |
|content |是 | String | 游记内容 |

**请求示例**

```JSON
{
    "reqId": "14343543543254",
    "timestamp": 1501731917705,
    "param": {
    	"title":1,
    	"content":"aaa"
    }
}
```



 **返回示例**

```JSON
{
    "code": 0,
    "message": "ok",
    "reqId": "14343543543254",
    "result": null
}
```

