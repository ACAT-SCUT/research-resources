## 1.数据中心节能与绿色计算

### 1.1 相关学习资料

1. 实验室内部报告：《ARM与x86服务器节能技术分析及能效测试报告》、《云业务节能技术分析报告》、《数据中心能效建模及基于模型的节能方法》（包括服务器能效建模、供电能效建模、散热能效建模和节能方法三个部分）、《基准测试场景集群能效优化调研报告》、《实际业务场景集群能效优化调研报告》
2. 《Energy Efficient servers Blueprints for Data Center Optimization》：是一本介绍能源高效服务器及其在数据中心优化中应用的图书。该书由C. Gough、I. Steiner和W. Saunders撰写，详细探讨了用于能源高效服务器的电源管理技术和方法。
3. 《性能之巅：洞悉系统、企业与云计算》：性能工程领域的经典著作，由资深专家Brendan Gregg撰写。本书系统性地探讨了复杂环境下的性能分析与优化方法，覆盖从传统硬件到云计算的全栈技术，结合理论与实践，为读者提供了应对现代系统性能挑战的全面指南。
4. 服务器功耗数据集：https://www.spec.org/power_ssj2008/results/power_ssj2008/
5. Marconi 100超算中心数据集：https://gitlab.com/ecs-lab/exadata/-/tree/main?ref_type=heads
6. 功耗相关基准：https://www.spec.org/power/
7. Wentai Wu，Weiwei Lin，Keqin Li. Energy efficiency of servers in data centers. (Encyclopedia of Sustainable Technologies (可持续技术百科全书), 2nd Edition) Elsevier. 2023.03  
8. Weiwei Lin，Wentai Wu，Keqin Li. Energy-Saving Technologies of Servers in Data Centers . (Data Center Handbook: Plan, Design, Build, and Operations of a Smart Data Center, 2021: 337-348.) John Wiley & Sons, Inc.. 2021.05

### 1.2 实验室相关成果

#### 1.2.1论文

