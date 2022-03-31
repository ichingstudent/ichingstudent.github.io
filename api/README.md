# web service 的全部API的全部说明

## private USER 用户管理 API
### USER_CREATE (mobile/email/nickname, password)
1. 创建一个新用户，并设置密码
2. 用户名和ID，用户不可见，不可修改 （系统备用）
3. mobile/email/昵称 必须唯一
4. 正则表达式自动判断 用户输入的是昵称还是手机号或email，并自动填写相应字段。
  - 如果没有输入昵称， 系统会自动生成一个
  - 昵称，可以修改，可以是中文

### private USER_SET_NICKNAME()



## OAUTH TOKEN API
