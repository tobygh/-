# 脚本说明
对学堂网的看视频和测试题两个模块，利用js注入的方式成功得到了想要的效果。推荐使用火狐或chrome。

2018-11-1更新
 - 自动脚本：
     - 补充了注释；
     - 修复了一个bug：submit与check间隔太短，导致check没有读取到真正的结果，使得遍历到不合法的答案。解决方法：调整了submit与check之间的时间间隔，确保check能读到submit之后的结果；
     - 提高了效率：做多选题时，跳过对选项少于2个的答案的枚举。
 
2018-10-31更新
 - 自动答题脚本：暴力枚举单选题、判断题以及多选题的选项，每五分钟自动提交一次。目前还没有实现对填空题自动提交。
 - 视频加速脚本：更改标签的值，突破速度限制。
 
重现方法：进入对应的网页，按F12并切换至控制台，将代码复制粘贴并按回车，将开始工作。

声明：仅供学习参考，代码运行的结果均为随机生成，不能代表本人的任何的直接或间接的观点。因使用代码而产生的一切后果，本人概不负责。
