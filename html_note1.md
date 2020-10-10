# HTML 筆記

## <font color = 'aqua'>1.基本 :</font>
1. DOCTYPE html 表示格式為html5
2. 網頁架構為 html -> head -> body 
    - html 為主要
    - head 塞title等，就是網頁上面看的標籤
    - body 顧名思義，給客官看得

```html

<!DOCTYPE html>
<html>
<head><title>hello world</title></head>
<body>
    
<h1>你好嗎</h1>
<p>段落段落</p>

</body>

</html>
```
---
## <font color = 'aqua'>2.快速產生html必要元素  就是Emmet套件 -> !</font> 
### 還有圖片部分
```html
<!DOCTYPE html>
<html lang="en"> <!--屬性英文-->
<head>
    <meta charset="UTF-8"> <!--編碼方式p-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
                <!--爭對螢幕解析度調整優化-->
    <title>Document</title>
</head>
<body>
    <h1>我是標題</h1>
   <p>段落</p>
  <img src="img/cat.jpg" alt="給視障人士看得">
  <!--img就是顯示圖片-->
</body>
</html>
```
>1. meta 細部資料
>2. charest 是編碼方式
>3. p*3 會出現三個 p
>4. 若是img不同資料夾則前面加 資料夾/檔名 即可喔
>5. img如果是網路上就直接 ->複製圖片位址貼上
>6. lorem10 產生10個假字哦
>7. emmet就是IDE自動補寫VScode有內建了!
---
## <font color = 'aqua'>3.連結網址 :</font>

```html
<a title = "彈跳提示視窗 "href="https://www.youtube.com/watch?v=KMDIPnV3dN0">連到很認真讀書那個人</a>
<!--a href = "網址"    名稱-->
<!--title = "abc" 放上去會有彈跳提示視窗-->
<a target = "_blank" href="https://www.dcard.tw/f">Dcard主頁</a>
<!--多了target = "_blank" 會開新的視窗，放前面後面都可->

```
---
## <font color = 'aqua'>4.   P段落 與 a 網址的混合用法 :</font> 

``` html
<p>其實一個人吃飯並不孤單一個人想吃什麼就要吃
    <a target = "_blank" href="https://yuanchuang666.wixsite.com/sioumazang">燒肉</a>才對！</p>
<!--中間文字穿插網址-->
```
---
## <font color = 'aqua'> 5. ul & ol 和 裡面li 標籤 :</font> 
* 他是負責序列的標籤
* ul 是無序 ; ol是有序的
* li 是裡面的標籤 有通用 li*3

``` html
    <ul>
        <li>項目1</li> <!--無序-->
        <li>項目2</li>
        <li>項目3</li>
    </ul>

   <ol>
    <li>第一個</li>  <!--有序-->
    <li>第二個</li>
    <li>第三個</li>
   </ol>
```