1. Huikang Huang, Weiwei Lin*, Jianpeng Lin, Keqin Li. Power Management Optimization for Data Centers: A Power Supply Perspective.  IEEE Transactions on Sustainable Computing, 2025: 1–20
2. Jianpeng Lin, Weiwei Lin*, Wentai Wu, Wenjun Lin, Keqin Li. Energy-aware virtual machine placement based on a holistic thermal model for cloud data centers.  Future Generation Computer Systems, 2024, 161:302-314
3. Jianpeng Lin,, Wenjun Lin, Weiwei Lin*, Tianyi Liu, Jiangtao Wang,, Hongliang Jiang. Multi-objective cooling control optimization for air-liquid cooled data centers using TCN-BiGRU-Attention-based thermal prediction models.  Building Simulation, 2024,17:2145–2161
4. Weiwei Lin, Jianpeng Lin*, Zhiping Peng, Huikang Huang, Wenjun Lin, Keqin Li. A systematic review of green-aware management techniques for sustainable data center.  Sustainable Computing: Informatics and Systems, 2024, 42: 100989
5. Wenjun Lin, Weiwei Lin*, Jianpeng Lin, Haocheng Zhong, Jiangtao Wang, Ligang He. A multi-agent reinforcement learning-based method for server energy efficiency optimization combining DVFS and dynamic fan control.  Sustainable Computing: Informatics and Systems, 2024, 42: 100977
6. Guokai Wu, Huabin Wang*, Weiwei Lin*, Ruichao Mo, Xiaoxuan Luo. FS-DBoost: cross-server energy efficiency and performance prediction in cloud based on transfer regression.  Cluster Computing, 2024, 27(6): 7705-7719.
7. Rui Chen, Huikang Huang, Xiaoxuan Luo, Weiwei Lin*. A Server Placement Algorithm for Reducing Risk and Improving Power Utilization in Data Centers.  Tsinghua Science and Technology , Tsinghua University Press, 2024, 29(1): 158--173
8. Lin, Jianpeng, Lin, Weiwei*, Huang, Huikang, Lin, Wenjun, Li, Keqin. Thermal Modeling and Thermal-aware Energy Saving Methods for Cloud Data Centers: A Review.  IEEE Transactions on Sustainable Computing, 2023: 1–20
9. Liang, Jiechao, Lin, Weiwei*, Xu, Yangguang, Liu, Yubin, Mo, Ruichao, Luo, Xiaoxuan. Energy-aware parameter tuning for mixed workloads in cloud server.  Cluster Computing, 2023, https://doi.org/10.1007/s10586-023-04212-6
10. Weiwei Lin, Xiaoxuan Luo*, ChunKi Li, Jiechao Liang, Guokai Wu, Keqin Li. An Energy-Efficient Tuning Method for Cloud Servers Combining DVFS and Parameter Optimization.  IEEE Transactions on Cloud Computing, 2023,11(4):3643-3655, DOI: 10.1109/TCC.2023.3308927
11. Rui Chen, Bo Liu, WeiWei Lin*, JianPeng Lin, HuiWen Cheng, KeQin Li. Power and thermal-aware virtual machine scheduling optimization in cloud data center.  Future Generation Computer Systems , 2023, 145: 578--589
12. Jianpeng Lin, Weiwei Lin*, Wenjun Lin, Jiangtao Wang, Hongliang Jiang. Thermal prediction for Air-cooled data center using data Driven-based model.  Applied Thermal Engineering, 2022,217,119207
13. 金育妍, 余天豪, 王松波, 林伟伟*, 潘宇聪. ARM架构云服务器的CPU功耗模型研究.  计算机科学, 2022, 49(10): 59-65.
14. 李俊祺, 林伟伟*, 石 方, 李克勤. 基于混合群智能的节能虚拟机整合方法.  软件学报, 2022,33(11):3944−3966
15. Wentai Wu, Weiwei Lin*, Ligang He, Guangxin Wu, Ching-Hsien Hsu. A Power Consumption Model for Cloud Servers Based on Elman Neural Network.  IEEE Transactions on Cloud Computing, 2021, 9(4): 1268-1277
16. Huiwen Cheng, Bo Liu, Weiwei Lin*, Zehua Ma, Keqin Li, Ching-Hsien Hsu. A survey of energy-saving technologies in cloud data centers.  The Journal of Supercomputing, 2021, 1-36, https://doi.org/10.1007/s11227-021-03805-5
17. Weiwei Lin, Tianhao Yu, Chongzhi Gao, Fagui Liu, Tengyue Li, Simon Fong, Yongxiang Wang. A Hardware-aware CPU Power Measurement Based on the Power-exponent Function Model for Cloud Servers.  Information Sciences, 2021,547, 1045-1065
18. Weiwei Lin*, Guangxin Wu, Xinyang Wang, Keqin Li. An Artificial Neural Network Approach to Power Consumption Model Construction for Servers in Cloud Data Centers.  IEEE Transactions on Sustainable Computing, 2020, 5(3):329-340
19. Weiwei Lin, Fang Shi*, Wentai Wu, Keqin Li, Guangxin Wu, Al-Alas Mohammed. A Taxonomy and Survey of Power Models and Power Modeling for Cloud Servers.  ACM Computing Surveys, 2020, 53(5): 1-41
20. Weiwei lin, Siyao xu, Ligang He, Jin Li. Multi-Resource Scheduling and Power Simulation for Cloud Computing.  Information Sciences, 2017, 397: 168-186.
21. Weiwei Lin, Weiqi Wang, Wentai Wu,Xiongwen Pang, Bo Liu, et al. A Heuristic Task Scheduling Algorithm Based on Server Power Efficiency Model in Cloud Environments.  Sustainable Computing: Informatics and Systems, 2017,DOI:10.1016/j.suscom.2017.10.007
22. Wentai Wu, Weiwei Lin*, Zhiping Peng. An Intelligent Power Consumption Model for Virtual Machines under CPU-intensive workload in Cloud Environment .  Soft Computing.2017, 21(19):5755–5764.
23. 林伟伟,吴文泰. 面向云计算环境的能耗测量和管理方法.  软件学报,2016,27(4):1026-1041

#### 1.2.2专利（详细参见学者网https://www.scholat.com/linweiwei）

1. 授权发明专利（202311844246.2）. 基于热预测模型的数据中心冷却控制方法及装置. 2024.12. 林伟伟, 林建鹏
2. 申请发明专利（2024118755550）. 一种基于软硬件联合优化的高性能计算集群基准能效调优方法. 2024.12. 林伟伟, 李志豪, 林建鹏
3. 申请发明专利（2024118755565）. 基于混合调节策略的加速器功耗优化方法、系统、设备及存储介质. 2024.12. 林伟伟, 牟奇
4. 申请发明专利（202410670153.0 ）. 知识迁移驱动的数据中心算力能效建模方法及装置. 2024.05. 林伟伟, 莫瑞超

## 2.云计算调度和算力管理优化（虚拟化、容器、AI资源） 

### 2.1 相关学习资料

#### 2.1.1 虚拟机、容器调度

