sellersprite-sdk
======

主要是封装了 卖家精灵 [Seller Sprite](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read) 接口

### 快速开始

#### `pom.xml`配置

```xml

<dependency>
    <groupId>com.kte</groupId>
    <artifactId>sellersprite-sdk</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

#### [io.github.ealenxie.SellerSpriteClient](http://192.168.180.10:9080/kte-chengdu-develop/infra/kte-sdk-all/-/tree/master/sellersprite-sdk/src/main/java/com/kte/sellersprite/SellerSpriteClient.java) 已支持的接口列表

| 接口名        | 方法名                   | 官方文档地址                                                     | 状态 |
|:-----------|:----------------------|:-----------------------------------------------------------|:---|
| 选产品        | productChoose         | [选产品](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)        | ✔️ |
| 查竞品        | competitorLookup      | [查竞品](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)        | ✔️ |
| 查产品类目      | productNode           | [查产品类目](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)      | ✔️ |
| 关键词挖掘      | keywordMiner          | [关键词挖掘](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)      | ✔️ |
| 关键词反查      | trafficKeyword        | [关键词反查](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)      | ✔️ |
| 查询 asin 详情 | asinDetail            | [查询 asin 详情](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/) | ✔️ |
| 谷歌趋势       | googleTrends          | [谷歌趋势](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)       | ✔️ |
| 关键词选品      | keywordResearch       | [关键词选品](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)      | ✔️ |
| 关键词趋势选品    | keywordResearchTrends | [关键词趋势选品](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)    | ✔️ |
| 关键词选品类目    | keywordDepartment     | [关键词选品类目](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)    | ✔️ |
| 关联流量统计     | trafficListingStat    | [关联流量统计](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)     | ✔️ |
| 关联流量列表     | trafficListing        | [关联流量列表](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)     | ✔️ |
| 流量词统计      | trafficKeywordStat    | [流量词统计](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)      | ✔️ |
| BSR销量预测    | predictionBsr         | [BSR销量预测](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)    | ✔️ |
| ASIN销量预测   | predictionAsin        | [ASIN销量预测](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)   | ✔️ |
| ABA数据选品    | abaResearch           | [ABA数据选品](https://shimo.im/docs/YJYyVGqvwGKTxPP3/read/)    | ✔️ |

