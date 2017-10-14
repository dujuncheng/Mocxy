### user相关接口定义

>1、登陆user相关信息

#### 接口

POST /user/login

#### Request

```js
{
    email: 'xxxx',
    password: 'xxxx'
}
```

#### Response

```js
{
    message: '登陆成功～',
}
```

>2、注册user相关信息

#### 接口

POST /user/register

#### Request

```js
{
    email: 'xxxxx',
    password: 'xxxx',
    confirm: 'xxx'
}
```

#### Response

```js
{
    message: '恭喜你注册成功了～'
}
```