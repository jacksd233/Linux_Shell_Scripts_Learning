# 对名字中包含"("的文件进行批量操作
  find . -type f -name "*(*).*" -exec mv {} ../duplicate_files/ \;