1. 实验室内部报告：《云数据中心VM调度优化方法》、《主流云业务类型的负载分类模式》、《云计算弹性调度与GPU共享调度调研报告》
2. 林伟伟，刘波，刘发贵. 《分布式计算、云计算与大数据》第2版. 机械工业出版社. 2024.07
3. 林伟伟，彭绍亮. 云计算与大数据技术理论及应用. 清华大学出版社. 2019.07
4. Kubernetes：容器编排工具，学习Pod调度、自动扩缩容策略，https://github.com/kubernetes/kubernetes
5. 云数据集综述：https://github.com/ACAT-SCUT/Awesome-CloudComputing-Datasets
6. 云计算调度仿真工具CloudSim：http://www.cloudbus.org/cloudsim/

#### 2.1.2 DL负载调度

---

#### - 最新DL负载调度论文梳理

##### 通用DL负载调度
- ​**Awesome-DL-Scheduling-Papers**​  
  [GitHub链接](https://github.com/S-Lab-System-Group/Awesome-DL-Scheduling-Papers)  
  📚 深度学习集群调度论文精选集，覆盖训练/推理调度器设计（如Acme、Cassini等）。

- ​**ML-Systems-Papers**​  
  [GitHub链接](https://github.com/byungsoo-oh/ml-systems-papers)  
  🔍 机器学习系统领域论文分类整理，含调度优化方向。

##### LLM推理负载调度（LLM System）
- ​**Awesome_LLM_System-PaperList**​  
  [GitHub链接](https://github.com/galeselee/Awesome_LLM_System-PaperList)  
  🚀 大语言模型推理优化技术全集（vLLM、DeepSpeed等），涵盖KV缓存、推测解码等。

- ​**LLMSys-PaperList**​  
  [GitHub链接](https://github.com/AmberLJC/LLMSys-PaperList)  
  🔥 补充性LLM系统论文列表。

---

#### - 开源算法实现项目
- ​**S-Lab开源调度器项目**​  
  [GitHub组织](https://github.com/S-Lab-System-Group)  
  ⚙️ 包含DL调度器原型实现（如Lucid、Hydro等）。

- ​**微软研究院工具集**​  
  [MSR-Fiddle](https://github.com/msr-fiddle?tab=repositories)  
  🧪 实验性调度算法与性能分析工具。

---

#### - 仿真调度器
| 项目名称 | 链接 | 特点 |
|---------|------|------|
| Blox | [GitHub](https://github.com/msr-fiddle/blox) | 集群调度模拟器 |
| Lucid | [GitHub](https://github.com/S-Lab-System-Group/Lucid) | 弹性训练调度仿真 |
| Splitwise-Sim | [GitHub](https://github.com/mutinifni/splitwise-sim) | 分阶段推理模拟 |
| Vidur | [GitHub](https://github.com/microsoft/vidur) | ​**微软开源的LLM服务仿真平台**，支持：<br>• 多维度并行策略（流水线/张量并行）<br>• 推测解码工作流模拟<br>• 自动化部署配置搜索<br>|
| DL-Cluster-Simulator | [GitHub](https://github.com/nexuslrf/DL_cluster_simulator) | 可视化集群调度模拟器 |

---

#### - 开源框架
- ​**vLLM**​  
  [GitHub](https://github.com/vllm-project/vllm)  
  🏆 生产级LLM服务框架，支持PagedAttention优化。

- ​**SGLang**​  
  [GitHub](https://github.com/sgl-project/sglang)  
  🌐 面向LLM的高效服务框架。

---

#### - 典型DL负载
##### 语音模型
- [DeepSpeech-PyTorch](https://github.com/SeanNaren/deepspeech.pytorch)  
  📢 开源的基于PyTorch的语音识别模型实现。

##### 视觉模型
- [TorchVision Models](https://github.com/pytorch/vision/tree/main/torchvision/models)  
  🖼️ 标准CV模型库（ResNet、ViT等）。

##### 语言模型
- [NVIDIA翻译模型](https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/Translation)  
  🌍 Transformer/GNMT实现。
- [NVIDIA语言建模](https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/LanguageModeling)  
  📖 BERT/Transformer-XL等模型。

---


### 2.2 实验室相关成果

1. Guozhi Liu, Weiwei Lin*, Haotong Zhang, Jianpeng Lin, Shaoliang Peng, Keqin Li. Public Datasets for Cloud Computing: A Comprehensive Survey.  ACM Computing Surveys, 2025,57(8):1-38
2. Wangbo Shen, Weiwei Lin*, Wentai Wu, Haijie Wu, Keqin Li. Reinforcement learning-based task scheduling for heterogeneous computing in end-edge-cloud environment.  Cluster Computing, 2025, 28(3)
3. Haijie Wu, Weiwei Lin*, Wangbo Shen, Xiumin Wang, C. L. Philip Chen, Keqin Li. Prediction of Heterogeneous Device Task Runtime Based on Edge Server-Oriented Deep Neuro-Fuzzy System.  IEEE Transactions on Services Computing, 2025,18(1):372 - 384
4. Peng Peng, Wentai Wu*, Weiwei Lin*, Fan Zhang, Yongheng Liu, Keqin Li. Reliable Task Offloading in Sustainable Edge Computing with Imperfect Channel State Information.  IEEE Transactions on Network and Service Management, 2024, 21(6):6423 - 6436
5. Haijie Wu, Wangbo Shen, Weiwei Lin*, Wei Li, Keqin Li,. End-Edge-Cloud Heterogeneous Resources Scheduling Method Based on RNN and Particle Swarm Optimization.  IEEE Transactions on Network and Service Management, 2024: 1–1
6. Peng Peng, Weiwei Lin, Wentai Wu, Haotong Zhang,, Shaoliang Peng, Qingbo Wu, Keqin Li. A survey on computation offloading in edge systems: From the perspective of deep reinforcement learning approaches.  Computer Science Review, 2024, 53: 100656.
7. Hongrui Lin, Guodong Liu*, Weiwei Lin*, Xinhua Wang, Xiumin Wang. A novel virtual machine consolidation algorithm with server power mode management for energy-efficient cloud data centers.  Cluster Computing, 2024: 1-17.
8. Haotong Zhang, Weiwei Lin*, Rong Xie, Shenghai Li, Zhiyan Dai, James Z. Wang. An optimal container update method for edge-cloud collaboration.  Software: Practice and Experience , Wiley, 2023, 1-18, DOI: 10.1002/spe.3232
9. Weiwei Lin, Chennian Xiong*, Wentai Wu*, Fang Shi, Keqin Li, Minxian Xu. Performance Interference of Virtual Machines: A Survey.  ACM Computing Surveys, 2023, 55(12): 1-37.
10. Bo Liu, Rui Chen, Weiwei Lin*, Wentai Wu*, Jianpeng Lin, Keqin Li. Thermal-aware virtual machine placement based on multi-objective optimization.  The Journal of Supercomputing , 2023, 79, pages12563–12590
11. 林伟伟, 石方, 李毓睿, 刘发贵, 刘捷, 彭绍亮, 王子骏. 面向混部云失败批处理作业的预测算法.  国防科技大学学报, 2022,44(5):71-79
12. Weiwei Lin, Kun Yao, Lan Zeng, Fagui Liu, Chun Shan, Xiaobin Hong*. A GAN-based method for time-dependent cloud workload generation.  Journal of Parallel and Distributed Computing , 2022,168:33-44
13. Weiwei Lin*, Wentai Wu*, Ligang He. An On-line Virtual Machine Consolidation Strategy for Dual Improvement in Performance and Energy Conservation of Server Clusters in Cloud Data Centers.  IEEE Transactions on Services Computing, 2022,15(2): 766-777 
14. 林伟伟, 王泽涛. 基于遗传算法的Docker集群调度策略.  华南理工大学学报(自然科学版), 2018, 46(3):127-133
15. Weiwei Lin, SiYao Xu, Jin Li, Lingling Xu, Zhiping Peng. Design and theoretical analysis of virtual machine placement algorithm based on peak workload characteristics.  Soft Computing. 2017, 21(5): 1301-1314
16. 徐思尧，林伟伟*，王子骏. 基于负载高峰特征的虚拟机放置算法.  软件学报, 2016,27(7):1876-1887



## 3.大模型优化与AI应用 

### 3.1 相关学习资料

#### 3.1.1传统机器学习与深度学习

1. 林伟伟. 云计算与AI应用技术. 清华大学出版社. 2023.07
2. tangyudi/Ai-Learn：人工智能学习路线图，整理近200个实战案例与项目，https://github.com/tangyudi/Ai-Learn
3. 《机器学习》（周志华）：经典入门教材，涵盖基础算法与理论，附带南瓜书（Datawhale 开源项目）提供公式推导解析，https://github.com/datawhalechina/pumpkin-book
4. 《统计学习方法》（李航）：聚焦统计学习算法的数学推导，适合进阶理解，https://book.douban.com/subject/10706114/
5. 《Deep Learning》（花书）：Goodfellow 等著，深度学习理论权威，开源电子版可在线阅读，https://www.deeplearningbook.org/
6. Keras 官方示例：简单易用的深度学习框架，提供图像分类、序列预测等实战案例，https://keras.io/examples/
7. Andrew Ng 机器学习课程：Coursera 经典课程，附带 Python/Matlab 代码练习，https://www.coursera.org/learn/machine-learning

#### 3.1.2大模型

1. Hoper-J/AI-Guide-and-Demos-zh_CN：一份入门AI/LLM大模型的逐步指南，包含教程和演示代码，带你从API走进本地大模型部署和微调，https://github.com/Hoper-J/AI-Guide-and-Demos-zh_CN
2. Hugging Face Transformers：一站式 NLP 工具库，含 BERT、GPT 等模型实现及教程，https://github.com/huggingface/transformers
3. 《大语言模型》经典图书，由作者赵鑫，李军毅，周昆，唐天一，文继荣 等作者编写，全面介绍了大型语言模型的技术背景、发展过程、关键技术、资源、预训练方法、微调与对齐技术、使用方法、评测以及应用等多个方面。https://llmbook-zh.github.io/

#### 3.1.3其他大模型学习资源
https://docs.google.com/document/d/1TWgjU9hV0XPo2gsXWexoULUe6rW_u7dbtkAzxbyKr_g/edit?usp=sharing

### 3.2 实验室相关成果

#### 3.2.1传统机器学习与深度学习

1. Haijie Wu, Lin, Weiwei*, Yuehong Chen, Fang Shi, Wangbo Shen, C. L. Philip Chen. Adaptive Incremental Broad Learning System Based on Interval Type-2 Fuzzy Set with Automatic Determination of Hyperparameters.  IEEE Transactions on Fuzzy Systems, 2025: 1–13
2. Peng Peng, Yuehong Chen, Weiwei Lin*, James Z. Wang. Attention-based CNN–LSTM for high-frequency multiple cryptocurrency trend prediction.  Expert Systems with Applications, 2024, 237: 121520
3. Wangbo Shen, Weiwei Lin*, Yulei Wu, Fang Shi, Wentai Wu, Keqin Li. Evolving Deep Multiple Kernel Learning Networks through Genetic Algorithms.  IEEE Transactions on Industrial Informatics, 2023,2(19):1569 - 1580

#### 3.2.2大模型

1. Li Y, Yang L, Shen W, et al. CrowdSelect: Synthetic Instruction Data Selection with Multi-LLM Wisdom[J]. arXiv preprint arXiv:2503.01836, 2025.
2. Liu G, Lin W, Huang T, et al. Targeted vaccine: Safety alignment for large language models against harmful fine-tuning via layer-wise perturbation[J]. arXiv preprint arXiv:2410.09760, 2024.

## 4.时序预测模型与应用 

### 4.1 相关学习资料

- 本团队的开源项目CycleNet（NeurIPS 2024 Spotlight），通过可学习循环周期来显式建模时序数据的周期模式，从而提升预测性能。​https://github.com/ACAT-SCUT/CycleNet.
- 本团队的开源项目SparseTSF（ICML 2024 Oral），通过引入跨周期稀疏预测机制，能够更有效地捕捉时间序列中的关键周期特征的同时显著压缩模型规模，实现预测模型的极致轻量化。 https://github.com/lss-1138/SparseTSF.
- 本团队的开源项目SegRNN，通过分段循环神经网络来实现高精度时序预测。https://github.com/lss-1138/SegRNN.
- TSFpaper仓库整理了 400 多篇关于时间序列预测（TSF）和时空预测（STF）的最新论文，按模型类型分类（如LLM-based、MLP-based），包括经典方法和最新的深度学习模型。​它是一个持续更新的阅读清单，适合快速查找相关文献，了解领域发展趋势。 https://github.com/ddz16/TSFpaper.
- Time-Series-Library (TSLib) 由清华大学 THUML 团队开发，是一个面向深度学习的时间序列任务库，支持五大任务：长期预测、短期预测、缺失值填补、异常检测和分类。​https://github.com/thuml/Time-Series-Library.
- TFB 是一个获得 PVLDB 2024 最佳论文提名的时间序列预测基准框架，旨在提供全面且公平的模型评估方法。​https://github.com/decisionintelligence/TFB.
- BasicTS 是一个面向时间序列预测的基准工具包，强调公平性和可扩展性。​http://github.com/GestaltCogTeam/BasicTS.

### 4.2 实验室相关成果

#### 4.2.1 时序预测建模

1. Lin, Shengsheng and Lin, Weiwei* and Wu, Wentai and Chen, Haojun and et al. SparseTSF: Modeling Long-term Time Series Forecasting with 1k Parameters. 2024 International Conference on Machine Learning. (ICML 2024 Oral)
2. Lin, Shengsheng and Lin, Weiwei* and Hu, Xinyi and et al. CycleNet: Enhancing Time Series Forecasting through Modeling Periodic Patterns, 2024 Advances in Neural Information Processing Systems. (NeurIPS 2024 Spotlight)
3. Lin, Shengsheng and Lin, Weiwei* and Wu, Wentai and Wang, Songbo and Wang, Yongxiang. Petformer: Long-term time series forecasting via placeholder-enhanced transformer. IEEE Transactions on Emerging Topics in Computational Intelligence, 2025.
4. Lin, Shengsheng and Lin, Weiwei* and Wu, Wentai and Zhao, Feiyu and Mo, Ruichao and Zhang, Haotong. Segrnn: Segment recurrent neural network for long-term time series forecasting. arXiv preprint arXiv:2308.11200, 2023.

#### 4.2.2 基于时序预测的异常检测

1. Lin, Weiwei and Wang, Songbo and Wu, Wentai and Li, Dongdong and Zomaya, Albert Y. HybridAD: A Hybrid Model-Driven Anomaly Detection Approach for Multivariate Time Series. IEEE Transactions on Emerging Topics in Computational Intelligence, 2024.
2. Wu, Wentai and He, Ligang and Lin, Weiwei and Su, Yi and Cui, Yuhua and Maple, Carsten and Jarvis, Stephen. Developing an unsupervised real-time anomaly detection scheme for time series with multi-seasonality. IEEE Transactions on Knowledge and Data Engineering, 2022.

#### 4.2.3 时序云负载预测

1. Zhao, Feiyu and Lin, Weiwei* and Lin, Shengsheng and Tang, Shaomin and Li, Keqin. MSCNet: Multi-Scale Network with Convolutions for Long-term Cloud Workload Prediction. IEEE Transactions on Services Computing, 2025.
2. Zhao, Feiyu and Lin, Weiwei* and Lin, Shengsheng and Tang, Keqin. TFEGRU: Time-Frequency Enhanced GRU with Attention for Cloud Workload Prediction. IEEE Transactions on Services Computing, 2025.
3. Lin, Shengsheng and Lin, Weiwei* and Zhao, Feiyu and Chen, Haojun. Benchmarking and Revisiting Time Series Forecasting Methods in Cloud Workload Prediction. Cluster Computing, 2025.

#### 4.2.4 时序压缩

1. Lin, Shengsheng and Lin, Weiwei* and Wu, Keyi and Wang, Songbo and Xu, Minxian and Wang, James Z. Cocv: A compression algorithm for time-series data with continuous constant values in IoT-based monitoring systems. Internet of Things, 2024.

#### 4.2.5 相关专利（来源网址：http://search.cnipr.com/pages!tableSearch.action）

1. 申请发明专利（CN202411347361.3）. 一种增强时间序列预测的残差周期预测方法. 2024.09. 林伟伟, 林升升
2. 申请发明专利（202311787568.8）. 基于双轴级联网络的时序预测方法及装置. 2023.12. 林伟伟, 林升升
3. 申请发明专利（CN202310083083.4）. 一种动态压缩时序数据的方法及系统. 2023.02. 林伟伟, 林升升

## 5.边缘智能

### 5.1 相关学习资料

1. 实验室内部报告：《基于Atlas计算平台的端边云协同及统一调度技术研究》
2. Docker: 容器化平台，轻量级部署，https://www.docker.com/
3. 《The Blockchain Developer: A Practical Guide for Designing, Implementing, Publishing, Testing, and Securing Distributed Blockchain-based Projects》：是一本实践指南，旨在帮助开发者学习如何设计、搭建、发布、测试和确保区块链应用的安全性。由Elad Elrom于2019年撰写，书中详细介绍了区块链的技术原理，并阐述了如何将这些原理应用于实际项目中。
4. 《Automated Machine Learning: Methods, Systems, Challenges (The Springer Series on Challenges in Machine Learning)》：是关于自动化机器学习（AutoML）的第一本全面概述，介绍了AutoML中的通用方法、基于这些方法的现有系统，并讨论了首系列国际AutoML系统挑战。由Frank Hutter、Lars Kotthoff和Joaquin Vanschoren编辑，2019年出版，书中深入探讨了商用机器学习应用的成功和这一领域的快速增长，为研究人员、高级学生及实践者提供了进入这一快速发展的领域的入门参考。

### 5.2 实验室相关成果

1. Wangbo Shen, Weiwei Lin*, Wentai Wu, Haijie Wu, Keqin Li. Reinforcement learning-based task scheduling for heterogeneous computing in end-edge-cloud environment.  Cluster Computing, 2025, 28(3)
2. Haijie Wu, Weiwei Lin*, Wangbo Shen, Xiumin Wang, C. L. Philip Chen, Keqin Li. Prediction of Heterogeneous Device Task Runtime Based on Edge Server-Oriented Deep Neuro-Fuzzy System.  IEEE Transactions on Services Computing, 2025,18(1):372 - 384
3. Peng Peng, Wentai Wu*, Weiwei Lin*, Fan Zhang, Yongheng Liu, Keqin Li. Reliable Task Offloading in Sustainable Edge Computing with Imperfect Channel State Information.  IEEE Transactions on Network and Service Management, 2024, 21(6):6423 - 6436
4. Haijie Wu, Wangbo Shen, Weiwei Lin*, Wei Li, Keqin Li,. End-Edge-Cloud Heterogeneous Resources Scheduling Method Based on RNN and Particle Swarm Optimization.  IEEE Transactions on Network and Service Management, 2024: 1–1
5. Peng Peng, Weiwei Lin, Wentai Wu, Haotong Zhang,, Shaoliang Peng, Qingbo Wu, Keqin Li. A survey on computation offloading in edge systems: From the perspective of deep reinforcement learning approaches.  Computer Science Review, 2024, 53: 100656.
6. Senjiong Zheng, Bo Liu*, Weiwei Lin*, Xiaoying Ye, Keqin Li. A package-aware scheduling strategy for edge serverless functions based on multi-stage optimization.  Future Generation Computer Systems , 2023, 144: 105--116
7. Haotong Zhang, Weiwei Lin*, Rong Xie, Shenghai Li, Zhiyan Dai, James Z. Wang. An optimal container update method for edge-cloud collaboration.  Software: Practice and Experience , Wiley, 2023, 1-18, DOI: 10.1002/spe.3232
8. Huabin Wang, Ruichao Mo, Yuping Chen, Weiwei Lin*, Minxian Xu, Bo Liu*. Pedestrian and Vehicle Detection Based on Pruning YOLOv4 with Cloud-Edge Collaboration.  Computer Modeling in Engineering & Sciences, 2023, 137(2):2025-2047
9. Tiansheng Huang, Weiwei Lin*, Xiaobin Hong, Xiumin Wang*, Qingbo Wu, Ching-Hsien Hsu, Albert Y. Zomaya. Adaptive Processor Frequency Adjustment for Mobile Edge Computing with Intermittent Energy Supply.  IEEE Internet of Things Journal, 2022,9(10):7446 - 7462
10. 陈玉平, 刘波, 林伟伟*, 程慧雯. 云边协同综述.  计算机科学, 2021, 48(3):259-267

## 6.联邦学习

### 6.1 相关学习资料

#### 6.1.1 官方教程与文档

**1.Google's Federated Learning:**
[https://ai.googleblog.com/2017/04/federated-learning-collaborative.html](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html)
**谷歌官方博客中介绍了FL的基本概念与应用。**

**2.TensorFlow Federated (TFF):**
[https://www.tensorflow.org/federated](https://www.tensorflow.org/federated)
**官方的联邦学习框架，适合实际动手实践。**

#### 6.1.2 基础文章推荐

**1.Kairouz et al. (2021). "Advances and Open Problems in Federated Learning"**
**这是联邦学习领域的权威综述文章：**
[https://arxiv.org/abs/1912.04977](https://arxiv.org/abs/1912.04977)

**2.McMahan et al. (2017). "Communication-Efficient Learning of Deep Networks from Decentralized Data"**
**提出FedAvg的经典论文：**
[https://arxiv.org/abs/1602.05629](https://arxiv.org/abs/1602.05629)

#### 6.1.3 推荐书籍

**1.Federated Learning: Privacy and Incentive**
**作者：Qiang Yang 等，Springer 出版，涵盖系统架构、隐私机制、激励机制等。**

**2.Federated Learning: Challenges, Methods, and Future Directions**
**一本稍微进阶一点的书，介绍研究热点与挑战。**

#### 6.1.4 课程与讲座推荐

**1.卡内基梅隆大学（CMU）10-719：联邦与协同学习**
**课程名称：10-719: Federated and Collaborative Learning**

**授课教师：Prof. Virginia Smith**

**课程主页：**[https://www.cs.cmu.edu/~smithv/10719/](https://www.cs.cmu.edu/~smithv/10719/)

#### 6.1.5 开源框架

**1.Flower**	**灵活的 FL 框架，支持多种ML库**	[https://flower.dev/](https://flower.dev/)
**2.FedML**	**支持跨设备/跨边缘服务器等多场景的研究平台**	[https://fedml.ai/](https://fedml.ai/)
**3.LEAF**	**联邦学习评估框架，含丰富数据集**	[https://leaf.cmu.edu/](https://leaf.cmu.edu/)

#### 6.1.6 开源项目

1. **一个精心整理的联邦学习（Federated Learning, FL）研究资源列表，涵盖了多个子领域的前沿论文、方法和应用。该列表主要从 arXiv 等来源收集，并按主题分类，便于研究人员查阅和学习。**

   * 基础与优化方法 ：包括如 SCAFFOLD、FedDANE、FedOpt 等优化算法，旨在提高联邦学习在非独立同分布（non-IID）数据和异构设备上的性能。
   * 垂直联邦学习（Vertical FL） ：聚焦于特征分布在不同参与方之间的场景，涵盖如 SecureBoost、基于准牛顿法的框架，以及利用同态加密进行实体解析的方法。
   * 分层联邦学习（Hierarchical FL） ：探讨了客户端、边缘设备和云端之间的协同学习机制，提升系统的可扩展性和隐私保护能力。
   * 通信效率优化 ：研究如深度梯度压缩（Deep Gradient Compression）、双向压缩（Artemis）等技术，以减少通信开销，提高训练效率。
   * 项目地址：https://github.com/FedML-AI/FedML/blob/master/research/Awesome-Federated-Learning.md
2. **该基准测试的主要目的是评估不同联邦学习算法在面对各种非IID数据分布时的性能表现。通过模拟现实中常见的数据异质性场景，如标签不均、特征差异和数据量不平衡，研究人员可以更全面地理解各算法的优势和局限性，从而为实际应用中的算法选择和优化提供参考。**

   * 项目地址：[https://github.com/Xtra-Computing/NIID-Bench](https://github.com/Xtra-Computing/NIID-Bench)
3. **最新联邦学习论文梳理**

   * 项目地址：https://github.com/luozhengquan/Federated-paper

6.2 实验室相关成果

1. Fang Shi, Weiwei Lin*, Chaoda Peng, Cankun Zhong, Dong Wang, Mingyue Cheng. Dynamic Client Selection for Over-the-Air Federated Learning Network.  IEEE Internet of Things Journal, 2025: 1–1
2. Dongdong Li, Weiwei Lin*, Wentai Wu, Haotong Zhang, XiuMin Wang. SynFlowFL: A Dynamic Synaptic Flow Framework for Efficient, Personalized Federated Learning.  IEEE Transactions on Emerging Topics in Computational Intelligence, 2025: 1–15
3. Dongdong Li, Bo Liu*, Chunqiao Yang, Fang Shi, Yunfei Peng, Weiwei Lin*. K-Core Structure Feature Encoding-Based Enhanced Federated Graph Learning Framework.  IEEE Transactions on Emerging Topics in Computational Intelligence, 2025: 1–15
4. Fang Shi, Weiwei Lin*, Xiumin Wang, Keqin Li, Albert Y. Zomaya. The Analysis and Optimization of Volatile Clients in Over-the-Air Federated Learning.  IEEE Transactions on Mobile Computing, 2024,23(12):13144 – 13157
5. Wentai Wu, Ligang He*, Weiwei Lin*, Carsten Maple. FedProf: Selective Federated Learning based on Distributional Representation Profiling.  IEEE Transactions on Parallel and Distributed Systems , 2023,34(6):1942 - 1953, DOI: 10.1109/TPDS.2023.3265588
6. Weiwei Lin*, Yinhai Xu, Bo Liu*, Dongdong Li, Tiansheng Huang, Fang Shi. Contribution-based Federated Learning client selection.  International Journal of Intelligent Systems , 2022, 37 (10):7235-7260
7. Fang Shi, Chunchao Hu, Weiwei Lin*, Lisheng Fan, Tiansheng Huang, Wentai Wu. VFedCS: Optimizing Client Selection for Volatile Federated Learning.  IEEE Internet of Things Journal, 2022, DOI: 10.1109/JIOT.2022.3195073
8. Wentai Wu, Ligang He, Weiwei Lin, Rui Mao, Carsten Maple, Stephen Jarvis. SAFA: a Semi-Asynchronous Protocol for Fast Federated Learning with Low Overhead.  IEEE Transactions on Computers, 2021,70(5): 655-668, DOI: 10.1109/TC.2020.2994391
9. Tiansheng Huang, Weiwei Lin*, Wentai Wu, Ligang He, Keqin Li, Albert Zomaya. An Efficiency-boosting Client Selection Scheme for Federated Learning with Fairness Guarantee.  IEEE Transactions on Parallel and Distributed Systems, 2021, 32(7): 1552-1564
10. 吴文泰, 吴应良*, 林伟伟, 左文明. 横向联邦学习：研究现状、系统应用与挑战.  计算机学报, 2025,48(1):35-67
11. 林伟伟, 石方, 曾岚, 李董东, 许银海, 刘波*. 联邦学习开源框架综述.  计算机研究与发展, 2023, 60(7): 1551-1580.
12. 梁文雅, 刘波*, 林伟伟*, 严远超. 联邦学习激励机制研究综述.  计算机科学, 2022, 49 (12): 46-52.
13. 林伟伟*, 彭绍亮, 王田, 吴文泰, LI Keqin. 联邦学习专题序言.  计算机科学 , 2022, 49(12): 1-4.
