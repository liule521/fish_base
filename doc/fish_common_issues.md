fish_common 特性列表

last update: 2017.2.22

####v1.0.10

* 19006，增加，get_time_uuid(), 获得带时间戳的流水号；ok
* 19007，增加，if_any_elements_is_space(),判断参数列表是否存在不合法的参数，如果存在None或空字符串或空格字符串，
    则返回True, 否则返回False；ok
* 19008，common，增加 conf_as_dict(),读入配置文件，返回根据配置文件内容生成的字典类型变量; 
    
---

####v1.0.9

* 19001, 增加，check_sub_path_create() 检查当前路径下的某个子路径是否存在, 不存在则创建；ok
* 19002, 修改，get_long_filename_with_sub_dir() 修改为 get_abs_filename_with_sub_path()；ok
* 19003, 修改，所有文件相关操作，转移到独立 py 文件; ok
* 19004, 修改，get_long_filename_with_sub_dir_module() 修改为 get_abs_filename_with_sub_path_module(); ok
* 19005, 修改，long_filename 都修改为 abd_filename; ok

2017.1.8 通过 r2c1 unittest

* 19006, 增加，在 fish_common中增加 check_platform() 通过调用os.platform来获得当前操作系统名称; ok