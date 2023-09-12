# 对名字中包含"("的文件进行批量操作

直接使用ls 和 mv 操作会报错syntax error  
```
find . -type f -name "*(*).*" -exec mv {} ../duplicate_files/ \;
```
