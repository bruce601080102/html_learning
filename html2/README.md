## 第二堂 群組化與css重要屬性介紹

- 標籤div
    > 將標籤群組化

    ```html
    <div></div>
    ```
- 標籤input
    > 表單空格的標籤

    ```html
    <input type="text" >
    <input type="password" placeholder="密碼">
    <input type="date">
    ```
- 標籤button
    > 按鈕的標籤

    ```html
    <button type="button">送出</button>
    ```
- css群組化
    ```css
    .自定義名稱{
        設定1:x;
        設定2:x;
    }
    .mystyle{
        color:red;
        background-color:black; 
    }
    ```

- css 置中

    > 文字置中
    ```css
    text-align:center      
    ```
    > 元素置中
    >> display: flex:影響子類並且並排
    ```css
    display: flex
    justify-content:center
    align-content:center
    ```
- css margin
    ```css
    margin:auto;          
    margin-bottom: 15px;
    margin-top: 15px;
    margin-left: 15px;
    margin-right: 15px;
    ```

- CSS position
    ```css
    position: static;
    ```

    > static 
    >> 默認固定物件的位置
    
    > absolute 
    >> 直接定位該頁面的位置,無視物件是否存在

    > relative
    >> 效果跟static一樣
    >>> 但可以讓absolute子元素根據他的位置定位

    > fixed
    >> 類似於便利貼那樣黏住該地方,滑動後依舊會在該位子

    > sticky
    >> 當道頂部後,會固定在頂部位置

- `自我練習`

    - <h3>作業1

    > 練習看看postion五個元素的應用
    >> 應用五個屬性設定圖片位子

    >> 嘗試做出帳號密碼的介面後並將介面放在網頁right:100px;top:50px的地方



