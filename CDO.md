CDO对nc文件进行操作

`cdo sinfon **.nc`
可以输出nc文件中的所有时间，以年月日时分秒的形式。

`cdo infon **.nc`
则可以输出所有时间以及对应时间的各个变量的值

`cdo -sellevel,1000,925,850,700,600,500,400,300,250,200,150,100,50 -selname,z,q,t,u,v $nc_file $output_dir/$date/plevel_${date}_${time}.nc`
从nc文件中提取指定高度level和指定variable

` cdo -R copy $grib_surface_file $grib_surface_file_normal`
ERA5的surface grib文件使用的是reduced GG网格，使用cdo将它转换到regular网格
