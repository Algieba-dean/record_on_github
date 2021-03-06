# **Markdown語法操作的一些記錄**  
- - -

1. 主要語法
    1. n級標題 用n個#加一個空格表示
    2. 列表
        * 有序列表 用數字.+空格表示
        * 無序列表 用一個*+空格表示
        * 多級列表 寫下一級列表時，縮進4個空格
    3. 換行 只需要在需要換行的最後+兩個空格即可
    4. 內嵌顯示 >+空格
    >PS:內嵌顯示這個功能，可以進行多層內嵌，也可以每段/行都加上一個>來標識同一層，>>標識內嵌層，>的個數標識內勤啊的層數  
        一個>默認是一個大段，故此，如果不想讓其他內容被誤判進內嵌框中，需要中間空一行來標識

    5. 格式
        1. 斜體 用 *括起來* （可以用於標識特殊內容）
        2. 加粗 用 **括起來** （可以用於標題加粗）
        3. 加粗斜體 用 ***括起來*** 就可以了（貌似*的左右兩邊需要加上空格以防誤識別）
        4. 刪除線 用 ~~~miao~~~ 括起來（測試可行）
    6. 鏈接
        1. 普通鏈接 [鏈接文字](鏈接地址"標題")
        2. 圖片鏈接 ![圖片名稱](圖片鏈接地址)  對，圖片鏈接就是只比普通鏈接多加了一個！而已
        3. 參考鏈接(測試不成功) [鏈接文字][鏈接編號]  [鏈接編號]:鏈接地址"標題" (有點可惜，並不能用，如果能用的話，應該可以省力不少)
        4. 自動鏈接 這個直接顯示例子好了，比如<http://www.baidu.com>和<algieba.king@gmail.com>這類地址可以直接解析
    7. 錨點  
        >PS: 錨點，大概就和鏈接差別不大，不過應該算是頁內連接，頁內跳轉之類的東西，使用起來也比較方便，所以單列出來啦  

        1. 用heml標記語言來做標記 <span id="test">文字</span>   [文字](#test)
    8. 表格
    > 表格就直接用實例來進行演示了，但是還是有一些注意的地方，  
    > 1. 表頭和表體之間（即第二行），需要至少每個格子用---將其劃開
    > 2. 第二行可以用:+---的位置，來標識對齊方式，左對齊，右對齊和居中
    > 3. 表格如果某些地方沒有東西，也需要用空格來進行佔位

    | 序號 | 學號 | 姓名 | 班級 |
    | :--- | :---: | :---: | ---: |
    | 1 | 001 | 蘇若 | 大班 |
    | 2 | 002 | 汪韻 | 小班 |
    | 3 | 003 | 江月 | 大班 |
    | 4 | 004 | 柳煙 | 小班 |

    9. 代碼塊
        1. 行內代碼塊 `like this`
        2. 多行代碼塊
            ```python
         就像這樣
            ```
    10. 腳註
    > 這個功能比較好用了，寫論文的最後用的文獻引用就用這個做的話效果會很不錯(貌似好像不得行)

        這[^1]是一個腳註,牠[^2]也是一個腳註
        [^1]:這 腳註的內容會放在這裡
        [^2]:牠 腳註的內容，雖然牠寫在這裡，但是會自動處理到文章的最後
    11. 公式
    > 顯示LaTeX公式

    12. 流程圖  
    [參考鏈接](https://blog.csdn.net/witnessai1/article/details/52551362)
