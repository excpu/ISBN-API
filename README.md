# ISBN-API
通过ISBN查询书本的基本信息

## API 接口
https://apis.5share.site/books/?isbn=ISBN

## 示例
https://apis.5share.site/books/?isbn=9787544790888
![图片](https://github.com/user-attachments/assets/f17e8763-61ff-4d42-8778-598e2a8a6fa5)

## 参数解析
### isbn
支持一下各种类型的输入  
10位ISBN  
13位ISBN  
**ISBN中包含的横线“-”不会影响返回结果**

## 身份验证
暂时无需验证

## 注意事项
### 请求
#### 速率限制
每10秒限制50个请求，超过限制IP关小黑屋10秒
### 返回内容
ISBN最后一位为验证位，如果输入ISBN验证位不正确，返回的ISBN会通过计算修正错误的ISBN
例子：  
请求URL：https://apis.5share.site/books/?isbn=9787544722761  
返回内容  
![图片](https://github.com/user-attachments/assets/da58960d-b118-4292-b37a-8a46a53a4f0a)



# 状态更新
2025.3.11 API 升级期间，查得率可能降低  
2025.3.19 NODE JS 重写完成  
2025.3.19 API 状态已完全恢复


