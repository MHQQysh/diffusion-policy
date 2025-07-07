# diffusion-policy
diffusion policy


就是上传我的代码而以

哪里涉及到仿真的事情





python3 collect_data.py --config-dir=imitation_learning_dp/config --config-name=image_ur5_grab_diffusion_policy_cnn

环境配置出现的问题记录

1. 

(robodiff) ysh@0:~/桌面/Coding/imitation_learning_dp-master$ python3 collect_data.py --config-dir=imitation_learning_dp/config --config-name=image_ur5_grab_diffusion_policy_cnn
Error executing job with overrides: []
Error locating target 'imitation_learning_dp.env.ur5_grab.ur5_grab_image_env.UR5GrabImageEnv', see chained exception above.
full_key: task.env

Set the enviro-nment variable HYDRA_FULL_ERROR=1 for a complete stack trace.


在collect.py中添加

from imitation_learning_dp.env.ur5_grab.ur5_grab_image_env import UR5GrabImageEnv

# 


pip3 install roboticstoolbox-python

pip3 install modern_robotics



python3 train.py --config-dir=imitation_learning_dp/config --config-name=image_ur5_grab_diffusion_policy_cnn



python3 roll_out.py --config-dir=imitation_learning_dp/config --config-name=image_ur5_grab_diffusion_policy_cnn