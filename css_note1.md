# CSS 筆記

## Abstract

* HTML 是骨架 , CSS 負責上色
* 所選要變的就叫選擇器 selector

``` css
1.一定要先用 link:css 變成 <link rel="stylesheet" href="style.css"> /*只要加一個就可以*/
2.再開一個檔案 如style.css
3.網頁上可以用F12 或是右鍵檢查結構，幫助學習，也可看到連接的'檔案'跟'位置'行數

h1{ #選擇器 /*格式*/
    color: aqua;   #屬性 : 設定值
    font-size: 15px;
}
```

***
## <font color = 'aqua'>1.選擇器</font>:

>1. <font color = 'orange'>標籤選擇器:</font>直接指定 h1 ,p ,a 等<font color="red">全部</font>直接更改
>2. <font color = 'orange'>擬態(互動)選擇器:</font>在過去標籤的時候 使用hover,active等<font color = 'red'>互動</font> 比較常使用在 "a" 標籤連結上。
>3. <font color = 'orange'>類別class選擇器:</font>在不同的標籤上做出樣式的<font color="red">差異化</font>

---

#### 2.擬態(互動)選擇器:
``` css
a:hover{  #擬態選擇器  這是鼠標碰到時切換
    color: salmon;
    font-style: inherit;
    font-size: 70px;
    }
a:active{ #這是點著不放時切換
    color:black;
}
```

#### 3.類別class選擇器:
``` html
<p class="style1">我是標題</p>
<p class="style2">我是標題</p>
```
css所對應的
``` css
.style1{
    color:red;
}
.style2{
    color: seagreen;
}
```
也可以交叉互動，如插入標籤到a連結
``` html
<a class="style1" href="https://www.google.com/">連結1</a>
<a class="style2" href="https://www.google.com/">連結2</a>
```

  <font color = 'yellow'>TIPS(一併使用):</font>
```css
h1 , a ,p,li{
    background : black ;
    color :white
    /*可以用逗點一併使用*/
}

```
***
## <font color = 'aqua'>2.文字設定段落:</font>
``` html
<p class="word_adjust1"><!--此處用class選擇器-->Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptatem repellendus officiis sapiente dolore atque consequatur sunt iure quod. Ex, quibusdam.</p>
```
所對應的css :
``` css
.word_adjust1{
    color: sienna; /* 顏色*/
    font-family: Verdana; /* 設定以前預設的 : 字型*/
    font-size: 36px; /* 字體大小*/
    line-height: 1.5; /* 每行上下間距 - 為大小1.5倍*/
    text-align: left; /* 文字靠左*/
    text-indent: 72px; /* 首行縮排:字體兩個字*/
    text-decoration: underline; /*底線*/
    letter-spacing: 2px; /*字的間距*/
```
---
## <font color = 'aqua'>3.關於畫線(border)的部分:</font>

```css
h1{
    border: 1px solid brown;
    /*畫線  粗度 線樣式 顏色*/
}
h1{
    border-top: 5px solid red;
    border-bottom: 5px solid yellow;
    border-left: 5px solid green;
    border-right: 5px solid blue;
}   /*也可以分別像這樣設定*/
    /*也可以用img在圖片上面加喔 */
```