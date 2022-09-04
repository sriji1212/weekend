- ```
  aaa = document.getElementsByClassName("view-content")[0].innerText
  
  aaa = aaa + "\\n\\n" + document.getElementsByClassName("attachment attachment-after")[0].innerText
  bbb = aaa.replaceAll("\n\n", "_")
  setTimeout(async()=>console.log(
       await window.navigator.clipboard.writeText(bbb)), 3000)
       
       
       
  aaa = "_ " + document.getElementsByClassName("view-content")[0].innerText + "_ "
  aaa = aaa + "   _" + document.getElementsByClassName("attachment attachment-after")[0].innerText + "_"
  setTimeout(async()=>console.log(
       await window.navigator.clipboard.writeText(aaa)), 3000)
       
       
  aaa = document.getElementsByClassName("view-content")[0].innerText
  aaa = aaa +  document.getElementsByClassName("attachment attachment-after")[0].innerText 
  setTimeout(async()=>console.log(
       await window.navigator.clipboard.writeText(aaa)), 3000)     
  ```
- `{{embed [[7_07]]}}`
-