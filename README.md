# HUWEI2019-rematch-contest
HUWEI2019 rematch contest

TO DO<br>
* 1.1.先安排优先车辆，从速度慢到速度快
* 1.2.再安排非优先车辆，从速度慢到速度快
* 1.3.使用调度器，看是否死锁。如果发生死锁，则降低死锁时刻前后的道路车辆容量，重复1.1和1.2。如果未死锁，则输出答案。
* 2.训练模型通过道路的（限速，长度，车道数）->预测车辆容纳数量
* 3.训练模型更精准的预测车辆通过该条道路所需的时间
