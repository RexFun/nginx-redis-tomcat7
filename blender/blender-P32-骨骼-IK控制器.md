# P32

## IK反向关节作用：骨架本身只能父级控制子级，装了IK后子级控制父级

###### Step1. 创建IK控制关节：骨骼(EditMode)下，选中脚跟或手跟处，按E长出一关节

###### Step2. 清除亲子关系：选中新关节，点击【螺丝批】，在【Relations】下【Parent】清空（快捷键 ALT+P）

###### Step3. 配置IK：(PoseMode)(左脚为例)， 选中脚跟(新关节) + 按住 SHIFT 选中小腿 -> 按 SHIFT+I 出菜单 -> 点【To Active Bone】 

###### Step4. 设置IK长度：(PoseMode)(左脚为例)，选中小腿骨头，【选单列】点击【Bone Constraints】（【螺丝批+锁链】），【Chain L】设为 2 （默认0，即控制所有骨头）
