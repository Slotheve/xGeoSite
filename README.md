# v2ray-SiteDAT

## 自定义site.dat 文件

### 规则:
  
  - include:another-file
  
  - domain:google.com @attr1 @attr2
  
  - keyword:google
  
  - regex:www\.google\.com
  
  - full:www.google.com


### 使用：

  1.   - 修改/添加sites文件夹下的域名文件，运行 ``` ./v2sitedat ``` 生成geosite.dat
    
        - 更多参考 ``` ./v2sitedat --help ```
    
  2.   - 可Fork后自行在sites文件夹下增减,后每天自动Build & Release
       
       - 文件在release分支里
 
