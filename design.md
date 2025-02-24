# 網站設計企劃書

## 網站主題

- 這個網站用來宣傳我所製作的所有應用軟體，包含這些應用軟體的介紹、下載、更新日誌、問題回報、聯絡我等等。
- 我的名字叫 Hikaru Wu，專注於使用 flutter 開發命理應用程式

## 網站架構

- 以每個應用軟體為一個網頁，且歸納所有檔案於一個資料夾之下。主頁也獨立一個資料夾。
- 例如：
    - appsite
        - index.html
        - images
        - adv_tarot
            - index.html
            - update.html
            - images
        - app_meiyi
            - index.html
            - update.html
            - images
            
## 應用軟體介紹

### adv_tarot

- 應用軟體名稱：AI塔羅大師(AI Tarot Master)
- 這是個適用於多國語言塔羅占卜程式，包含：
    - en("English"),
    - zh("中文"),
    - jp("日本語"),
    - ko("한국어"),
    - es("Español"),
    - fr("Français");
- 所以網頁也必須是多國語言的，且歸納所有檔案於一個資料夾之下。

#### 功能介紹

- 包含四大占卜功能：
    - 占卜
    使用五張塔羅牌，根據提問的問題，使用AI來解讀卡牌對問題所帶來的影響與指導。
    想掌握未來的方向嗎？占卜模式透過五張塔羅牌找出關鍵牌，揭示命運的奧秘。  
    無論是感情、事業或人生難題，都能提供深入的指引，幫助你做出最佳選擇。  

    - 日誌  
    三張卡牌日誌占卜是一種簡單而深具啟發性的塔羅占卜方式，適合作為每日指引，幫助你理解當日的能量走向，並提供實用的行動建議。
    沒有提問則是占卜整天的運勢，如果提問將套用問題而解讀卡牌的意義與指導。

    - 評分  
    難以在多個選項中抉擇？評分模式為每個選項抽取一張塔羅牌，解析優勢與潛在可能。  
    透過直覺性的評分參考，幫助你權衡選擇，找到最適合的方向。
    例如選擇學校、工作、生活方向等等。

    - 抉擇  
    需要明確的答案？抉擇模式讓你抽取一張塔羅牌，直接獲得「是」或「否」的指引。  
    適用於快速決策，幫助你果斷前行，不再猶豫。

- 三種選牌模式：
    - 隨機抽取，依照每種占卜法顯示需要的蓋著的卡牌張數，按下時隨機在卡牌堆抽取，是一種快速的占卜方式。
    - 蓋著78張牌選擇抽取，卡牌背面標號方便幫遠端朋友報號抽牌。
    - 分類選牌，使用手邊實體卡牌抽牌，在軟體上選牌，讓軟體紀錄抽牌結果，並使用AI解讀。

- 多國語文解讀

### app_meiyi

- 應用軟體名稱：AI梅花易數
- 目前只提供中文版本

#### 功能介紹 

- 多種起卦方式：
    - 三數：輸入或隨機取的三個數字，又稱數字起卦法，是所有起卦法的根本。
    - 八卦：直接選擇上下卦以及一個動爻起卦。
    - 陽曆：使用陽曆的年月日時來起卦。
    - 陰曆：使用陰曆的年月日時來起卦。
    - 卡牌：使用抽牌的方式起卦，比起隨機取卦，多了人的意志的影響。

- 多種解讀方式：
    - 觀卦：透過起卦方式進行牌卦，讓梅花易數學習者觀察起卦的意義。
    - AI易經：用AI解讀用所提問題，在易經本卦、變卦、互卦的意義。
    - AI體用：用AI解讀用所提問題，使用梅花易數體用法的意義。
    - 分類解卦：使用查表的方式，得到爻辭在各種分類的意義。
    - 爻辭解卦：使用查表的方式，得到卦辭及爻辭的解釋。
    - 易經解卦：使用查表的方式，得到易經本卦、變卦、互卦的解釋。
