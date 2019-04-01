## 1. 登录
接口地址：Systems/System/LoginForHFAX
请求方式：post
入参列表：

| 参数名| 参数类型|  是否必传| 备注|
| --------- | -------- | -----: | --: |
| userName    | String  | 是 |  用户名 |
| password| String  |   是 |  密码 |

返回参数列表

| 参数名| 参数类型|  备注|
| --------- | -------- | -----: | --: |
| Code| integer| 1 = 请求成功 2 = 请求异常 |
| Message| string| 请求信息\异常信息 |


## 2. 客户号换手机号
接口地址：Customers/Customer/GetCustomerMobile
请求方式：Post
入参列表：
| 参数名| 参数类型|  是否必传| 备注|
| --------- | -------- | -----: | --: |
| customerId| String  | 是 |  客户号 |

返回参数列表

| 参数名| 参数类型|  备注|
| --------- | -------- | -----: | --: |
| Code| integer| 1 = 请求成功 2 = 请求异常 |
| Message| string| 请求信息\异常信息 |
| Data| string| 手机号 |


## 3. 手机号换客户号
接口地址：Customers/Customer/GetCustomerIdByMobile
请求方式：Post
入参列表：
| 参数名| 参数类型|  是否必传| 备注|
| --------- | -------- | -----: | --: |
| Mobile| String  | 是 |  手机号 |

返回参数列表

| 参数名| 参数类型|  备注|
| --------- | -------- | -----: | --: |
| Code| integer| 1 = 请求成功 2 = 请求异常 |
| Message| string| 请求信息\异常信息 |
| Data| string| 客户Id |



