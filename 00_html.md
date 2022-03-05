# HTML

## 什麼是 HTML ?

超文本標記語言的縮寫 (Hypertext Markup Language)

HTML 不是程式語言 (programming language)

用於創建 WebPages / Documents

## 標籤語法 (Tag Syntax)

- 尖括號中的元素
- 通常會有一個開始標籤跟一個結束標籤
- 有一些標籤自己關閉

## HTML 基本骨架 (Skeleton)

```html
<!-- Boilerplate -->
<!DOCTYPE html>
<html lang="zh-Hant">
  <!-- head 標籤 - 網頁背後設定與編碼 -->
  <head>
    <meta charset="UTF-8" />
    <!-- character set -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>

    <!-- 一般教學當中比較不容易提到的實用meta標籤 -->
    <meta name="robots" content="index, follow" />
    <meta name="description" content="網頁描述" />
    <meta name="author" content="Kun-Yu Chang" />
  </head>
  <!-- body 標籤 - 網頁呈現內容 -->
  <body>
    <!-- something tag -->
  </body>
</html>
```

參考 : [A simple guide to HTML <head> elements](https://htmlhead.dev/)

## 需要了解的 HTML 知識

1. Comment 如何註解
2. 什麼是 Block, Inline 元素?
3. 認識 Div, Span, Br, Hr
4. Index.html 的意義
5. 關於 Icon
6. 自閉合標籤 (Self closing tag) 是什麼? 與其他標籤差異?
7. 如何顯示特殊符號? (HTML Entities) https://www.htmlsymbols.xyz/

### Self closing tag

為什麼有些標籤會自動關閉（img、br 等等）而其他標籤不會？
差異在於 Self closing tag 標籤元素為置空元素(empty element)或稱空元素(void element)，代表不包含任何內容。
參考 : [置空元素](https://developer.mozilla.org/zh-TW/docs/Glossary/Empty_element)

## 那些關於 HTML 標籤的意義

p 段落 paragraph
h1 - h6 標題 heading
a 超連結 anchor
ol 有序清單 ordered list
ul 有序清單 unordered list
br 空行 Line Break
div 區塊元素 Division 區分的意思
hr = 水平分隔線 Horizontal Rule

## 參考

[15 個常用的 HTML 標籤與屬性基本介紹](https://selflearningsuccess.com/html-tags/?fbclid=IwAR3lJv73yLyJamOu79-weojL7D1N3p9EwM_STG2uPsO76ktONRjoswgBtls)
[HTML 語法教學，快速攻略網頁 HTML 標籤的基本元素｜ ALPHA Camp Blog](https://tw.alphacamp.co/blog/html-guide?fbclid=IwAR2s3Rr63MpvcF0jt0dr-d1taxilbyPYVNJcCRlz29b80Y06r_jgrbjXPX4)
[HTML 基礎 - 學習該如何開發 Web | MDN](https://developer.mozilla.org/zh-TW/docs/Learn/Getting_started_with_the_web/HTML_basics?fbclid=IwAR0iLkJ-1xQEKMJ2Ah-8j4stKzxmp1P4E-z6Q0V9KvOrsGZX2Ay0XAYTyAo)
