# Target_models
***Some target models for Blind-Knowledge project.*** <br />
***数据使用说明*** 
```bash
# 各文件夹下图片随机划分没有重叠
# 请使用cifar100-5way-test下的5*100=500张图片进行替代模型精度/对抗样本测试
├── classify-cifar100-5way
|   ├── cifar100-5way-meta(5*50)
|   ├── cifar100-5way-test(5*100)
|   ├── cifar100-5way-train(5*400)
|   └── cifar100-5way-twostage(5*50)
```
***模型使用说明*** 
```bash
model = torch.load("./checkpoints/ResNet18/ResNet18-cifar10-5way-92.4.pth")
```
