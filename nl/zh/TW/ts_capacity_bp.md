---



copyright:
  years: 2017
lastupdated: "2018-01-03"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:tip: .tip}
{:table: .aria-labeledby="caption"}


# 容量考量

## 發生狀況

當您佈建虛擬伺服器時，可能會收到下列錯誤訊息： 

```
There is insufficient capacity to complete the request.
```
{:screen}

佈建失敗時，特定要求內的所有虛擬伺服器實例都會失敗。
{:tip}

## 發生原因

路由器或資料中心內的可用資源不足而無法滿足服務要求時，發生容量錯誤。有數個原因，您都會收到此錯誤。資源可用性會經常變更，因此您可能需要等待，然後再試一次。

## 修正方式 

您可以使用下列策略來嘗試重新佈建：

1. 指定不同路由器的佈建。  
2. 未指定路由器的佈建。
3. 在不同資料中心內佈建。
4. 佈建較少的實例。 
5. 佈建至多個資料中心來分散實例。
6. 佈建較小的實例大小。
7. 將 VSI 儲存空間從 SAN 變更為 LOCAL，或從 LOCAL 變更為 SAN。 



