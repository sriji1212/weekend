- ```
  aaa = document.getElementsByClassName("view-content")[0].innerText
  
  aaa = aaa + "\\n\\n" + document.getElementsByClassName("attachment attachment-after")[0].innerText
  
  setTimeout(async()=>console.log(
       await window.navigator.clipboard.writeText(aaa)), 3000)
  ```
-