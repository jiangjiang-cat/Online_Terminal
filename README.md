# Online_Terminal
智能隔离开关在线监测终端4.0

使用步骤：
1、新建一个文件夹例如glkg_disp（可以自己随意命名），名称和保存路径都不能包含中文字符！将所有文件夹解压到这个文件夹中
2、将core文件夹中的所有文件解压到新建的glkg_disp下，即保持core中的.cpp\.h\.ui文件与其他qss\modbus等文件夹处于同一目录下
3、将Qt_Dir文件复制放入E:盘中，若电脑中没有E盘，可放入其他盘，但是要修改：
（1）sgmdb.h文件下的
      #define DEV_DB_DIR    "E:\\Qt_Dir\\DB\\"
（2）devwave.h下的
      #define DEV_WAVE_DIR                "E:\\Qt_Dir\\WaveFile\\"
      #define DEV_WAVE_YDIR               "E:\\Qt_Dir\\YBFile\\"
      ========》修改为实际放入的盘中
4、运用版本为5.9.0的Qt软件运行.pro文件（采用其他版本可能存在不兼容等风险）
