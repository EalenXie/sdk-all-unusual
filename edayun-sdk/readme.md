edayun-sdk
======

主要是封装了 易达云 [EDA开放平台接入规范文档(V1.2.8)20220817 暂无 接口

### 快速开始

#### `pom.xml`配置

```xml

<dependency>
    <groupId>io.github.ealenxie</groupId>
    <artifactId>edayun-sdk</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

#### [EdayunClient](https://github.com/EalenXie/sdk-all-unusual/blob/main/edayun-sdk/src/main/java/io/github/ealenxie/edayun/EdayunClient.java)  已支持的接口列表

| 接口名            | 方法名                     | 官方文档地址 | 状态  |
|:---------------|:------------------------|:-------|:----|
| wms-创建订单       | createOrderEx           | 暂无     | ✔️  |
| wms-取消订单       | cancelOrder             | 暂无     | ✔️  |
| wms-查询订单       | getOrderInfoByIdEx      | 暂无     | ✔️  |
| wms-批量查询订单     | getOrders               | 暂无     | ✔️  |
| wms-创建产品       | createProduct           | 暂无     | ✔️  |
| wms-库存汇总查询扩展接口 | queryInventoryEx        | 暂无     | ✔️  |
| wms-库存流水接口     | queryInventoryHistory   | 暂无     | ✔️  |
| wms-产品锁库存接口    | lockInventory           | 暂无     | ✔️  |
| wms-产品解锁库存接口   | unLockInventory         | 暂无     | ✔️  |
| wms-库存查询新接口    | queryInventoryV2        | 暂无     | ✔️  |
| wms-查询产品库龄     | searchInventoryAge      | 暂无     | ✔️  |
| wms-获取公共仓库列表   | listPublicWarehouseInfo | 暂无     | ✔️  |
