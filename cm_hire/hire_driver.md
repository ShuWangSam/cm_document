##司机申请表格申请API参数

| Tables |  说明 |  默认值|
| :-------------:| :-----:|:-----:|
| URL | 　https://www.chanmao.ca/index.php?r=Site/ApplyDriver ||
| HTTP请求方式 | POST |  |
| 是否需要登录 | 否 |  |
| 授权访问限制 | 暂无 |  |
| 授权范围() | 暂无 | |
| 支持格式 | JSON | |


表头参数:

| Tables | 类型及其范围 | 说明 |  默认值|
| -------------|-------------| -----|-----|
| Authortoken | string | token验证信息 |hire_driver_chanmao_inc|

请求参数:


| Tables | 类型及其范围 | 说明 |  默认值|
| ------------- |-------------| -----|-----|
| driver_information | string | 申请司机信息表格(HTML) ||





返回字段说明:

| Tables | 类型及其范围 | 说明 |  默认值|
| ------------- |-------------|-----|-----|
| ev_result | number |  请求是否成功|0为成功, 1为错误|
| ev_message | string | 报错信息 | 空|

返回结果(默认JSON):
```
{
    result: number,
    message: string
}
```

