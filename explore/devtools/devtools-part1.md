# DevTools - Network Tab

1. **What is the name of the new JSON file?**  
   `citylots.json`

2. **Which file initiated the download of the new file?**  
   `expose.js:4`

3. **What is the file size of the downloaded file?**  
   `0 B` (fulfilled from disk cache)

4. **How long did it take to download?**  
   `89 ms`

5. **What was your User-Agent for the browser that made the request?**  
   `Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36 Edg/135.0.0.0`

6. **In the response header, what type of server did it come from?**   
   `GitHub.com` 
   
7. **When was the file last modified?**  
   `Thu, 15 Sep 2022 22:44:30 GMT`  
   
8. **What was the Content-Type of the file?**  
   `Thu, 15 Sep 2022 22:44:30 GMT`

9. **Which function inside the initiating file made the request?**  
   `fetchData()` The following code was given:
   ```
   // part2.js
   function fetchData() {
    fetch('./citylots.json')
    }
    function init() {
    document.getElementById('fetchData').addEventListener('click', fetchData);
    }
    window.addEventListener('DOMContentLoaded', init);
   ```
