# 圖書館空間預約管理系統優化 - 系統分析與設計

## 專案簡介

本專案為「系統分析與設計」課程的期末專案，旨在分析現有圖書館空間預約系統的問題，並提出優化方案的設計藍圖。團隊透過系統分析方法，定義功能與非功能性需求，並利用資料塑模 (Data Modeling) 與 UML 圖表來視覺化系統架構與流程。

**團隊成員：**
* 黃柏軒
* 史岱澂
* 葉宇翔
* 林祐頡
* 陳柏銓

## 問題分析與目標

現行系統在學號驗證、預約時間彈性、預約內容修改等方面存在不足。本專案旨在設計一個更優化的系統，解決以下主要問題：

* 缺乏對預約成員學號的有效驗證。
* 預約時間單位固定，缺乏彈性。
* 無法直接修改預約內容，需取消後重新預約。

優化目標是提升使用者體驗、增加系統靈活性與安全性。

## 系統設計成果 (主要圖表)

本專案的核心產出為一系列系統設計圖表，作為未來系統開發的藍圖。主要包含：

1.  **功能模型 (Functional Model):**
    * 使用案例圖 (Use Case Diagram)
    * 活動圖 (Activity Diagram) - 包含使用者預約、修改/刪除、管理者管理等流程
    * 使用案例描述 (Use Case Description) - 詳細描述核心使用案例

2.  **資料流程圖 (Data Flow Diagram - DFD):**
    * 描繪系統與外部實體（使用者、管理者）以及內部資料儲存之間的資料流動。

3.  **結構模型 (Structural Model):**
    * 實體關係模型 (Entity Relationship Model - ERM / ERD) - 定義系統中的主要實體及其關係。
    * 正規化綱要 (Normalized Schema) - 基於 ERM 設計的資料庫綱要。
    * 類別圖 (Class Diagram) - 描述系統中的類別、屬性、方法及其關係。

4.  **行為模型 (Behavioral Model):**
    * 循序圖 (Sequence Diagram) - 展示物件之間互動的順序，涵蓋登入、預約、修改、管理、遲到判定等場景。
    * 行為狀態機圖 (Behavior State Machine) - 描述系統或物件在不同事件觸發下的狀態轉換。

## 主要功能需求 (優化後)

* 強化使用者身份驗證機制。
* 提供更彈性的預約時間選項。
* 允許使用者修改現有預約（時間、成員等）。
* 即時查看空間與設備狀態。
* 防止預約衝突。
* 根據空間大小限制預約人數。
* 自動處理遲到紀錄與停權機制。
* 預約成功與提醒通知。
* 管理者權限管理。

## 使用技術與工具

* 系統分析與設計方法論
* 資料塑模 (Data Modeling)
* UML (Unified Modeling Language)
* Figma (用於繪製圖表)

## 團隊分工 (Team Contribution)

* **黃柏軒:** Sequence Diagram、Activity Diagram
* **史岱澂:** Sequence Diagram、Entity Relationship Model、Normalized Schema、Class Diagram
* **葉宇翔:** Sequence Diagram、Use Case Diagram、Use Case Description
* **林祐頡:** Sequence Diagram、Behavior State Machine
* **陳柏銓:** Data Flow Diagram
* **問題與原因分析、功能性需求、非功能性需求:** 全體成員共同完成
