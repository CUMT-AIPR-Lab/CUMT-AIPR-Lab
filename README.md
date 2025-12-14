# 1、Lightweight network based on residual information for foreign body classification on coal conveyor belt
Plenty of studies on the safe and efficient transportation of coal in mines reveal that the belts often suffer some hazards caused by foreign objects such as large gangue, bolts and other foreign bodies scratching, tearing the belt, and blocking the coal discharge point in the process of coal transportation．To overcome the problems of large amount of network parameters, poor real-time performance, and low recognition accuracy in the current classification and recognition of belt foreign objects, a lightweight network that integrates residual information is proposed, and we release the coal mine underground foreign object dataset CUMT-BelT.

皮带在煤炭输送过程中存在大块矸石、锚杆等异物划伤、撕裂皮带和堵塞落煤口等安全隐患，预警、分选及联动控制不及时会严重影响煤炭的运输效率。为克服当前对皮带异物分类识别时存在的网络参数量大、实时性差、识别精度低等问题，提出了一种融合残差信息的轻量级网络，并开源了煤矿井下异物数据集CUMT-BelT。

Paper：[融合残差信息轻量级网络的运煤皮带异物分类](http://www.chinacaj.net/d/file/48-2022-03/42e7f030c8e74e7f8f8e361004d20e4c.pdf).  
CUMT-BelT Dataset：[(pwd:z39g)](https://pan.baidu.com/s/1AJsjkPqXjkIJY8KQQdKfcw?pwd=z39g).


# 2、Lightweight super-resolution reconstruction method based on hierarchical features fusion and attention mechanism for mine image
The images in coal mines have problems of dim, blurry and unclear edges. To address these issues, this article proposes a lightweight mine image super-resolution reconstruction method that fuses hierarchical features and attention mechanism. In addition, to make the proposed model have better generalization performance in real-mine scenes, a coal mine underground image dataset CMUID is constructed for the training and testing experiments of the network model.

针对矿井图像灰暗模糊、边缘不清晰等问题，提出了一种融合层次特征和注意力机制的轻量化矿井图像超分辨率重建方法。为了使模型在真实矿井场景中具有更好的泛化能力，构建了一种煤矿井下图像数据集CUMT-CMUID用于网络模型的训练和测试实验。

Paper1：[融合层次特征和注意力机制的轻量化矿井图像超分辨率重建方法](http://yqyb.etmchina.com/yqyb/article/abstract/20220808).    
Paper2：[Structure-Preserving and Color-Restoring Up-Sampling for Single Low-Light Image](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9446912)  
Paper3：[Light-Guided and Cross-Fusion U-Net for Anti-Illumination Image Super-Resolution](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9841591)   
CUMT-CMUID Dataset：[(pwd:249a)](https://pan.baidu.com/s/1RPT-xTtnUpTOV6PRYVBaDQ?pwd=249a).


# 3、Helmets dataset underground mine
In recent years, national policies on intelligent construction of coal mines have been introduced one after another, and the coal mining industry has been paying more and more attention to the construction of intelligent mines with "intelligence and safety" as the core, wearing helmets is the most basic and important measure to protect personnel safety in coal mining. For this reason, our group collected helmet wearing data from underground personnel and established an underground helmet detection data set to help the construction of intelligent mines.

近年来，国家关于煤矿智能化建设的政策相继出台，煤矿行业越来越重视以“智能、安全”为核心的智慧矿山建设，佩戴安全帽是煤矿生产中保护人员安全的最基本也是最重要的措施。为此课题组专门收集井下人员安全帽佩戴数据，建立了井下安全帽检测数据集CUMT-HelmeT助力智慧矿山的建设。

CUMT-HelmeT Dataset：[(pwd:d2x2)](https://pan.baidu.com/s/1yELcc8DpuiG4HNV-eWFeTw?pwd=d2x2).

## If this project is of assistance, please consider citing our papers：  
[1] 程德强等.融合层次特征和注意力机制的轻量化矿井图像 超分辨率重建方法[J].仪器仪表学报,2022,43(8):73-84.  
[2] 程德强等.融合残差信息轻量级网络的运煤皮带异物分类[J].煤炭学报,2022,47(3):1361-1369.    
[3] liangliang Chen, et al. Structure-Preserving and Color-Restoring Up-Sampling for Single Low-Light Image[J]. IEEE Transactions on Circuits and Systems for Video Technology,2022,32(4): 1889-1902.
[4] Cheng Deqiang, et al. Light-Guided and Cross-Fusion U-Net for Anti-Illumination Image Super-Resolution[J]. IEEE Transactions on Circuits and Systems for Video Technology,2022, 32(12): 8436-8449.
##### In English：
[1] CHENG Deqiang, et al. Lightweight network based on residual information for foreign body classification on coal conveyor belt[J]. Journal of China Coal Society, 2022, 47(3): 1361-1369．  
[2] CHENG D Q, et al. Lightweight super-resolution reconstruction method based on hierarchical features fusion and attention mechanism for mine image [J]. Chinese Journal of Scientific Instrument, 2023, 43(8): 73-84.  
[3] liangliang Chen, et al. Structure-Preserving and Color-Restoring Up-Sampling for Single Low-Light Image[J]. IEEE Transactions on Circuits and Systems for Video Technology,2022,32(4): 1889-1902.  
[4] Cheng Deqiang, et al. Light-Guided and Cross-Fusion U-Net for Anti-Illumination Image Super-Resolution[J]. IEEE Transactions on Circuits and Systems for Video Technology,2022, 32(12): 8436-8449.   


# 4、Underground Mine Dust-and-Haze Image Dataset (CUMT-DustFog)
This dataset was collected from three real mining faces in Shandong Province, where high humidity and heavy dust concentrations result in images that commonly suffer from severe haze, blurring, and color distortion. Clear reference images are unavailable due to the uncontrolled, real-world operating conditions. To support research on image dehazing algorithms, we publicly release a representative subset of 300 images for testing.The dataset faithfully captures the complex visual degradation encountered underground and is well-suited for evaluating the robustness and generalization of dehazing models in industrial environments with high dust and humidity—thereby advancing vision-based perception systems for intelligent mines.

本数据集采集自山东地区3处真实采掘工作面，作业环境湿度高、粉尘浓度大，图像普遍存在严重雾霾、模糊和色彩失真，且无法获取对应的清晰参考图像。为支持去雾算法研究，我们公开其中300张具有代表性的图像作为测试子集。该数据集真实反映井下复杂视觉退化情况，适用于评估图像去雾模型在工业粉尘高湿环境下的鲁棒性与泛化能力，助力智能矿山视觉感知系统的发展。

## If this project is of assistance, please consider citing our papers：  
[1]寇旗旗,张海龙,陈加鹏,等.基于雾气分级与域间差异的采掘工作面图像去雾方法[J/OL].采矿与岩层控制工程学报,1-13[2025-12-14].https://doi.org/10.13532/j.jmsce.cn10-1638/td.2025-1198.

## 若涉及版权问题，请联系我们，我们会及时处理
