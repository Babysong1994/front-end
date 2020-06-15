---
description: '# 面试题'
---

# HTML面试题

## 💛 HTML基础

### Q1：DOCTYPE 有什么作用？怎么写？ 

### Q2：列出常见的标签，并简单介绍这些标签用在什么场景？

### Q3：页面出现了乱码，是怎么回事？如何解决？ 

### Q4：title 属性和 alt 属性分别有什么作用？ 

### Q5：HTML 的注释怎样写？

### Q6：HTML5 为什么只写 `<!DOCTYPE html>` ？ 

### Q7： data- 属性的作用？ 

### Q8：`<img>`的 title 和 alt 有什么区别？

### Q9：Web 标准以及 W3C 标准是什么？ 

### Q10：DOCTYPE 作用？严格模式与混杂模式如何区分？它们有何意义？ 

### Q11：HTML 全局属性（Global Attribute）有哪些？

### 🔸 Q12：以下哪种多媒体格式支持最广泛？

❌  .m3u8  
✅  .mp4  
❌  .wmv  
❌  .flv  
❌  .mov

### Q13：打开一个页面，发现页面出现了乱码，以下说法正确的是：

✅   英文和数字不会出现乱码，中文可能会出现。  
****❌   只要给 HTML 的 head 标签里加`<meta charset="UTF-8">`就一定能解决乱码问题。  
✅   给 HTML 的 head 标签里加`<meta charset="UTF-8">`不一定能解决乱码问题。  
✅   页面保存的时候用的是什么编码格式，就给 HTML 的 head 标签里 meta 的 charset 属性设置 相同编码格式。

### Q14：关于浏览器乱码，以下说法正确的是？\(不定项\)

❌   只要在 HTML 的 head 标签里设置 `<meta charset="UTF-8">` 就一定能解决乱码问题。  
✅   用不合适的编辑器编辑文件，常常会出现乱码，比如 Windows 记事本。  
✅   HTML 保存的时候需关注保存时的编码格式，保存什么格式，就设置 `<meta charset="xxx">`  ， 其中 xxx 为保存文件时的编码格式。  
❌   如果 HTML 里只有英文和数字，一般不会出现乱码，所以 HTML 里没必要设置 charset 了。

## 💛 HTML 元素、属性详解

### Q1：meta 有哪些常见的值？



### Q2：meta viewport 是做什么用的，怎么写？



### Q3：列出常见的标签，并简单介绍这些标签用在什么场景？



### Q4：如何在 HTML 页面上展示  这几个字符？



### Q5：你是如何理解 HTML 语义化的？



### Q6：前端需要注意哪些 SEO?



### Q7：你对网页标准和 W3C 重要性的理解?



### Q8：关于语义化，以下说法错误的是？（不定项）

✅   在做页面做整体布局的时候，table 标签用起来很方便可以作为布局的一种推荐方案。   
❌   语义化的本质是可读性，让代码适合自己阅读、适合队友阅读、适合机器阅读。   
✅   对于 h1-h6、p、span 这些标签，用 div 替换也没关系，修改它的 display 属性即可。   
❌   使用语义化标签能让代码更简洁，所以能用尽量用。

## 💛 表单详解

### Q1：POST 和 GET 方式提交数据有什么区别？



### Q2：在 input 里，name 有什么作用？ 



### Q3：label 有什么作用？如何使用？ 



### Q4：radio 如何分组？

同一组设置相同的name

### Q5：placeholder 属性有什么作用？ 

能够让你在文本框里显示提示信息，一旦你在文本框里输入了什么信息，提示信息就会隐藏。

### Q6：type=hidden 隐藏域有什么作用？举例说明。 



### Q7：CSRF 攻击是什么？如何防范？ 



### Q8：网页验证码是干嘛的？是为了解决什么安全问题？



### Q9：常见 Web 安全及防护原理？



### 🔸 Q10：以下哪种写法会导致 checkbox 被勾选：

✅ `<input type="checkbox" checked="false">`   
✅ `<input type="checkbox" checked="true">`  
✅ `<input type="checkbox" checked="">`  
✅ `<input type="checkbox" checked>`  
❌ `<input type="checkbox">`

### 🔸 Q11：如果想勾选 checkbox，以下哪些是推荐的写法： 

✅   `<input type="checkbox" checked>`  
❌   `<input type="checkbox" checked="checked">`  
❌   `<input type="checkbox" checked="true">`  
❌   `<input type="checkbox" checked="false">`  
❌   `<input type="checkbox" checked=true>`

### 🔸 Q12：有 4 个 radio，想 id1 和 id2 一组，id3 和 id4 一组，实现单选，以下说法正确的是？（不定项）

✅   id1 和 id2 需要设置相同的 name，id3 和 id4 需要设置相同的 name。   
❌   id1 和 id2 需要设置相同的 value，id3 和 id4 需要设置相同的 value。   
❌   id1 和 id2 需要设置相同的 class，id3 和 id4 需要设置相同的 class。  
❌   id1 和 id2 需要设置相同的 label，id3 和 id4 需要设置相同的 label。

### Q13：关于 POST 和 GET 的区别，以下说法正确的是？

✅  GET 的语义是“要”数据，POST 的语义是“给”数据或者“创建”数据。   
✅  GET 把参数拼装成 URL，发 GET 请求实际上是浏览器请求拼接后的 URL。  
❌  GET 提交的数据没有最大长度限制，POST 提交的数据有最大长度限制（和服务端的设置有关）。  
✅  GET 提交的数据有最大长度限制，根本原因是浏览器地址栏对输入的 URL 有最大长度限制，超过会截断。   
✅  POST 相对更“安全”一些，因为 GET 请求拼装的 URL 会保存在浏览器历史记录，到了服务器之后一般 也有保存的请求日志可以直接看到请求参数。  
✅  从严格的安全意义上讲，只要是 HTTP 的请求，都不安全。HTTPS + POST 才安全。



