# Mavens
自定义第三方插件maven库




1、图片选择框架增加指定文件夹数组扫描，传入指定文件夹数组后会监听指定文件夹下图片以及视频的改变，在application中使用，如下
     SdCardFileChangeUtils.geInstance(getApplicationContext()).startWatching(new String[]{
                PROJECT_FILE_DIR_VIDEO,
