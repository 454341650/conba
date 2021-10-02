# 协助文档
## 基础约定
* 1.入参

	@RequestBody String body,
	
	公共参数 
	{
		"timestamp":时间戳 System.currentTimeMillis();
		"app_key":
		"sign":
		--其他
	}
* 2.返回值
``` 

	{
		"code":200, //200 成功  100 失败 
		"msg":"成功" //返回提示信息
		"data":object //数据
	}

```
## 登录接口 
	地址 ：   POST https://img.zc511.com/getway/v1/login_auth_verification.shtml
![avatar](https://img.zc511.com/pic/1f57178ec479a2015b9488891441776.png)

## 商品列表获取
	地址 ：   POST https://img.zc511.com/getway/v1/goodslist_get.shtml
	入参 {"pageNum":"1","pageSize":"5","buyerCode":"33300098"}
	
## 加入购物车
	地址 ：   POST https://img.zc511.com/getway/v1/shoppingcart_add.shtml
	入参 {"productCode":"1","amount":"5","buyerCode":"33300098"}
	
## 生成订单
	地址 ：   POST https://img.zc511.com/getway/v1/order_create.shtml
	入参 {"shoppingcartId":"1","buyerCode":"33300098"}
		
## 红包冲入
	地址 ：   POST https://img.zc511.com/getway/v1/red_envelopes_fill.shtml	
	入参 {"couponId":"1","buyerCode":"33300098"}
	
## 优惠劵列表获取
	地址 ：   POST https://img.zc511.com/getway/v1/couponlist_get.shtml
	入参 {"pageNum":"1","pageSize":"5","buyerCode":"33300098"}
	
## 优惠劵发放
	地址 ：   POST https://img.zc511.com/getway/v1/coupon_give.shtml
	入参 {"couponId":"1","buyerCode":"33300098"}



 

