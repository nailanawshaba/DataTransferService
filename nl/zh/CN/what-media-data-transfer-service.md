---

copyright:
  years: 2017
lastupdated: "2017-12-18"

---
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}

# 什么是媒体数据传输服务？
 
数据传输服务允许您将兼容 USB 2.0 或 3.0 的设备和/或 CD 及 DVD 发送到 {{site.data.keyword.BluSoftlayer_full}} 数据中心，以直接连接到您的网络。设备将位于所选数据中心的专用机架中，并作为 iSCSI 目标安装。现在也支持高级格式的驱动器。

## 硬件需求
1.    设备电源必须兼容 208v/220v
2.    设备电源插头必须匹配标准 120v 插座 (NEMA 5-15P)
3.    设备必须兼容 USB 2.0（现在也支持 3.0）
4.    设备必须具有 USB 连接线和 USB A 公头接口（匹配大部分计算机的标准插头）
5.    CD/DVD
      1.    必须置于 CD 簿、盒、包装盒或其他容器中，最好全部都置于一个容器中（例如，一个 CD 簿），并且每个磁盘都已进行独特标记。
      2.    磁盘将根据客户的请求，通过凭单指示进行循环播放

## 您的开销
1.    初始服务请求：$0
2.    初始 2 周数据传输：$0
      **注**：延期费用为每周 $25
3.    与 {{site.data.keyword.IBM}} 数据中心来往的装运成本，包括支付任何关税和税款。

**注**：客户负责：  
- 确保无需进口或出口许可即可将设备装运到 {{site.data.keyword.IBM}} 数据中心，或将其退回至客户（如果适用）。 
- 确保内容中所包含数据的客户或任何客户最终用户均未涉及美国政府有关撤销或拒绝其美国出口特权的任何命令。如果客户或任何相关最终用户涉及任何此类命令，客户同意立即通知 {{site.data.keyword.IBM}}；  
- 获取设备的所有许可、装运和清关，包括支付装运到 {{site.data.keyword.IBM}} 数据中心以及从该数据中心装运（如果适用）的任何关税、税款和运费。   
- 符合所有适用的法律，包括隐私法、与交付和退回设备关联的进出口法，以及将内容传输到 {{site.data.keyword.IBM}} 数据中心的相关法律；以及 
- 准备好适当的协议，并获取客户最终用户将任何最终用户数据传输到硬件的所有必需许可权。

## 发出请求
此项在**存储器** > **数据迁移** >  **数据传输**下完成，然后单击页面右上角的**订购数据传输请求**链接。

![发出数据传输请求](/images/DTS.png)
 

在此表单填写设备的信息
1. 序列号
2. 类型
3. 设备的简短描述
4. 您希望设备位于哪个数据中心
5. 用于跟踪装运的跟踪号
6. 使用的承运方服务
7. 完成后，您希望将设备运回的退回地址。

填写此表单后，将自动创建支持凭单，以提醒我们的技术人员，设备已发货给我们，使他们能够跟踪交付。收到设备后，我们将继续将其连接到我们的专用机架。连接设备后，凭单将更新，其中为您提供 iSCSI 目标登录凭证的链接。

## 请求退回
如果您提供了退回地址并在包装中包含了预付的装运标签，那么在 2 周的传输周期期间，您可以随时请求将设备运回给您。通过 [{{site.data.keyword.slportal}}](https://control.softlayer.com/){:new_window} 可执行此操作，请选择**存储器** > **数据迁移** > **数据传输**，并从设备的**操作**下拉列表中，选择**请求退回**。这将提醒我们的技术人员，您希望将设备断开连接并运回给您。

## 请求延期
在 2 周的免费期后，如果仍需使用您的 USB 设备，那么必须请求延期，以提醒我们的技术人员，您希望延长设备的连接时间。此操作与请求退回设备的方法相同，请选择**存储器** > **数据迁移** > **数据传输**，并在设备的**操作**下拉列表中，选择**请求延期**。在初始两周之后，必须支付每周 25 美元的服务费用。此外，根据数据中心可用于您的设备的空间，可能会拒绝您的请求。如果请求获得授权，那么凭单将会更新，指示已授权您再使用一周。

## 断开连接
两周期限之后，设备将自动从我们的数据中心断开连接，并通过选择的承运方退回至您在初始请求中指定的退回地址。凭单将会更新，指示设备已断开连接。如果不请求退回，将就地销毁设备。