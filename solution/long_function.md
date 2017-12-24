# 過長函式

接手前人的程式碼，看到一個好幾十行甚至上百行的函式，一定會覺得很頭痛吧。

## 提煉函式

- 如果這個函式的邏輯可以分段，嘗試「提煉函式」（Extract Method）

## 以查詢式取代暫時變數

- 如果函式有暫存變數影響提煉，嘗試「以查詢式取代暫時變數」（Replace Temp With Query）

## 以函式物件取代函式

- 如果一個函式非常複雜，有大量的變數與邏輯，那就應該獨立成自己的物件。嘗試「以函式物件取代函式」（Replace Method With Method Object）

## 分解條件式

- 如果這個函式裡面有複雜的條件式（if-elseif-else），嘗試「分解條件式」（Decompose Conditional）



