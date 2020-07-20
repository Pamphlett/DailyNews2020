#### 2020/5/23 My first day to use MarkdownPad ;)
Cause I'm going to do an intern in HikVision soon .(actually in June 1st) To prepare, I decide to be more familiar with ROS, Linux and CMake.

最近在看***SegMatch***。看完感觉想法十分简洁，中间很少的公式推导。所以准备先把代码跑起来，在这个过程中复习一哈ROS。

---

#### 2020/5/27
Finally succeeded to build tensorflow from source and now waiting to download datasets of segmap. :smile:

Things should know before building tensorflow from source:
* Be sure with the correspondence between the version of ***tensorflow*** and ***bazel***;
* Due to the Internet restriction, better to download the `.sh` file of bazel;

About how to build `tensorflow_ros_cpp`: see [here](https://github.com/ethz-asl/segmap/issues/108#issuecomment-420964940).

About ROS
* `catkin clean` restores the workspace and let you be able to rebuild from scratch.

---

#### 2020/6/3
公司生活有点难顶，容易疲倦 :(
最近两天在整理已经做过的东西，要在小组内做个pre，无新进展嗷。

---

#### 2020/6/8
`.launch` file is actually a parameter setting file written in xml.

---

#### 2020/6/9
Use `rqt_bag` to preview a rosbag.

---
#### 2020/7/16
Long time no see :smile:

Recently I'm working on poor initial value registration issues. Teaser++ seems to be capable of handling all this.

So now a global localization procedure is something like this:

Scan Context -> poor but reasonable initial value -> Robust registration technique -> ICP fine pose estimation

Typical Coarse to Fine.
---
#### 2020/7/20
Isotropic Gaussian: the covariance matrix is \sigma^2 * Identity.

This goes for a circular symmetry of the pdf.
