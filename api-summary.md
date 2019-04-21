# CBBB API Summary (alpha version)

## 商家类
0. /merchants 商户列表，支持各类筛选条件
1. /merchants/:id 商户基本信息
2. /merchants/:id/registration-info 工商注册信息

## 用户类

1. /authentication/login 登录
2. /authentication/logout 退出
3. /authentication/register 注册
4. /authentication/sms 短信
5. /users/:id/info 用户信息
6. /users/:id/realname-authentication/zmxy 芝麻信用实名认证状态

## 通知类

1. /notifications 通知列表
2. /notifications/:id 单个通知

## 投诉类

1. /complaints/configuration
1. /complaints?mid=xxx || uid=xxx 投诉列表
4. /complaints/:id 单个投诉信息
5. /complaints/:id/comment 投诉回复
6. /complaints/:id/relevant-complaints 关联/历史投诉
6. /complaints POST 新建投诉
7. /complaints/:id/audition  投诉审核

## 其他

1. /feedbacks 反馈列表
2. /feedbacks/:id 单个反馈
3. /search 模糊搜索
