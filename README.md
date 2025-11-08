# 前言

随着新冠疫情的全球蔓延，抗疫用品需求激增。为了满足市场需求，我们开发了基于SSM（Spring、SpringMVC、MyBatis）的抗疫用品销售平台。本项目致力于为用户提供一个方便、快捷、安全的在线购物环境，让用户能够轻松购买到所需的抗疫用品。

# 内容介绍

基于SSM的抗疫用品销售平台主要包括以下功能模块：

1. 用户模块：注册、登录、修改个人信息等；
2. 商品模块：浏览商品、搜索商品、查看商品详情、加入购物车、下单购买等；
3. 订单模块：查看订单、支付订单、取消订单等；
4. 购物车模块：添加商品、删除商品、修改商品数量等；
5. 后台管理模块：商品管理、订单管理、用户管理等。

# 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12/14/16

# 核心代码

以下是一段关于商品搜索功能的核心代码：

```java
// 商品搜索接口
@RequestMapping(value = "/search", method = RequestMethod.GET)
public ResponseEntity<List<Product>> searchProduct(@RequestParam("keyword") String keyword) {
    List<Product> productList = productService.search(keyword);
    if (productList == null || productList.isEmpty()) {
        return new ResponseEntity<>(HttpStatus.NOT_FOUND);
    }
    return new ResponseEntity<>(productList, HttpStatus.OK);
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/345022/29/1573/116325/68c05ca2Fef193f35/dace5fdb4899536f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/331439/24/11375/24860/68c05c7eFe5554300/3225d08cbf66dac6.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/344952/32/1503/58710/68c05c7fF320c65c2/d1758b9d2781cecb.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/349782/4/1521/44982/68c05c80F4c08c6e5/ae0958d27e0df9ba.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324746/37/18255/77972/68c05c82Fa12c70c2/c908e2c84b22fd4d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325379/40/17745/30423/68c05c82F8a775c45/ed9e2263856810a0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329992/3/11288/22866/68c05c83Fe5b42277/ac1d1184c4509f33.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/335949/3/8851/27313/68c05c83F5096988e/5015bd3a2cb152a3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/341787/38/1522/65442/68c05c84F818a8b86/f1fcad83cff88176.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328734/24/17805/50052/68c05c84F875733ab/bc3966a55c6eef7e.jpg)

