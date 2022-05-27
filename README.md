## 原始模型
### 模型简介
#### Swin Transformer
在Swin Transformer出现之前，transformer有两大挑战：1,视觉实体变化da，在不同场景下视觉Transformer性能不够好。2，图像分辨率高，像素点多，Transformer基于全局自注意力的计算导致计算量大。针对以上问题，swin transformer设计了一种包含滑窗操作、具有层级设计的Transformer结构。该结构可以作为通用视觉backbone，灵活应用于目标分类、目标检测、图像分割等任务。
![swin-transformer](/imgs/swin-transformer.png "swin-transfomer")

#### MaskRcnn
MaskRCNN在两阶段检查网络的基础上，通过ROIAlign，以及拓展的FCN网络进行实例分割。广泛应用于自动驾驶、行人关键点领域
![maskrcnn](/imgs/maskrcnn.png "maskrcnn")
