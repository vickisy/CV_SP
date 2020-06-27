# PRCV_SP

## Implementation
        运用改进的SENet显式地建模特征通道之间的相互依赖关系，通过自学习方式获取到每个特征通道的权重，针对性地提升显著特征并抑制无关特征，以对鞋印图像数据进行挖掘分析，获取足迹对应的样本年龄信息，实现鞋印图像数据挖掘年龄信息的目的。
### 环境要求:
    python=3.6
        pytorch=0.4.1
        numpy
        pandas
        scikit-learn
        matplotlib
        pillow
        opencv-python
        
## Squeeze-and-Excitation Networks
### Approach
<div align="center">
  <img src="https://github.com/vickisy/PRCV_SP/blob/master/Figures/SE-pipeline.jpg">
</div>
<p align="center">
  Figure 1: Diagram of a Squeeze-and-Excitation building block.
</p>

<div align="center">
   <img src="https://github.com/vickisy/PRCV_SP/blob/master/Figures/SE-Inception-module.jpg" width="420">
  <img src="https://github.com/vickisy/PRCV_SP/blob/master/Figures/SE-ResNet-module.jpg"  width="420">
</div>
<p align="center">
  Figure 2: Schema of SE-Inception and SE-ResNet modules. We set r=16 in all our models.
</p>


