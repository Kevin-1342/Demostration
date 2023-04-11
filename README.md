# Demostration on Kitti Dataset
因数据隐私原因，此处只做kitti公开数据集和部分AIDAY的展示
（Due to data privacy reasons, only the kitti public dataset and AIDAY demos are displayed here）

**图片加载可能会比较慢**

## 输入 (Input)
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_input.gif" width="400">
</p>

## 可控背景更换及维持多帧一致性 (Controllable Background Editing with View Consistency)
Prompt: "Convert to a foggy day"
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_foggy.gif" width="400">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_foggy_left_rotate.gif" width="400">
</p>

Prompt: "Convert to dawn"
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_dawn.gif" width="400">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_dawn_left_rotate.gif" width="400">
</p>

Prompt: "Convert to Piet Mondrian painting"
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_M.gif" width="400">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_M_left_rotate.gif" width="400">
</p>

## 自车新视角生成（New View Generation）
左右平移，旋转（Move left and right, rotate）
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_car_left_right_rotate.gif" width="400">
</p>

模拟压线行驶（A simulation of driving on the solid lines）
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_car_lane_right.gif" width="400">
</p>

## 前景障碍物编辑 （Foreground Editing）
移动障碍物模拟碰撞（A simulation of car accident）
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/kitti_car_move.gif" width="400">
</p>
前景障碍物的跨场景融合及可控坐标编辑（Cross-scene fusion and controllable coordinate editing of foreground objects）
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/aidaydemo_1.gif" width="400">
</p>
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/aidaydemo_2.gif" width="400">
</p>
<p float="center">
  <img src="https://github.com/Kevin-1342/Demostration/blob/main/imgs/aidaydemo_3.gif" width="400">
</p>
