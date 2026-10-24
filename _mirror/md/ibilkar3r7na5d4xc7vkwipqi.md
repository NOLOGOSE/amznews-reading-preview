# 亚马逊德国站 Merchant Fulfillment API v0 新增身份验证枚举值

> 原标题：New Enum Values for Domestic Shipments in the Germany Amazon Store

- 来源：Amazon SP-API 更新
- 原文发布时间：2026-09-17 05:11
- 本站收录时间：2026-10-07T11:19:42.691Z
- 历史内容补录
- AMZNEWS：https://nologose.github.io/amznews-reading-preview/items/ibilkar3r7na5d4xc7vkwipqi
- 原文：https://developer-docs.amazon/sp-api/changelog/new-enum-values-for-domestic-shipments-in-the-germany-amazon-store

## 摘要

官方公告说明，自2026年10月1日起，Merchant Fulfillment API v0 在 getEligibleShipmentServices 和 createShipment 的 DeliveryExperience 与 DeliveryExperienceOption 字段中新增 DeliveryConfirmationWithIdentityCheck 和 DeliveryConfirmationWithNameVerification。配送验证服务适用于德国（DE）商城的 DHL Paket National Shipping；新增枚举会进入全球 API 模型，使用固定枚举列表进行校验或反序列化的集成需检查兼容性，并按原文要求更新处理逻辑。
