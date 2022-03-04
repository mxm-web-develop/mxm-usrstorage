### MxM User LocalStorage 用户信息，Token本地存储管理

#### install
 `yarn add @mxm/usrstorage` or `npm i @mxm/usrstorage`

#### 版本信息
- v.1.0.0 实现本地快速存储，更新用户信息，支持ts

----------------------------------------------------------------

#### setStore() 
    设置用户信息，一般在请求获取token后调用，可以设置token过期时间

#### getStore()
    获取用户信息，在需要token或者用户资料的时候调用

#### updateUserInfo()
    更新用户信息结构体中的部分信息