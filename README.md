# CloudPaper-NoteBook


在此更新关于云原生容器/虚拟机调度或者其他相关方面的优秀论文

目前话题包括但不限于以下内容：

*弹性伸缩

*调度器的设计结构

*资源预测

*多云代理

......

欢迎大家一起开issue分享论文！



# Multi-cloud Related Paper（2019-2022）

- [CloudPaper-NoteBook](#cloudpaper-notebook)
- [Multi-cloud Related Paper（2019-2022）](#multi-cloud-related-paper2019-2022)
  - [**CCF A**](#ccf-a)
    - [**2022**](#2022)
      - [[TPDS 2022]Multi-Swarm Co-Evolution Based Hybrid Intelligent Optimization for Bi-Objective Multi-Workflow Scheduling in the Cloud【6】](#tpds-2022multi-swarm-co-evolution-based-hybrid-intelligent-optimization-for-bi-objective-multi-workflow-scheduling-in-the-cloud6)
    - [**2021**](#2021)
      - [[TS 2021]Multi-objective Optimization of Data Placement in a Storage-as-a-Service Federated Cloud【7】](#ts-2021multi-objective-optimization-of-data-placement-in-a-storage-as-a-service-federated-cloud7)
      - [[TPDS 2021]Hierarchical Multi-Agent Optimization for Resource Allocation in Cloud Computing【6】](#tpds-2021hierarchical-multi-agent-optimization-for-resource-allocation-in-cloud-computing6)
    - [**2020**](#2020)
      - [[TPDS 2020]Location-Aware and Budget-Constrained Service Deployment for Composite Applications in Multi-Cloud Environment【8】](#tpds-2020location-aware-and-budget-constrained-service-deployment-for-composite-applications-in-multi-cloud-environment8)
      - [[TPDS 2020]Scheduling Periodical Multi-Stage Jobs With Fuzziness to Elastic Cloud Resources【6】](#tpds-2020scheduling-periodical-multi-stage-jobs-with-fuzziness-to-elastic-cloud-resources6)
    - [**2019**](#2019)
      - [[TIFS 2019]Extensible Conditional Privacy Protection Authentication Scheme for Secure Vehicular Networks in a Multi-Cloud Environment【4】](#tifs-2019extensible-conditional-privacy-protection-authentication-scheme-for-secure-vehicular-networks-in-a-multi-cloud-environment4)
      - [[TKDE 2019]NewMCOS: Towards a Practical Multi-Cloud Oblivious Storage Scheme【4】](#tkde-2019newmcos-towards-a-practical-multi-cloud-oblivious-storage-scheme4)
  - [**CCF B**](#ccf-b)
    - [**2022**](#2022-1)
      - [[SPE 2022]Towards cloud-based unobtrusive monitoring in remote multi-vendor environments【4】](#spe-2022towards-cloud-based-unobtrusive-monitoring-in-remote-multi-vendor-environments4)
      - [[ASTS 2022]Efficient multi-attribute precedence-based task scheduling for edge computing in geo-distributed cloud environment【8】](#asts-2022efficient-multi-attribute-precedence-based-task-scheduling-for-edge-computing-in-geo-distributed-cloud-environment8)
    - [**2021**](#2021-1)
      - [[CJ 2021]A proposed framework for cloud-aware multimodal multimedia big data analysis toward optimal resource allocation【6】](#cj-2021a-proposed-framework-for-cloud-aware-multimodal-multimedia-big-data-analysis-toward-optimal-resource-allocation6)
      - [[2021]Location-Aware and Budget-Constrained Service Brokering in Multi-Cloud via Deep Reinforcement Learning【7】](#2021location-aware-and-budget-constrained-service-brokering-in-multi-cloud-via-deep-reinforcement-learning7)
      - [[CC 2021]Truthful online double auction based dynamic resource provisioning for multi-objective trade-offs in IaaS clouds【7】](#cc-2021truthful-online-double-auction-based-dynamic-resource-provisioning-for-multi-objective-trade-offs-in-iaas-clouds7)
      - [[CN 2021]Game-based distributed pricing and task offloading in multi-cloud and multi-edge environments【7】](#cn-2021game-based-distributed-pricing-and-task-offloading-in-multi-cloud-and-multi-edge-environments7)
      - [[JPDC 2021]A novel cooperative resource provisioning strategy for Multi-Cloud load balancing【8】](#jpdc-2021a-novel-cooperative-resource-provisioning-strategy-for-multi-cloud-load-balancing8)
      - [[JSA 2021]TOPSIS inspired Budget and Deadline Aware Multi-Workflow Scheduling for Cloud computing【7】](#jsa-2021topsis-inspired-budget-and-deadline-aware-multi-workflow-scheduling-for-cloud-computing7)
      - [[JSS 2021]Tuning configuration of apache spark on public clouds by combining multi-objective optimization and performance prediction model【6】](#jss-2021tuning-configuration-of-apache-spark-on-public-clouds-by-combining-multi-objective-optimization-and-performance-prediction-model6)
      - [[SoCC 2021]Mind the Gap: Broken Promises of CPU Reservations in Containerized Multi-tenant Clouds【6】](#socc-2021mind-the-gap-broken-promises-of-cpu-reservations-in-containerized-multi-tenant-clouds6)
      - [[TSC 2021]A QoS-Based Splitting Strategy for a Resource Embedding Across Multiple Cloud Providers【4】](#tsc-2021a-qos-based-splitting-strategy-for-a-resource-embedding-across-multiple-cloud-providers4)
      - [[MobiHoc 2021]Joint Update Rate Adaptation in Multiplayer Cloud-Edge Gaming Services: Spatial Geometry and Performance Tradeoffs【4】](#mobihoc-2021joint-update-rate-adaptation-in-multiplayer-cloud-edge-gaming-services-spatial-geometry-and-performance-tradeoffs4)
      - [[TSC 2021]A Game-Based Price Bidding Algorithm for Multi-Attribute Cloud Resource Provision【7】](#tsc-2021a-game-based-price-bidding-algorithm-for-multi-attribute-cloud-resource-provision7)
    - [**2020**](#2020-1)
      - [[SPE 2020]A multicriteria optimization model for cloud service provider selection in multicloud environments【7】](#spe-2020a-multicriteria-optimization-model-for-cloud-service-provider-selection-in-multicloud-environments7)
      - [[ICWS 2020]Location-Aware and Budget-Constrained Application Replication and Deployment in Multi-Cloud Environment【7】](#icws-2020location-aware-and-budget-constrained-application-replication-and-deployment-in-multi-cloud-environment7)
    - [**2019**](#2019-1)
      - [[JPDC 2019]Managing renewable energy and carbon footprint in multi-cloud computing environments【5】](#jpdc-2019managing-renewable-energy-and-carbon-footprint-in-multi-cloud-computing-environments5)
  - [**CCF C**](#ccf-c)
    - [**2022**](#2022-2)
      - [[2022 NCA CCFC]Correction to: Multi-objective hybrid genetic algorithm for task scheduling problem in cloud computing](#2022-nca-ccfccorrection-to-multi-objective-hybrid-genetic-algorithm-for-task-scheduling-problem-in-cloud-computing)
    - [**2021**](#2021-2)
      - [[2021 FCS CCFC]An improved multi-objective evolutionary algorithm for computation offloading in the multi-cloudlet environment](#2021-fcs-ccfcan-improved-multi-objective-evolutionary-algorithm-for-computation-offloading-in-the-multi-cloudlet-environment)
      - [[2021 ICCC CCFC]Cost-Effective Dynamic Optimisation for Multi-Cloud Queries](#2021-iccc-ccfccost-effective-dynamic-optimisation-for-multi-cloud-queries)
      - [[2021 JNCA CCFC]A Survey and Comparative Study on Multi-Cloud Architectures: Emerging Issues And Challenges For Cloud Federation](#2021-jnca-ccfca-survey-and-comparative-study-on-multi-cloud-architectures-emerging-issues-and-challenges-for-cloud-federation)
      - [[2021 BD CCFC]Performance Profile of Transformer Fine-Tuning in Multi-GPU Cloud Environments](#2021-bd-ccfcperformance-profile-of-transformer-fine-tuning-in-multi-gpu-cloud-environments)
      - [[2021 CCGrid CCFC]Security aspects in blockchain-based scheduling in mobile multi-cloud computing](#2021-ccgrid-ccfcsecurity-aspects-in-blockchain-based-scheduling-in-mobile-multi-cloud-computing)
      - [[2021 IPCCC CCFC]Diagnosing the Interference on CPU-GPU Synchronization Caused by CPU Sharing in Multi-Tenant GPU Clouds](#2021-ipccc-ccfcdiagnosing-the-interference-on-cpu-gpu-synchronization-caused-by-cpu-sharing-in-multi-tenant-gpu-clouds)
      - [[2021 CCGrid CCFC]Fuzzy-Engineered Multi-Cloud Resource Brokering for Data-intensive Applications](#2021-ccgrid-ccfcfuzzy-engineered-multi-cloud-resource-brokering-for-data-intensive-applications)
    - [**2020**](#2020-2)
      - [[2020 JNCA CCFC]MultiCloud Tournament: A cloud federation approach to prevent Free-Riders by encouraging resource sharing](#2020-jnca-ccfcmulticloud-tournament-a-cloud-federation-approach-to-prevent-free-riders-by-encouraging-resource-sharing)
      - [[2020 JETAI CCFC]Bi-objective web service composition problem in multi-cloud environment: a bi-objective time-varying particle swarm optimisation algorithm](#2020-jetai-ccfcbi-objective-web-service-composition-problem-in-multi-cloud-environment-a-bi-objective-time-varying-particle-swarm-optimisation-algorithm)
      - [[2020 GECCO CCFC]Divide and conquer: Seeding strategies for multi-objective multi-cloud composite applications deployment](#2020-gecco-ccfcdivide-and-conquer-seeding-strategies-for-multi-objective-multi-cloud-composite-applications-deployment)
      - [[2020 ICONIP CCFC]ANN-Assisted Multi-cloud Scheduling Recommender](#2020-iconip-ccfcann-assisted-multi-cloud-scheduling-recommender)
      - [[2020 NOMS CCFC]A Cloud-Agnostic Framework to Enable Cost-Aware Scheduling of Applications in a Multi-Cloud Environment](#2020-noms-ccfca-cloud-agnostic-framework-to-enable-cost-aware-scheduling-of-applications-in-a-multi-cloud-environment)
      - [[2020 PAM CCFC]A First Comparative Characterization of Multi-cloud Connectivity in Today's Internet](#2020-pam-ccfca-first-comparative-characterization-of-multi-cloud-connectivity-in-todays-internet)
      - [[2020 SecureComm CCFC]A Brokerage Approach for Secure Multi-Cloud Storage Resource Management](#2020-securecomm-ccfca-brokerage-approach-for-secure-multi-cloud-storage-resource-management)
      - [[2020 HPC CCFC]Running a Pre-Exascale, Geographically Distributed, Multi-Cloud Scientific Simulation](#2020-hpc-ccfcrunning-a-pre-exascale-geographically-distributed-multi-cloud-scientific-simulation)
    - [](#)
  - [**其他**](#其他)
    - [**2022**](#2022-3)
      - [[2022 CC]Reliable budget aware workflow scheduling strategy on multi-cloud environment](#2022-ccreliable-budget-aware-workflow-scheduling-strategy-on-multi-cloud-environment)
    - [**2021**](#2021-3)
      - [[2021 Access]A Resource Allocation Model Based on Trust Evaluation in Multi-Cloud Environments](#2021-accessa-resource-allocation-model-based-on-trust-evaluation-in-multi-cloud-environments)
      - [[2021 ESAN]EdgeNet: A Multi-Tenant and Multi-Provider Edge Cloud](#2021-esanedgenet-a-multi-tenant-and-multi-provider-edge-cloud)
      - [[2021 Access]A Resource Allocation Model Based on Trust Evaluation in Multi-Cloud Environments](#2021-accessa-resource-allocation-model-based-on-trust-evaluation-in-multi-cloud-environments-1)
      - [[2021 Access]DropStore: A Secure Backup System Using Multi-Cloud and Fog Computing](#2021-accessdropstore-a-secure-backup-system-using-multi-cloud-and-fog-computing)
      - [[2021 IJTD]A Requirements-Oriented Modelling Language for an Optimized Distribution of Business Processes on a Multi-Cloud Environment.](#2021-ijtda-requirements-oriented-modelling-language-for-an-optimized-distribution-of-business-processes-on-a-multi-cloud-environment)
      - [[2021 JAIHC]Cloud service recommendation system based on clustering trust measures in multi-cloud environment](#2021-jaihccloud-service-recommendation-system-based-on-clustering-trust-measures-in-multi-cloud-environment)
      - [[2021 JHSN]QoS and QoE aware multi objective resource allocation algorithm for cloud gaming](#2021-jhsnqos-and-qoe-aware-multi-objective-resource-allocation-algorithm-for-cloud-gaming)
    - [**2020**](#2020-3)
      - [[2020 ESOCC]Are Cloud Platforms Ready for Multi-cloud?](#2020-esoccare-cloud-platforms-ready-for-multi-cloud)
      - [[2020 PEARC]Demonstrating a Pre-Exascale, Cost-Effective Multi-Cloud Environment for Scientific Computing](#2020-pearcdemonstrating-a-pre-exascale-cost-effective-multi-cloud-environment-for-scientific-computing)



## **CCF A**

### **2022**

#### [TPDS 2022]Multi-Swarm Co-Evolution Based Hybrid Intelligent Optimization for Bi-Objective Multi-Workflow Scheduling in the Cloud【6】

**摘要：**

许多科学应用可以很好地建模为大规模的工作流。云计算已经成为托管和执行它们的合适平台。工作流调度近年来受到了广泛的关注。然而，由于云服务提供商必须为多个具有不同QoS要求的用户提供服务，**因此调度多个具有不同QoS要求的应用具有很高的挑战性**。针对多工作流调度问题，提出了一种基于多群协同进化的混合智能优化(MCHO)算法，**在满足每个工作流的截止时间约束的情况下，使总最大完工时间和成本最小**。首先，我们设计了一种多群体协同进化机制，采用三个群体充分搜索不同的精英解。其次，为了提高粒子群优化器的全局搜索和收敛性能，我们将局部和全局引导信息嵌入到粒子群优化器的更新过程中，并开发了一种群协作技术。第三，提出了一种基于遗传算法的精英增强策略，利用更多的非支配个体，并利用模拟退火的Metropolis接受规则更新每个群体的局部引导解，以防止其在早期陷入局部最优。大量的实验结果表明，MCHO算法具有更好的分布式非支配解，其调度性能优于现有调度算法。



### **2021**

#### [TS 2021]Multi-objective Optimization of Data Placement in a Storage-as-a-Service Federated Cloud【7】

**摘要：**

云联合使服务提供商能够相互协作，为客户提供更好的服务。对于云存储服务来说，**优化联邦成员的客户对象布局是一个真正的挑战。需要考虑存储、迁移和延迟成本**。在某些情况下，这些成本是相互矛盾的。在本文中，我们将对象放置建模为一个**多目标优化问题**。**建议的模型考虑了与本地基础设施、联邦环境、客户工作负载及其sla相关的参数**。为了解决这个问题，我们提出了CDP-NSGAIIIR，一种基于NSGAII的带有注入和修复函数的约束数据放置数学模型。注入功能旨在提高解决方案的质量。它包括用精确的方法计算一些解，然后将它们注入到nsgai的初始种群中。修复函数确保解决方案服从问题约束，从而防止探索大量不可行的解决方案。它大大减少了NSGAII的执行时间。实验结果表明，注入函数使NSGAII和精确方法的HV分别提高了94%和60%，而修复函数平均减少了68%的执行时间。



#### [TPDS 2021]Hierarchical Multi-Agent Optimization for Resource Allocation in Cloud Computing【6】

**摘要：**

在云计算中，**一个重要的问题是将服务节点的可用资源按需分配给被请求的任务，并使目标函数最优，即资源利用率、收益和可用带宽最大化**。本文提出了一种分层多agent优化(HMAO)算法，以使云计算的资源利用率最大化，带宽成本最小。该算法是遗传算法(GA)和多智能体优化算法(MAO)的结合。在资源利用率最大化的情况下，采用改进的遗传算法查找一组用于部署请求任务的服务节点。提出了一种基于分散的MAO算法，以最小化带宽开销。利用方法研究了关键参数对HMAO算法的影响，并对算法的性能结果进行了评价。结果表明，在解决大规模资源分配优化问题时，HMAO算法比两种基线算法遗传算法(GA)和快速精英非支配排序遗传算法(NSGA-II)更有效。此外，我们还比较了HMAO算法与两种启发式的Greedy算法和Viterbi算法在在线资源分配方面的性能。



### **2020**

#### [TPDS 2020]Location-Aware and Budget-Constrained Service Deployment for Composite Applications in Multi-Cloud Environment【8】

**摘要：**

企业应用程序提供商为了技术和经济利益，越来越多地将他们的工作负载转移到云上。多云环境使得协调多个云资源成为可能。随着多个云提供商在不同地点以不同价格提供的可用云资源数量的增加，**应用程序提供商面临着选择合适的云资源以组件服务单元工作流的形式部署其应用程序的挑战**。现有的研究通常考虑最小化执行时间或/和部署成本。然而，从应用程序提供者的角度来看，他们也非常关注应用程序的响应时间，特别是包括部署的服务和用户之间的网络延迟。同时，应用程序的部署通常受到严格的预算控制，以确保财务可行性。本文研究了一种新型的复合应用程序部署问题，该问题在全局尺度上**综合考虑了多云环境下的性能优化和预算控制**。为了在不产生超支风险的情况下以最小的响应时间找到解决方案，我们提出了一种基于混合遗传算法的方法，该方法设计了新的领域定制服务聚类、修复算法、解决方案表示、种群初始化和遗传算子。使用真实数据集的大量实验表明，我们提出的混合遗传算法优于最近提出的一些方法。



#### [TPDS 2020]Scheduling Periodical Multi-Stage Jobs With Fuzziness to Elastic Cloud Resources【6】

**摘要：**

研究了一类任务到达时间随机、任务处理时间和截止日期模糊的工作流调度问题**。这个问题在许多实时和基于工作流的应用程序中很常见，在这些应用程序中，具有固定阶段数和线性依赖关系的任务是在具有多种价格选项的可伸缩云资源上执行的。挑战在于如何在随机和模糊任务下提出有效、稳定和鲁棒的算法。建立了基于三角模糊数的模型。研究了两个度量标准:**成本和满意度。提出了一种迭代启发式的任务调度框架**，该框架由任务集合和模糊任务调度阶段组成。提出了两种任务收集策略和两种任务优先化策略。为了获得较高的满意度，在工作和任务级别上都定义了期限约束。通过精心设计的实验，并应用复杂的统计技术，实验结果表明，该算法比现有的两种方法具有更好的有效性和鲁棒性。



### **2019**

#### [TIFS 2019]Extensible Conditional Privacy Protection Authentication Scheme for Secure Vehicular Networks in a Multi-Cloud Environment【4】

**摘要：**

随着云服务提供商(csp)数量的增加，针对多云环境提供解决方案以避免厂商锁定和处理单点故障问题的研究工作已经大大扩展。然而，少数方案关注的是多云环境下车载网络的条件隐私保护认证。为此，我们提出了一种健壮、可扩展的车载网络认证方案，以满足用户日益多样化的业务需求。根据我们的解决方案，车辆只需要向可信授权机构(TA)注册一次，就可以与csp实现快速、高效的身份验证。此外，只要新的CSP在TA成功注册，它就可以参与车辆服务。由电讯局长管理的云代理负责连接所有云服务;因此，用户看不到csp选择的复杂性。详细的安全分析表明，该方案能够实现有条件的隐私保护，实现车载网络的安全目标。该方案基于椭圆曲线密码体制，不采用复杂的双线性对运算。对该方案的性能评估表明，该方案适用于涉及车辆网络的应用。



#### [TKDE 2019]NewMCOS: Towards a Practical Multi-Cloud Oblivious Storage Scheme【4】

**摘要：**

加密本身不足以保护数据隐私，因为访问模式会泄露一些敏感信息。健忘RAM (ORAM)是这个问题的解决方案，但对于存储和通信/计算开销巨大的实际部署来说，它仍然任重道远。为了减少它们，提出了一种很有见地的想法，即利用非云来将客户端计算和客户端云通信转移到云上。提出的多云ORAM实现了O(1)客户端云带宽成本，并消除了大部分客户端计算。在本文中，我们利用“断开连接的ORAMoperation”和设计“两层加密”来进一步减少这些开销。实验表明，与其他方案相比，我们提出的新mcos方案显著降低了从GB/MB到KB级别的驱逐缓存大小，响应时间降低了约2-3倍，云带宽节省了20%。从理论上讲，我们将逐出缓存的大小从O(VN)减少到O(ZK)，其中N是真实数据块的数量，K是云的数量(2 <;K <;<;VN)， Z是客户端上传的用于驱逐的实际块数。通过采用“延迟逐出操作”，写入频率降低了O(Z)，洗牌带宽开销降低了Q(Z log Z)，同时证明了NewMCOS的安全性。

 

## **CCF B**

### **2022**

#### [SPE 2022]Towards cloud-based unobtrusive monitoring in remote multi-vendor environments【4】

**摘要：**

如今，许多复杂的多供应商生产环境，如智能城市中的电信基础设施或火车上的乘客信息系统，都是基于微服务并部署在云中。从服务集成商的角度来看，为这些环境构建新的解决方案(这些环境可以承载大量外部设计和开发的微服务)通常是复杂且容易出错的。这部分是由于此类系统的无文档化行为或无文档化架构规范造成的。高级服务监控可以提供一种解决方案，在现场集成期间快速检测异常或意外的服务交互行为。但是，监视服务不应该对生产环境本身产生影响。因此，本文提出了一种基于代理的不显眼的监视平台，能够通过使用sidecar容器监视内部开发的和外部开发的服务。它监控微服务水平上的状态、指标和网络流量，该研究是DynAMo研究项目的一部分，该项目是与多个行业合作伙伴合作进行的。原型评估证明，我们的解决方案对现有微服务环境的影响可以忽略不计(平均CPU使用量低于0.02%)，就像Prometheus等其他监控系统一样，同时提供了专注于多供应商服务集成的额外功能。这使得它适用于复杂的生产领域，进一步帮助现场集成，并快速发现潜在的新异常。



#### [ASTS 2022]Efficient multi-attribute precedence-based task scheduling for edge computing in geo-distributed cloud environment【8】

**摘要：**

为了实现云计算的全球化，不同云提供商的不同服务联合使用已成为必然趋势。地理分布式云由几个不同的云组成，为云计算提供了一个通用的环境。在数据放置方面，最近提出的许多数据放置算法都单方面地使用单一的性能指标来评价算法的性能。在任务调度中，当分配任务的云资源过多时，会造成资源的浪费。当分配给复杂任务的云资源较少时，导致系统整体进度停滞，系统整体进度停滞。针对上述问题，提出了数据布置方法和任务调度方法。在提出的数据放置方案中，考虑了多个性能指标。在任务调度过程中，考虑了稀疏节点的检测和云资源的合理分配。为了证明所提方法的优越性，进行了大量的实验。的数据位置,当文件数量设置为8 oo,提出数据布局算法的安全水平为7.0,高于27.3%的国内流离失所者算法,GA-DPSO算法的高出45.8%和16.7%高于H2DP算法。在任务调度方面，本文提出的任务调度方法对时间开销的改进百分比最低，说明本文提出的任务调度算法的时间开销最接近最优时间，也是最短的。



### **2021**

#### [CJ 2021]A proposed framework for cloud-aware multimodal multimedia big data analysis toward optimal resource allocation【6】

**摘要：**

本文的主要目标是演示云平台(MMSCP)中多模式多媒体服务的结构设计。因此，我们提出的MMSCP体系结构分为服务平台、执行平台和结构平台三个层次。服务平台的功能是将媒体创作者生成的不同形式的视频文件收集起来，存储在本地平台上。第二个执行平台集成了Hadoop和Mapreduce功能。最后，基于QoS的云计算功能(即负载均衡、安全、资源分配和网络流量管理)被用于第三个结构平台。很可能，我们在结构平台中引入了乌鸦搜索算法(CSA)来优化资源配置。我们采用一个Hadoop集群来执行这个实验。此外，为了进行资源分配实验，我们使用了一些传统的优化算法，如ABC、GA和PSO，并与我们提出的CSA算法在结构平台上进行了比较。然而，为了评估算法的性能，我们配置了CloudAnalyst工具。仿真结果表明，该算法能够以最小的响应时间对虚拟机进行最优分配。



#### [2021]Location-Aware and Budget-Constrained Service Brokering in Multi-Cloud via Deep Reinforcement Learning【7】

**摘要：**

多云使得有效利用位于不同位置的多个云提供商提供的各种云服务成为可能。为了处理对延迟敏感的应用程序的请求，云代理必须在多云环境中选择合适的云服务，以最小化网络延迟，同时避免出现超支的风险。在多云环境中，位置感知和预算约束的服务代理问题需要一种机器学习方法来处理高度动态的请求。在本文中，我们应用深度强化学习来解决这个问题。提出的算法名为DeepBroker，可以动态地、自适应地在多云中为新到达的请求在全球范围内选择虚拟机。具体来说，DeepBroker通过使用深度q网络结合新设计的状态提取器和动作执行器来训练代理策略。为了确保财务可行性，我们引入了基于罚款的奖励功能，以防止超支的情况。基于真实数据集的评估表明，在网络延迟最小化和预算满意度方面，DeepBroker可以显著优于几种常用的基于启发式算法。



#### [CC 2021]Truthful online double auction based dynamic resource provisioning for multi-objective trade-offs in IaaS clouds【7】

**摘要：**

拍卖设计最近被用于laaS云中的静态和动态资源供应，比如Microsoft Azure和Amazon EC2。然而，现有机制大多局限于简单的拍卖、单一目标、离线设置、云用户或云服务提供商(csp)之间的单向互动，以及云用户私人信息可能出现的误报。在云数据中心基于时间的服务器维护下，利用云用户请求时变到达的弹性特性，提出了一种更加现实的laaS云在线拍卖场景。我们提出了一种在线真实双拍卖技术来平衡laaS云中能量、收益和性能之间的多目标权衡，其中，基于加权二部匹配的中标算法用于资源分配，基于Vickrey Clarke Groves (VCG)驱动的中标支付计算。通过严格的理论分析和利用谷歌集群工作负载跟踪的广泛跟踪驱动模拟研究，我们证明了我们的机制在保证真实性、异质性、经济效率、个体合理性的同时显著提高了性能，并具有多项式时间的计算复杂性。

 

#### [CN 2021]Game-based distributed pricing and task offloading in multi-cloud and multi-edge environments【7】

使cloud-edge协作物联网(很多)系统可以更好的满足移动设备的应用程序需求(MDs)。在云服务提供商(CSPs)和边缘服务提供商(esp)共存的环境下，设计一种机制来实现竞争激烈的loT市场中CSPs和esp的收益最大化，优化MDs的体验质量(QoE)是至关重要的。现有工程很少考虑到这一领域。为此，我们提出了一种针对多云、多边缘loT环境的分布式定价和任务卸载机制。我们引入一个多领导者多follower两层Stackelberg博弈模型来模拟服务提供者与服务提供者之间的交互。我们进一步设计了两种分布式算法，即迭代近端卸载算法(IPOA)和迭代Stackelberg博弈定价算法(ISPA)。前者解决了MDs之间的跟随者非合作博弈问题，后者利用逆向归纳法处理服务商之间的价格竞争问题。实验结果表明，与其他传统的任务卸载方案相比，IPOA能显著降低MDs的负效用，且无状态代价(PoA)始终小于2。此外,结果还表明,当前提高服务提供者的收入,同时保证可靠MDs的体验质量。



#### [JPDC 2021]A novel cooperative resource provisioning strategy for Multi-Cloud load balancing【8】

云计算的范式预示了计算的新途径，以低成本提供了增加数据可访问性的好处。连续编写应用程序(CWA)(例如，为医疗保健提供的增强在线服务)对数据存储、计算和带宽有特定的要求，因此在预算和时间有限的情况下对成本很敏感。为此，我们提出了一种由多云服务提供商(CSP)或“多云”为CWA提供服务的体系结构，并设计了一种新的资源调度算法以使系统成本最小化。为了满足用户在MCP上对资源的需求，利用经典的CWAs系统模型。该研究有助于了解不同资源的特点，并得出结论:对许多CWA实现来说，多云是最有吸引力的。介绍了多个csp的互连及其负载路径(即通过可能互连的数据)。在此基础上，提出了基于系统负载路径最小一阶导数长度(MFDL)的最优用户调度问题。理论分析表明，所提出的算法能够以最小的成本获得最优的多云用户调度方案。通过对不同影响因素的严格仿真，证明该策略在许多实际场景中具有可扩展性、灵活性和有效性。

 

#### [JSA 2021]TOPSIS inspired Budget and Deadline Aware Multi-Workflow Scheduling for Cloud computing【7】

调度是一种决策机制，它通过确定活动在可用资源上的执行顺序，允许在多个活动之间共享资源。在异构分布式系统中，如何调度不同用户在不同时间提交的并发工作流是一个很大的挑战。由于云动态特性(如按需供应、弹性、丰富的资源类型和各种定价方案)，对云系统来说，有截止日期和预算限制的调度变得更加具有挑战性。为了优化系统性能和最终用户满意度，需要一个管理良好的预算和期限约束调度。因此，提高系统性能，同时优化多个调度条件是一个很大的挑战。针对这些问题，提出了一种基于多准则决策(MCDM)方法的多工作流调度算法——TOPSIS (Order Preference by Similarity To Ideal Solution)。根据任务需求，利用运行时间、成本和数据传输时间的加权和确定可用资源中的最优资源。与基于预算约束、期限约束的异构最早完工时间算法(Budget-Heterogeneous early Finish Time, BHEFT)、基于预算约束、期限约束的异构最早完工时间算法(Cloud-based Workflow Scheduling algorithm, CWSA)进行了性能比较。和资源利用率。实验结果表明，提出的T-BDMWS在达到用户指定的预算或期限约束和资源效率的标准下，优于目前最先进的启发式算法。

 

#### [JSS 2021]Tuning configuration of apache spark on public clouds by combining multi-objective optimization and performance prediction model【6】

为部署在公有云中的Spark选择正确的配置以确保周期性作业的高效运行是一件困难的事情，因为需要探索的配置空间非常大，这些配置由不同维度(如应用级和云级)的大量性能相关参数组成。选择不当不仅会显著降低性能，还可能导致更大的开销。然而，自动搜索各种应用程序的最佳配置以权衡性能和成本是一个挑战。针对这一问题，将多目标优化算法与性能预测模型相结合，提出了一种新的优化配置搜索算法AB-MOEA/D。AB-MOEA/D采用基于分解的多目标优化算法来寻找以执行时间和成本最小为目标的配置，其中使用Adaboost算法构建的性能模型来评估每个候选配置的适合度。此外，我们还介绍了以AB-MOEA/D为优化引擎的组态自动调优系统。在5个数据集的6个基准上的实验结果表明，AB-MOEA/D在执行时间和成本方面显著优于之前的工作，平均提高了约35%和40%。



#### [SoCC 2021]Mind the Gap: Broken Promises of CPU Reservations in Containerized Multi-tenant Clouds【6】

容器化正变得越来越流行，但不幸的是，容器常常不能通过分配的资源提供预期的性能。在本文中，我们首先演示了在容器共存的多租户环境中，性能差异和降低是显著的(高达5倍)。然后我们研究这种性能下降的根本原因。通常认为这种降级是由资源争用和干扰引起的，与此相反，我们发现一个容器的CPU储量与实际获得的CPU数量之间存在差距。其根本原因在于当今Linux调度机制的设计选择，我们称之为强制运行队列共享CPU时间。事实上，在保留CPU资源的需求和complete Fair Scheduler的工作节约特性之间存在着根本的冲突，这种矛盾阻碍了容器充分利用其请求的CPU资源。作为概念证明，我们在广泛使用的Kubernetes和Linux之上实现了一种新的资源配置机制，以展示其潜在的好处，并为未来的调度程序重新设计提供了启示。我们的概念证明，与现有的调度器相比，批处理和交互式容器化应用程序的性能提高了5.6倍和13.7倍。



#### [TSC 2021]A QoS-Based Splitting Strategy for a Resource Embedding Across Multiple Cloud Providers【4】

在云计算中，基础设施即服务模型的一个基本管理问题在于如何高效地将计算和网络资源嵌入到分布式虚拟化基础设施中。这个问题通常被称为虚拟网络嵌入(VNE)问题，已经针对单个云提供商(CP)进行了很好的研究。然而，广域服务交付可能需要在多个CPs上嵌入异构资源。这增加了更多的复杂性和可伸缩性问题，因为虚拟网络请求(VNR)嵌入过程需要两个操作阶段:多云VNR拆分，然后是内云VNR段映射。本文提出了一种VNR分割策略，以提高生成的VNR段的性能和QoS。利用整数线性规划(ILP)将分裂相位问题形式化为带约束的最大化问题。然后，为了最小化总体延迟，采用了一种形式化为混合整数线性规划(MILP)的多目标内云资源映射方法。通过仿真验证了该方法的有效性。其中，接受率和延迟分别提高了15.1和18.5%，同时防止违反QoS。



#### [MobiHoc 2021]Joint Update Rate Adaptation in Multiplayer Cloud-Edge Gaming Services: Spatial Geometry and Performance Tradeoffs【4】

本文分析了多人云游戏(MCG)系统的性能。为此，我们引入了一个模型和新的mcg服务质量(QoS)指标，用来捕捉玩家更新的新鲜度和游戏体验的公平性。我们引入了一种高效的基于测量的联合多人速率适应(JMRA)算法，该算法通过增加相关玩家的更新速率来克服大的(可能变化的)网络传输延迟，从而优化MCG-QoS。由此产生的MCG-QoS在网络延迟中显示为schur凹，导致与玩家的空间几何和网络拥塞相关的自然特征和性能比较。特别是，联合速率适应使服务提供商能够应对网络延迟的变化，以及玩家的地理分布，从而实现高服务覆盖率。这反过来又允许我们探索需要提供的计算资源的空间密度和容量。最后，我们利用优化理论中的工具，来展示如何做出服务布局决策，以提高MCG-QoS对随机网络延迟的鲁棒性。

 

#### [TSC 2021]A Game-Based Price Bidding Algorithm for Multi-Attribute Cloud Resource Provision【7】

云计算资源的定价机制对云客户和服务提供商来说都是一个至关重要的问题，特别是从多提供商竞争的角度来看。虽然提出了各种资源提供机制，但很少有研究关注多属性资源提供，以提高云客户和服务提供商的利益。为了解决这个问题,我们提出一个多属性的竞价机制提供云计算资源从非合作博弈的角度,在每个玩家的信息(客户和供应商)对他人是不完整的,每个玩家希望他/她自己的利益最大化。更具体地说，在考虑公平定价竞争的情况下，我们提出了一种基于服务质量(QoS)和投标价格的激励资源提供模型。然后，结合资源提供模型，将价格竞标问题构建为一个博弈，为每个云供应商寻找合适的价格。我们通过假设每个提供者提供的资源的数量函数是连续的，证明了所建立的博弈模型纳什均衡解集的存在性。为了找到一个纳什均衡解，我们提出了一个均衡解迭代算法，并证明了该算法收敛于一个纳什均衡。最后，提出了一种近似均衡竞价(NPB)算法来修正得到的纳什均衡解。大量的仿真实验结果以及与当前最先进的解决方案和基准方案的对比实验验证了该方法的可行性。





### **2020**

#### [SPE 2020]A multicriteria optimization model for cloud service provider selection in multicloud environments【7】

多云计算是一种策略，可以帮助客户减少对任何单一云提供商的依赖(称为供应商锁定问题)。这种战略的价值随着适当选择合格的服务提供者而增加。本文提出了一种有约束的多准则多云提供商选择数学模型。采用模拟退火算法(SA)、遗传算法(GA)和粒子群优化算法(PSO)三种元启发式算法对模型进行求解，并通过一个假设案例对其性能进行了研究和比较。为了比较，采用田口的稳健设计方法来选择算法的参数值，采用层次分析法(AHP)生成初始可行解，这是文献中解决云提供商选择问题最常用的方法，三种算法都采用了该解，并且，为了避免层次分析法的局限性，三种算法随机生成另一个初始解，并在第二组性能实验中使用。结果表明，SA、GA、PSO分别将AHP解提高了53.75%、60.41%和60.02%，SA和PSO在初始解不变的情况下仍能得到相同的最优解，具有较强的鲁棒性。



#### [ICWS 2020]Location-Aware and Budget-Constrained Application Replication and Deployment in Multi-Cloud Environment【7】

为了获得技术和经济利益，企业应用程序提供商越来越多地将他们的工作负载转移到云上。随着来自不同地点、价格不同的多家云提供商的云资源数量的增加，应用程序提供商面临的挑战是选择合适的云资源来复制和部署应用程序，以保持低响应时间和高质量的用户体验，同时又不会遇到超支的风险。在本文中，我们研究了全球范围内的云应用程序复制和部署问题，考虑了应用程序的平均响应时间，特别是应用程序执行时间和网络延迟，并在预算控制的情况下。为了解决这一问题，我们提出了一种基于遗传算法的方法，该方法具有领域定制的解决方案表示、适应度测量和种群初始化。使用真实世界的数据集进行的大量实验表明，我们提出的基于GA的方法显著优于常见的应用放置策略，即NearData和NearUsers，以及我们最近提出的混合GA方法。





### **2019**

#### [JPDC 2019]Managing renewable energy and carbon footprint in multi-cloud computing environments【5】

云计算为服务提供商和客户提供了有吸引力的功能。用户可以从“现收现付”模式中节省开支，而服务提供商也将他们的服务部署到云数据中心以减少维护工作。然而，由于云数据中心的快速发展，数据中心所消耗的能源会导致大量的碳排放，并对环境造成影响，不同的能源来源，不同的电厂在不同地点的碳强度是不同的。因此，在本文中，为了解决数据中心的碳排放问题，我们考虑在位于不同时区的多云之间转移工作负载。我们还制定了数据中心的能源使用和碳排放，并建立了相应位置的太阳能模型。这有助于减少棕色能源的使用，并在不同的地点最大限度地利用可再生能源。我们提出了一种方法，为位于不同时区的加利福尼亚、弗吉尼亚和都柏林的多个数据中心管理碳足迹和可再生能源。结果表明，在保证用户请求的平均响应时间的同时，我们提出的应用工作负载转移的方法可以比基线减少约40%的碳排放。





## **CCF C**

### **2022**

#### [2022 NCA CCFC]Correction to: Multi-objective hybrid genetic algorithm for task scheduling problem in cloud computing

云计算系统是一种共享的附属结构，从一开始就有这种需求。在这些系统中，客户可以根据自己的需求访问现有的服务，而不需要知道服务的位置和交付方式，只需要为所使用的服务付费。与其他系统一样，云计算系统也存在挑战。由于在这个系统中有广泛的客户和各种各样的服务，可以说，调度问题，当然，能源消耗是这个系统的基本挑战。因此，它应该适当地提供给用户，使供应商和消费者的成本和能量消耗都最小化，这需要使用最优的调度算法。本文提出了一种基于遗传算法和基于遗传算法的能量敏感调度启发式两步混合调度方法。第一步是对任务进行排序，第二步是将任务分配给处理器。我们对任务进行排序，生成主染色体，并使用能量意识调度启发式模型(Energy-Conscious Scheduling Heuristic model)将任务分配给处理器。仿真结果表明，该算法的性能优于其他算法。





### **2021**

#### [2021 FCS CCFC]An improved multi-objective evolutionary algorithm for computation offloading in the multi-cloudlet environment

云计算从网格计算、效用计算和软件即服务(SaaS)发展而来，是一种管理互联网上IT服务的颠覆性技术。经过最初的怀疑之后，跨国公司正广泛地将它们的IT工作转移到私有和公有云上，以优化地理覆盖范围，并推出新的数字服务。目前，混合和多云环境在管理服务质量(QoS)方面带来了额外的复杂性，因此需要更复杂的服务水平协议(Service Level agreement, sla)。为了解决这些问题，我们的研究开发了一个支持sla的精益信息服务体系结构(LISA)，用于管理在整个服务生命周期中支持用户的多云环境。LISA的性能在一家全球电信运营商的创新实验室进行了测试，通过在私有云和公共云提供商上部署服务。实验结果证明了LISA在防止SLA违规和业务性能下降、优化Qos、控制跨多个公有云提供商部署的业务组件等方面的有效性和有效性。



#### [2021 ICCC CCFC]Cost-Effective Dynamic Optimisation for Multi-Cloud Queries

最近，通过各种数据库即服务(Database-as-a-Service, DBaaS)提供商提供公共数据已经成为一个重要的趋势，得到了各大组织的支持。本文介绍了Nebula，这是一个非盈利的中间件，通过将用户的查询完全外包给相关的DBaaS提供商来提供多云查询功能。首先，我们为这些查询提出了一个引用过程，这些查询的需求源于提供者的“按查询付费”策略。这些报价包含货币成本和响应时间估计，并使用供应商生成的投标来计算。然后，我们提供了一个基于代理的动态优化引擎，它协调查询的外包执行。该引擎内的代理商合作，以满足报价的价值。我们通过使用联合订单基准(JOB)来评估Nebula与模拟提供商之间的关系。实验结果表明，在大多数情况下，与现有的多云DBMS文献相比，Nebula的方法在货币成本和响应时间方面更具竞争力。



#### [2021 JNCA CCFC]A Survey and Comparative Study on Multi-Cloud Architectures: Emerging Issues And Challenges For Cloud Federation

多云的概念已经拓宽了云计算的世界，并成为今天的一个流行词。“多云”一词的意思是通过客户场所的单一架构，利用来自多个异构云提供商的服务。尽管云计算存在许多问题，提供了开放的研究挑战，但学术界和工业界的研究仍为多云环境铺平了道路。多云的概念正处于成熟阶段，许多研究项目正在进行中，以提供一个在易配置、安全、管理等各个方面都成功实现的多云架构。本文讨论了云环境的概念、挑战、需求和未来的发展方向。本文综述了不同的云架构提供的现有方法和解决方案，分析了不同架构的优缺点，并对其进行了比较。



#### [2021 BD CCFC]Performance Profile of Transformer Fine-Tuning in Multi-GPU Cloud Environments

本文的研究重点是在多gpu环境中，在现场云计算资源和商业云服务(Azure)上运行机器学习任务的性能特征和权衡。具体来说，本研究通过检查基于变压器的深度学习(DL)网络在临床记录和数据上的训练和微调的性能来研究这些权衡，这在医学领域是一项至关重要的任务。为此，我们在广泛部署的NVIDIA V100 gpu和通过NVLink或PCle连接的较新的A100 gpu上进行了dl相关的实验。本研究分析主要操作的执行时间，以训练DL模型，并调查流行的选项，以优化每一个。我们检查并展示了各种操作(例如数据加载到gpu、训练、微调)、优化和系统配置(单gpu vs多gpu、NVLink vs PCle)对整体训练性能的影响的结果。

 

#### [2021 CCGrid CCFC]Security aspects in blockchain-based scheduling in mobile multi-cloud computing

随着移动云计算服务的密集发展和普及，迫切需要引入新的解决方案，以提高云计算和用户安全水平。任务调度是高分布式计算系统的关键问题之一。此过程可能会暴露于许多外部和内部的安全威胁，如任务注入、机器故障或生成不正确的调度。这些问题在移动环境中尤为重要。如果我们考虑到所提供服务的个性化，情况可能会更加复杂。最近，区块链迅速流行起来，它将高效与分布式和高度个性化的计算环境中的应用程序相结合。本文基于区块链技术开发并描述了一种新的云计算安全感知任务调度模型。与其他基于区块链的解决方案不同，该模型使用了权益证明(Proof of Stake)，对计算能力要求不高。一系列实验验证了该模型的有效性。



#### [2021 IPCCC CCFC]Diagnosing the Interference on CPU-GPU Synchronization Caused by CPU Sharing in Multi-Tenant GPU Clouds

随着GPU虚拟化技术的成熟，GPU加速云已经成为最具吸引力的高性能计算和机器学习工作负载平台。然而，构建多租户的GPU云是一个众所周知的挑战，在那里可以共享cpu和GPU等资源。一个众所周知且被大量研究的原因是，当GPU被共享时，工作负载会受到性能隔离不良和GPU利用率低的影响。但是，对于另一个尚未被研究的基本问题却很少有人关注:GPU实例之间共享cpu会如何影响工作负载性能?针对这一问题，本文通过实验测量CPU共享干扰下的性能下降和vGPU利用率下降。结果表明，由于CPU的共享，GPU工作负载的性能较差且不可预测，vGPU利用率较低。我们发现，这种干扰是CPU-GPU交互特性与共享vCPU的特殊行为——vCPU不连续之间复杂相互作用的结果。为了诊断vCPU中断是如何导致干扰的，本文利用NVIDIA Nsight系统进行细粒度分析，发现如下:1)vCPU中断导致CPU-GPU同步效率低下;2) vCPU中断延迟了任务的卸载到vGPU;3)基于轮询的CPU-GPU同步比基于阻塞的CPU-GPU同步受到更多干扰;4)频繁的任务卸载和同步的GPU工作负载更容易受到攻击。在此基础上，提出了一种基于轮询阻塞的CPU-GPU同步原语。通过评价，可以提高4.2倍的性能。

 

#### [2021 CCGrid CCFC]Fuzzy-Engineered Multi-Cloud Resource Brokering for Data-intensive Applications

对于需要高规模、多样性和弹性的应用程序来说，多云资源代理正成为一种关键需求。应用需要及时选择分布式数据存储和计算平台，这些平台既可以跨本地私有云资源，也可以跨多个云服务提供商(csp)资源。不同的功能和策略，以及云服务的性能/成本，都是选择CSP的主要因素。然而，在社区/公共云中需要合适的网络资源的应用程序所有者往往对某些csp有初步的了解和偏好。他们也缺乏专家指导来处理csp资源选择过多的问题，并优化以弥补服务动态。在本文中，我们通过基于性能、敏捷性、成本和安全性等复杂因素的多级模糊逻辑建模，解决了优化资源选择的挑战，同时利用有限的用户专业知识和对csp的偏好。我们通过案例研究和CSPs评估的独立验证来评估我们的模糊工程资源代理在改善资源配置和用户满意度方面的效率。





### **2020**

#### [2020 JNCA CCFC]MultiCloud Tournament: A cloud federation approach to prevent Free-Riders by encouraging resource sharing

通过联合组织，云计算提供商能够以更有吸引力的价格从其他提供商那里获得资源，同时允许将自己的闲置资源销售给各自的云计算联盟的其他成员。然而，云间关联的特征是资源共享环境，这允许被称为“搭便车者”的恶意提供者的存在。“搭便车者”具有掠夺性行为，只寻求为自己的利益服务，从而损害环境中的其他提供者。在云联盟等云间环境中，需要一些机制来避免搭便车，以及保持资源供应与需求的平衡。例如，资源消耗控制机制的缺失可能导致“搭便车者”以一种与提供给Inter-Cloud的方式不相称的方式消耗资源，就像前面描述的问题一样。鉴于上述情况，本文提出了一种名为multicloud Tournament (MCT)的新型跨云竞赛，旨在解决独立云提供商的限制。这个Inter-Cloud的灵感来自于足球比赛的形式，并基于Cloud Federations的主要特征。我们使用一个实际的工作负载对MCT进行了评估，显示它提供了一种增加了联盟特征的体系结构，在csp的管理中是有效的，在防止搭便车和csp的主要策略方面是强大的。



#### [2020 JETAI CCFC]Bi-objective web service composition problem in multi-cloud environment: a bi-objective time-varying particle swarm optimisation algorithm

云计算成为必然的信息技术产业。尽管它有一些优点，如规模经济和快速弹性，但它面临供应商锁定、资源限制和网络安全攻击，导致业务中断甚至业务失败。另一方面，多云可以是一个可靠的范例，可以消除前面提到的单一云的令人不快的特性等障碍。最大的挑战之一是，就安全目标而言，知道哪种云与用户的业务流程是相称的。为此，提出了一种量化用户业务流程云安全风险的新方法。因此，本文将web服务组合问题表述为在不断增长的多云环境(MCE)下，每个提供商的定价策略都是可变的，安全级别也不同的，具有服务成本和多云风险观点的双目标优化问题。这显然是一个NP-Hard问题。为了解决组合问题，我们提出了一种双目标时变粒子群优化算法(BOTV-PSO)。这些参数是根据运行时间调整的，因此可以在探索和开发之间实现良好的平衡。为了说明该算法的有效性，我们定义了几种场景，并与多目标遗传算法(MOGA)优化器、只优化成本函数而忽略CSR的单目标遗传算法(SOGA)和多目标模拟退火算法(MOSA)进行了性能比较。实验结果表明，所提出的BOTV-PSO算法在收敛性、多样性、适应度、性能甚至可扩展性等方面都优于其他算法



#### [2020 GECCO CCFC]Divide and conquer: Seeding strategies for multi-objective multi-cloud composite applications deployment

多云复合应用程序部署问题(MCADP)旨在从不同位置的多个云提供商中选择合适的云资源，部署具有共享组成服务的应用程序，以优化性能和成本。在本文中，我们提出了分而治之的播种策略，以找到多样化和高质量的种子部署方案。通过使用真实数据集，实验结果表明，所提出的种子策略可以优于最近提出的方法，如AO-Seed和SO-Seed，对于MCADP。

 

#### [2020 ICONIP CCFC]ANN-Assisted Multi-cloud Scheduling Recommender

云计算已经被广泛采用，以公共云和私有云的形式，有许多好处，例如可用性和成本效率。在本文中，我们解决了跨多个云(包括私有云)调度作业的问题，以在考虑数据隐私的情况下显式优化成本效率。特别是，本研究中的问题涉及几个因素，如工作的数据隐私，私有云的不同电价，以及公共云的不同计费政策/周期，大多数(如果不是全部的话)现有调度算法没有“集体”考虑。为此，我们设计了一个由一种新的调度算法和一个基于网络的推荐器组成的网络辅助的多云调度推荐器(MCSR)框架。前一种调度算法可以单独对作业进行调度，但其输出调度也作为后一种推荐算法的训练数据。使用真实的Facebook工作负载数据和更大规模的合成数据进行的实验表明，我们的基于ann的推荐器能够在尊重隐私的情况下成本有效地安排工作。



#### [2020 NOMS CCFC]A Cloud-Agnostic Framework to Enable Cost-Aware Scheduling of Applications in a Multi-Cloud Environment

我们已经见证了由各种云供应商托管的大数据应用程序的激增，以及它们每天产生和消耗的天文数字数据量。传统的集群计算框架由于其有限的可伸缩性和跨异构云的适应性，难以应对前所未有的数据量和地理分布、跨云的数据分布。此外，随意跨云运行数据密集型应用程序的成本非常低，而且很可能招致巨额开支。因此，我们引入了云无关系统PIVOT和新颖的成本感知调度算法，该算法允许数据密集型应用程序以经济高效的方式跨云运行和扩展。我们对我们的系统和调度算法进行了广泛的评估，通过阿里巴巴生产集群的跟踪，以及真实世界的大数据应用，在AWS和GCP上部署了跨越11个地区(31个可用区域)的100个节点。实验结果表明，与最先进的基线相比，PIVOT在虚拟机订阅费用和出口网络流量方面分别节省了90.8%和99.2%。值得注意的是，对于数据密集型应用程序，成本感知调度还可以实现4倍以上的数据传输速度。

 

#### [2020 PAM CCFC]A First Comparative Characterization of Multi-cloud Connectivity in Today's Internet

今天的企业正以前所未有的速度采用多云策略。这里，多云策略指定了企业运行业务所依赖的多个云提供商(CPs)之间的端到端连接。这种采用是由大型CPs快速构建的全球规模的私有骨干网推动的，这种骨干网是一种连接它们的丰富的私有对等网络，以及新的第三方私有连接提供商(如DataPipe、HopOne等)的出现。然而，我们对与当前可用的多云连接选项相关的性能方面、路由问题和拓扑特性知之甚少。为了阐明这些可用的连接性选项之间的权衡，我们从云到云的角度，并在本文中介绍了一个以云为中心的测量研究的结果，该研究对一个位于美国的典型现代企业可能采用的海岸到海岸的多云部署进行了研究。我们将vm部署在两个区域(例如,VA和CA)三大的每一个云提供商(例如,AWS, Azure和GCP)连接起来,使用三种不同的选择:(i)交通机构的最优公共网络(cep),(2)第三方机构提供私人(TPP)连接,和(3)CP-based私人(CPP)连接。通过在现实世界的多云部署中进行主动测量，我们对TPP性能的可变性、CPP性能和拓扑结构的稳定性以及CPP运输供应商的缺失提供了新的见解。



#### [2020 SecureComm CCFC]A Brokerage Approach for Secure Multi-Cloud Storage Resource Management

如今,越来越多的云客户使用多个云服务提供商(CSP)将它们的数据存储在云,因为它提供了更好的数据可用性和服务比存储在单个CSP的依赖。然而，在多云场景中，云客户在为云终端用户(用户或服务)安全管理云存储资源时面临着几个挑战，如在多个CSP中实现不同的ap和服务实现，因为CSP不需要遵守云计算标准和多云资源管理技能差距。在本文中，我们提出了一个统一的多云存储资源管理框架，用于管理对象存储和身份与访问管理服务的云存储资源及其配置。我们提出了一个统一的云存储资源模型，继续我们之前的工作，以解决多个csp中云存储资源的各种数据和云访问控制模型。在统一模型的基础上，我们引入了一个统一的多云存储资源管理平台，用于对Amazon Web Services和谷歌cloud两种主流公共csp开发的云存储资源进行管理，并对云终端用户的访问权限进行授权/撤销。统一平台收集和处理信息的云存储资源,让云客户发现、创建、删除、修改、评价和监控云存储资源跨各种csp。

 

#### [2020 HPC CCFC]Running a Pre-Exascale, Geographically Distributed, Multi-Cloud Scientific Simulation

随着我们接近Exascale时代，重要的是要验证现有的框架和工具仍将在这个规模下工作。此外，公共云计算已经成为原型和紧急计算的可行解决方案。利用云的弹性，我们已经放置了一个前百亿亿级HTCondor设置，用于在云中运行科学模拟，选择的应用程序是IceCube的光子传播模拟。也就是说，这不是一个纯粹的演示运行，但它也被用来产生有价值和非常需要的科学成果冰立方合作。为了达到预期的规模，我们聚集了来自Amazon Web Services、Microsoft Azure和谷歌云平台多个地理区域的8种GPU模型的GPU资源。使用这种设置，我们达到了超过51k GPU的峰值，对应于380 PFLOP32s，总的集成计算GPU小时约为100k。在这篇文章中，我们提供了设置的描述，发现和克服的问题，以及练习的实际科学产出的简短描述。

 

### 

## **其他**

### **2022**

#### [2022 CC]Reliable budget aware workflow scheduling strategy on multi-cloud environment

摘要：在多云环境中使用现收现用框架的资源供应和工作流执行最近引起了云计算研究社区的注意。由于云的动态特性，特别是异构资源类型、多重计费机制、弹性、按需供应和系统可靠性，在多云平台中调度工作流是一项挑战。此外，这些工作流应用程序有一个运行时约束——最典型的是执行时间和执行成本。另一个至关重要的服务质量(QoS)度量是可靠性。提出了一种基于规范化的可靠预算约束工作流调度(NRBWS)算法，在用户指定的预算约束下，提高了工作流的执行可靠性，降低了工作流的最大完工时间。这个方案经历了一个最小归一化过程，这个过程后面是期望合理预算(erb)的计算，以将任务分配给一个计算资源。NRBWS算法通过在分配的预算范围内将每个工作流任务分配给最可靠、完成时间最早的计算资源来降低完成时间。仿真结果表明，该算法的性能优于现有的启发式算法。

 

### **2021**

#### [2021 Access]A Resource Allocation Model Based on Trust Evaluation in Multi-Cloud Environments

在云环境中，考虑服务质量的资源分配和管理是一个基本而复杂的研究问题。一个最优的资源分配优化几个参数，如优化成本和资源利用或最大化任何质量参数。然而，为了确保更好的客户服务，云服务提供商(csp)在为云基础设施分配资源时应该考虑大多数质量属性。现有的研究没有将信任作为一个量化的属性进行评价，因此在研究领域也缺乏信任与资源配置绩效之间的权衡。本文提出了一个同时考虑信任和延迟的模型。CSP的信任是通过一些属性和度量来定量估计的。通过考虑可用性、可靠性、数据完整性和效率来评估信任。目标是最大化分配的信任，同时最小化通信延迟。本文提出的联合优化模型结合了csp之前的凭据和当前的资源约束。应用遗传算法启发式地求解该问题。该模型使用了许多参数，这些参数提供了适应多个服务需求的灵活性。通过实验验证了该方法的有效性和适用性。结果表明，对于具有所提出属性的不同csp，信任评估的估计是有效的。将信任集成到资源分配模型中，在整体分配中增强信任，减少通信时延的同时，分配适当的资源。



#### [2021 ESAN]EdgeNet: A Multi-Tenant and Multi-Provider Edge Cloud

EdgeNet是一个公共的Kubernetes集群，专门用于网络和分布式系统的研究，支持由独立小组并发部署的实验。它的节点由世界各地的多个机构托管。它与经典的Kubernetes模型不同，在Kubernetes模型中，对单个租户可用的节点驻留在少量互连良好的数据中心中。免费的开源EdgeNet代码将Kubernetes扩展到了极致，它做出了三个关键贡献:多租户、地理部署和单命令节点安装。我们证明了在互联网上建立一个公共的Kubernetes集群，有多个租户和多个托管提供商是可行的。初步结果还表明，我们运行的EdgeNet测试平台提供了一个令人满意的环境，可以以最小的网络开销运行各种实验。



#### [2021 Access]A Resource Allocation Model Based on Trust Evaluation in Multi-Cloud Environments

在云环境中，考虑服务质量的资源分配和管理是一个基本而复杂的研究问题。一个最优的资源分配优化几个参数，如优化成本和资源利用或最大化任何质量参数。然而，为了确保更好的客户服务，云服务提供商(csp)在为云基础设施分配资源时应该考虑大多数质量属性。现有的研究没有将信任作为一个量化的属性进行评价，因此在研究领域也缺乏信任与资源配置绩效之间的权衡。本文提出了一个同时考虑信任和延迟的模型。CSP的信任是通过一些属性和度量来定量估计的。通过考虑可用性、可靠性、数据完整性和效率来评估信任。目标是最大化分配的信任，同时最小化通信延迟。本文提出的联合优化模型结合了csp之前的凭据和当前的资源约束。应用遗传算法启发式地求解该问题。该模型使用了许多参数，这些参数提供了适应多个服务需求的灵活性。通过实验验证了该方法的有效性和适用性。结果表明，对于具有所提出属性的不同csp，信任评估的估计是有效的。将信任集成到资源分配模型中，在整体分配中增强信任，减少通信时延的同时，分配适当的资源。

 

#### [2021 Access]DropStore: A Secure Backup System Using Multi-Cloud and Fog Computing

数据备份是灾难恢复的基础。当前基于云的解决方案提供了安全的基础设施。然而，将数据托管在一个云上并不能保证数据隐私。另一个解决方案是使用多云技术。虽然使用多个云来保存较小的数据块可以增强数据的私密性，但这是以边缘设备需要管理不同的帐户和管理与不同云的通信为代价的。这些缺点使得这种技术很少使用技术。在本文中，我们建议DropStore使用最先进的多云技术和加密技术，提供一个易于使用、高度安全、可靠的备份系统。DropStore为终端用户增加了一个抽象层，通过本地托管设备“the drop”来隐藏所有复杂的系统，该设备完全由用户管理。因此，用户不依赖任何不可信的第三方。这是使用雾计算技术实现的。DropStore的独特性来自于多云和雾计算原理的融合。系统实现是开源的，可以在线使用。性能结果表明，该系统在可靠性、安全性和隐私保护方面提高了数据保护，同时保持了与边缘设备的简单易用的接口。



#### [2021 IJTD]A Requirements-Oriented Modelling Language for an Optimized Distribution of Business Processes on a Multi-Cloud Environment.

在当今激烈的市场竞争中，许多公司都采用业务流程外包(BPO)来生存。随着云计算的出现，这种趋势得到了加强，云计算带来了一种新的支付和消费资源的方式。尽管如此，保存公司的技术诀窍，保护敏感数据，以及确保业务流程(BPs)的合规性，仍然是云业务流程外包中最重要的挑战。因此，组织必须考虑几个因素来决定哪些BP部件应该外包，并分配给他们最合适的云服务。本文提出了一种业务流程模型符号(BPMN)的扩展，它允许在安全性、合规性、成本、性能、数据传输和混淆方面指定BP活动的需求。此扩展旨在BP建模阶段，旨在分配到云提供的每个活动，最好满足其需求。

 

#### [2021 JAIHC]Cloud service recommendation system based on clustering trust measures in multi-cloud environment

由于技术的进步，云计算是当今不可避免的计算形式，被认为是中型行业的福音。随着云计算使用量的日益增加，服务部署也在不断改进，这也为安全威胁铺平了道路。寻找值得信任的服务是一个非常具有挑战性的问题，这可能会导致时间消耗或导致不适当的服务。由于这个问题，最终用户需要基于信任的、耗时最少的适当服务，并且服务也应该是可靠的。因此，云服务推荐系统是当前云环境的需要。该系统可以从可用的云服务池中推荐保存可靠可信服务的时间。本文试图以此为目标，提出一种基于聚类的信任度计算算法的云服务推荐系统。信任度量用于计算每个动态服务的信任度(TD)，每次都计算信任度，并维护历史信息。由于信任代理以自动化的方式对服务进行聚类，从而将最可信的服务从所有可用的集群云服务中分离出来，并使用可信服务分配算法将服务有效地分配给最终用户。服务搜索和推荐的过程需要最小的时间消耗。向信任代理(TA)注册服务可以提供最可靠的值得信任的服务。该推荐系统以准确率、召回率、f测度和时间消耗率为指标进行评价。提出的工作的平均f -度量率是通过用户数量从200到300的变化来计算的，平均f -度量率为91.85%，比现有方法花费的时间最少。



#### [2021 JHSN]QoS and QoE aware multi objective resource allocation algorithm for cloud gaming

云游戏是一种集电子游戏于一体的创新模式。用户可能有不同的体验质量(QoE)， QoE是一个用来衡量用户对特定服务的满意程度和享受程度的术语。为了保证在有限的云资源下所有用户的总体满意度，这成为云中的一个主要问题。本文在云博弈模型中利用博弈论中的资源优化方法，找到解决资源分配问题的最优解。为了提高云计算系统的效率，提出了基于Rider的和谐搜索算法(Rider-based HSA)，它是Rider优化算法(ROA)和和谐搜索算法(HSA)的结合。考虑到公平性指数、量化玩家体验(QE)和平均意见评分(MOS)等参数，设计了适应度函数。与基于潜在博弈的优化算法、主动资源分配算法、感知qos的资源分配算法、分布式算法和Yusen Li等相比，提出的基于rider的HSA性能更好，公平性最大为0.999,MOS最大为0.873,QE最大为1。 





### **2020**

#### [2020 ESOCC]Are Cloud Platforms Ready for Multi-cloud?

由于多云计算提供了各种优势，包括避免厂商锁定、更好的客户端接近性和应用程序性能改进，因此它正在获得发展势头。因此，各种各样的多云平台已经被开发出来，每个平台都有自己的优势和局限性。本文旨在对所有这些平台进行比较，以揭示出最佳的平台，并根据用户的需求和偏好方便选择合适的平台。此外，它还确定了有待弥补的平台目前的差距，以便充分发挥多云计算的潜力。最后，提出了进一步研究的方向。



#### [2020 PEARC]Demonstrating a Pre-Exascale, Cost-Effective Multi-Cloud Environment for Scientific Computing

随着时间的推移，科学计算的需求正在急剧增长，并且在以前不是计算密集型的科学领域中不断扩展。当计算工作流的峰值远远超过其本地计算资源的能力时，应该从其他地方临时提供能力，以满足最后期限和增加科学产出。公共云已经成为一个有吸引力的选择，因为它们能够在最少的提前通知下进行配置。成本效益高的实例的可用能力还没有得到充分了解。本文介绍了如何利用从Amazon Web Services、Microsoft Azure和谷歌云平台这三家主要云提供商收集的具有成本效益的GPU实例，以抢占模式扩展IceCube的HTCondor产品池。使用这种设置，我们在整个工作日维持了大约15k的gpu，相当于大约170个PFLOP32s，集成了超过1个EFLOP32小时的科学产出，价格标签约为60k美元。在本文中，我们提供了云实例选择背后的原因、设置的描述和所提供资源的分析，以及练习的实际科学输出的简短描述。

