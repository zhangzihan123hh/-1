# 记录
## 下载 _Anaconda3_
下载地址（**这个博客下出来时，会遇见选择ALL User 还是 私人，记得选择私人，不然需要迁移环境** ）：
https://blog.csdn.net/weixin_43412762/article/details/129599741?app_version=6.3.6&code=app_1562916241&csdn_share_tail=%7B"type"%3A"blog"%2C"rType"%3A"article"%2C"rId"%3A"129599741"%2C"source"%3A"zzh192837"%7D&uLinkId=usr1mkqgl919blen&utm_source=app

目的：
Anaconda是一个强大的开源数据科学平台,它将很多好的工具整合在一起，极大地简化了使用者的工作流程，并能够帮助使用者解决一系列数据科学难题。
### 跟进项目
* 项目地址 https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix.git
* 下载压缩包，解压
* 打开promote进入解压后地址空间
* 选择标注处指令，复制执行创建环境指令![QQ20241015-181324](https://github.com/user-attachments/assets/f2616988-22bc-4f99-96b3-4c94af847397)

* 查看环境是否搭建:conda info --envs![QQ20241015-173514](https://github.com/user-attachments/assets/a3b071fb-afa4-4e5a-a82c-e15c475f28b8)
* 如果环境被下载到c盘，可以迁移，见博客：https://blog.csdn.net/qq_40968179/article/details/128990022
* 进入环境，输入指令conda activate pytorch-CycleGAN-and-pix2pix
![QQ20241015-174435](https://github.com/user-attachments/assets/88c5f7cc-3d72-4aa8-b4aa-1ff06d4b5c3a)

### 数据集准备
* 选择pix2pix train/test
  ![QQ20241015-174936](https://github.com/user-attachments/assets/0afb4b2b-eb05-42d3-9264-529651bca632)
* 下载数据集地址（任选其一即可）：https://efrosgans.eecs.berkeley.edu/pix2pix/datasets/
* 下载压缩包后需要解压到指定文件夹下：D:\DeepLearning\pytorch-CycleGAN-and-pix2pix-master\pytorch-CycleGAN-and-pix2pix-master\datasets
*  若需要查看损害函数，输入python -m visdom.server
*  若出现以下情况，需要下载插件![QQ20241015-180217](https://github.com/user-attachments/assets/137024b0-4223-45e8-bc7c-9a73b6dd422b)
*  下载插件： 先输入，pip uninstall visdom，选择y。再输入pip install visdom即可解决问题
### Pycharm准备
* 下载pycharm:https://blog.csdn.net/weixin_45503499/article/details/114396143

