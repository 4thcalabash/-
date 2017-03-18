# -
本软件转为杨洋而造
用来作为南大LOL校园杯的抽奖器
随机数字范围为0-128
日后会更新出可以由用户决定随机数上下限的正式版

借这个机会学习了一下javafx的runLater，并更好的理解了分层架构的好处->其实是自己把两个层混在一起写导致debug到死
//java倒不会出现这个情况，而javafx的的application thread不是线程安全的，所以不能用thread来修改scene的东西，
必须交由javafx的application thread来做，方法就是Platform.runLater(()->{code&code})；
第一次用了全屏窗口+css设置背景图片+css设置背景图片自适应尺寸（刚好充满全屏）
