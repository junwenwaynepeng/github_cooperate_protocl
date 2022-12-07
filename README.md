# 工作協議

## 命名規則

### python
* Class: UpperCamelCase
* GLOBAL_CONSTANT: 全域變數採用全大寫，並以_取代空格的命名法
* other_thing: 區域變數或函數使用全小寫，並以_取代空格的命名法
* do_something: 用動詞開頭作為函數的命名原則
* THIS_VARIABLE_MIGHT_BE_CONSTANTLY_CHECKED: 如果某個常數在開發的過程要被經常的訪問並改動，用長命名
* 用 _list, _tuple, s, 做為變數結尾，代表這個變數是可迭代的。
* 用 a_b_dict, 作為 a對應到 b的字典
### JS
### Files
* 均以小寫命名(方便在終端機裡面打字搜尋)，字與字之間的空格使用_取代。
* static裡面放所有放所有靜態文件，例如: css, fonts, html, img, js, misc(存法其他任何雜項)
* project用客戶名作為命名主體
* 用v1, v2, v3, ...作為穩定板本代號的編碼。
* 如果客戶有不同種類的app，那命名規則採用"應用程式名_版本號"(e.g. app1_v3, app2_v1, ...)作為命名規則

## 工作流程
1. 在自己的branch, e.g. develop-Wayne, 先做開發。
2. develop-Wayne穩定後，可以pull and push到 develop-unstable，並且在那邊做測試直到確認可以完整複製在 develop-username開發的結果。
  * 當某人在develop-unstable做開發的時候，其他人只可以做pull，但是不能push
3. PM在確認沒有人想再對develop-unstable做push的之後，把develop-unstable merge 到develop-stable，並且在那個分支做debug的工作，PM再確認完develop-stable沒有bug之後，merge到master。

## Git筆記
###第一次使用
####步驟大綱：
0. 下載必要套件 
1. 設定git
2. 產生SSH key
3. 用SSH key
###連線到專案
###連線到專案分支
