# website-reptiles
将制定网站爬取到本地实现离线访问  

用法：  
```Node.js
let downloadSite = reuqire('website-reptiles')   
downloadSite('http://localhost:8080') // 传入你想要爬取的网站路径
```

Tips:  
1.有些vue开发的网站如果资源路径不正确，需要手动把dist文件夹下所有的__webpack_require__.p = "/" 替换成__webpack_require__.p = "./"  

