---
title: 應用程式介面（API）
status: Completed
category: 概念
tags: ["架構", "基本原理", ""]
---

## 是什麼 {#what-it-is}

應用程式介面（API）是電腦程式互動的一種方式。就像人類透過網頁與網站互動一樣，API 允許電腦程式之間進行互動。
與人類的互動不同，API 可以限制對方可以和不可以問什麽。對互動的限制有助於在程式之間創建穩定且實用的資訊傳輸。

## 解決的問題 {#problem-it-addresses}

隨著應用程式變得越來越複雜，微小的程式碼更改也可能會對其他功能產生巨大的影響。
如果應用程式想要在擴展的同時保持其穩定性，則需要用模組化方法來管理其功能。
沒有 API，應用程式之間就缺乏一個應用程式之間互動的框架。
沒有一個共享的框架，應用程式[擴展](/zh-tw/scalability/)和整合將會變得很辛苦。

## 如何幫助我們 {#how-it-helps}

API 允許電腦程式或應用程式以一種明確的、可理解的方式互動和共享資訊。
它們是奠定現代應用程式的基礎，它們為開發人員提供了一種將應用程式整合在一起的方法。
每當您聽到[微服務](/zh-tw/microservices-architecture/)在一起運作時，就可以推斷它們是透過某種 API 互動的。