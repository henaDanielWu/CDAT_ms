# CDAT:Adaptive Teaching for Cross-Domain Crowd Counting
 This code is based on [MindSpore](https://gitee.com/mindspore/mindspore).

## Install
a. Install the [MindSpore(CPU)](https://www.mindspore.cn/install): 

If your machine is Linux-x86_64 and you have Python 3.7, you can run the following command:

```shell
pip install https://ms-release.obs.cn-north-4.myhuaweicloud.com/2.2.11/MindSpore/unified/x86_64/mindspore-2.2.11-cp37-cp37m-linux_x86_64.whl --trusted-host ms-release.obs.cn-north-4.myhuaweicloud.com -i https://pypi.tuna.tsinghua.edu.cn/simple
```

b. Install the dependent libraries as follows: 

Install the dependent python libraries: 

```shell
pip install -r requirements.txt
```


## Training and Testing

* Test:
Need to load the trained [model file]()[], put the file in `./code/pre_models/`.
Then run the following command：
```shell
./run.sh
```
