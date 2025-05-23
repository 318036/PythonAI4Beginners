# 🐻 Python 程式設計作業總覽

這份作業集將帶領你從基礎輸入運算、條件判斷，到 Pandas 資料處理，循序漸進掌握 Python 必備技能。每一題皆附有題目連結與解說影片，請依序完成！

---

## 📚 作業一：加權總成績計算與成績等第判斷

- 📝 題目連結：[HW1 - 加權總成績與成績等第](https://judgecode.org/problem/0/11111)
- 🎥 解說影片：[點此觀看](https://youtu.be/kiCeVAwfDf0)

> **題目說明**  
> - 使用者輸入兩行資料：  
>   1️⃣ 五個科目權重（浮點數，加總為 1）  
>   2️⃣ 對應的五個成績（整數，範圍 0 ~ 100）  
> - 輸出加權總成績（小數點後兩位）及對應等第（A+, A, B+...）
> - 並處理各類錯誤：數量不符、範圍錯誤、非有效數字等。

> **學習目標**
> ✅ 輸入處理與資料格式檢查  
> ✅ 計算加權平均並四捨五入  
> ✅ 條件判斷 (if-else) 與等第對照表  
> ✅ 例外處理 (`try-except`) 強化穩定性

---

## 📚 作業二：Pandas 銷售紀錄統計

- 📝 題目連結：[HW2 - 銷售數量統計](https://judgecode.org/problem/0/11112)
- 🎥 解說影片：[點此觀看](https://youtu.be/38mwEo5xV5U)

> **題目說明**  
> - 給定 pandas DataFrame 內部消費紀錄  
> - 任務：統計 **2023/1/3** 當天，各商品類別的總購買數量，並更新到 `results` 字典。
> - 初始字典格式：
> ```python
> results = {'chai': 0, 'juice': 0, 'coffee': 0, 'coldrink': 0, 'others': 0}
> ```

> **學習目標**
> ✅ pandas DataFrame 基礎操作  
> ✅ 條件篩選：指定日期資料  
> ✅ 遍歷資料與累加統計  
> ✅ DataFrame 到 Python 原生字典的整合應用

---

## 📚 作業三：Pandas 旅館價格查詢

- 📝 題目連結：[HW3 - 旅館價格查詢](https://judgecode.org/problem/0/11113)
- 🎥 解說影片：[點此觀看](https://youtu.be/WbmUo2HT3-I)

> **題目說明**  
> - 使用者輸入一個最低可接受價格（如 2000）  
> - 篩選 DataFrame 中符合條件的旅館資訊，輸出格式化結果：
> ```
> 旅館名稱: XX旅館, 城市: XX市
> ```

> **學習目標**
> ✅ pandas DataFrame 條件篩選  
> ✅ 資料格式化輸出  
> ✅ 初探資料科學應用場景  
> ✅ Python 字串處理與迴圈遍歷
