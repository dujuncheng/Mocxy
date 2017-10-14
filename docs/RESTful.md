# RESTful API HTTP Status Code

> 1、GET

### Success
- 200 OK，正常获取数据
### Fail
- 400 Bad Request，格式正确但是存在某些原因使得调用接口失败
- 404 Not Found，请求的数据不存在
- 406 Not Acceptable，请求的格式不正确

> 2、POST
### Success
- 201 Created，新建数据成功
### Fail
- 400 Bad Request，格式正确但是存在某些原因使得调用接口失败
- 406 Not Acceptable，请求格式不正确

> 3、PUT
### Success
- 201 Created，更新数据成功
### Fail
- 400 Bad Request，格式正确但是存在某些原因使得调用接口失败
- 404 Not Found，更新的数据不存在
- 406 Not Acceptable，请求格式不正确

> 4、DELETE
### Success
- 204 No Content，删除数据成功
### Fail
- 400 Bad Request，格式正确但是存在某些原因使得调用接口失败
- 404 Not Found，需要删除的数据不存在
- 406 Not Acceptable，请求格式不正确