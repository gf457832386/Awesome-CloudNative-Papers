# CloudPaper-NoteBook


在此更新关于云原生容器/虚拟机调度或者其他相关方面的优秀论文

目前话题包括但不限于以下内容：

*弹性伸缩

*调度器的设计结构

*资源预测

*多云代理

......

欢迎大家一起开issue分享论文！



# JointCloud Resource Management Related Paper

- [JointCloud Resource Management Related Paper](#jointcloud-resource-management-related-paper)
  - [**CCF A类**](#ccf-a类)
    - [**IEEE Transactions on Computers**](#ieee-transactions-on-computers)
      - [[TC 2022]Inverse Queuing Model-Based Feedback Control for Elastic Container Provisioning of Web Systems in Kubernetes【8】](#tc-2022inverse-queuing-model-based-feedback-control-for-elastic-container-provisioning-of-web-systems-in-kubernetes8)
      - [[TC 2022]PRESTO: A Penalty-Aware Real-Time Scheduler for Task Graphs on Heterogeneous Platforms【8】](#tc-2022presto-a-penalty-aware-real-time-scheduler-for-task-graphs-on-heterogeneous-platforms8)
      - [[TC 2022]Multi-Resource VNF Deployment in a Heterogeneous Cloud【8】](#tc-2022multi-resource-vnf-deployment-in-a-heterogeneous-cloud8)
      - [[TC 2022]Toward QoS-Awareness and Improved Utilization of Spatial Multitasking GPUs【4】](#tc-2022toward-qos-awareness-and-improved-utilization-of-spatial-multitasking-gpus4)
      - [[TC 2022]Breaking the Interaction Wall: A DLPU-Centric Deep Learning Computing System【3】](#tc-2022breaking-the-interaction-wall-a-dlpu-centric-deep-learning-computing-system3)
    - [**IEEE Transactions on Parallel and Distributed Systems**](#ieee-transactions-on-parallel-and-distributed-systems)
      - [[TPDS 2022]COSCO: Container Orchestration Using Co-Simulation and Gradient Based Optimization for Fog Computing Environments【8】](#tpds-2022cosco-container-orchestration-using-co-simulation-and-gradient-based-optimization-for-fog-computing-environments8)
      - [[TPDS 2022]A Potential Game Theoretic Approach to Computation Offloading Strategy Optimization in End-Edge-Cloud Computing【8】](#tpds-2022a-potential-game-theoretic-approach-to-computation-offloading-strategy-optimization-in-end-edge-cloud-computing8)
      - [[TPDS 2022]Taming System Dynamics on Resource Optimization for Data Processing Workflows: A Probabilistic Approach【8】](#tpds-2022taming-system-dynamics-on-resource-optimization-for-data-processing-workflows-a-probabilistic-approach8)
      - [[TPDS 2022]EdgeDR: An Online Mechanism Design for Demand Response in Edge Clouds【8】](#tpds-2022edgedr-an-online-mechanism-design-for-demand-response-in-edge-clouds8)
      - [[TPDS 2022]Optimizing Network Transfers for Data Analytic Jobs Across Geo-Distributed Datacenters【8】](#tpds-2022optimizing-network-transfers-for-data-analytic-jobs-across-geo-distributed-datacenters8)
      - [[TPDS 2022]Adaptive and Efficient Resource Allocation in Cloud Datacenters Using Actor-Critic Deep Reinforcement Learning【8】](#tpds-2022adaptive-and-efficient-resource-allocation-in-cloud-datacenters-using-actor-critic-deep-reinforcement-learning8)
      - [[TPDS 2022]Cost-Effective Web Application Replication and Deployment in Multi-Cloud Environment【8】](#tpds-2022cost-effective-web-application-replication-and-deployment-in-multi-cloud-environment8)
      - [[TPDS 2022]A Practical and Efficient Bidirectional Access Control Scheme for Cloud-Edge Data Sharing【8】](#tpds-2022a-practical-and-efficient-bidirectional-access-control-scheme-for-cloud-edge-data-sharing8)
      - [[TPDS 2022]Mechanisms for Resource Allocation and Pricing in Mobile Edge Computing Systems【8】](#tpds-2022mechanisms-for-resource-allocation-and-pricing-in-mobile-edge-computing-systems8)
      - [[TPDS 2022]Data, User and Power Allocations for Caching in Multi-Access Edge Computing【8】](#tpds-2022data-user-and-power-allocations-for-caching-in-multi-access-edge-computing8)
      - [[TPDS 2022]Customer Adaptive Resource Provisioning for Long-Term Cloud Profit Maximization under Constrained Budget【8】](#tpds-2022customer-adaptive-resource-provisioning-for-long-term-cloud-profit-maximization-under-constrained-budget8)
      - [[TPDS 2022]A Bifactor Approximation Algorithm for Cloudlet Placement in Edge Computing【7】](#tpds-2022a-bifactor-approximation-algorithm-for-cloudlet-placement-in-edge-computing7)
      - [[TPDS 2022]Adaptive Resource Efficient Microservice Deployment in Cloud-Edge Continuum【7】](#tpds-2022adaptive-resource-efficient-microservice-deployment-in-cloud-edge-continuum7)
      - [[TPDS 2022]Online Reconfiguration of IoT Applications in the Fog: The Information-Coordination Trade-Off【7】](#tpds-2022online-reconfiguration-of-iot-applications-in-the-fog-the-information-coordination-trade-off7)
      - [[TPDS 2022]Energy-Efficient Offloading for DNN-Based Smart IoT Systems in Cloud-Edge Environments【7】](#tpds-2022energy-efficient-offloading-for-dnn-based-smart-iot-systems-in-cloud-edge-environments7)
      - [[TPDS 2022]Decentralized Edge Intelligence: A Dynamic Resource Allocation Framework for Hierarchical Federated Learning【7】](#tpds-2022decentralized-edge-intelligence-a-dynamic-resource-allocation-framework-for-hierarchical-federated-learning7)
      - [[TPDS 2022]Harnessing the Potential of Function-Reuse in Multimedia Cloud Systems【7】](#tpds-2022harnessing-the-potential-of-function-reuse-in-multimedia-cloud-systems7)
      - [[TPDS 2022]Taskflow: A Lightweight Parallel and Heterogeneous Task Graph Computing System【7】](#tpds-2022taskflow-a-lightweight-parallel-and-heterogeneous-task-graph-computing-system7)
      - [[TPDS 2022]Towards Revenue-Driven Multi-User Online Task Offloading in Edge Computing【6】](#tpds-2022towards-revenue-driven-multi-user-online-task-offloading-in-edge-computing6)
      - [[TPDS 2022]Elastic Parameter Server: Accelerating ML Training With Scalable Resource Scheduling【6】](#tpds-2022elastic-parameter-server-accelerating-ml-training-with-scalable-resource-scheduling6)
      - [[TPDS 2022]Multi-Swarm Co-Evolution Based Hybrid Intelligent Optimization for Bi-Objective Multi-Workflow Scheduling in the Cloud【6】](#tpds-2022multi-swarm-co-evolution-based-hybrid-intelligent-optimization-for-bi-objective-multi-workflow-scheduling-in-the-cloud6)
      - [[TPDS 2022]TODG: Distributed Task Offloading With Delay Guarantees for Edge Computing【5】](#tpds-2022todg-distributed-task-offloading-with-delay-guarantees-for-edge-computing5)
      - [[TPDS 2022]Horus: Interference-Aware and Prediction-Based Scheduling in Deep Learning Systems【4】](#tpds-2022horus-interference-aware-and-prediction-based-scheduling-in-deep-learning-systems4)
      - [[TPDS 2022]VQL: Efficient and Verifiable Cloud Query Services for Blockchain Systems【4】](#tpds-2022vql-efficient-and-verifiable-cloud-query-services-for-blockchain-systems4)
      - [[TPDS 2022]On Mixing Eventual and Strong Consistency: Acute Cloud Types【3】](#tpds-2022on-mixing-eventual-and-strong-consistency-acute-cloud-types3)
      - [[TPDS 2022]Performance and Cost-Efficient Spark Job Scheduling Based on Deep Reinforcement Learning in Cloud Computing Environments【3】](#tpds-2022performance-and-cost-efficient-spark-job-scheduling-based-on-deep-reinforcement-learning-in-cloud-computing-environments3)
      - [[TPDS 2021]Hierarchical Multi-Agent Optimization for Resource Allocation in Cloud Computing【6】](#tpds-2021hierarchical-multi-agent-optimization-for-resource-allocation-in-cloud-computing6)
      - [[TPDS 2020]Location-Aware and Budget-Constrained Service Deployment for Composite Applications in Multi-Cloud Environment【8】](#tpds-2020location-aware-and-budget-constrained-service-deployment-for-composite-applications-in-multi-cloud-environment8)
      - [[TPDS 2020]Scheduling Periodical Multi-Stage Jobs With Fuzziness to Elastic Cloud Resources【6】](#tpds-2020scheduling-periodical-multi-stage-jobs-with-fuzziness-to-elastic-cloud-resources6)
    - [**International World Wide Web Conferences**](#international-world-wide-web-conferences)
      - [[WWW 2021]CoopEdge: A Decentralized Blockchain-based Platform for Cooperative Edge Computing【8】](#www-2021coopedge-a-decentralized-blockchain-based-platform-for-cooperative-edge-computing8)
      - [[WWW 2021]Surrounded by the Clouds: A Comprehensive Cloud Reachability Study【4】](#www-2021surrounded-by-the-clouds-a-comprehensive-cloud-reachability-study4)
      - [[WWW 2021]CoResident Evil: Covert Communication In The Cloud With Lambdas【4】](#www-2021coresident-evil-covert-communication-in-the-cloud-with-lambdas4)
      - [[WWW 2021]NTAM: Neighborhood-Temporal Attention Model for Disk Failure Prediction in Cloud Platforms【3】](#www-2021ntam-neighborhood-temporal-attention-model-for-disk-failure-prediction-in-cloud-platforms3)
    - [**ACM Symposium on Operating Systems Principles**](#acm-symposium-on-operating-systems-principles)
      - [[SOSP 2021]RAS: Continuously Optimized Region-Wide Datacenter Resource Allocation【8】](#sosp-2021ras-continuously-optimized-region-wide-datacenter-resource-allocation8)
      - [[SOSP 2021]Solving Large-Scale Granular Resource Allocation Problems Efficiently with POP【7】](#sosp-2021solving-large-scale-granular-resource-allocation-problems-efficiently-with-pop7)
    - [**IEEE International Conference on Computer  Communications**](#ieee-international-conference-on-computer--communications)
      - [[INFOCOM 2021]Tailored Learning-Based Scheduling for Kubernetes-Oriented Edge-Cloud System【8】](#infocom-2021tailored-learning-based-scheduling-for-kubernetes-oriented-edge-cloud-system8)
      - [[INFOCOM 2021]Monitoring Cloud Service Unreachability at Scale【7】](#infocom-2021monitoring-cloud-service-unreachability-at-scale7)
      - [[INFOCOM 2021]Layer Aware Microservice Placement and Request Scheduling at the Edge【7】](#infocom-2021layer-aware-microservice-placement-and-request-scheduling-at-the-edge7)
      - [[INFOCOM 2021]Cost-Driven Data Caching in the Cloud: An Algorithmic Approach【7】](#infocom-2021cost-driven-data-caching-in-the-cloud-an-algorithmic-approach7)
      - [[INFOCOM 2021]Resource-Efficient Federated Learning with Hierarchical Aggregation in Edge Computing【4】](#infocom-2021resource-efficient-federated-learning-with-hierarchical-aggregation-in-edge-computing4)
      - [[INFOCOM 2021]Distributed Threshold-based Offloading for Large-Scale Mobile Cloud Computing【3】](#infocom-2021distributed-threshold-based-offloading-for-large-scale-mobile-cloud-computing3)
    - [**Symposium on Network System Design and  Implementation**](#symposium-on-network-system-design-and--implementation)
      - [[NSDI 2021]Twenty Years After: Hierarchical Core-Stateless Fair Queueing【7】](#nsdi-2021twenty-years-after-hierarchical-core-stateless-fair-queueing7)
      - [[NSDI 2021]Ship Compute or Ship Data? Why Not Both?【3】](#nsdi-2021ship-compute-or-ship-data-why-not-both3)
      - [[NSDI 2021]Caerus: NIMBLE Task Scheduling for Serverless Analytics【3】](#nsdi-2021caerus-nimble-task-scheduling-for-serverless-analytics3)
      - [[NSDI 2021]When to Hedge in Interactive Services【2】](#nsdi-2021when-to-hedge-in-interactive-services2)
      - [[NSDI 2021]When to Hedge in Interactive Services【2】](#nsdi-2021when-to-hedge-in-interactive-services2-1)
    - [**USENIX Annul Technical Conference**](#usenix-annul-technical-conference)
      - [[ATC 2021]Scaling Large Production Clusters with Partitioned Synchronization【6】](#atc-2021scaling-large-production-clusters-with-partitioned-synchronization6)
      - [[ATC 2021]Prediction-Based Power Oversubscription in Cloud Platforms【6】](#atc-2021prediction-based-power-oversubscription-in-cloud-platforms6)
      - [[ATC 2021]Fighting the Fog of War: Automated Incident Detection for Cloud Systems【4】](#atc-2021fighting-the-fog-of-war-automated-incident-detection-for-cloud-systems4)
    - [**Real-Time Systems Symposium**](#real-time-systems-symposium)
      - [[RTSS 2021]Partitioned Scheduling of Recurrent Real-Time Tasks【6】](#rtss-2021partitioned-scheduling-of-recurrent-real-time-tasks6)
    - [**International Joint Conference on  Artificial Intelligence**](#international-joint-conference-on--artificial-intelligence)
      - [[IJCAI 2021]Predictive Job Scheduling under Uncertain Constraints in Cloud Computing【6】](#ijcai-2021predictive-job-scheduling-under-uncertain-constraints-in-cloud-computing6)
      - [[RTSS 2021]Joint Model and Data Adaptation for Cloud Inference Serving【2】](#rtss-2021joint-model-and-data-adaptation-for-cloud-inference-serving2)
      - [[RTSS 2021]LaLaRAND: Flexible Layer-by-Layer CPU/GPU Scheduling for Real-Time DNN Tasks【2】](#rtss-2021lalarand-flexible-layer-by-layer-cpugpu-scheduling-for-real-time-dnn-tasks2)
    - [**IEEE Transactions on Computer-Aided Design of  Integrated Circuits And System**](#ieee-transactions-on-computer-aided-design-of--integrated-circuits-and-system)
      - [[TCAD 2022]Contention Cognizant Scheduling of Task Graphs on Shared Bus-Based Heterogeneous Platforms【5】](#tcad-2022contention-cognizant-scheduling-of-task-graphs-on-shared-bus-based-heterogeneous-platforms5)
    - [**International Conference for High Performance  Computing, Networking, Storage, and Analysis**](#international-conference-for-high-performance--computing-networking-storage-and-analysis)
      - [[SC 2021]The hidden cost of the edge: a performance comparison of edge and cloud latencies【5】](#sc-2021the-hidden-cost-of-the-edge-a-performance-comparison-of-edge-and-cloud-latencies5)
      - [[SC 2021]Understanding, predicting and scheduling serverless workloads under partial interference【4】](#sc-2021understanding-predicting-and-scheduling-serverless-workloads-under-partial-interference4)
      - [[SC 2021]Generalizable coordination of large multiscale workflows: challenges and learnings at scale【3】](#sc-2021generalizable-coordination-of-large-multiscale-workflows-challenges-and-learnings-at-scale3)
    - [**IEEE Journal of Selected Areas in Communications**](#ieee-journal-of-selected-areas-in-communications)
      - [[JSAC 2022]Blockchain-Based Task Offloading for Edge Computing on Low-Quality Data via Distributed Learning in the Internet of Energy【4】](#jsac-2022blockchain-based-task-offloading-for-edge-computing-on-low-quality-data-via-distributed-learning-in-the-internet-of-energy4)
      - [[JSAC 2022]Information Freshness-Aware Task Offloading in Air-Ground Integrated Edge Computing Systems【2】](#jsac-2022information-freshness-aware-task-offloading-in-air-ground-integrated-edge-computing-systems2)
      - [[JSAC 2022]Private Retrieval, Computing, and Learning: Recent Progress and Future Challenges【2】](#jsac-2022private-retrieval-computing-and-learning-recent-progress-and-future-challenges2)
    - [**ACM Transactions on Computer Systems**](#acm-transactions-on-computer-systems)
      - [[TOCS 2021]AI Tax: The Hidden Cost of AI Data Center Applications【3】](#tocs-2021ai-tax-the-hidden-cost-of-ai-data-center-applications3)
    - [**IEEE Transactions on Computer-Aided Design of  Integrated Circuits And System**](#ieee-transactions-on-computer-aided-design-of--integrated-circuits-and-system-1)
      - [[TCAD 2022]Fixed-Priority Scheduling for Reliable and Energy-Aware (m, k)-Deadlines Enforcement With Standby-Sparing【3】](#tcad-2022fixed-priority-scheduling-for-reliable-and-energy-aware-m-k-deadlines-enforcement-with-standby-sparing3)
    - [**High Performance Computer Architecture**](#high-performance-computer-architecture)
      - [[HPCA 2021]Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling【3】](#hpca-2021layerweaver-maximizing-resource-utilization-of-neural-processing-units-via-layer-wise-scheduling3)
    - [**International Conference on Architectural Support  for Programming Languages and Operating Systems**](#international-conference-on-architectural-support--for-programming-languages-and-operating-systems)
      - [[ASPLOS 2022]Serverless computing on heterogeneous computers【3】](#asplos-2022serverless-computing-on-heterogeneous-computers3)
    - [**IEEE Transactions on Mobile Computing**](#ieee-transactions-on-mobile-computing)
      - [[TMC 2022]Imitation Learning Enabled Task Scheduling for Online Vehicular Edge Computing【3】](#tmc-2022imitation-learning-enabled-task-scheduling-for-online-vehicular-edge-computing3)
      - [[TS 2021]Multi-objective Optimization of Data Placement in a Storage-as-a-Service Federated Cloud【7】](#ts-2021multi-objective-optimization-of-data-placement-in-a-storage-as-a-service-federated-cloud7)
      - [IEEE Transactions on Information Forensics and Security](#ieee-transactions-on-information-forensics-and-security)
      - [[TIFS 2019]Extensible Conditional Privacy Protection Authentication Scheme for Secure Vehicular Networks in a Multi-Cloud Environment【4】](#tifs-2019extensible-conditional-privacy-protection-authentication-scheme-for-secure-vehicular-networks-in-a-multi-cloud-environment4)
    - [**IEEE Transactions on Knowledge and Data Engineering**](#ieee-transactions-on-knowledge-and-data-engineering)
      - [[TKDE 2019]NewMCOS: Towards a Practical Multi-Cloud Oblivious Storage Scheme【5】](#tkde-2019newmcos-towards-a-practical-multi-cloud-oblivious-storage-scheme5)
  - [**CCF B类**](#ccf-b类)
    - [**International Conference on Distributed Computing Systems**](#international-conference-on-distributed-computing-systems)
      - [[ICDCS 2021]Harmony: A Scheduling Framework Optimized for Multiple Distributed Machine Learning Jobs【7】](#icdcs-2021harmony-a-scheduling-framework-optimized-for-multiple-distributed-machine-learning-jobs7)
      - [[ICDCS 2021]A Truthful Procurement Auction for Incentivizing Heterogeneous Clients in Federated Learning【6】](#icdcs-2021a-truthful-procurement-auction-for-incentivizing-heterogeneous-clients-in-federated-learning6)
      - [[ICDCS 2021]GeoCol: A Geo-distributed Cloud Storage System with Low Cost and Latency using Reinforcement Learning【5】](#icdcs-2021geocol-a-geo-distributed-cloud-storage-system-with-low-cost-and-latency-using-reinforcement-learning5)
      - [[ICDCS 2021]Defuse: A Dependency-Guided Function Scheduler to Mitigate Cold Starts on FaaS Platforms【5】](#icdcs-2021defuse-a-dependency-guided-function-scheduler-to-mitigate-cold-starts-on-faas-platforms5)
      - [[ICDCS 2021]A Multi-Tenant Framework for Cloud Container Services【5】](#icdcs-2021a-multi-tenant-framework-for-cloud-container-services5)
      - [[ICDCS 2021]Statistical Tail-Latency Bounded QoS Provisioning for Parallel and Distributed Data Centers【5】](#icdcs-2021statistical-tail-latency-bounded-qos-provisioning-for-parallel-and-distributed-data-centers5)
      - [[ICDCS 2021]Infinite Balanced Allocation via Finite Capacities【4】](#icdcs-2021infinite-balanced-allocation-via-finite-capacities4)
      - [[ICDCS 2021]SHARE: Shaping Data Distribution at Edge for Communication-Efficient Hierarchical Federated Learning【4】](#icdcs-2021share-shaping-data-distribution-at-edge-for-communication-efficient-hierarchical-federated-learning4)
      - [[ICDCS 2021]Incentive-Driven Long-term Optimization for Edge Learning by Hierarchical Reinforcement Mechanism【3】](#icdcs-2021incentive-driven-long-term-optimization-for-edge-learning-by-hierarchical-reinforcement-mechanism3)
    - [**Software: Practice and Experience**](#software-practice-and-experience)
      - [[SPE 2022]Towards cloud-based unobtrusive monitoring in remote multi-vendor environments【4】](#spe-2022towards-cloud-based-unobtrusive-monitoring-in-remote-multi-vendor-environments4)
      - [[SPE 2020]A multicriteria optimization model for cloud service provider selection in multicloud environments【7】](#spe-2020a-multicriteria-optimization-model-for-cloud-service-provider-selection-in-multicloud-environments7)
      - [[ASTS 2022]Efficient multi-attribute precedence-based task scheduling for edge computing in geo-distributed cloud environment【8】](#asts-2022efficient-multi-attribute-precedence-based-task-scheduling-for-edge-computing-in-geo-distributed-cloud-environment8)
    - [**The Computer Journal**](#the-computer-journal)
      - [[CJ 2021]A proposed framework for cloud-aware multimodal multimedia big data analysis toward optimal resource allocation【6】](#cj-2021a-proposed-framework-for-cloud-aware-multimodal-multimedia-big-data-analysis-toward-optimal-resource-allocation6)
      - [[2021]Location-Aware and Budget-Constrained Service Brokering in Multi-Cloud via Deep Reinforcement Learning【7】](#2021location-aware-and-budget-constrained-service-brokering-in-multi-cloud-via-deep-reinforcement-learning7)
    - [**ACM Symposium on Cloud Computing**](#acm-symposium-on-cloud-computing)
      - [[SoCC 2021]Mind the Gap: Broken Promises of CPU Reservations in Containerized Multi-tenant Clouds【6】](#socc-2021mind-the-gap-broken-promises-of-cpu-reservations-in-containerized-multi-tenant-clouds6)
    - [**IEEE International Conference on Cluster Computing**](#ieee-international-conference-on-cluster-computing)
      - [[CC 2021]Truthful online double auction based dynamic resource provisioning for multi-objective trade-offs in IaaS clouds【7】](#cc-2021truthful-online-double-auction-based-dynamic-resource-provisioning-for-multi-objective-trade-offs-in-iaas-clouds7)
    - [**Computer Networks**](#computer-networks)
      - [[CN 2021]Game-based distributed pricing and task offloading in multi-cloud and multi-edge environments【7】](#cn-2021game-based-distributed-pricing-and-task-offloading-in-multi-cloud-and-multi-edge-environments7)
    - [**Journal of Parallel and Distributed Computing**](#journal-of-parallel-and-distributed-computing)
      - [[JPDC 2021]A novel cooperative resource provisioning strategy for Multi-Cloud load balancing【8】](#jpdc-2021a-novel-cooperative-resource-provisioning-strategy-for-multi-cloud-load-balancing8)
      - [[JPDC 2019]Managing renewable energy and carbon footprint in multi-cloud computing environments【5】](#jpdc-2019managing-renewable-energy-and-carbon-footprint-in-multi-cloud-computing-environments5)
    - [**Journal of Systems Architecture: Embedded Software Design**](#journal-of-systems-architecture-embedded-software-design)
      - [[JSA 2021]TOPSIS inspired Budget and Deadline Aware Multi-Workflow Scheduling for Cloud computing【7】](#jsa-2021topsis-inspired-budget-and-deadline-aware-multi-workflow-scheduling-for-cloud-computing7)
    - [**Journal of Systems and Software**](#journal-of-systems-and-software)
      - [[JSS 2021]Tuning configuration of apache spark on public clouds by combining multi-objective optimization and performance prediction model【6】](#jss-2021tuning-configuration-of-apache-spark-on-public-clouds-by-combining-multi-objective-optimization-and-performance-prediction-model6)
    - [**IEEE Transactions on Service Computing**](#ieee-transactions-on-service-computing)
      - [[TSC 2021]A QoS-Based Splitting Strategy for a Resource Embedding Across Multiple Cloud Providers【4】](#tsc-2021a-qos-based-splitting-strategy-for-a-resource-embedding-across-multiple-cloud-providers4)
      - [[TSC 2021]A Game-Based Price Bidding Algorithm for Multi-Attribute Cloud Resource Provision【7】](#tsc-2021a-game-based-price-bidding-algorithm-for-multi-attribute-cloud-resource-provision7)
    - [**International Symposium on Mobile Ad Hoc Networking and  Computing**](#international-symposium-on-mobile-ad-hoc-networking-and--computing)
      - [[MobiHoc 2021]Joint Update Rate Adaptation in Multiplayer Cloud-Edge Gaming Services: Spatial Geometry and Performance Tradeoffs【4】](#mobihoc-2021joint-update-rate-adaptation-in-multiplayer-cloud-edge-gaming-services-spatial-geometry-and-performance-tradeoffs4)
    - [**International Conference on Web Services （Research  Track）**](#international-conference-on-web-services-research--track)
      - [[ICWS 2020]Location-Aware and Budget-Constrained Application Replication and Deployment in Multi-Cloud Environment【7】](#icws-2020location-aware-and-budget-constrained-application-replication-and-deployment-in-multi-cloud-environment7)
  - [**CCF C类**](#ccf-c类)
    - [**Journal of Grid computing**](#journal-of-grid-computing)
      - [[JGC 2022]An Incentive-Compatible Offloading Mechanism in Fog-Cloud Environments Using Second-Price Sealed-Bid Auction【8】](#jgc-2022an-incentive-compatible-offloading-mechanism-in-fog-cloud-environments-using-second-price-sealed-bid-auction8)
      - [[JGC 2022]Effective Scheduler for Distributed DNN Training Based on MapReduce and GPU Cluster【7】](#jgc-2022effective-scheduler-for-distributed-dnn-training-based-on-mapreduce-and-gpu-cluster7)
      - [[JGC 2022]TORCH: a TOSCA-Based Orchestrator of Multi-Cloud Containerised Applications【6】](#jgc-2022torch-a-tosca-based-orchestrator-of-multi-cloud-containerised-applications6)
      - [[JGC 2022]Energy Refining Balance with Ant Colony System for Cloud Placement Machines【6】](#jgc-2022energy-refining-balance-with-ant-colony-system-for-cloud-placement-machines6)
      - [[JGC 2022]A Survey on Auction based Approaches for Resource Allocation and Pricing in Emerging Edge Technologies【6】](#jgc-2022a-survey-on-auction-based-approaches-for-resource-allocation-and-pricing-in-emerging-edge-technologies6)
      - [[JGC 2022]Greening Duplication-Based Dependent-Tasks Scheduling on Heterogeneous Large-Scale Computing Platforms【6】](#jgc-2022greening-duplication-based-dependent-tasks-scheduling-on-heterogeneous-large-scale-computing-platforms6)
      - [[JGC 2022]A Survey of Service Placement in Cloud Environments【6】](#jgc-2022a-survey-of-service-placement-in-cloud-environments6)
      - [[JGC 2022]Offloading Coalition Formation for Scheduling Scientific Workflow Ensembles in Fog Environments【6】](#jgc-2022offloading-coalition-formation-for-scheduling-scientific-workflow-ensembles-in-fog-environments6)
      - [[JGC 2022]Distributed and Decentralized Orchestration of Containers on Edge Clouds【6】](#jgc-2022distributed-and-decentralized-orchestration-of-containers-on-edge-clouds6)
      - [[JGC 2022]Energy and Makespan Aware Scheduling of Deadline Sensitive Tasks in the Cloud Environment.【5】](#jgc-2022energy-and-makespan-aware-scheduling-of-deadline-sensitive-tasks-in-the-cloud-environment5)
      - [[JGC 2022]A Hybrid Meta-Heuristic for Optimal Load Balancing in Cloud Computing【5】](#jgc-2022a-hybrid-meta-heuristic-for-optimal-load-balancing-in-cloud-computing5)
      - [[JGC 2021]Deployment Management and Topology Discovery of Microservice Applications in the Multicloud Environment【5】](#jgc-2021deployment-management-and-topology-discovery-of-microservice-applications-in-the-multicloud-environment5)
      - [[JGC 2022]Computing Offloading Strategy Using Improved Genetic Algorithm in Mobile Edge Computing System【5】](#jgc-2022computing-offloading-strategy-using-improved-genetic-algorithm-in-mobile-edge-computing-system5)
      - [[JGC 2022]MiCADO-Edge: Towards an Application-level Orchestrator for the Cloud-to-Edge Computing Continuum【4】](#jgc-2022micado-edge-towards-an-application-level-orchestrator-for-the-cloud-to-edge-computing-continuum4)
      - [[JGC 2022]SLA-aware Stochastic Load Balancing in Dynamic Cloud Environment【4】](#jgc-2022sla-aware-stochastic-load-balancing-in-dynamic-cloud-environment4)
      - [[JGC2022]An Evolutionary Computing-Based Efficient Hybrid Task Scheduling Approach for Heterogeneous Computing Environment【4】](#jgc2022an-evolutionary-computing-based-efficient-hybrid-task-scheduling-approach-for-heterogeneous-computing-environment4)
      - [[JGC2022]Opportunistic Deployment of Distributed Edge Clouds for Latency-Critical Applications【4】](#jgc2022opportunistic-deployment-of-distributed-edge-clouds-for-latency-critical-applications4)
      - [[JGC2022]Ultra-Reliable and Low-Latency Computing in the Edge with Kubernetes【4】](#jgc2022ultra-reliable-and-low-latency-computing-in-the-edge-with-kubernetes4)
      - [[JGC2022]A Computing Resource Allocation Optimization Strategy for Massive Internet of Health Things Devices Considering Privacy Protection in Cloud Edge Computing Environment【4】](#jgc2022a-computing-resource-allocation-optimization-strategy-for-massive-internet-of-health-things-devices-considering-privacy-protection-in-cloud-edge-computing-environment4)
      - [[JGC2022]Deployment of Elastic Virtual Hybrid Clusters Across Cloud Sites【2】](#jgc2022deployment-of-elastic-virtual-hybrid-clusters-across-cloud-sites2)



## **CCF A类**

### **IEEE Transactions on Computers**

#### [TC 2022]Inverse Queuing Model-Based Feedback Control for Elastic Container Provisioning of Web Systems in Kubernetes【8】

**摘要：**

容器编排平台，如Kubernetes和Kubernetes衍生的KubeEdge(统称为基于Kubernetes的系统)，已经逐渐被用来对Cloud、Fog和Edge资源进行统一管理。容器供应算法对于保证这种基于kubernetes的系统的服务质量(QoS)至关重要。然而，现有的算法大多只关注固定数量容器的放置和迁移，而没有考虑容器的**弹性供应**。同时，**在不同平台上广泛使用的基于线性性能模型的反馈控制或基于固定处理速率的排队模型无法准确描述容器化Web系统的性能**。此外，现有方法使用的固定参考点很可能产生不准确的输出误差，在到达率发生较大变化时产生较大波动。在这篇文章中,设计了一种**基于变处理率排队模型和线性模型相结合的弹性供给容器反馈控制方法**，该方法通过自动学习不同到达率的参考模型，并将输出误差从参考模型映射到排队模型，提高了输出误差的准确性。在一个真实的Kubernetes集群上，我们的方法与几种最先进的算法进行了比较。实验结果表明，该方法获得了最低的服务水平协议(SLA)违反率(降低不低于8.44%)和第二低的成本。

**关键词：** Containers,Adaptation models,Computational modeling,Feedback control,Time factors,Quality of service,Cloud computing 

#### [TC 2022]PRESTO: A Penalty-Aware Real-Time Scheduler for Task Graphs on Heterogeneous Platforms【8】

**摘要：**

调度异构分布式平台上建模为有向无环图的实时应用程序是一个具有挑战性和计算要求的问题。本文讨论了**在由一组完全连接的异构处理器组成的分布式平台上执行实时任务图的高效调度器的设计**。调度策略的目标是最小化通用罚函数，该罚函数可友好地应用于各种应用领域，如实时嵌入式系统、云/雾计算、工业自动化和loTs、智能电网、汽车和航空电子系统等。我们首先将问题编码为约束满足问题，然后开发了一种高效的基于列表的启发式调度算法，称为**异构平台上任务图的惩罚感知实时调度算法**(PRESTO)，以生成最小惩罚截止时间的静态调度。PRESTO的通用效能通过使用标准基准任务图的大量基于仿真的实验得到了验证。PRESTO在不同场景下的实际适用性得到了进一步的展示，在两个不同的实际案例研究中，前者涉及汽车嵌入式系统，而后者则涉及雾计算领域。

**关键词：** Task analysis, Real-time systems, Processor scheduling, Program processors, Schedules, Optimal scheduling, Job shop scheduling



#### [TC 2022]Multi-Resource VNF Deployment in a Heterogeneous Cloud【8】

**摘要：**

新兴的网络功能虚拟化(NFV)模式有望通过在商用服务器上灵活部署虚拟化网络功能(VNFs)来缩短网络功能的更新周期并降低资本支出。但是，每种类型所需的资源(CPU、内存等。)来保证处理数据包时的性能。**这带来了不同的部署成本，尤其是在由来自不同供应商的大量网络功能平台组成的异构云中。**为了优化VNFs的运行，网络运营商有必要在昂贵的云基础架构中动态部署VNFs。在本文中，我们发起了**异构云中多资源约束下最小化部署成本**的研究。我们将多资源VNF部署问题(MVDP)公式化为一个最优化问题，并证明了它的困难性。我们提出了一种离线(1，d+1)-双标准近似算法和一种(O(1)，O(n logn))-竞争在线算法，以可扩展的方式部署VNFs，其中d是资源类型的数量，n是所需VNFs的数量。大规模仿真和基于DPDK的OpenNetVM实现表明，我们的算法可以减少34%的总开销，并提高多资源分配的性能。

**关键词：** Network Function Virtualization, Heterogeneous Cloud, approximation algorithm



#### [TC 2022]Toward QoS-Awareness and Improved Utilization of Spatial Multitasking GPUs【4】

**摘要：**

数据中心使用gpu提供新兴的面向用户的服务所需的显著计算吞吐量。面向用户的服务的每日用户访问模式为实现更好的GPU利用率提供了强大的激励，之前的工作集中在实现多核处理器和传统非抢占GPU上的共同位置。然而，**当前的gpu正在向空间多任务发展，并引入了一组新的挑战来消除QoS违规。**为了解决这个开放的问题，我们探究了空间多任务gpu上QoS冲突的潜在原因。针对这些原因，我们提出了C-Laius，这是一个运行时系统，它**仔细地将计算资源分配给位于同一位置的应用程序，以最大限度地提高批处理应用程序的吞吐量，同时保证面向用户的服务所需的QoS**。C-Laius不仅支持一个面向用户的应用与多个批处理应用共存，还支持多个面向用户的应用与多个批处理应用共存。在单个共定位面向用户的应用程序的情况下，我们对Nvidia RTX 2080Ti GPU的评估表明，C-Laius将空间多任务GPU的利用率提高了20.8%，同时实现了面向用户的服务的99%的延迟目标。对于多个面向用户的应用程序共存的情况，C-Laius保证了不违反QoS，同时平均提高了35.9%的加速器利用率。

**关键词：** Quality of service, Kernel, Multitasking, Task analysis, Graphics processing units ,Resource management, Bandwidth



#### [TC 2022]Breaking the Interaction Wall: A DLPU-Centric Deep Learning Computing System【3】

**摘要：**

由于深度学习的广泛成功，许多以cpu为中心的人工智能计算系统都采用gpu、fpga、asic等专用设备来处理计算密集型的深度学习任务，这些设备可以被称为DLPUs (deep learning Processing unit)。**由于映射到cpu上的标量控制操作和映射到DLPUs上的向量计算操作的分离，导致cpu和DLPUs之间的交互频繁且代价高昂，从而导致交互墙**。此外，算法复杂度的增加和DLPU计算速度的提高，将进一步大大加剧交互墙。为了打破交互壁垒，我们提出了一种新的以DLPU为中心的深度学习计算系统，该系统由面向异常的编程(EOP)模型和cpuess DLPU的体系结构支持组成。EOP模型将深度学习任务中的标量控制操作作为异常处理程序处理，最大限度地避免了关键的矢量计算操作的停滞。与集成了标量控制操作的标量处理单元(SPU)和矢量计算操作的并行处理单元(PPU)的cpuess  DLPU一起，形成了一个融合的管道，**该以dlpu为中心的系统可以经济有效地利用EOP模型，在不干扰对方的情况下同时执行两种操作**。实验结果表明，与目前最先进的基于PCle总线的V100离散GPU的商用cpu为中心的系统相比，以dlpu为中心的系统性能提高10.30倍，节能92.99%。此外，与以cpu为中心的DLPU系统(SPU作为主机，并集成了PPU)相比，本文提出的以DLPU为中心的系统在避免交互的情况下仍然获得了15.60%的性能提升。

**关键词：** Neural net accelerators, system architectures, interaction wall



------

### **IEEE Transactions on Parallel and Distributed Systems**

> 期刊链接：[dblp: IEEE Transactions on Parallel and Distributed Systems (uni-trier.de)](https://dblp.uni-trier.de/db/journals/tpds/index.html)



#### [TPDS 2022]COSCO: Container Orchestration Using Co-Simulation and Gradient Based Optimization for Fog Computing Environments【8】

**摘要：**

由于现代工作负载应用程序的高度不稳定性，以及用户对低能耗和响应时间的敏感需求，大规模雾平台中的智能任务配置和任务管理具有挑战性。容器编排平台的出现缓解了这一问题，现有技术要么使用启发式来快速达成调度决策，要么使用增强学习和进化方法等Al驱动方法来适应动态场景。前者常常不能快速适应高度动态的环境，而后者的运行时足够慢，会对响应时间产生负面影响。因此，**需要一种既能在不稳定的环境中有效工作又能降低调度开销的调度策略**。为了实现这一目标，我们提出了一种基于梯度的优化策略，使用梯度相对于输入的反向传播(GOBI)。此外，我们通过开发耦合仿真和容器编排框架(COSCO)，利用预测数字孪生模型的准确性和仿真能力。基于此，我们创建了一种**混合仿真驱动决策**方法GOBI，以优化服务质量(QoS)参数。**联合仿真和反向传播方法允许这些方法在不稳定的环境中快速适应**。在雾应用中使用GOBI和GOBI方法进行的真实数据实验表明，与最先进的算法相比，在能源消耗、响应时间、服务水平目标和调度时间方面分别有15%、40%、4%和82%的显著提高。

**关键词：** Fog Computing, Coupled Simulation, Container Orchestration, Back-propagation to input, QoS Optimization



#### [TPDS 2022]A Potential Game Theoretic Approach to Computation Offloading Strategy Optimization in End-Edge-Cloud Computing【8】

**摘要：**

将终端(ue)、边缘服务器(ESs)和云集成到EECC (end-edge cloud computing)中，可以提高资源利用率和体验质量(QoE)。然而，**EECC的性能受到其体系结构的显著影响**。在本文中，根据云对终端的可见性和可访问性，我们将**EECC分为两种计算架构类型，即层次末端云计算(Hi-EECC)和水平末端云计算(Ho-EECC)**。在Hi-EECC中，终端可以将其任务只卸给ESs。当ESs资源耗尽时，会向云请求向终端提供资源。在Ho-EECC中，ue可以将其任务直接卸载给ESs和云。在本文中，我们构建了一种基于EECC环境的潜在博弈，在这种博弈环境下，每个EECC都自私地最小化其收益，研究了**计算卸载策略优化问题**，并在Hi-EECC和Ho-EECC中开发了两种潜在的基于博弈的算法。在真实世界的数据中进行了大量的实验，以证明所提出算法的性能。并对两种计算体系结构的可扩展性和适用性进行了综合分析。我们的研究结论可以为在不同的应用环境下选择特定的计算体系结构提供有用的建议，以提高EECC和QoE的性能。



#### [TPDS 2022]Taming System Dynamics on Resource Optimization for Data Processing Workflows: A Probabilistic Approach【8】

**摘要：**

在许多数据密集型应用程序中，工作流通常被用作组织数据处理任务的重要模型，而资源配置是提高工作流性能的一个重要且具有挑战性的问题。最近，云和大规模集群中的系统变化，如**I/O和网络性能和故障事件**，已经被观察到，极大地影响工作流的性能。**传统的资源配置方法忽略了这些变化，可能导致资源配置结果不理想。**在本文中，我们为考虑系统变化的**工作流性能优化**提供了一个通用的解决方案。具体地说，我们将系统动力学建模为随时间变化的随机变量，并将其概率分布作为优化输入。尽管该解决方案很有效，但它涉及大量的计算开销。因此，我们**提出了三种剪枝技术来简化工作流结构，减少概率计算开销**。我们在运行时库中实现了我们的技术，这允许用户将有效的概率优化整合到现有的资源配置方法中。实验表明，与最先进的静态解相比，概率解可以提高65%的性能，我们的剪枝技术可以大大减少我们的概率方法的开销。

**关键词：** Optimization, Task analysis, Probabilistic logic, Dynamic scheduling, Data processing,Cloud computing, Probability distribution

 

#### [TPDS 2022]EdgeDR: An Online Mechanism Design for Demand Response in Edge Clouds【8】

**摘要：**

计算的前沿正从集中式的大型数据中心向网络边缘的分布式云转移。我们认为，云非常适合处理电力需求响应，以帮助电网保持稳定，因为它们的分布式特性使工作负载管理更加灵活。然而，它们也需要计算需求响应来避免过载和维护可靠性。为此，我们**提出了一种新颖的在线市场机制EdgeDR，以实现边缘需求响应计划的成本效率**。在较高的水平上，我们观察到cloudlet操作员可以动态地打开/关闭整个cloudlet，以补偿电网所需的能量减少或为边缘服务提供足够的计算资源。我们制定了一个长期的社会成本最小化问题，并将其分解为一系列一轮的采购拍卖。在每个拍卖实例中，我们建议让**cloudlet租户使用其二维服务质量退化容忍的成本函数进行竞价，并让cloudlet运营商选择服务质量、管理工作负载和调度cloudlet激活状态**。此外，我们提出了**一个动态的支付机制，在更实际的情况下，运营商可以平衡短期利益和长期利益之间的权衡**。通过严格的分析，我们证明了我们的投标政策是理性和真实的;我们的工作负载管理算法在每次拍卖中都有接近最优的性能;我们的整体在线算法实现了一个可证明的竞争率。我们通过大量的跟踪驱动模拟进一步证实了我们的机制的性能。

**关键词:** Edge demand response, energy saving, cloudlet control, online mechanism

 

#### [TPDS 2022]Optimizing Network Transfers for Data Analytic Jobs Across Geo-Distributed Datacenters【8】

**摘要：**

跨地理分布的数据中心生成、存储和处理大量数据已成为最近的趋势。在使用MapReduce、Spark等流行的数据并行框架处理地理分布数据时，由于数据中心间链路的带宽远低于数据中心内链路，因此在通信阶段优化网络传输对应用性能的影响越来越重要。在本文中，我们将重点关注**如何为数据分析作业的跨数据中心流开发多路径路由的灵活性**，希望能够更好地利用跨数据中心链接，从而提高作业性能。我们设计了一个**最优的多路径路由和调度策略，以实现所有并行作业的最佳网络性能**，基于我们的优化问题可以转化为一个等价的线性规划(LP)问题来有效地解决。作为本文的重点，我们在一个应用层软件定义的跨数据中心叠加试验台的控制器上实现了本文提出的算法，该试验台旨在为Spark作业提供传输优化服务。通过对我们在谷歌Cloud上的实际实现的广泛评估，我们已经展示了令人信服的证据，表明我们的最优多路径路由和调度策略在工作性能方面取得了显著的改进。

**关键词：** Data analysis, Routing, Bandwidth, Task analysis, Sparks, Optimization, Internet

 

#### [TPDS 2022]Adaptive and Efficient Resource Allocation in Cloud Datacenters Using Actor-Critic Deep Reinforcement Learning【8】

**摘要：**

随着云数据中心规模的不断扩大，自动化资源配置势在必行，以最好地满足低延迟和高能效的需求。然而，由于系统状态的动态性和用户需求的多样性，云环境下资源的高效分配面临着巨大的挑战。现**有的云资源分配解决方案大多依赖于云系统的先验知识，不能有效地处理动态云环境，这可能会导致能源消耗过多和QoS (Quality-of-Service, QoS)降低**。为了解决这一问题，我们提出了一种基于Actor-Critic深度强化学习(DRL)的自适应高效云资源分配方案。首先，**参与者参数化策略(分配资源)，并根据批评家(评估操作)评估的分数选择操作(调度作业)**。**然后利用梯度上升更新资源分配策略，利用优势函数减小策略梯度的方差，提高了训练效率;**我们使用来自谷歌云数据中心的真实数据进行了广泛的模拟实验。结果表明，与两种基于DRL的高级云资源分配方法和五种经典的云资源分配方法相比，该方法在延迟和任务丢弃率方面具有更高的QoS，并提高了能量效率。

**关键词：**Resource management, Cloud computing, Quality of service, Training, Dynamic scheduling, Reinforcement learning, Energy consumption

 

#### [TPDS 2022]Cost-Effective Web Application Replication and Deployment in Multi-Cloud Environment【8】

**摘要：**

多云正在成为一个流行的云生态系统，因为它允许企业用户在多个云服务提供商之间共享工作负载，以更低的运营成本和更高的应用弹性实现高质量的服务。在多云中，云服务广泛分布在不同的地点，价格也不同。因此，**Web应用程序提供者面临着为应用程序复制和部署选择合适的云服务以最小化部署成本的挑战**。同时，**部署的应用程序副本必须满足请求响应时间的约束**，以保持用户体验的质量。为了满足这两个主要需求，本文研究了一个新的问题，即Web应用程序在多云环境下的复制和部署(WARDMC)，该问题**同时考虑了成本最小化和平均响应时间的约束**，特别是请求处理时间和网络延迟。为了解决这个问题，我们开发了一种名为MCApp的新方法。**MCApp将迭代混合整数线性规划与领域定制的大型邻域搜索相结合，以优化应用程序副本部署和用户请求调度**。使用真实数据集进行的大量实验表明，MCApp显著优于最近提出的几种方法。

**关键词：**Cloud computing, Costs, Time factors, Optimization, Upper bound, Pricing, User experience

 

#### [TPDS 2022]A Practical and Efficient Bidirectional Access Control Scheme for Cloud-Edge Data Sharing【8】

**摘要：**

云计算范式提供了许多诱人的优势，使用户能够方便地存储和共享数据。然而，用户自然不愿意将他们的数据直接外包给云计算，因为这些数据通常包含敏感信息。虽然已经提出了几种云数据共享的细粒度访问控制方案，但**大多数方案都关注于加密数据的访问控制**(例如，限制接收者的解密能力)。与现有的工作不同，本文旨在通过开发一个**更实用的双向细粒度访问控制方案**来解决这个具有挑战性的问题，该方案可以限制发送方和接收方的能力。为此，我们系统地研究了云数据共享的访问控制。受访问控制加密(ACE)的启发，我们提出了一种**将云端和边缘端结合起来的新型数据共享框架**。边缘服务器位于所有通信的中间，根据预定义的访问策略检查和防止非法通信。接下来，我们开发了一种有效的访问控制算法，利用基于属性的加密和代理再加密的框架。实验结果表明，与之前的工作相比，我们的方案在加解密方面具有更好的性能。      

**关键词：** Cloud computing, Access control, Receivers, Encryption, Servers, Cryptography, Search problems

 

#### [TPDS 2022]Mechanisms for Resource Allocation and Pricing in Mobile Edge Computing Systems【8】

**摘要：**

在本文中，我们将讨论移动边缘计算(MEC)系统中的资源分配和货币化挑战，在MEC系统中，**用户有不同的需求，并为高质量的服务而竞争**。我们将边缘资源分配问题(ERAP)表述为混合整数线性规划(MILP)，并证明了ERAP是NP-hard。为了有效地解决这一问题，我们提出了两种资源配置机制。首先，我们开发了一个**基于拍卖的机制**，并证明所提出的机制是个体理性的，并产生了无嫉妒的分配。我们还提出了一个**基于LP的近似机制**，该机制不能保证无嫉妒，但它提供的解决方案可以保证与最优解决方案保持一定距离。我们通过对各种规模的ERAP实例进行广泛的实验分析来评估所提出机制的性能。我们使用商业求解器求解MILP模型得到的最优解作为基准来评估解决方案的质量。我们的分析表明，所提出的机制可以在合理的时间内为相当大的问题实例获得接近最优的解决方案。

**关键词：**Resource management,Servers,Pricing,Edge computing,Cloud computing,Cost accounting,Computational modeling

 

#### [TPDS 2022]Data, User and Power Allocations for Caching in Multi-Access Edge Computing【8】

**摘要：**

在多访问边缘计算(MEC)环境中，应用程序供应商的数据可以缓存在边缘服务器上，以确保低延迟的数据检索。通过对传输功率的灵活分配，海量用户可以同时访问高速率的边缘服务器。管理网络资源的能力为应用程序供应商提供了独特的机会，但也带来了前所未有的挑战。为了**保证MEC环境下用户的快速数据检索，边缘数据缓存必须同时考虑数据、用户和传输功率的分配**。我们首次尝试研究**数据、用户和功率分配(DUPA 3)问题**，旨在**服务于大多数用户，最大化他们的总体数据速率**。首先，我们制定DUPA问题并证明其NP完备性。然后，我们将DUPA 3问题建模为一个潜在的承认至少一个纳什均衡的**DUPA 3博弈**，并提出一个**两阶段博弈论**的去中心化算法DUPA 3博弈来实现纳什均衡，作为DUPA 3问题的解决方案。为了评估DUPA 3博弈，我们分析了它的理论性能，并进行了广泛的实验来证明它的有效性和效率。

**关键词：** Servers, Resource management, Games, Interference, NOMA, Intercell interference, Distributed databases

 

#### [TPDS 2022]Customer Adaptive Resource Provisioning for Long-Term Cloud Profit Maximization under Constrained Budget【8】

**摘要：**

云计算作为一种高效的商业信息技术，已经吸引了越来越多的用户和企业使用。面对如此众多且种类繁多的客户，预算有限的云服务提供商(CPs)需要提供满意的定制定价服务，盈利的客户和系统投资，灵活的系统资源配置策略，以提高客户体验和长期利润。**现有的利润优化研究很少考虑客户的多样性和动态性**，**由于客户关系管理不善，可能会对长期利润增长产生负面影响**。在本文中，我们通过**考虑客户多样性和动态特性来实现客户关系管理，并提出了一种客户自适应资源配置方案，以在有限预算下实现长期利润最大化**。我们考虑了**四种客户类型(即忠诚的、旧的、新的和失去的)**，它们可以在客户与CP交互的生命周期中相互转换。CP构建多个云服务子平台，每个子平台包含多个多服务器系统，服务于同一类型的客户。对于云服务平台，我们首先使用分析方法对单个多服务器系统进行分析，以获得其最优利润、投入资金和系统配置。特别是，对于服务新客户和失去客户的系统，我们开发了一种**基于客户终身价值(CLV)的客户投资方案**，该方案在有限的营销预算下选择有价值的客户进行投资。基于上述分析，我们提出了一种由客户保留率(CRR)驱动的三阶段启发式方案，该方案在有限的基础设施预算下，优先投资于面临危险的客户的多服务器系统，以减少客户流失，促进长期利润增长。我们进行了大量的仿真实验来验证我们方法的有效性。仿真结果表明，与基准算法相比，该方法可将长期利润和CRR分别提高3.4倍和7.8倍。

**关键词：** Pricing, Cloud computing, Biological system modeling, Quality of service, Investment,Optimization, Costs

 

#### [TPDS 2022]A Bifactor Approximation Algorithm for Cloudlet Placement in Edge Computing【7】

**摘要：**

具有低延迟需求的新兴应用，如实时分析、沉浸式媒体应用和智能虚拟助手，使边缘计算成为关键的计算基础设施。现有的研究已经在具有不同目标(如延迟最小化、负载均衡、能源效率和放置成本最小化)的同构场景中探索了云的放置问题。然而，考虑到下一代5G网络和loT应用，将**云应用于高度异构的部署场景仍然是一个开放的挑战**。这些应用程序的新需求表明，在部署cloudlet时，在确保低延迟服务保证方面仍然存在差距。此外，**以经济有效的方式部署cloudlets和确保边缘计算中所有用户的完全覆盖是另一个关键的冲突问题。**在本文中，我们通过**设计一个双因子近似算法来解决异构云布局问题，以保证有限制的延迟和布局成本，同时将用户应用程序完全映射到适当的云**，从而解决这些问题。我们首先将该问题表述为一个多目标整数规划模型，并证明它是一个计算NP-hard问题。然后我们提出了一个双因子逼近算法，ACP，以解决其棘手的问题。我们通过在基于纽约市OpenData的多个部署场景中进行广泛的理论分析和实验，来研究ACP的有效性。我们证明了ACP提供了一个(2,4)近似比的延迟和放置成本。实验结果表明，ACP在一个多项式的运行时间内获得了接近最优的结果，使其适用于异构部署场景下的短期和长期云部署。

**关键词：**Cloud computing, Costs, Approximation algorithms, Edge computing, Servers, Low latency communication, Internet of Things

 

#### [TPDS 2022]Adaptive Resource Efficient Microservice Deployment in Cloud-Edge Continuum【7】

**摘要：**

面向用户的服务现在正朝着微服务体系结构发展，在这种体系结构中，服务是通过连接多个微服务阶段来构建的。由于整个服务是繁重的，所以微服务架构显示了只将一些微服务阶段卸载给接近终端用户的边缘设备的机会。然而，新兴技术往往导致云边缘连续体中基于微服务的服务质量(QoS)的违背，因为它们**没有考虑通信开销或微服务与外部协同任务之间的资源争用**。我们提出了Nautilus，这是一个运行时系统，可以在云边缘连续体中有效地部署基于微服务的面向用户的服务。**Nautilus确保基于微服务的面向用户的服务的QoS，同时最小化所需的计算资源**，它由一个通信感知的微服务映射器、一个争用感知的资源管理器和一个io敏感和负载感知的微服务迁移调度程序组成。映射器根据通信开销将微服务图划分为多个分区，并将这些分区映射到适当的节点。在每个节点上，资源管理器基于可能捕获复杂争用行为的强化学习确定其微服务的最佳资源分配。一旦微服务受到外部IO压力的影响，IO敏感的微服务调度器将关键节点迁移到空闲节点。此外，当微服务的负载动态变化时，负载敏感的微服务调度器将微服务从繁忙节点迁移到空闲节点，以确保整个服务的QoS目标。实验结果表明，在当前存在QoS违规的情况下，Nautilus能够在外部共享资源竞争下保证所要求的QoS目标。同时，Nautilus减少了23.9%的计算资源占用和53.4%的网络带宽占用，同时实现了所需的99%-ile延迟。

**关键词：** Quality of service, Cloud computing, Task analysis, Resource management, Computer architecture Runtime, Bandwidth

 

#### [TPDS 2022]Online Reconfiguration of IoT Applications in the Fog: The Information-Coordination Trade-Off【7】

**摘要：**

物联网(loT)的发展正在推动流量和处理需求的惊人增长，说服5G参与者改变他们的基础设施。在这种情况下，雾计算作为一种潜在的解决方案出现了，它为运行loT应用程序提供了附近的资源。然而，Fog带来了一些阻碍其应用的挑战。在本文中，我们考虑了重新配置问题，即**如何根据应用程序需求和资源使用的发展动态地调整在Fog上运行的loT应用程序的位置**。我们提出并评估了一系列基于在线调度和在线学习方法的重构算法。通过在现实测试平台上的大量实验，我们证明了**性能强烈依赖于Fog基础设施和loT应用程序信息的质量和可用性**。这些信息主要涉及应用程序的资源使用情况(由用户在应用程序设计期间估计)和基础设施中的资源可用性(由商业的现成监控工具收集)。最后，我们展示了一种**反应性和贪心策略，它依赖于这些额外的信息，可以克服最先进的在线学习算法的性能，即使在一个场景中不准确的信息。**

**关键词：** Internet of Things, Sensors, Cloud computing, Quality of service, Performance evaluation, Automobiles, Sensor phenomena and characterization

 

#### [TPDS 2022]Energy-Efficient Offloading for DNN-Based Smart IoT Systems in Cloud-Edge Environments【7】

**摘要：**

深度神经网络(DNNs)已成为智能物联网(loT)系统必不可少的重要支撑技术。由于大规模dnn的计算成本较高，直接将其部署在能量受限的loT设备中可能是不可行的。计算卸载技术通过将计算密集型任务卸载到云或边缘，为dnn的执行提供了一种可行的解决方案。然而，在云边缘环境中，**基于DNN且有截止日期限制的智能loT系统的节能卸载仍然是一个开放的挑战**。为了应对这一挑战，我们首先设计了一个**新的系统能耗模型**，该模型考虑了所有参与服务器(来自云和边缘)和loT设备的运行时、切换和计算能耗。其次，提出了一种基于自适应粒子群优化算法和遗传算法算子的节能卸载策略。该策略通过分层划分操作有效地对DNN层进行卸载决策，降低了SPSO-GA的编码维数，提高了执行时间。仿真结果表明，与其他经典方法相比，该策略能显著降低能耗。

**关键词：** Energy consumption, Internet of Things, Cloud computing, Servers, Data communication, Quality of service, Task analysis

 

#### [TPDS 2022]Decentralized Edge Intelligence: A Dynamic Resource Allocation Framework for Hierarchical Federated Learning【7】

**摘要：**

为了实现人工智能(Al)的大规模和高效部署，Al和边缘计算的融合产生了边缘智能(Edge Intelligence)，它利用终端设备和边缘服务器的计算和通信能力，在离数据产生地点更近的地方处理数据。Edge Intelligence的一项支持技术是隐私保护机器学习范式，即联邦学习(federallearning, FL)，它使数据所有者无需将原始数据传输到第三方服务器就可以进行模型训练。然而，FL网络被设想包含数千个异构的分布式设备。因此，沟通效率低下仍然是一个关键的瓶颈。**为了减少节点故障和设备丢失**，提出了**层次化联合学习**(Hierarchical Federated Learning, HFL)框架，通过中间模型聚合指定簇头来支持数据所有者。这种分散学习方法减少了对中央控制器(如模型所有者)的依赖。然而，**在人力资源管理框架中，资源配置和激励设计问题却没有得到很好的研究**。本文考虑了一个**二级资源配置与激励机制设计问题**。在较低的层次上，集群负责人为数据所有者的参与提供奖励，数据所有者可以自由选择加入哪个集群。具体来说，我们应用**进化博弈论来模拟集群选择过程的动力学**。在上层，每个集群头可以选择服务于一个模型所有者，而模型所有者必须相互竞争集群头的服务。因此，我们提出了一种基于深度学习的拍卖机制来推导每个集群头服务的估值。通过性能评估，验证了进化博弈的唯一性和稳定性，以及基于深度学习的拍卖算法的收益最大化特性。

**关键词：** Training, Computational modeling, Resource management, Magnetic heads, Data models, Games, Servers

 

#### [TPDS 2022]Harnessing the Potential of Function-Reuse in Multimedia Cloud Systems【7】

**摘要：**

**由于用户的预算限制或某些资源类型的限制，基于云的计算系统可能会超额订阅。超额订阅反过来会降低用户感知的服务质量(QoS)**。我们研究的减少超额订阅和产生的成本的方法是基于处理服务请求(即任务)所需计算的智能重用。我们为等待执行的任务提出了一个重用范例。在**多个用户可以同时请求类似服务的无服务器平台中，这种范式尤其具有影响力。**我们的动机是一个多媒体流媒体引擎，以按需方式处理媒体片段。我们提出了**一种机制来识别各种类型的“可合并”任务，并将它们聚合起来，以提高QoS和减少产生的成本**。我们开发了一种新的方法来确定何时以及如何执行任务聚合，以保证其他任务的QoS不受影响。评估结果表明，所提出的机制可以显著降低任务的逾期率，并将使用云服务的总时间(以及随后产生的成本)减少9%以上，从而提高QoS。

**关键词：** Streaming media, Task analysis, Cloud computing, Containers, Engines, Delays, Admission control

 

#### [TPDS 2022]Taskflow: A Lightweight Parallel and Heterogeneous Task Graph Computing System【7】

**摘要：**

Taskflow旨在使用基于任务图的轻量级方法简化并行和异构应用程序的构建。Taskflow引入了一种具有表达能力的任务图编程模型，以帮助开发人员在异构计算平台上实现并行和异构分解策略。**我们的编程模型将自己区分为一个非常通用的任务图并行类，它具有图内控制流，以实现端到端并行优化**。为了使我们的模型具有高性能，我们设计了一个高效的系统运行时，解决了我们模型中出现的许多新的调度挑战，**并在延迟、能源效率和吞吐量方面优化了性能**。我们已经在实际应用程序中演示了Taskflow的良好性能。例如，在一台拥有40个cpu和4个gpu的机器上，Taskflow解决的大规模机器学习工作负载比工业系统(oneTBB)快29%，内存少1.5倍，吞吐量高1.9倍。我们已经开放了Taskflow的源代码，并将其部署到开源社区的大量用户中。

**关键词：** Task analysis, Parallel processing, Graphics processing units, Computational modeling, Programming, Solid modeling, Runtime



#### [TPDS 2022]Towards Revenue-Driven Multi-User Online Task Offloading in Edge Computing【6】

**摘要：**

移动边缘计算(MEC)是一种利用边缘节点的可用资源来提高移动设备的计算和存储能力的解决方案。在MEC中，**任务的到达是高度动态的，很难精确预测**。在保证系统性能的前提下，将任务分配给边缘节点具有重要意义和挑战性。在本文中，我们的目标是通过**将任务最优地卸载给边缘节点来优化每个边缘节点所获得的收益**。提出了**收入驱动的在线任务卸载(ROTO)问题**，该问题被证明是NP-hard问题。首先，我们将ROTO分解为一个线性分式规划问题，提出了水平均衡分配(Level Balanced Allocation, LBA)算法。然后通过严格的理论分析证明了LBA的性能保证，并利用原对偶技术提出了ROTO的LBRounding算法。该算法以相当大的概率达到(d | 1)中2(1 + ξ)的近似比，其中d为边缘节点的最大进程槽数，f为一个小常数。通过跟踪驱动仿真和实验验证了该算法的性能。结果表明，与基线算法相比，该算法具有更高的效率。

**关键词：** Task analysis, Cloud computing, Approximation algorithms, Wireless communication, Software, Resource management, Optimization



#### [TPDS 2022]Elastic Parameter Server: Accelerating ML Training With Scalable Resource Scheduling【6】

**摘要：**

基于工作服务器通信的参数服务器(PS)设计用于集群中的分布式机器学习训练。在ML模型训练的反馈驱动探索中，用户利用每个作业的早期反馈来决定是终止作业还是继续运行作业，从而找到最优的模型配置。但是，PS不支持在运行时调整作业的工作者和服务器的数量。由于集群资源无法动态分配或释放到作业中，导致早期反馈延迟和资源利用率不足，成为可扩展分布式ML训练的瓶颈。本文重新思考PS体系结构的原理。我们提出了弹性参数服务器(EPS)，一个轻量级和用户透明的PS，加速了对分布式ML训练的反馈驱动探索。EPS允许从运行中的作业中删除工人和服务器的子集，并在运行时将释放的资源分配给传入的作业，以减少早期反馈延迟。它还可以使用一个终止作业释放的资源，将工人和服务器添加到正在运行的作业中，以提高资源利用率和训练速度。我们开发了一个启发式调度程序，利用EPS并为多个ML作业提供**可伸缩的资源调度**。我们在腾讯天使中实现EPS，在Apache Yarn中实现调度器，并使用各种ML模型进行评估。实验结果表明，EPS与PS相比，ML训练速度提高了1.5倍。

**关键词：**Servers, Training, Runtime, Clocks, Yarn, Resource management, Training data





#### [TPDS 2022]Multi-Swarm Co-Evolution Based Hybrid Intelligent Optimization for Bi-Objective Multi-Workflow Scheduling in the Cloud【6】

**摘要：**

许多科学应用可以很好地建模为大规模的工作流。云计算已经成为托管和执行它们的合适平台。工作流调度近年来受到了广泛的关注。然而，由于云服务提供商必须为多个具有不同QoS要求的用户提供服务，**因此调度多个具有不同QoS要求的应用具有很高的挑战性**。针对多工作流调度问题，提出了一种基于多群协同进化的混合智能优化(MCHO)算法，**在满足每个工作流的截止时间约束的情况下，使总最大完工时间和成本最小**。首先，我们设计了一种多群体协同进化机制，采用三个群体充分搜索不同的精英解。其次，为了提高粒子群优化器的全局搜索和收敛性能，我们将局部和全局引导信息嵌入到粒子群优化器的更新过程中，并开发了一种群协作技术。第三，提出了一种基于遗传算法的精英增强策略，利用更多的非支配个体，并利用模拟退火的Metropolis接受规则更新每个群体的局部引导解，以防止其在早期陷入局部最优。大量的实验结果表明，MCHO算法具有更好的分布式非支配解，其调度性能优于现有调度算法。



#### [TPDS 2022]TODG: Distributed Task Offloading With Delay Guarantees for Edge Computing【5】

**摘要：**

边缘计算已经成为一种通过计算卸载为资源和延迟敏感的loT应用程序提供快速和近数据计算服务的有效方法。有效的计算卸载策略需要综合处理以下几个主要问题**:1)动态通信和计算资源的分配;2)异构任务的延迟约束;3)计算成本低廉和分布式算法的要求**。然而，现有的工作主要集中在这些问题的一部分，这不足以在复杂和实际的场景中实现预期的性能。为了解决这一问题，本文系统地研究了一个具有延迟约束的分布式计算卸载问题，即**异构计算任务需要通过有限数量的随机通信信道不断地卸载到一组边缘服务器上**。将任务卸载问题描述为未知先验统计知识下的时滞约束长期随机优化问题。为了解决这个问题，我们首先提供了一个技术路径，将其转换并分解为几个槽级子问题。然后，我们设计了一种分布式在线算法，即TODG，以有效地分配资源和调度卸载任务。此外，我们从**最优差距、最坏情况下的延迟和系统参数的影响等方面对TODG进行了全面的分析**。大量的仿真结果验证了TODG算法的有效性和有效性。

**关键词：**Task analysis,Delays,Servers,Edge computing,Resource management,Mobile handsets,Optimization



#### [TPDS 2022]Horus: Interference-Aware and Prediction-Based Scheduling in Deep Learning Systems【4】

**摘要：**

深度学习(DL)模型作为任务部署在包含gpu的机器上。这些DL系统——从单一的GPU设备到机器集群——需要最先进的资源管理来提高资源利用率和作业吞吐量。虽然已经发现协同定位(多个任务同时位于同一GPU内)是实现这一目标的有效手段，但这种协同定位会导致性能干扰，直接削弱DL训练和推理性能。**现有的减少干扰的方法需要耗费大量资源和时间的内核分析，不适合运行时调度决策**。目前DL系统资源管理并没有针对这些问题进行设计。本文提出Horus，一种干涉感知资源管理器。我们的方法不是利用昂贵的内核分析，而是**估计作业资源利用率和共定位模式，以确定有效的DL作业安排，以最大限度地减少干扰的可能性，并提高系统资源利用率和完成时间**。我们的分析显示，干扰导致的工作减速高达3.2倍DL。我们在Kubernetes资源管理器中集成了我们的方法，并通过使用13种不同的模型类型训练2500个DL作业，在DL集群中进行了实验。结果表明，Horus在资源利用率和完成时间方面比其他DL资源管理者高出61.5%和33.6%。



#### [TPDS 2022]VQL: Efficient and Verifiable Cloud Query Services for Blockchain Systems【4】

**摘要：**

尽管出现了越来越多的应用程序，但区块链完全实用的一个主要问题是数据查询的低效率。在区块链上进行直接查询需要花费大量的时间来搜索每个块，而在区块链数据库上进行间接查询会大大降低查询结果的真实性。为了克服真实性问题，我们提出了一种可验证查询层(Verifiable Query Layer, VQL)，它可以部署在云上，为区块链系统提供高效和可验证的数据查询服务。中间件层从底层区块链系统中提取数据，并在数据库中有效地对其进行重组。为了防止在中间件中存储伪造的数据，根据每个构建的数据库计算一个密码指纹。数据库指纹将首先由矿工验证，然后写入区块链。此外，公共用户可以在中间件层验证整个数据库或几个他们感兴趣的数据库。我们将VQL与验证方案一起实现，并在一个实际的区块链系统上进行了大量的实验。评估结果表明，VQL能够有效地支持区块链系统的各种数据查询服务，并保证查询结果的真实性。

**关键词：**Blockchains, Peer-to-peer computing, Middleware, Bitcoin, Data mining, Distributed ledger, Costs



#### [TPDS 2022]On Mixing Eventual and Strong Consistency: Acute Cloud Types【3】

**摘要：**

本文研究了混合了最终一致性和强一致性的分布式系统的性质。我们通过急性云类型(ACTs)来形式化这样的系统，这是一种类似于无冲突复制数据类型(CRDTs)的抽象，在默认情况下，它以一种高可用性、最终一致的方式工作，但它也为需要全局一致的任务提供了强一致的操作。与其他混合一致性解决方案不同，ACTs可以依赖于高效的基于仲裁的协议，如Paxos。因此，对于强一致性操作，ACTs也可以优雅地容忍机器和网络故障。我们正式地研究ACTs并论证既不存在于纯粹最终一致的系统中也不存在于强烈一致的系统中的现象。特别是，我们确定了临时操作重新排序，这意味着在客户机请求执行的相对顺序上，副本之间的临时不一致。如果处理不当，这种现象可能会导致不期望的异常，包括循环因果关系。我们证明了在具有足够复杂语义的混合一致性系统中，临时操作重排序是不可避免的不可能结果。我们的结果是惊人的，因为它表明系统语义的明显增强(通过向最终一致的系统引入强一致的操作)会导致对最终一致操作的保证的弱化

 

#### [TPDS 2022]Performance and Cost-Efficient Spark Job Scheduling Based on Deep Reinforcement Learning in Cloud Computing Environments【3】

**摘要：**

Spark和Hadoop等大数据框架被广泛应用于研究和行业中运行分析工作。云计算提供了价格合理、易于管理的计算资源。因此，许多组织正在转向云部署他们的大数据计算集群。然而，在存在各种服务水平协议(Service Level Agreement, SLA)目标(如货币成本降低和工作性能改进)的情况下，**作业调度是一个复杂的问题。现有的大多数研究没有同时处理多个目标，也没有捕捉到固有的集群和工作负载特征**。在本文中，我们阐述了一个云部署的Spark集群的作业调度问题，并提出了一种新的强化学习(RL)模型来适应SLA目标。我们开发了RL集群环境，并在TF-Agents框架中实现了**两个基于深度强化学习(DRL)的调度器**。提出的基于DRL的调度代理在细粒度级别上工作，**在利用云虚拟机实例的定价模型的同时放置作业的执行器**。此外，基于DRL的代理还可以**了解不同类型作业的固有特征，从而找到合适的位置，以降低集群虚拟机的总使用成本和作业的平均持续时间**。结果表明，本文提出的基于drl的算法可将虚拟机的使用成本降低30%。

**关键词：**Sparks, Cloud computing, Costs, Task analysis, Service level agreements, Big Data, Reinforcement learning

#### [TPDS 2021]Hierarchical Multi-Agent Optimization for Resource Allocation in Cloud Computing【6】

**摘要：**

在云计算中，**一个重要的问题是将服务节点的可用资源按需分配给被请求的任务，并使目标函数最优，即资源利用率、收益和可用带宽最大化**。本文提出了一种分层多agent优化(HMAO)算法，以使云计算的资源利用率最大化，带宽成本最小。该算法是遗传算法(GA)和多智能体优化算法(MAO)的结合。在资源利用率最大化的情况下，采用改进的遗传算法查找一组用于部署请求任务的服务节点。提出了一种基于分散的MAO算法，以最小化带宽开销。利用方法研究了关键参数对HMAO算法的影响，并对算法的性能结果进行了评价。结果表明，在解决大规模资源分配优化问题时，HMAO算法比两种基线算法遗传算法(GA)和快速精英非支配排序遗传算法(NSGA-II)更有效。此外，我们还比较了HMAO算法与两种启发式的Greedy算法和Viterbi算法在在线资源分配方面的性能。

#### [TPDS 2020]Location-Aware and Budget-Constrained Service Deployment for Composite Applications in Multi-Cloud Environment【8】

**摘要：**

企业应用程序提供商为了技术和经济利益，越来越多地将他们的工作负载转移到云上。多云环境使得协调多个云资源成为可能。随着多个云提供商在不同地点以不同价格提供的可用云资源数量的增加，**应用程序提供商面临着选择合适的云资源以组件服务单元工作流的形式部署其应用程序的挑战**。现有的研究通常考虑最小化执行时间或/和部署成本。然而，从应用程序提供者的角度来看，他们也非常关注应用程序的响应时间，特别是包括部署的服务和用户之间的网络延迟。同时，应用程序的部署通常受到严格的预算控制，以确保财务可行性。本文研究了一种新型的复合应用程序部署问题，该问题在全局尺度上**综合考虑了多云环境下的性能优化和预算控制**。为了在不产生超支风险的情况下以最小的响应时间找到解决方案，我们提出了一种基于混合遗传算法的方法，该方法设计了新的领域定制服务聚类、修复算法、解决方案表示、种群初始化和遗传算子。使用真实数据集的大量实验表明，我们提出的混合遗传算法优于最近提出的一些方法。

#### [TPDS 2020]Scheduling Periodical Multi-Stage Jobs With Fuzziness to Elastic Cloud Resources【6】

**摘要：**

研究了一类任务到达时间随机、任务处理时间和截止日期模糊的工作流调度问题**。这个问题在许多实时和基于工作流的应用程序中很常见，在这些应用程序中，具有固定阶段数和线性依赖关系的任务是在具有多种价格选项的可伸缩云资源上执行的。挑战在于如何在随机和模糊任务下提出有效、稳定和鲁棒的算法。建立了基于三角模糊数的模型。研究了两个度量标准:**成本和满意度。提出了一种迭代启发式的任务调度框架**，该框架由任务集合和模糊任务调度阶段组成。提出了两种任务收集策略和两种任务优先化策略。为了获得较高的满意度，在工作和任务级别上都定义了期限约束。通过精心设计的实验，并应用复杂的统计技术，实验结果表明，该算法比现有的两种方法具有更好的有效性和鲁棒性。

------



### **International World Wide Web Conferences**

#### [WWW 2021]CoopEdge: A Decentralized Blockchain-based Platform for Cooperative Edge Computing【8】

**摘要：**

边缘计算(Edge computing, EC)是近年来兴起的一种为用户提供低延迟服务的新型计算模式。边缘服务器由于其物理大小有限，计算资源有限，无法在独立运行的情况下及时处理所有传入的计算任务。他们经常需要通过同侪分担来合作。边缘服务器由不同的利益相关者部署和管理，在一个不受信任的环境中运行。**信任和激励是它们之间合作计算面临的两个主要问题**。欧共体环境中的另一个独特挑战是以分散的方式促进信任和激励。为了系统地应对这些挑战，本文提出了一种**基于区块链的去中心化平台CoopEdge，来驱动和支持协同边缘计算。在CoopEdge上，边缘服务器可以发布一个计算任务，供其他边缘服务器竞争**。获胜者将根据他们的声誉从候选边缘服务器中选出。然后在边缘服务器之间达成共识，记录区块链上任务执行的性能。我们基于Hyperledger Sawtooth实现了CoopEdge，并在一个模拟EC环境中对基线和两个最先进的实现进行了实验评估。结果验证了CoopEdge的有效性和性能。



#### [WWW 2021]Surrounded by the Clouds: A Comprehensive Cloud Reachability Study【4】

**摘要：**

在云计算的早期，数据中心稀疏地部署在远离终端用户的位置，具有较高的端到端通信延迟。然而，今天的云数据中心在地理上更加分散，网络带宽不断增加，从而降低了终端用户的延迟。**在本文中，我们提供了一个全面的云可达性研究，因为我们对来自所有主要云提供商的189个数据中心执行广泛的全球客户端到云延迟测量**。我们利用了知名的测量平台RIPE Atlas，包括多达8500个探头，部署在不同的环境中，如家庭和办公室。我们的目标是评估现代云环境对各种当前和预测应用程序的适用性。我们通过将我们的延迟测量值与已知的人类感知阈值进行比较来实现这一目标，并能够推断出当前云对新应用(如增强现实)的适用性。我们的结果表明，当前的云覆盖可以很容易地为世界上大多数人支持几个对延迟至关重要的应用程序，比如云游戏。

 

#### [WWW 2021]CoResident Evil: Covert Communication In The Cloud With Lambdas【4】

**摘要：**

“无服务器”云服务，如AWS lambdas，是云服务市场增长最快的部分之一。这些服务之所以受欢迎，部分原因在于它们的轻量级特性以及调度和成本方面的灵活性，然而，与无服务器计算相关的安全问题还没有得到很好的理解。在这项工作中，我们探讨了从lambda构造一个实用的隐蔽信道的可行性。我们确定了lambdas的快速共居住检测是实现这种隐蔽通道的关键，并继续开发了基于内存总线硬件的可靠和可扩展的共居住检测器。我们的技术支持对共同驻留的lambdas进行动态发现，而且速度非常快，只需几秒钟即可执行。我们评估了我们的方法的正确性和可伸缩性，并使用它来建立隐蔽通道和在AWS lambdas上执行数据传输。我们表明，我们可以为每部署1000个lambdas建立数百个单独的隐蔽通道，每个这些通道都可以以每秒oo位的速度发送数据，因此证明通过lambdas进行隐蔽通信是完全可行的。



#### [WWW 2021]NTAM: Neighborhood-Temporal Attention Model for Disk Failure Prediction in Cloud Platforms【3】

**摘要：**

随着云平台的快速部署，高服务可靠性变得尤为重要。工业云平台中存在大量硬盘，硬盘故障是导致业务不可靠的常见原因。近年来，许多基于机器学习的硬盘故障预测方法被提出，它们可以在故障发生之前，根据硬盘状态数据预测硬盘故障。这样可以提前采取主动行动，提高服务的可靠性。但是，现有的方法单独处理每个磁盘，并不研究相邻磁盘的影响。本文提出了一种基于深度学习的硬盘故障预测方法——邻域-时间注意模型(NTAM)。在预测磁盘是否会在不久的将来发生故障时，NTAM是一种新颖的方法，它不仅利用磁盘自身的状态数据，而且还考虑其邻居的状态数据。此外，NTAM还包括一种新颖的基于注意力的时间组件，以捕获磁盘状态数据的时间特性。此外，我们提出了一种数据增强方法，称为时间渐进采样(TPS)，以处理极端的数据不平衡问题。我们在一个公共数据集和两个从微软Azure中数百万个磁盘收集的工业数据集上评估NTAM。我们的实验结果显示，NTAM的表现明显优于最先进的竞争对手。此外，我们的实证评估也显示了nam的邻域组件、时间组件的有效性，以及TPS的有效性。更令人鼓舞的是，我们已经成功地将NTAM和TPS应用于微软云平台(包括微软Azure和微软365)，并在行业实践中获得了效益。





------

### **ACM Symposium on Operating Systems Principles**

#### [SOSP 2021]RAS: Continuously Optimized Region-Wide Datacenter Resource Allocation【8】

**摘要：**

容量预留是公共云和内部基础设施中的常见产品。但是，**没有任何前期工作提供容量预留，并提供SLO保证，以考虑随机和相关的硬件故障、数据中心维护和异构硬件**。在本文中，我们描述了Facebook的区域级资源津贴系统(RAS)如何解决这些问题并**提供有保障的容量。RAS使用一种称为预留的能力抽象来表示一组动态分配给逻辑集群的服务器**。我们**采用两级方法将资源分配扩展到一个区域内的所有数据中心**，其中混合整数编程求解器不断优化服务器到预留分配的关键路径，而传统的容器分配器在预留中的服务器上实时放置容器。作为Facebook已有10年历史的集群管理器Twine的一个相对较新的组件，RAS已经在生产中运行了近两年，不断地优化数以百万计的服务器分配到数千个预订。我们描述RAS的设计，并分享大规模部署它的经验。



#### [SOSP 2021]Solving Large-Scale Granular Resource Allocation Problems Efficiently with POP【7】

**摘要：**

许多计算机系统中的资源分配问题可以表述为数学优化问题。然而，对于具有严格sla的大型问题来说，使用现成的求解器来找到这些问题的精确解通常是很难的，这导致系统设计师依赖于廉价的启发式算法。然而，我们观察到许多分配问题是细粒度的:它们由大量的客户端和资源组成，每个客户端请求资源总量的一小部分，并且客户端可以互换地使用不同的资源。对于这些问题，我们提出了另一种方法，重用原来的优化问题公式，并导致更好的分配比领域特定的启发式。我们的技术，**分区优化问题(Partitioned Optimization Problems, POP)，随机地将问题分解为更小的问题(使用系统中客户端和资源的子集)，并将结果子分配合并为所有客户端的全局分配**。我们提供了理论和经验的证据来解释为什么随机划分工作得很好。在我们的实验中，与现有的集群调度、流量工程和负载平衡系统相比，POP在运行时有数量级的改进，实现了最优分配的1.5%以内。



------

### **IEEE International Conference on Computer  Communications**

#### [INFOCOM 2021]Tailored Learning-Based Scheduling for Kubernetes-Oriented Edge-Cloud System【8】

**摘要：**

Kubernetes (k8s)具有合并分布式边缘和云的潜力，但缺乏一个专门用于边缘云系统的调度框架。此外，异构资源的分层分布以及请求和资源之间复杂的依赖关系使得面向k8s的边缘云系统的建模和调度变得尤为复杂。在本文中，我们引入了一种基于学习的边缘云系统调度框架KaiS，以提高请求处理的长期吞吐率。首先，我们设计了一种**协调的多智能体参与者批评算法，以满足边缘集群内分散的请求调度和动态调度空间**。其次，针对不同规模和结构的系统，利用图神经网络嵌入系统状态信息，并将嵌入结果与多个策略网络相结合，通过逐步调度降低编排维数;最后，我们采用了两种时间尺度的调度机制来协调请求调度和服务编排，并给出了部署上述算法与本地k8s组件兼容的实现设计。使用实际工作负载跟踪的实验表明，不管请求到达模式和系统规模如何，Kais都能成功地学习适当的调度策略。与基线相比，KaiS系统的平均吞吐量提高了14.3%，调度成本降低了34.7%。

 

#### [INFOCOM 2021]Monitoring Cloud Service Unreachability at Scale【7】

**摘要：**

我们考虑的是**全球规模的云托管服务中网络不可达的问题**，该服务面向数亿用户。甚至当服务本身启动时，用户所在位置和云之间的“最后一英里”往往是导致服务不可达的薄弱环节。我们介绍了NetDetector，这是一种基于基于客户端的HTTP-ping服务的测量来检测网络不可达性的工具。NetDetector采用两种模型。首先，GA(高斯警报)模型将http -ping的原始成功率暂时平均为高斯分布，并将显著下降标记为不可达事件。第二种更复杂的方法(BB，或Beta-Binomial)将网络连接的健康状况建模为访问请求成功的概率，从嘈杂的样本中估计健康状况，并根据从数据中导出的健康状况低于客户端网络特定SLO(服务水平目标)的情况发出警报。这些算法通过一种下钻技术得到增强，这种技术可以更精确地识别不可达事件的范围。我们介绍了已经部署的遗传算法和经过4个月时间的BB探测器的实验结果。例如，GA标记了49个国家一级的不可达事件，其中42个根据随叫随到的调查被标记为真实阳性工程师(OCEs)。

 

#### [INFOCOM 2021]Layer Aware Microservice Placement and Request Scheduling at the Edge【7】

**摘要：**

基于容器的微服务是一种很有前途的提高边缘计算弹性的技术。在运行时，**以容器映像形式封装的微服务需要频繁地从远程注册中心下载到本地边缘服务器，这可能会导致大量的下载流量和大量的本地存储开销**。由于边缘资源有限，为了增强微服务，最小化这种开销至关重要。**基于容器的微服务有一个尚未被开发的特点，那就是微服务图像是分层结构的，公共层可以由位于同一位置的微服务共享**。在本文中，我们研究了一种层感知的微服务布局和边缘请求调度。直观地说，通过共享位于同一位置的图像，可以显著提高吞吐量和托管微服务的数量。我们将其转化为一个具有近似子模性的优化问题，并证明这是NP-hard。设计了一种保证逼近比的迭代贪心算法。大量实验验证了该方法的有效性，结果表明，与最先进的微服务放置策略相比，放置的微服务数量增加了27.61%，微服务吞吐量提高了73.13%。

 

------

#### [INFOCOM 2021]Cost-Driven Data Caching in the Cloud: An Algorithmic Approach【7】

**摘要：**

云中的数据缓存是提高各种数据应用的QoS的一种有效方法。但是，考虑到管理云中缓存的成本，这种好处并不是免费的。在本文中，我们研究的是**云环境下的数据缓存问题**，它是由货币成本降低驱动的，而不是传统情况下有限容量下的命中率。特别是,给定一个流的请求R共享数据项,我们提出一个基于最短路径的最优算法,可以最小化总转移和在O (mn)时间离线缓存成本情况下,这里m表示网络中节点的数目,而n是请求流的长度。该计算的代价模型为半homo，表明所有节点对具有相同的传输代价，但每个缓存服务器节点都有自己的缓存代价率。我们的离线算法改进了之前的结果，不仅将时间复杂度从O(m2 n)降低到O(mn)，而且将代价模型松弛为半齐次的，使算法在现实中更加实用。此外,我们还研究这个问题在其在线形式,通过扩展先行缓存概念,我们提出一个2-competitive在线算法基于相同的成本模型和显示其紧张通过给一个下界的竞争比2 - o(1)对于任何确定的在线算法。我们通过对问题的深刻见解和对解决算法的仔细分析，以及基于跟踪的研究来评估它们在现实中的表现，可以证明我们实现了这些结果。



#### [INFOCOM 2021]Resource-Efficient Federated Learning with Hierarchical Aggregation in Edge Computing【4】

**摘要：**

联邦学习(FL)出现在边缘计算中，以解决传统基于云的集中式培训的带宽限制和隐私问题。然而，现有的**FL机制可能会导致训练时间过长，消耗大量的沟通资源**。本文提出了一种有效的FL机制，**通过平衡聚类将边缘节点划分为K个簇**。集群中的边缘节点通过同步方法(称为集群聚合)将它们的本地更新转发到集群报头进行聚合，而所有集群报头执行全局聚合的异步方法。这个处理过程称为**分层聚合**。我们的分析表明，收敛界取决于簇的个数和训练的时间。我们正式定义了资源高效的分层聚合联合学习(RFL-HA)问题。我们提出了一种有效的算法来确定具有资源约束的最优集群结构(即K的最优值)，并将其扩展到处理动态网络条件。针对不同模型和数据集的大量仿真结果表明，与已知的FL机制相比，本文提出的算法在实现类似精度的情况下，可将完井时间减少34.8%-70%，通信资源减少33.8%-56.5%。



#### [INFOCOM 2021]Distributed Threshold-based Offloading for Large-Scale Mobile Cloud Computing【3】

**摘要:** 

移动云计算使受计算限制的移动设备能够利用强大的云服务器执行实时密集计算，如语音识别或对象检测。大规模移动云计算中的一个重要问题是计算卸载，即每个移动设备**通过考虑本地处理延迟和使用云服务器的成本来决定何时和多少计算应该上传到云服务器。**在本文中，我们开发了一种**基于阈值的分布式卸载算法，当在设备上排队的任务数量达到阈值时，该算法将传入的计算任务上传到云服务器，否则在本地进行处理**。**阈值根据计算负载和使用云服务器的成本迭代更新**。我们将该问题表述为一个对称博弈，并给出了纳什均衡存在唯一性的充要条件。然后，当网元存在时，我们展示了我们提出的分布式算法对网元的收敛性。最后，我们进行了大量的仿真来验证我们的理论发现，并证明了我们提出的分布式算法在各种实际场景下的效率，如一般服务时间，不完美的服务器利用率估计，和异步阈值更新。



------

### **Symposium on Network System Design and  Implementation**

#### [NSDI 2021]Twenty Years After: Hierarchical Core-Stateless Fair Queueing【7】

**摘要：**

核心无状态公平排队(CSFQ)是20多年前提出的一种可扩展算法，目的是实现公平排队，而不需要保持网络中每个流的状态。不幸的是，CSFQ并没有流行起来，部分原因是它需要协议的改变(例如，在包头添加新的字段)，以及硬件支持以行速率处理包。在本文中，我们认为两个新兴的趋势使CSFQ再次相关:(1)云计算，它使在同一数据中心内或同一提供商拥有的跨数据中心更改协议成为可能;(2)可编程交换机，它可以实现线速度复杂的包处理。为此，我们提出了使用可编程开关的CSFQ的第一个实现。此外，我们将CSFQ推广为一个多级层次结构，它可以很自然地捕获当今数据中心的流量，例如，第一级的租户和第二级的每个租户的流量。我们将这种调度程序称为**分层核心无状态公平排队**(HCSFQ)，并证明它能够精确地近似分层公平排队。HCSFQ是高度可伸缩的:它只使用一个FIFO队列，不执行每包调度，只需要维护层次结构内部节点的状态。给出了证明HCSFQ下界的解析结果。实验和大规模仿真表明，CSFQ和HCSFQ能够提供公平的带宽分配和保证隔离。

#### [NSDI 2021]Ship Compute or Ship Data? Why Not Both?【3】

**摘要：**

云应用程序应该如何与他们的数据交互仍然是一个活跃的研究领域。在过去的十年中，许多人建议依赖键值(KV)接口来与存储在远程存储服务器中的数据进行交互，而其他人则担保使用远程过程调用(RPC)的好处。在本文中，我们认为理想的解决方案必须自适应地将两者结合在一起，从而在满足应用程序延迟需求的同时最大化吞吐量。为此，我们提出了一个名为Kayak的新系统，它主动调整请求的速率，以及使用RPC或KV执行的请求的比例，所有这些都以一种完全分散和自我调节的方式进行。从理论上证明了Kayak能够快速收敛到最优参数。我们实现了Kayak的系统原型。我们的评估表明，对于计算密集型工作负载，Kayak实现了亚秒级的收敛，并将总体吞吐量提高了32.5%-63.4%，而对于非计算密集型工作负载和事务负载，在目前状态下提高了12.2%

 

#### [NSDI 2021]Caerus: NIMBLE Task Scheduling for Serverless Analytics【3】

**摘要：**

无服务器平台促进了透明的资源弹性和细粒度的计费，使它们成为数据分析的一个有吸引力的选择。我们发现，虽然以服务器为中心的分析框架通常通过作业间调度策略优化作业完成时间(JCT)、资源利用和隔离，但**无服务器的分析需要对JCT和执行成本进行优化**，从而引入了一个新的调度问题。我们介绍了Caerus，这是一个任务调度器，用于无服务器的分析框架，它使用了一个细粒度的NIMBLE调度算法来解决这个问题。在任意分析作业中，NIMBLE能够高效地将任务执行流水线化，**最小化执行成本，同时实现成本和JCT之间的pareto优化**。为此，NIMBLE建模了各种各样的执行参数——可流水线化和非流水线化的数据依赖关系、数据生成、消耗和处理速率等——以确定理想的任务启动时间。我们的评估结果表明，在实践中，Caerus能够在广泛的分析工作负载中实现查询的最佳成本和JCT。

#### [NSDI 2021]When to Hedge in Interactive Services【2】

**摘要：**

在在线数据密集型(OLDI)服务中，每个客户端请求通常在多个服务器上并行执行;因此，“系统故障”虽然在单个服务器中很少见，但可能会干扰许多客户端请求并导致服务水平目标的违反。长期以来，服务提供商一直在通过“对冲”来解决这个“大规模尾巴”问题，也就是说，通过发出冗余查询来掩盖系统故障。然而，这可能会导致拥塞。本文提出了一个问题:在OLDI服务中，什么时候对冲是有意义的?我们如何对冲足够多的对冲来掩盖系统的小故障，但又不至于造成拥塞?首先，我们表明，在许多现实的场景中，套期保值可能没有任何好处——任何基于套期保值的调度策略，包括最先进的策略，与不使用套期保值的最佳负载平衡相比，都不会减少延迟。其次，我们提出了一种将最优负载平衡和保存工作的对冲结合起来的调度策略LAEDGE，并在AWS云部署中对其进行了评估。我们证明LAEDGE达到了正确的平衡:首先，与目前的技术不同，它从不导致不必要的拥塞;其次，它执行的调度策略接近于理想的调度策略，将$99百分位延迟提高了$49，这是在$60的系统利用率上测量的——没有任何困难的参数训练，就像目前的技术水平一样。



#### [NSDI 2021]When to Hedge in Interactive Services【2】

**摘要：**

在在线数据密集型(OLDI)服务中，每个客户端请求通常在多个服务器上并行执行;因此，“系统故障”虽然在单个服务器中很少见，但可能会干扰许多客户端请求并导致服务水平目标的违反。长期以来，服务提供商一直在通过“对冲”来解决这个“大规模尾巴”问题，也就是说，通过发出冗余查询来掩盖系统故障。然而，这可能会导致拥塞。本文提出了一个问题:在OLDI服务中，什么时候对冲是有意义的?我们如何对冲足够多的对冲来掩盖系统的小故障，但又不至于造成拥塞?首先，我们表明，在许多现实的场景中，套期保值可能没有任何好处——任何基于套期保值的调度策略，包括最先进的策略，与不使用套期保值的最佳负载平衡相比，都不会减少延迟。其次，我们提出了一种将最优负载平衡和保存工作的对冲结合起来的调度策略LAEDGE，并在AWS云部署中对其进行了评估。我们证明LAEDGE达到了正确的平衡:首先，与目前的技术不同，它从不导致不必要的拥塞;其次，它执行的调度策略接近于理想的调度策略，将$99百分位延迟提高了$49，这是在$60的系统利用率上测量的——没有任何困难的参数训练，就像目前的技术水平一样。





------

### **USENIX Annul Technical Conference**

#### [ATC 2021]Scaling Large Production Clusters with Partitioned Synchronization【6】

**摘要：**

近年来，计算机集群的规模显著增长。现在，一个集群每天可能有10万台机器，执行数十亿个任务，特别是短任务。因此，管理集群中资源利用的调度器也需要升级，以在更大的规模下工作。然而，在大型生产集群中，**升级调度程序(一个中央系统组件)是一项艰巨的任务，因为我们需要确保集群的稳定性和鲁棒性**，例如，应该保证用户透明性，其他集群组件和现有的调度策略需要保持不变。我们研究了现有的调度器设计，发现大多数都不能处理我们的生产集群的规模，或者可能会危及它们的鲁棒性。我们分析了一种最合适的设计，它遵循共享状态体系结构，它的限制使我们得到了一种细粒度的过时感知状态共享设计，称为分区同步(ParSync)。**ParSync具有维护生产集群健壮性所需的简单性，同时实现高调度效率和高质量的扩展**。ParSync已经部署，并在我们的生产集群中稳定运行。



#### [ATC 2021]Prediction-Based Power Oversubscription in Cloud Platforms【6】

**摘要：**

之前的工作使用功率封顶来减少罕见的功率峰值，并为数据中心增加更多的服务器，从而超额占用其资源并降低成本。当工作负载及其服务器位置已知时，这种方法可以很好地工作。不幸的是，**这些因素在公共云中是未知的，迫使供应商限制超额认购，从而限制功率封顶带来的潜在性能损失**。在本文中，我们认为提供商**可以使用工作负载性能临界度和虚拟机(VM)资源利用率的预测来增加超额订阅**。这带来了许多挑战，例如从不透明的vm识别性能关键的工作负载，创建对临界状态敏感的电源管理的支持，以及在限制上限影响的同时增加超额订阅。我们针对微软Azure的硬件和软件解决了这些挑战。结果表明，我们使超订阅增加了2倍，而对关键工作负载的影响最小。我们描述了在生产环境中部署工作的经验教训。



#### [ATC 2021]Fighting the Fog of War: Automated Incident Detection for Cloud Systems【4】

**摘要：**

**事件和中断极大地降低了AWS、Azure和GCP等大规模云计算系统的可用性**。在当前的事件响应实践中，每个团队对整个系统只有部分的看法，这使得事件的检测就像在“战争迷雾”中战斗。因此，减缓时间延长，财务损失增加。在本工作中，我们**提出了一个自动事件检测系统**，即Warden，作为事件管理(IcM)平台的一部分。管理者从不同的服务收集警报，并从全球的角度检测事件的发生。**对于检测到的每一个潜在事件，管理者都会通知相关的随叫随到的工程师，以便他们能够适当地安排任务的优先级，并启动跨团队协作**。我们在Azure的IcM平台上实现并部署了Warden。我们的评估结果基于18个月期间从26个主要服务项目收集的数据，表明Warden方法是有效的，并且优于基线方法。对于大多数成功检测到的事件(约68%)，Warden比人类更快，尤其是那些需要很长时间手动检测的事件。





------

### **Real-Time Systems Symposium**

#### [RTSS 2021]Partitioned Scheduling of Recurrent Real-Time Tasks【6】

**摘要：**

考虑了在多处理器平台(包括相同的和不同的)上周期性和偶发性任务系统的分区调度问题。研究了大量这种分区可调度性问题的计算复杂性。对几个问题提出了复杂性的新的上下界。一些问题以这种方式被归入它们精确的复杂性类别。汇编了一份问题清单，对这些问题的确切分类仍然没有定论。



------

### **International Joint Conference on  Artificial Intelligence**

#### [IJCAI 2021]Predictive Job Scheduling under Uncertain Constraints in Cloud Computing【6】

**摘要:** 

由于在不同时间运行大量异构的按需实例，容量管理一直是云平台的一大挑战。为了更好地规划整个平台的容量，已经发布了一类云计算实例来提前收集计算需求。要使用这样的实例，用户可以提交作业，在未来一段灵活的时间内，在预先指定的不间断时间内运行，与正常的需求实例相比，有一定的折扣。考虑到平台的容量状态，主动调度这些预先收集到的作业请求，可以在较长时间内极大地平衡计算负载。在本工作中，**我们将这些预先收集的作业请求在不确定可用容量下的调度问题定义为一个具有约束不确定性的预测+优化问题**，并提出了一种有效的算法，称为在不确定约束下的控制(controlled under uncertainty constraints, CUC)。其中，**预测容量指导作业调度的优化，并利用作业调度结果通过贝叶斯优化提高对容量的预测**。所提出的公式和解决方案通常适用于云计算中的主动调度问题。我们在三个公开的工业数据集上进行了广泛的实验，表明CUC在支持云平台的高可靠性方面具有巨大的潜力。



#### [RTSS 2021]Joint Model and Data Adaptation for Cloud Inference Serving【2】

**摘要：**

实时深度学习推理服务系统通常需要禁止性的资源和多样化的用户需求。现有推理服务系统的设计主要集中在计算资源效率上，很大程度上忽略了计算资源和所需带宽资源之间的权衡。次优的资源利用通常会导致巨大的服务成本浪费。在本文中，我们通过提出A2(一种高效的联合自适应模型)和跨地理数据中心的自适应数据深度学习服务解决方案来应对计算带宽权衡和成本效益的双重挑战。受实现相同精度的计算成本和带宽成本之间的权衡的启发，我们设计了实时推理服务框架，该框架选择性地将深度学习模型的不同“版本”放置在不同的地理位置，并调度不同的数据样本版本发送到那些模型版本进行推理。目标是最小化总服务成本，同时满足服务请求的延迟和准确性要求。我们提出了一个联合布局和服务问题，并提出了一个有效的近似算法来解决它，同时保证了理论上的性能。我们在Amazon EC2上部署了A2进行实验，实验表明，与基线相比，在相同的延迟和准确性要求下，A2实现了30%-50%的服务成本降低。

 

#### [RTSS 2021]LaLaRAND: Flexible Layer-by-Layer CPU/GPU Scheduling for Real-Time DNN Tasks【2】

**摘要：**

深度神经网络(DNNs)在各种机器学习(ML)任务中表现出显著的成功，这些任务对于许多安全关键的实时嵌入式系统是有用的。在实时嵌入式系统上实现DNN执行的首要设计目标是用有限的计算资源提供最坏情况下的时序保证。事实上，最新的ML框架很难利用异构计算资源(即CPU、GPU)来提高实时DNN任务的可调度性，这是由于几个因素，包括粗粒度的资源分配模型(每任务一个资源)、CPU和GPU上DNN执行的非对称性质以及缺乏可调度性感知的CPU/GPU分配方案。据我们所知，本文首次提出了解决上述三个主要障碍的研究，并检验了它们对可调度性改进的协同效应。在本文中，我们提出了实时层级DNN调度框架LaLaRAND，它通过将CPU友好的量化与细粒度的CPU/GPU分配方案(每层一个资源)紧密耦合，实现了单个DNN层的灵活CPU/GPU调度，同时在不牺牲时序保证的情况下减轻了精度损失。我们在最先进的ML框架上实现并评估了LaLaRAND，以展示其在使更多DNN任务集可调度性方面的有效性，分别比现有方法和基线(vanilla PyTorch)高56%和80%,而性能(推理准确性)差异仅为-0.4%。

 







------

### **IEEE Transactions on Computer-Aided Design of  Integrated Circuits And System**

#### [TCAD 2022]Contention Cognizant Scheduling of Task Graphs on Shared Bus-Based Heterogeneous Platforms【5】

**摘要：**

**在严格的资源预算内对高性能和可靠性的需求正在推动从同质处理平台向异构处理平台的转变，以实施当今的网络物理系统 (CPS)。**这些 CPS 通常表示为有向无环任务图 (DTG)，因为它们的功能组件之间通常分布在自然界中的复杂交互。这项工作处理调度建模为 DTG 的 CPS 的问题。首先，我们**提出了一个使用整数线性规划 (ILP) 的 DTG 最佳解决方案**，该解决方案将在通过共享总线互连的分布式异构处理器上执行。然而，这种基于 ILP 的最优解决方案具有很高的计算复杂性，并且不适用于中等规模的问题。因此，我们提出了一种称为争用识别任务和消息调度器（CC-TMS）的低开销启发式算法，它能够在合理的时间内产生令人满意的高效和快速的解决方案。所提出方案的效率已通过使用基准 DTG 的基于仿真的实验进行了广泛评估。通过对真实世界汽车牵引力控制器的案例研究，我们证明了我们提出的方案的实际适用性。





------

### **International Conference for High Performance  Computing, Networking, Storage, and Analysis**

 

#### [SC 2021]The hidden cost of the edge: a performance comparison of edge and cloud latencies【5】

**摘要：**

边缘计算已经成为运行对延迟敏感的应用程序的流行范例，因为它能够为最终用户提供较低的网络延迟。在本文中，我们认为，与云数据中心相比，尽管其网络延迟较低，但边缘资源受限的本质可能导致更高的端到端延迟，特别是在更高的利用率时。我们通过对边缘和云延迟的分析比较来研究边缘性能反演问题，并**分析在哪些条件下，边缘可能产生比云更差的性能**。为了验证我们的分析结果，我们使用一个真实的应用程序和真实的云工作负载，对边缘和云延迟进行了详细的实验比较。我们的分析和实验结果都表明，即使**在适度的利用率下，边缘排队延迟也可以抵消较低网络延迟的好处，甚至会导致性能反转，即在云中运行可以提供更好的延迟**。最后，我们讨论了我们的结果的实际含义，并提供了应用程序设计者和服务提供者应该如何设计边缘应用程序和系统以避免这些缺陷的见解。

 

#### [SC 2021]Understanding, predicting and scheduling serverless workloads under partial interference【4】

**摘要：**

分布式云应用之间的干扰可以分为三种类型:完全干扰、部分干扰和零干扰。虽然之前的研究只关注于完全干扰，但**出现在部分应用中的部分干扰更为常见，但仍缺乏深入的研究**。**无服务器计算将应用程序结构成小型的、寿命较短的函数，这进一步加剧了部分干扰**。我们将无服务器环境下的部分干扰特征描述为高波动性、时空变化和传播。鉴于这些观察结果，我们提出了一种**增量学习预测器**，名为Gsight，它可以**通过端到端调用路径利用函数的时空重叠代码和概要来实现高精度**。实验结果表明，Gsight的平均误差为1.71%。它的收敛速度至少比服务器系统快3倍。调度实例研究表明，该方法在保证服务质量的前提下，函数密度提高了18.79%。



#### [SC 2021]Generalizable coordination of large multiscale workflows: challenges and learnings at scale【3】

**摘要：**

机器学习技术的进步和当前大多数超级计算机的异构架构推动了对大型多尺度模拟的需求，这种模拟可以自动和自主地耦合不同的组件，并将它们映射到相关资源，以解决多尺度的复杂问题。然而，尽管工作流技术最近取得了进展，但当前的功能仅限于耦合两个尺度。在首次使用三种分辨率的演示中，我们提出了一个可扩展和可推广的框架，该框架使用机器学习和原位反馈对模型进行耦合。我们扩展了大规模并行的多尺度机器学习建模基础设施(MUMMI)，一个获得好评的工作流，并在原有设计之外推广了框架。我们讨论了在执行一个大规模的多尺度模拟活动时所面临的挑战和学习，该活动在Summit上使用了超过60万个节点小时，GPU占用率超过98%，占用时间超过83%。我们提供的创新可以实现几个数量级的扩展，包括同时协调24,000个工作，每天管理数tb的新数据和总计超过10亿个文件。最后，我们将描述框架的通用性，并在即将发布的开源版本中讨论如何将所呈现的框架用于新的应用程序。

**关键词：**multiscale simulations, adaptive simulations, massively parallel, heterogenous architecture, machine learning, cancer research





------

### **IEEE Journal of Selected Areas in Communications**

#### [JSAC 2022]Blockchain-Based Task Offloading for Edge Computing on Low-Quality Data via Distributed Learning in the Internet of Energy【4】

**摘要：**

随着能源互联网的发展，越来越多的参与者通过不同类型的边缘设备共享数据。然而，这种多源异构数据通常包含低质量的数据，例如丢失的值，这可能会导致潜在的风险。在边缘计算网络中，资源受限的设备会造成较大的延迟。为了减少这种延迟，分布式任务卸载方案可以在边缘节点和附近服务器之间分担计算量。然而，这类计划有三个主要缺点。首先，**低质量的数据没有被场景下的约束仔细评估**，这可能导致**分布式计算收敛缓慢**。其次，在没有隐私保护的情况下，**计算包括敏感信息在内的多源数据并在边缘节点之间共享**。第三，在**低质量数据上的分布式任务即使采用最优的卸载方案也可能导致低质量的结果**。针对上述问题，本文提出了一种**基于联盟区块链和分布式强化学习的边缘计算任务卸载框架，该框架能够提供高质量的任务卸载策略，同时保护数据隐私**。这个框架由三个主要组成部分组成:基于多个数据质量维度的数据质量评价(DQ)、基于修复共识机制的修复算法的数据修复(DR)和基于低质量数据分布策略的分布式强化学习(DELTA)。数值计算结果表明，所提出的任务卸载框架对于低质量数据的边缘计算是有效和高效的。



#### [JSAC 2022]Information Freshness-Aware Task Offloading in Air-Ground Integrated Edge Computing Systems【2】

**摘要：**

本文研究了一种由基础设施提供商(InP)部署的空地综合多接入边缘计算系统。根据与InP的商业协议，第三方服务提供商为订阅移动用户(MUs)提供计算服务。MUs会随着时间的推移而竞争共享的频谱和计算资源，以实现它们独特的目标。从MU的角度来看，我们有意定义更新的时间，以从更新的计算结果中捕获过时的信息。在给定系统动力学的情况下，我们将MUs之间的相互作用建模为一个随机博弈。在没有合作的纳什均衡中，每个MU的行为都符合系统的局部状态和猜想。因此，我们可以将随机博弈转化为单个体的马尔可夫决策过程。作为另一个主要贡献，我们开发了一种在线深度强化学习(RL)方案，该方案采用了两个独立的双深度q网络来分别逼近q因子和决策后q因子。深度RL方案允许每个MU优化具有未知动态统计量的行为。数值实验表明，在不同的系统条件下，我们提出的方案在平均效用方面优于基线。



#### [JSAC 2022]Private Retrieval, Computing, and Learning: Recent Progress and Future Challenges【2】

**摘要：**

我们的大部分生活都是在网络空间中进行的。人类对隐私的概念转化为网络空间中许多功能上的隐私概念。本文主要关注这三个功能:如何私下地从网络空间检索信息(信息检索中的隐私)，如何私下地利用大规模分布式/并行处理(分布式计算中的隐私)，以及如何从跨多个用户的隐私数据学习/训练机器学习模型(分布式(联邦)学习中的隐私)。本文对每个隐私设置进行了激励，描述了问题的提法，总结了每个问题历史上的突破性成果，给出了最近的成果，并讨论了每个领域中出现的一些主要思想。此外，还讨论了横切技术和三个主题之间的相互联系，以及一系列开放的问题和挑战。

------

### **ACM Transactions on Computer Systems**

#### [TOCS 2021]AI Tax: The Hidden Cost of AI Data Center Applications【3】

**摘要：**

人工智能和机器学习正在工业界和学术界得到广泛采用。这是由日益复杂的算法和模型在人工智能的应用和准确性方面的快速进步推动的；这反过来又刺激了对专门硬件人工智能加速器的研究。鉴于进步的速度很快，人们很容易忘记它们通常是在真空中开发和评估的，而没有考虑完整的应用程序环境。这篇文章强调了对人工智能(AI)工作负载进行整体、端到端分析的必要性，并揭示了“AI税”。我们在边缘数据中心部署和表征人脸识别。该应用程序是一个以人工智能为中心的边缘视频分析应用程序，使用流行的开源基础设施和机器学习(ML)工具构建。尽管使用了最先进的AI和ML算法，但该应用程序严重依赖于预处理和后处理代码。随着以人工智能为中心的应用受益于加速器承诺的加速，我们发现它们给**硬件和软件基础设施带来了压力:随着人工智能加速的增加，存储和网络带宽成为主要瓶颈**。通过专门针对人工智能应用，我们表明，**专门构建的边缘数据中心可以针对加速人工智能的压力进行设计，其总拥有成本比来自同构服务器和基础设施的数据中心低15%**。

**关键词：**Computing methodologies; Machine learning; Artificial intelligence; Software and its engineering; Software performance



------

### **IEEE Transactions on Computer-Aided Design of  Integrated Circuits And System**

#### [TCAD 2022]Fixed-Priority Scheduling for Reliable and Energy-Aware (m, k)-Deadlines Enforcement With Standby-Sparing【3】

**摘要：**

对于实时计算系统，能源效率、服务质量 (QoS) 和容错是主要的设计关注点。在这项工作中，我们研究了在固定优先级分配下使用备用的可靠和能量感知备用,备用系统采用一个主处理器和一个备用处理器来为永久和瞬时故障提供容错。为了降低此类系统的能耗，我们在 (m,k)的 QoS 约束下提出了两种新颖的调度方案(m, k )(m, k ) -deadlines：一种用于以深红色模式划分的任务集，另一种用于以均匀分布模式划分的任务集。评估结果表明，我们提出的方法显着优于先前的节能研究，同时确保实时系统的(m, k )

**关键词：** 任务分析, 实时系统,瞬态分析, 服务质量,容错系统,能源消耗,可靠性



### **High Performance Computer Architecture**

#### [HPCA 2021]Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling【3】

**摘要：**

为了满足日益增长的深度学习推理服务需求，许多云计算供应商采用了高性能的专业加速器，称为神经处理单元(NPUs)。对于NPUs的有效利用，一个重要的挑战是在广泛的深度神经网络(DNN)模型上实现不同算法强度的高资源利用率。NPU的**计算内存带宽比和它执行的模型的算法强度之间经常存在内在的不匹配，导致计算资源或内存带宽利用率不足**。理想情况下，我们希望使计算TOP/s和DRAM带宽达到饱和，以实现高系统吞吐量。因此，我们提出了一种具有新颖多模型时间复用调度的npu推理服务系统layer - weaver。Layerweaver**通过将具有相反特征(计算密集型和内存密集型)的多个不同模型的层执行交织在一起，减少了计算资源的时间浪费**。Layerweaver通过将内存密集型模型与计算密集型模型相对较长的计算时间重叠来隐藏内存密集型模型的内存时间，从而最小化计算单元等待片外数据传输的空闲时间。批处理的两种模型服务场景1和16不同的计算和内存密集型模型,对Layerweaver提高时间利用率的计算单位和记忆频道44.0%和28.7%,分别平均提高系统吞吐量的60.1%,在基线执行一个模型。

**关键词：**Schedules, Scheduling algorithms, Computational modeling, Neural networks, Memory management, Random access memory, Bandwidth



------

### **International Conference on Architectural Support  for Programming Languages and Operating Systems**

#### [ASPLOS 2022]Serverless computing on heterogeneous computers【3】

**摘要：**

现有的无服务器计算平台构建在同构计算机上，限制了功能密度，并将无服务器计算限制在有限的场景中。我们介绍了molecular，**第一个利用异构计算机的无服务器计算系统**。分子支持通用设备(如Nvidia DPU)和特定领域的加速器(如FPGA和GPU)，用于无服务器应用程序，显著提高功能密度(50%以上)和应用程序性能(高达34.6倍)。为了实现这些结果，我们首先提出了XPU-Shim，这是一种分布式shim，用于弥合底层多操作系统(当使用通用设备时)和我们的无服务器运行时(即Molecule)之间的差距。我们进一步引入了向量化沙盒，一种用于抽象硬件异构性的沙盒抽象(当使用特定领域的加速器时)。此外，我们还回顾了在启动和通信延迟方面的最先进的无服务器优化，并克服了在异构计算机上实现这些优化的挑战。我们已经使用Nvidia dpu和Xilinx fpga在实际平台上实现了Molecule，并使用基准测试和实际应用对其进行了评估。



------

### **IEEE Transactions on Mobile Computing**

#### [TMC 2022]Imitation Learning Enabled Task Scheduling for Online Vehicular Edge Computing【3】

**摘要：**

车辆边缘计算(vehicle edge computing, VEC)是一种基于车联网为终端用户提供计算资源、减轻蜂窝网络沉重流量负担的有前景的计算模式。在本文中，我们考虑了一个具有动态拓扑、不稳定连接和不可预测运动的VEC网络。**车内车辆可以将计算任务卸载到由车载资源组成的相邻VEC集群中，以达到最小化系统能耗和满足任务延迟约束的目的**。对于在线任务调度，现有研究要么设计启发式算法，要么利用机器学习，如深度强化学习(DRL)。但是，这些算法在大规模网络中**搜索效率低，收敛速度慢，不够有效**。相反，我们提出了一种**基于模仿学习的在线任务调度算法，该算法从初始阶段就具有接近最优的性能**。特别地，专家可以在离线的情况下，用少量的样本来求解所制定的优化问题，从而得到最优的调度策略。对于在线学习，我们根据专家的论证，在理论上可以接受的绩效差距来训练代理策略。性能结果显示，与基准测试相比，我们的解决方案有超过50%的改进，具有显著的优势。



#### [TS 2021]Multi-objective Optimization of Data Placement in a Storage-as-a-Service Federated Cloud【7】

**摘要：**

云联合使服务提供商能够相互协作，为客户提供更好的服务。对于云存储服务来说，**优化联邦成员的客户对象布局是一个真正的挑战。需要考虑存储、迁移和延迟成本**。在某些情况下，这些成本是相互矛盾的。在本文中，我们将对象放置建模为一个**多目标优化问题**。**建议的模型考虑了与本地基础设施、联邦环境、客户工作负载及其sla相关的参数**。为了解决这个问题，我们提出了CDP-NSGAIIIR，一种基于NSGAII的带有注入和修复函数的约束数据放置数学模型。注入功能旨在提高解决方案的质量。它包括用精确的方法计算一些解，然后将它们注入到nsgai的初始种群中。修复函数确保解决方案服从问题约束，从而防止探索大量不可行的解决方案。它大大减少了NSGAII的执行时间。实验结果表明，注入函数使NSGAII和精确方法的HV分别提高了94%和60%，而修复函数平均减少了68%的执行时间。

------

#### IEEE Transactions on Information Forensics and Security

#### [TIFS 2019]Extensible Conditional Privacy Protection Authentication Scheme for Secure Vehicular Networks in a Multi-Cloud Environment【4】

**摘要：**

随着云服务提供商(csp)数量的增加，针对多云环境提供解决方案以避免厂商锁定和处理单点故障问题的研究工作已经大大扩展。然而，少数方案关注的是多云环境下车载网络的条件隐私保护认证。为此，我们提出了一种健壮、可扩展的车载网络认证方案，以满足用户日益多样化的业务需求。根据我们的解决方案，车辆只需要向可信授权机构(TA)注册一次，就可以与csp实现快速、高效的身份验证。此外，只要新的CSP在TA成功注册，它就可以参与车辆服务。由电讯局长管理的云代理负责连接所有云服务;因此，用户看不到csp选择的复杂性。详细的安全分析表明，该方案能够实现有条件的隐私保护，实现车载网络的安全目标。该方案基于椭圆曲线密码体制，不采用复杂的双线性对运算。对该方案的性能评估表明，该方案适用于涉及车辆网络的应用。



### **IEEE Transactions on Knowledge and Data Engineering**

#### [TKDE 2019]NewMCOS: Towards a Practical Multi-Cloud Oblivious Storage Scheme【5】

**摘要：**

加密本身不足以保护数据隐私，因为访问模式会泄露一些敏感信息。健忘RAM (ORAM)是这个问题的解决方案，但对于存储和通信/计算开销巨大的实际部署来说，它仍然任重道远。为了减少它们，提出了一种很有见地的想法，即利用非云来将客户端计算和客户端云通信转移到云上。提出的多云ORAM实现了O(1)客户端云带宽成本，并消除了大部分客户端计算。在本文中，我们利用“断开连接的ORAMoperation”和设计“两层加密”来进一步减少这些开销。实验表明，与其他方案相比，我们提出的新mcos方案显著降低了从GB/MB到KB级别的驱逐缓存大小，响应时间降低了约2-3倍，云带宽节省了20%。从理论上讲，我们将逐出缓存的大小从O(VN)减少到O(ZK)，其中N是真实数据块的数量，K是云的数量(2 <;K <;<;VN)， Z是客户端上传的用于驱逐的实际块数。通过采用“延迟逐出操作”，写入频率降低了O(Z)，洗牌带宽开销降低了Q(Z log Z)，同时证明了NewMCOS的安全性。

 

## **CCF B类**



### **International Conference on Distributed Computing Systems**

#### [ICDCS 2021]Harmony: A Scheduling Framework Optimized for Multiple Distributed Machine Learning Jobs【7】

**摘要：**

我们引入了一个新的调度框架Harmony，它可以同时执行多个参数服务器ML训练任务，以提高集群资源利用率。Harmony协调具有互补资源使用的协同作业的细粒度执行，以避免争用，并在作业之间有效地共享资源。为了解决由于同时进行的作业数量增加而造成的内存压力，Harmony使用了一种数据溢出/重新加载机制，这种机制通过迭代执行模式为多个作业进行了优化。我们的评估显示,和谐集群资源利用率提高了1.65倍,导致平均工作时间的减少约53%,考,总时间处理所有工作,约38%,比传统方法,专用的资源分配给每个工作。

 

#### [ICDCS 2021]A Truthful Procurement Auction for Incentivizing Heterogeneous Clients in Federated Learning【6】

**摘要：**

联邦学习(FL)是一种新的分布式机器学习(ML)方法，它使数千个移动设备使用本地数据协同训练人工智能(Al)模型，而不损害用户隐私。尽管FL代表了一种很有前途的计算范式，但如果没有适当的经济机制来激励异质客户的参与，这样的培训过程是无法完全实现的。本工作以社会成本最小化为目标，通过采购拍卖的方式研究了供应链激励机制的设计。与现有文献不同，我们考虑了一个实际的FL场景，在不同的全局迭代中选择和安排客户端，以保证FL工作的完成，并捕捉到FL的显著特征，即全局迭代次数由所有参与者的局部精度决定，以平衡计算和通信。我们的拍卖框架AFL首先将社会成本最小化问题分解为一系列基于全局迭代次数的获胜者决定问题(wdp)。然后，为了求解每个WDP, AFL调用一个贪婪算法来确定赢家，并调用一个支付算法来计算赢家的报酬。最后，AFL返回所有wdp中最好的解决方案。理论分析证明，AFL是真实的，个人理性的，计算效率高的，并达到一个接近最优的社会成本。我们进一步开展了基于真实世界数据的大规模模拟研究。仿真结果表明，与最先进的算法相比，AFL可以降低高达75%的社会成本。



#### [ICDCS 2021]GeoCol: A Geo-distributed Cloud Storage System with Low Cost and Latency using Reinforcement Learning【5】

**摘要：**

越来越多的web应用部署在云存储服务上，云存储服务将web应用的数据对象存储在属于云服务提供商(csp)的地理分布式数据中心中。为了给web应用用户提供低的请求延迟，在之前的工作中，web应用开发者需要在大量的数据中心中存储更多的数据对象副本，或者向多个数据中心(例如，最近的数据中心)发送冗余请求，这两种方式都增加了货币成本。在本文中，我们对一个GENI服务器(作为客户端)到AWS S3数据中心的请求延迟进行了一个月的测量，我们的观察为我们提出的名为GeoCol的系统奠定了基础，这是一个使用强化学习(RL)的低成本和延迟的地理分布式云存储系统。为了实现资金成本和请求延迟之间的最佳权衡，GeoCol包含了请求分割方法和存储规划方法。请求分割方法使用SARIMA机器学习(ML)技术来预测作为RL模型输入的请求延迟，以确定子请求的数量和请求的每个子请求的数据中心，以便实现数据对象的并行传输。在存储规划方法中，每个数据中心使用RL来决定是否存储每个数据对象以及存储的数据对象的存储类型。我们在AWS S3和GENI平台上进行的跟踪驱动实验表明，GeoCol在货币成本降低32%和数据对象请求延迟降低51%方面优于其他比较方法。

 



#### [ICDCS 2021]Defuse: A Dependency-Guided Function Scheduler to Mitigate Cold Starts on FaaS Platforms【5】

**摘要：**

功能即服务(FaaS)正在成为开发云应用程序的流行范例。使用FaaS，客户端可以将应用程序开发为无服务器功能，而将资源管理的负担留给云提供商。然而，FaaS平台受到无服务器功能冷启动导致的性能下降的影响。当无服务器的函数在加载到内存之前被调用时，就会发生冷启动。这个问题是不可避免的，因为数据中心的内存通常太有限，无法同时容纳所有无服务器的功能。冷函数调用的延迟将极大地降低FaaS平台的性能。目前，FaaS平台采用多种调度方法来减少冷启动的发生。但是，他们没有考虑到无服务器函数之间普遍存在的依赖关系。观察到使用依赖项来缓解冷启动的可能性，我们提出了一种在FaaS平台上使用依赖项引导的函数调度器。具体地说，它识别了无服务器函数之间的两种依赖类型，即强依赖和弱依赖。它使用频繁模式挖掘和正向点互信息分别从函数调用历史中挖掘这些依赖关系。通过这种方式，构造了一个函数依赖图。可以对图上连接的组件(即依赖函数)进行调度，以减少冷启动的发生。我们将其应用于一个工业无服务器数据集，以评估其有效性。实验结果表明，与最先进的方法相比，该方法可以减少22%的内存使用，同时降低35%的功能冷启动率。

   

#### [ICDCS 2021]A Multi-Tenant Framework for Cloud Container Services【5】

**摘要：**

容器技术在云原生时代发展迅速。Kubernetes，作为一个生产级的容器编排平台，已经被证明在管理本地数据中心的容器化应用程序方面是成功的。然而，Kubernetes在设计上缺乏足够的多租户支持，这意味着在云环境中，需要专用集群来服务多个用户，即租户。这种限制极大地削弱了云计算的好处，并使得使用Kubernetes构建多租户软件服务(SaaS)产品变得困难。在本文中，我们提出了一个新的多租户框架VirtualCluster，它为Kubernetes扩展了足够的多租户支持。基本上，Virtual Cluster提供控制平面和数据平面隔离，同时在租户之间共享底层计算资源。新的框架通过避免修改Kubernetes核心组件来保持API的兼容性。因此，它可以很容易地与现有的Kubernetes用例集成。我们的实验结果表明，在延迟和吞吐量方面，VirtualCluster引入的开销是适度的。

 

#### [ICDCS 2021]Statistical Tail-Latency Bounded QoS Provisioning for Parallel and Distributed Data Centers【5】

**摘要：**

在数据中心架构中，大规模的交互式服务将客户端请求分发到大量的物理机器上，以提高服务质量(QoS)性能。在并行和分布式数据中心体系结构中，即使是任何服务组件的延迟的一个临时尖峰也会显著影响端到端延迟。除了平均延迟外，服务的尾延迟(即最坏情况下的延迟)也引起了大量的研究关注。尾延迟是数据中心中的一个关键性能指标，长尾延迟指的是与平均延迟时间相比，延迟的较高百分比(如98、99)。虽然统计延迟限制QoS提供理论已经被证明是一种强大的技术和有用的性能指标，用于支持移动计算网络上对时间敏感的多媒体传输，如何有效地扩展和实现这种技术/性能指标，以在统计上限制数据中心网络的尾延迟，目前还没有得到很好的理解和深入的研究。本文对三层并行分布式数据中心体系结构的尾时延分布进行了建模和描述，该体系结构中，客户端请求不同类型的服务，10个客户端通过先到先服务的M/M/1排队系统从数据中心下载其请求的数据包。我们首先定义了有统计尾延迟限制的QoS，并利用广义极值理论和广义Pareto分布理论研究了尾延迟问题。然后，我们提出了一种方案来识别语义上下文中主要的延迟变化来源，以便我们能够优化这些来源的指令以减少延迟尾。最后，利用数值分析，我们验证和评估了我们开发的建模技术和方案，以描述支持数据中心网络的尾时延QoS供应理论。

 

#### [ICDCS 2021]Infinite Balanced Allocation via Finite Capacities【4】

**摘要：**

我们分析以下无限负载平衡过程,建模为一个经典balls-into-bins游戏:有n个垃圾箱(服务器),能力有限(缓冲区)的大小c = c (n) E n .给定一个固定的到达率= (n) E(0, 1),在每一轮(请求)生成一个新球。再加上前几轮可能的剩菜，这些球会竞争着被分配到垃圾箱里。为此，每个球都独立地、均匀地随机地对一个容器进行采样，并试图将自己分配到该容器中。每个球箱可以接收尽可能多的球，直到它的缓冲区满，更喜欢年龄较高的球。在回合结束时，每个bin删除它首先分配的球。我们研究缓冲区大小c如何影响这个进程的性能。为此，我们分析了每轮比赛的球数(包括前几轮的剩余)以及单个球的最坏情况等待时间。我们证明了(i)竞争球的数量在任意(甚至指数大)时间范围内以4 - c-l- In(1/(1 - A))为高概率为界。n + O (c。(N)， (ii)给定球的等待时间最大概率为(4。(1 / (1 - 1))) / (c。(1 - 1/e)) + logn + O(c)这些结果表明选择c的最佳点在c = 9(Vlog(1/(1 - a)))左右。与具有无限容量的相关过程相比[Berenbrink等人，PODC'16]，当a为常数时，等待时间从O(log n)减少到O(log log n)。即使对于较大的A=1 - 1/n，我们也将等待时间从O(log n)减少到O(Vlogn)



#### [ICDCS 2021]SHARE: Shaping Data Distribution at Edge for Communication-Efficient Hierarchical Federated Learning【4】

**摘要：**

联合学习(FL)可以在不共享隐私敏感的原始数据的情况下，在移动节点上实现分布式模型训练。然而，为了实现高效的FL，一个重要的挑战是，由于频繁的云模型聚合通常需要达到目标精度，特别是当移动节点上的数据分布不平衡时，提交模型更新的通信开销是禁止的。通过试点实验，验证了如果在边缘进行模型聚合，可以避免云模型频繁聚合而不降低性能。为此，我们研究了分层联合学习(HFL)框架，该框架选择分布式节点的子集作为边缘聚合器进行边缘聚合。特别地，在HFL框架下，我们提出了一个通信成本最小化(CCM)问题，通过对边缘聚合器选择和分布式节点关联的决策来最小化边缘/云聚合带来的通信成本。HFL的潜力在于边缘聚合器的数据分布，受此启发，我们提出了SHARE，即整形边缘数据分布，以转换和解决CCM问题。在SHARE中，我们将原问题分解为两个子问题，以最小化每轮通信成本和边缘聚合器数据的平均Kullback-Leibler散度，并分别设计了两种轻量级算法来求解。在不同的环境下进行了广泛的实验来证实SHARE的有效性。

 

#### [ICDCS 2021]Incentive-Driven Long-term Optimization for Edge Learning by Hierarchical Reinforcement Mechanism【3】

**摘要：**

边缘学习是移动边缘网络中新兴的分布式机器学习。有限的研究设计了激励边缘节点参与边缘学习的机制。但其机制只考虑了资源消耗的短视优化，缺乏学习算法性能保障和长期可持续性。本文提出了一种基于层次深度强化学习的激励驱动的边缘学习长效机制——Chiron。首先，我们的优化目标将学习算法度量(即模型精度)与系统度量(即学习时间和资源消耗)相结合，可以在固定的训练预算下提高边缘学习质量。其次，我们提出了一个两层H-DRL设计，包含外部和内部代理，分别实现了边缘学习的长期和短期优化。最后，在三个不同的真实数据集上进行了实验，以证明我们所提出的方法的优越性。特别是，与现有方法相比，在相同的预算约束下，最终的全局模型精度和时间效率分别提高了6.5%和39%。我们的实现可以在https://github.com/Joey61Liuyi/Chiron上找到。



------

### **Software: Practice and Experience**

#### [SPE 2022]Towards cloud-based unobtrusive monitoring in remote multi-vendor environments【4】

**摘要：**

如今，许多复杂的多供应商生产环境，如智能城市中的电信基础设施或火车上的乘客信息系统，都是基于微服务并部署在云中。从服务集成商的角度来看，为这些环境构建新的解决方案(这些环境可以承载大量外部设计和开发的微服务)通常是复杂且容易出错的。这部分是由于此类系统的无文档化行为或无文档化架构规范造成的。高级服务监控可以提供一种解决方案，在现场集成期间快速检测异常或意外的服务交互行为。但是，监视服务不应该对生产环境本身产生影响。因此，本文提出了一种基于代理的不显眼的监视平台，能够通过使用sidecar容器监视内部开发的和外部开发的服务。它监控微服务水平上的状态、指标和网络流量，该研究是DynAMo研究项目的一部分，该项目是与多个行业合作伙伴合作进行的。原型评估证明，我们的解决方案对现有微服务环境的影响可以忽略不计(平均CPU使用量低于0.02%)，就像Prometheus等其他监控系统一样，同时提供了专注于多供应商服务集成的额外功能。这使得它适用于复杂的生产领域，进一步帮助现场集成，并快速发现潜在的新异常。

#### [SPE 2020]A multicriteria optimization model for cloud service provider selection in multicloud environments【7】

多云计算是一种策略，可以帮助客户减少对任何单一云提供商的依赖(称为供应商锁定问题)。这种战略的价值随着适当选择合格的服务提供者而增加。本文提出了一种有约束的多准则多云提供商选择数学模型。采用模拟退火算法(SA)、遗传算法(GA)和粒子群优化算法(PSO)三种元启发式算法对模型进行求解，并通过一个假设案例对其性能进行了研究和比较。为了比较，采用田口的稳健设计方法来选择算法的参数值，采用层次分析法(AHP)生成初始可行解，这是文献中解决云提供商选择问题最常用的方法，三种算法都采用了该解，并且，为了避免层次分析法的局限性，三种算法随机生成另一个初始解，并在第二组性能实验中使用。结果表明，SA、GA、PSO分别将AHP解提高了53.75%、60.41%和60.02%，SA和PSO在初始解不变的情况下仍能得到相同的最优解，具有较强的鲁棒性。

#### [ASTS 2022]Efficient multi-attribute precedence-based task scheduling for edge computing in geo-distributed cloud environment【8】

**摘要：**

为了实现云计算的全球化，不同云提供商的不同服务联合使用已成为必然趋势。地理分布式云由几个不同的云组成，为云计算提供了一个通用的环境。在数据放置方面，最近提出的许多数据放置算法都单方面地使用单一的性能指标来评价算法的性能。在任务调度中，当分配任务的云资源过多时，会造成资源的浪费。当分配给复杂任务的云资源较少时，导致系统整体进度停滞，系统整体进度停滞。针对上述问题，提出了数据布置方法和任务调度方法。在提出的数据放置方案中，考虑了多个性能指标。在任务调度过程中，考虑了稀疏节点的检测和云资源的合理分配。为了证明所提方法的优越性，进行了大量的实验。的数据位置,当文件数量设置为8 oo,提出数据布局算法的安全水平为7.0,高于27.3%的国内流离失所者算法,GA-DPSO算法的高出45.8%和16.7%高于H2DP算法。在任务调度方面，本文提出的任务调度方法对时间开销的改进百分比最低，说明本文提出的任务调度算法的时间开销最接近最优时间，也是最短的。



------

### **The Computer Journal**

#### [CJ 2021]A proposed framework for cloud-aware multimodal multimedia big data analysis toward optimal resource allocation【6】

**摘要：**

本文的主要目标是演示云平台(MMSCP)中多模式多媒体服务的结构设计。因此，我们提出的MMSCP体系结构分为服务平台、执行平台和结构平台三个层次。服务平台的功能是将媒体创作者生成的不同形式的视频文件收集起来，存储在本地平台上。第二个执行平台集成了Hadoop和Mapreduce功能。最后，基于QoS的云计算功能(即负载均衡、安全、资源分配和网络流量管理)被用于第三个结构平台。很可能，我们在结构平台中引入了乌鸦搜索算法(CSA)来优化资源配置。我们采用一个Hadoop集群来执行这个实验。此外，为了进行资源分配实验，我们使用了一些传统的优化算法，如ABC、GA和PSO，并与我们提出的CSA算法在结构平台上进行了比较。然而，为了评估算法的性能，我们配置了CloudAnalyst工具。仿真结果表明，该算法能够以最小的响应时间对虚拟机进行最优分配。



#### [2021]Location-Aware and Budget-Constrained Service Brokering in Multi-Cloud via Deep Reinforcement Learning【7】

**摘要：**

多云使得有效利用位于不同位置的多个云提供商提供的各种云服务成为可能。为了处理对延迟敏感的应用程序的请求，云代理必须在多云环境中选择合适的云服务，以最小化网络延迟，同时避免出现超支的风险。在多云环境中，位置感知和预算约束的服务代理问题需要一种机器学习方法来处理高度动态的请求。在本文中，我们应用深度强化学习来解决这个问题。提出的算法名为DeepBroker，可以动态地、自适应地在多云中为新到达的请求在全球范围内选择虚拟机。具体来说，DeepBroker通过使用深度q网络结合新设计的状态提取器和动作执行器来训练代理策略。为了确保财务可行性，我们引入了基于罚款的奖励功能，以防止超支的情况。基于真实数据集的评估表明，在网络延迟最小化和预算满意度方面，DeepBroker可以显著优于几种常用的基于启发式算法。



------

### **ACM Symposium on Cloud Computing**

#### [SoCC 2021]Mind the Gap: Broken Promises of CPU Reservations in Containerized Multi-tenant Clouds【6】

**摘要：**

容器化正变得越来越流行，但不幸的是，容器常常不能通过分配的资源提供预期的性能。在本文中，我们首先演示了在容器共存的多租户环境中，性能差异和降低是显著的(高达5倍)。然后我们研究这种性能下降的根本原因。通常认为这种降级是由资源争用和干扰引起的，与此相反，我们发现一个容器的CPU储量与实际获得的CPU数量之间存在差距。其根本原因在于当今Linux调度机制的设计选择，我们称之为强制运行队列共享CPU时间。事实上，在保留CPU资源的需求和complete Fair Scheduler的工作节约特性之间存在着根本的冲突，这种矛盾阻碍了容器充分利用其请求的CPU资源。作为概念证明，我们在广泛使用的Kubernetes和Linux之上实现了一种新的资源配置机制，以展示其潜在的好处，并为未来的调度程序重新设计提供了启示。我们的概念证明，与现有的调度器相比，批处理和交互式容器化应用程序的性能提高了5.6倍和13.7倍。



### **IEEE International Conference on Cluster Computing**

#### [CC 2021]Truthful online double auction based dynamic resource provisioning for multi-objective trade-offs in IaaS clouds【7】

**摘要：**

拍卖设计最近被用于laaS云中的静态和动态资源供应，比如Microsoft Azure和Amazon EC2。然而，现有机制大多局限于简单的拍卖、单一目标、离线设置、云用户或云服务提供商(csp)之间的单向互动，以及云用户私人信息可能出现的误报。在云数据中心基于时间的服务器维护下，利用云用户请求时变到达的弹性特性，提出了一种更加现实的laaS云在线拍卖场景。我们提出了一种在线真实双拍卖技术来平衡laaS云中能量、收益和性能之间的多目标权衡，其中，基于加权二部匹配的中标算法用于资源分配，基于Vickrey Clarke Groves (VCG)驱动的中标支付计算。通过严格的理论分析和利用谷歌集群工作负载跟踪的广泛跟踪驱动模拟研究，我们证明了我们的机制在保证真实性、异质性、经济效率、个体合理性的同时显著提高了性能，并具有多项式时间的计算复杂性。



### **Computer Networks**

#### [CN 2021]Game-based distributed pricing and task offloading in multi-cloud and multi-edge environments【7】

**摘要：**

使cloud-edge协作物联网(很多)系统可以更好的满足移动设备的应用程序需求(MDs)。在云服务提供商(CSPs)和边缘服务提供商(esp)共存的环境下，设计一种机制来实现竞争激烈的loT市场中CSPs和esp的收益最大化，优化MDs的体验质量(QoE)是至关重要的。现有工程很少考虑到这一领域。为此，我们提出了一种针对多云、多边缘loT环境的分布式定价和任务卸载机制。我们引入一个多领导者多follower两层Stackelberg博弈模型来模拟服务提供者与服务提供者之间的交互。我们进一步设计了两种分布式算法，即迭代近端卸载算法(IPOA)和迭代Stackelberg博弈定价算法(ISPA)。前者解决了MDs之间的跟随者非合作博弈问题，后者利用逆向归纳法处理服务商之间的价格竞争问题。实验结果表明，与其他传统的任务卸载方案相比，IPOA能显著降低MDs的负效用，且无状态代价(PoA)始终小于2。此外,结果还表明,当前提高服务提供者的收入,同时保证可靠MDs的体验质量。



### **Journal of Parallel and Distributed Computing** 

#### [JPDC 2021]A novel cooperative resource provisioning strategy for Multi-Cloud load balancing【8】

**摘要：**

云计算的范式预示了计算的新途径，以低成本提供了增加数据可访问性的好处。连续编写应用程序(CWA)(例如，为医疗保健提供的增强在线服务)对数据存储、计算和带宽有特定的要求，因此在预算和时间有限的情况下对成本很敏感。为此，我们提出了一种由多云服务提供商(CSP)或“多云”为CWA提供服务的体系结构，并设计了一种新的资源调度算法以使系统成本最小化。为了满足用户在MCP上对资源的需求，利用经典的CWAs系统模型。该研究有助于了解不同资源的特点，并得出结论:对许多CWA实现来说，多云是最有吸引力的。介绍了多个csp的互连及其负载路径(即通过可能互连的数据)。在此基础上，提出了基于系统负载路径最小一阶导数长度(MFDL)的最优用户调度问题。理论分析表明，所提出的算法能够以最小的成本获得最优的多云用户调度方案。通过对不同影响因素的严格仿真，证明该策略在许多实际场景中具有可扩展性、灵活性和有效性。

#### [JPDC 2019]Managing renewable energy and carbon footprint in multi-cloud computing environments【5】

**摘要：**

云计算为服务提供商和客户提供了有吸引力的功能。用户可以从“现收现付”模式中节省开支，而服务提供商也将他们的服务部署到云数据中心以减少维护工作。然而，由于云数据中心的快速发展，数据中心所消耗的能源会导致大量的碳排放，并对环境造成影响，不同的能源来源，不同的电厂在不同地点的碳强度是不同的。因此，在本文中，为了解决数据中心的碳排放问题，我们考虑在位于不同时区的多云之间转移工作负载。我们还制定了数据中心的能源使用和碳排放，并建立了相应位置的太阳能模型。这有助于减少棕色能源的使用，并在不同的地点最大限度地利用可再生能源。我们提出了一种方法，为位于不同时区的加利福尼亚、弗吉尼亚和都柏林的多个数据中心管理碳足迹和可再生能源。结果表明，在保证用户请求的平均响应时间的同时，我们提出的应用工作负载转移的方法可以比基线减少约40%的碳排放。

### **Journal of Systems Architecture: Embedded Software Design**

#### [JSA 2021]TOPSIS inspired Budget and Deadline Aware Multi-Workflow Scheduling for Cloud computing【7】

**摘要：**

调度是一种决策机制，它通过确定活动在可用资源上的执行顺序，允许在多个活动之间共享资源。在异构分布式系统中，如何调度不同用户在不同时间提交的并发工作流是一个很大的挑战。由于云动态特性(如按需供应、弹性、丰富的资源类型和各种定价方案)，对云系统来说，有截止日期和预算限制的调度变得更加具有挑战性。为了优化系统性能和最终用户满意度，需要一个管理良好的预算和期限约束调度。因此，提高系统性能，同时优化多个调度条件是一个很大的挑战。针对这些问题，提出了一种基于多准则决策(MCDM)方法的多工作流调度算法——TOPSIS (Order Preference by Similarity To Ideal Solution)。根据任务需求，利用运行时间、成本和数据传输时间的加权和确定可用资源中的最优资源。与基于预算约束、期限约束的异构最早完工时间算法(Budget-Heterogeneous early Finish Time, BHEFT)、基于预算约束、期限约束的异构最早完工时间算法(Cloud-based Workflow Scheduling algorithm, CWSA)进行了性能比较。和资源利用率。实验结果表明，提出的T-BDMWS在达到用户指定的预算或期限约束和资源效率的标准下，优于目前最先进的启发式算法。

### **Journal of Systems and Software**

#### [JSS 2021]Tuning configuration of apache spark on public clouds by combining multi-objective optimization and performance prediction model【6】

**摘要：**

为部署在公有云中的Spark选择正确的配置以确保周期性作业的高效运行是一件困难的事情，因为需要探索的配置空间非常大，这些配置由不同维度(如应用级和云级)的大量性能相关参数组成。选择不当不仅会显著降低性能，还可能导致更大的开销。然而，自动搜索各种应用程序的最佳配置以权衡性能和成本是一个挑战。针对这一问题，将多目标优化算法与性能预测模型相结合，提出了一种新的优化配置搜索算法AB-MOEA/D。AB-MOEA/D采用基于分解的多目标优化算法来寻找以执行时间和成本最小为目标的配置，其中使用Adaboost算法构建的性能模型来评估每个候选配置的适合度。此外，我们还介绍了以AB-MOEA/D为优化引擎的组态自动调优系统。在5个数据集的6个基准上的实验结果表明，AB-MOEA/D在执行时间和成本方面显著优于之前的工作，平均提高了约35%和40%。

### **IEEE Transactions on Service Computing**

####  [TSC 2021]A QoS-Based Splitting Strategy for a Resource Embedding Across Multiple Cloud Providers【4】

**摘要：**

在云计算中，基础设施即服务模型的一个基本管理问题在于如何高效地将计算和网络资源嵌入到分布式虚拟化基础设施中。这个问题通常被称为虚拟网络嵌入(VNE)问题，已经针对单个云提供商(CP)进行了很好的研究。然而，广域服务交付可能需要在多个CPs上嵌入异构资源。这增加了更多的复杂性和可伸缩性问题，因为虚拟网络请求(VNR)嵌入过程需要两个操作阶段:多云VNR拆分，然后是内云VNR段映射。本文提出了一种VNR分割策略，以提高生成的VNR段的性能和QoS。利用整数线性规划(ILP)将分裂相位问题形式化为带约束的最大化问题。然后，为了最小化总体延迟，采用了一种形式化为混合整数线性规划(MILP)的多目标内云资源映射方法。通过仿真验证了该方法的有效性。其中，接受率和延迟分别提高了15.1和18.5%，同时防止违反QoS。

#### [TSC 2021]A Game-Based Price Bidding Algorithm for Multi-Attribute Cloud Resource Provision【7】

**摘要：**

云计算资源的定价机制对云客户和服务提供商来说都是一个至关重要的问题，特别是从多提供商竞争的角度来看。虽然提出了各种资源提供机制，但很少有研究关注多属性资源提供，以提高云客户和服务提供商的利益。为了解决这个问题,我们提出一个多属性的竞价机制提供云计算资源从非合作博弈的角度,在每个玩家的信息(客户和供应商)对他人是不完整的,每个玩家希望他/她自己的利益最大化。更具体地说，在考虑公平定价竞争的情况下，我们提出了一种基于服务质量(QoS)和投标价格的激励资源提供模型。然后，结合资源提供模型，将价格竞标问题构建为一个博弈，为每个云供应商寻找合适的价格。我们通过假设每个提供者提供的资源的数量函数是连续的，证明了所建立的博弈模型纳什均衡解集的存在性。为了找到一个纳什均衡解，我们提出了一个均衡解迭代算法，并证明了该算法收敛于一个纳什均衡。最后，提出了一种近似均衡竞价(NPB)算法来修正得到的纳什均衡解。大量的仿真实验结果以及与当前最先进的解决方案和基准方案的对比实验验证了该方法的可行性。

### **International Symposium on Mobile Ad Hoc Networking and  Computing**

#### [MobiHoc 2021]Joint Update Rate Adaptation in Multiplayer Cloud-Edge Gaming Services: Spatial Geometry and Performance Tradeoffs【4】

**摘要：**

本文分析了多人云游戏(MCG)系统的性能。为此，我们引入了一个模型和新的mcg服务质量(QoS)指标，用来捕捉玩家更新的新鲜度和游戏体验的公平性。我们引入了一种高效的基于测量的联合多人速率适应(JMRA)算法，该算法通过增加相关玩家的更新速率来克服大的(可能变化的)网络传输延迟，从而优化MCG-QoS。由此产生的MCG-QoS在网络延迟中显示为schur凹，导致与玩家的空间几何和网络拥塞相关的自然特征和性能比较。特别是，联合速率适应使服务提供商能够应对网络延迟的变化，以及玩家的地理分布，从而实现高服务覆盖率。这反过来又允许我们探索需要提供的计算资源的空间密度和容量。最后，我们利用优化理论中的工具，来展示如何做出服务布局决策，以提高MCG-QoS对随机网络延迟的鲁棒性。



### **International Conference on Web Services （Research  Track）**

#### [ICWS 2020]Location-Aware and Budget-Constrained Application Replication and Deployment in Multi-Cloud Environment【7】

**摘要：**

为了获得技术和经济利益，企业应用程序提供商越来越多地将他们的工作负载转移到云上。随着来自不同地点、价格不同的多家云提供商的云资源数量的增加，应用程序提供商面临的挑战是选择合适的云资源来复制和部署应用程序，以保持低响应时间和高质量的用户体验，同时又不会遇到超支的风险。在本文中，我们研究了全球范围内的云应用程序复制和部署问题，考虑了应用程序的平均响应时间，特别是应用程序执行时间和网络延迟，并在预算控制的情况下。为了解决这一问题，我们提出了一种基于遗传算法的方法，该方法具有领域定制的解决方案表示、适应度测量和种群初始化。使用真实世界的数据集进行的大量实验表明，我们提出的基于GA的方法显著优于常见的应用放置策略，即NearData和NearUsers，以及我们最近提出的混合GA方法。



## **CCF C类**

### **Journal of Grid computing**

#### [JGC 2022]An Incentive-Compatible Offloading Mechanism in Fog-Cloud Environments Using Second-Price Sealed-Bid Auction【8】

**摘要：**

在雾云环境中，最终用户提交的任务首先被发送到称为雾节点的中间节点。当云节点计算资源不足时，云节点会将任务卸载到远端云。当然，中间节点不愿意将任务转移到上游实体，这反过来导致了网络性能的下降。为了激发这些不情愿的节点，以前的一些研究使用了博弈论方法。我们认为拍卖理论是激励雾节点参与卸载操作的最重要的数学工具之一。在本文中，我们提出了一种第二价格密封竞价拍卖机制来优化卸载。在我们的模型中，服务单元扮演着商品的角色。此外，雾节点和云数据中心分别扮演竞标者和拍卖者的角色。我们证明了所提出的拍卖机制具有激励相容和激励合理性两个重要性质。我们在边缘层和云层中使用排队理论来表述这个问题。在每一层中，都使用拍卖机制来分配资源。我们将提出的机制与最先进的方法进行了比较。使用iFogSim模拟器的实验评估表明，在执行时间、能源消耗和网络使用等重要标准方面，所提出的方法比其他方法要好得多。

 

#### [JGC 2022]Effective Scheduler for Distributed DNN Training Based on MapReduce and GPU Cluster【7】

**摘要：**

并行训练通过并行gpu加速深度神经网络(DNN)的训练。而内存内的数据传输由于gpu分布在不同的节点上，变成了跨节点的网络传输，从而拖延了训练时间。大多数研究通过减少网络链接上的数据大小来解决这个问题。然而，忽略了网络距离的因素。本文基于MapReduce构建了分布式DNN训练体系结构。定制的调度器旨在使完成训练的计算节点更接近存储数据的节点。同时，通过调整数据传输时间，实现并行训练模型的同步。实验结果表明，缩短网络距离有利于减少网络流量的使用。由此产生的数据传输时间使训练时间减少了至少50%，保证了并行训练的同步性。



#### [JGC 2022]TORCH: a TOSCA-Based Orchestrator of Multi-Cloud Containerised Applications【6】

**摘要：**

为IT客户提供的基于云计算的服务的数量和类型的增长，得益于市场不断有新参与者进入，以及人工智能、大数据和微服务等颠覆性技术的整合。从客户的角度来看，在云服务由于存在多个竞争的服务提供商而高度多样化的市场环境中，选择最适合他们特定需求的服务是一个关键的挑战。一旦做出选择，就需要所谓的“云编配工具”(编配器)来处理客户应用程序的生命周期。虽然大公司为他们的客户提供专有的编排器，但在文献中，相当多的开源项目已经推出了能够在最具代表性的云平台上透明地管理应用程序的多云编排器。在本文中，我们提出了TORCH，这是一个基于tosca的框架，用于在多个云提供商上部署和编排云应用程序(经典的和容器的)。该框架通过使用标准规范模型帮助云客户定义应用程序需求。与其他多云协调器不同，它采用了一种策略，将供应工作流与私有云服务API的实际调用分离开来。主要的好处是可以以很低的实现成本为任何云平台添加支持。在本文中，我们提出了TORCH的一个原型实现，并展示了它与两个不同的基于容器的集群平台的交互。在一个小型试验台上进行的初步性能测试证实了TORCH的潜力。

 

#### [JGC 2022]Energy Refining Balance with Ant Colony System for Cloud Placement Machines【6】

**摘要：**

近年来，云计算已经成为互联网和本地网络等社交网络处理服务的重要领域之一。云计算的主要问题之一是将虚拟服务器放置到物理服务器上。这个问题将会对能量消耗产生显著的影响，因为如果不为它选择一个合适的位置，将会使用大量的能量来保持物理服务器的运行。本文的目标是优化物理服务器的能量使用，为了实现它，考虑了虚拟机(vm)和物理机(pm)的最后位置。本文提出了一种基于蚁群算法的虚拟机资源分配方法。这种方法解决了虚拟机放置问题，并试图对环境和能源消耗产生最小的影响。



#### [JGC 2022]A Survey on Auction based Approaches for Resource Allocation and Pricing in Emerging Edge Technologies【6】

**摘要：**

传感技术、智能设备、可穿戴设备和通信范式的进步，使物联网、智慧城市、虚拟和增强现实、普及医疗等愿景成为可能。这些应用程序对低延迟交付、高数据速率和即时响应有严格的要求。为此，各种新技术应运而生，如雾计算、移动边缘计算、云计算、微纳米中心、微型和微型云等。一整套新兴的边缘计算范式通常被称为“边缘技术”，其中计算资源和存储更接近于设备和云数据中心之间的用户/终端设备。边缘技术的目标是通过减少下行和上行时间和数据流量，以最小的延迟交付计算服务。像云服务提供商一样，边缘服务提供商也正在兴起，一个边缘计算资源的市场已经形成。因此，作为经济学的一个分支，拍卖理论正被广泛应用于新兴的边缘技术的资源配置。本研究对新兴的边缘技术中基于拍卖的资源分配和定价方法进行了全面的调查。本文首先对边缘技术和拍卖理论进行了概述，然后从经济属性的角度对现有的基于拍卖的边缘技术资源配置和定价方法进行了全面的回顾和比较。最后讨论了各种开放的研究问题，确定了未来的研究方向。



#### [JGC 2022]Greening Duplication-Based Dependent-Tasks Scheduling on Heterogeneous Large-Scale Computing Platforms【6】

**摘要：**

如果没有大规模的异构计算平台，目前计算密集型应用程序的低成本和高性能执行将是不可能的。这些平台巨大的计算能力提出了这些平台所消耗的电能的问题。在这样的平台上实现高性能的关键问题之一是任务调度。在基于启发式的编译时依赖任务调度启发式中，基于重复的列表调度启发式给出应用程序任务的最早完成时间。不幸的是，由于复制需要额外的计算成本，这些启发式消耗更多的计算能力，从而导致更多的电能消耗。能源效率和绿色计算将注意力转向对新一代能源感知任务调度算法的需求。本文提出了一种重复减少机制，该机制可应用于任何基于重复的调度算法产生的调度。该机制的目标是保持应用程序任务的完成时间不变，保持基于启发式的依赖任务调度算法的时间复杂度下界，并显著降低任务重复所消耗的能量。这种机制被称为绿色机制。Green被应用于四种最新和著名的基于重复的列表调度算法。利用c#语言对随机生成的大型图形集和三个实际应用图形集进行了计算机仿真，实验结果表明，Green算法可以显著降低每个算法的能量消耗。



#### [JGC 2022]A Survey of Service Placement in Cloud Environments【6】

**摘要：**

云计算已经被当今的计算行业广泛采用。云的可扩展性不仅能让用户受益，也越来越吸引企业。此外，提供的云服务(如SaaS、BPaaS、移动服务等)的数量也在持续增长。这就提出了一个问题，即如何有效地将它们安排和放置在云中，以提供高性能的服务。事实上，企业和供应商的利益与云服务及其相关数据的最佳配置和管理密切相关。这产生了各种各样的挑战，包括托管云区域的异构性和动态性，特定于云/服务的放置约束，等等。最近的云服务放置方法通过不同的技术和修改各种标准来优化，从而解决了这些问题。此外，研究人员还考虑了其他特性，如云环境类型、部署模型和部署模式。本文对云服务安置方案进行了全面的研究。我们还指出了当前不同云服务模型和环境所面临的挑战，并提供了未来的发展方向。



#### [JGC 2022]Offloading Coalition Formation for Scheduling Scientific Workflow Ensembles in Fog Environments【6】

**摘要：**

雾计算提供了一种分布式计算范式，可以执行交互式的分布式应用程序，比如物联网(IoT)应用程序。大规模的科学应用程序，通常以工作流集成的形式，具有分布式和交互式的性质，这需要一个分散的执行环境，比如雾计算。然而，在雾计算的异构环境中处理大规模应用需要在从物联网到云的连续统一体中协调不同的资源。本文研究了在以工作流集成形式考虑物联网应用的雾计算环境中，资源协调的卸载和任务分配问题。我们将这种机制称为“卸载-定位”(Offload-Location)，它被设计用来寻找卸载联盟结构，以及将卸载任务分配到雾/云资源的匹配算法。引入的解决方案试图最小化执行时间和服务器为执行任务所付出的代价，前提是保持集合的截止日期和预算的服务质量(QoS)要求。这些目标的最终目标是将整体的已完成工作流的数量最大化。研究了该机制在不同工作流应用和环境下的性能。

 

#### [JGC 2022]Distributed and Decentralized Orchestration of Containers on Edge Clouds【6】

**摘要：**

云计算已经成功地为部署可伸缩和高可用性的应用程序提供了大量的资源。然而，越来越需要低延迟服务和廉价带宽访问，以适应物联网和其他互联网边缘应用的扩展。社区网络和志愿计算的发展，以及当今低成本的计算和存储设备，使互联网的边缘充满了大量尚未充分利用的资源。因此，新的计算范式如边缘计算和雾计算正在出现。Caravela是一个Docker的容器协调器，它利用用户自愿提供的边缘资源来构建一个边缘云，在这个云中可以使用标准的Docker容器部署应用程序。当前的云解决方案大多与集中式集群环境部署绑定在一起。Caravela采用了一个完全分散的架构，资源发现和调度算法来处理(1)大量的志愿设备，不稳定的环境，(2)连接设备的广域网和(3)不存在的自然中央管理。

 

#### [JGC 2022]Energy and Makespan Aware Scheduling of Deadline Sensitive Tasks in the Cloud Environment.【5】

**摘要：**

云计算支持在虚拟化的云环境中执行用户提交的各种应用程序。然而，云基础设施为向用户提供服务而消耗大量电能，这对环境造成了有害影响。这些应用程序(任务)中的许多都是有截止日期限制的，比如属于医疗保健系统、科学研究、物联网(IoT)等的应用程序(任务)。因此，有效的任务调度对于防止违反截止日期，减少最大完工时间，同时降低能源消耗至关重要。为了解决这一问题，我们考虑了能量和最大完工时间最小化的双目标优化问题，并提出了两种异构云环境中独立的、对截止日期敏感的任务调度方法。我们的第一个方法是基于线性加权和技术的贪婪启发式。第二种算法基于蚁群算法，采用启发式搜索和信息正反馈相结合的方法改进求解。这两种方法都使用三层模型，在这种模型中，任务是通过考虑三个实体(任务、虚拟机和主机)的属性来调度的。此外，我们还提出了一种合适的云资源伸缩策略，以提高能源效率和任务可调度性。使用谷歌云跟踪日志进行的大量模拟，以及与一些最先进的方法的比较，验证了我们提出的调度技术在实现虚拟化云基础设施的能源消耗和任务平均完成时间之间的适当平衡方面的有效性。

 

#### [JGC 2022]A Hybrid Meta-Heuristic for Optimal Load Balancing in Cloud Computing【5】

**摘要：**

如今，一种基于互联网提供虚拟计算机资源的趋势技术被称为云计算，这些云的性能主要取决于各种因素之间的负载均衡。在云系统之间分配动态工作负载，并平均地共享资源，这样就不会出现数据库服务器负载过重或负载不足的情况，这在技术上称为负载均衡(LB)。因此，在云计算中，主动负载均衡方案可以提高可靠性、服务和资源利用率。本文将这些优势整合到Harries Hawks Optimization和Pigeon inspired Optimization Algorithm中，创建了高效的负载均衡方案，在任务响应时间的前提下，保证了资源的最优利用。本文提出的方法是在cloudsim框架中包含的JAVA Net beans IDE中实现的，cloudsim框架根据不同的任务数量进行分析，以评估性能。仿真结果表明，本文提出的基于Hawks Optimization和Pigeon Optimization算法的负载均衡方案在较短的时间内显著地实现了虚拟机负载的最优均衡。与现有方法相比，该方法的效率为97%。确定了算法的计算时间、成本、吞吐量分析、生成跨度、延迟、执行时间，并与Harries Hawks Optimization、Spider Monkey Optimization、Ant Colony Optimization、Honey Bee Optimization进行了比较。

 

#### [JGC 2021]Deployment Management and Topology Discovery of Microservice Applications in the Multicloud Environment【5】

**摘要：**

云计算使现代软件应用程序设计的发展成为可能。基于微服务体系结构的应用程序就是一个例子。同时，多云作为一种基础设施战略被企业广泛接受;然而,挑战仍然存在。现代应用程序的自治和分布式特性，以及多云基础设施的复杂性，通常使得通用应用程序部署管理不切实际。这种现象可能会进一步阻碍应用的质量和效率。因此，在多云基础设施环境中部署资源控制和拓扑发现是云计算研究的一个有趣的领域。本文提出了一个在多云环境下管理应用程序部署的框架。该框架使用基于策略的部署控制来自动选择和提供来自多云基础设施的部署资源，然后使用拓扑发现来可视化和验证实际的部署。本文介绍了提出的框架设计，并实现了一个概念证明原型。在实验场景中进行了实验。实验结果表明，该框架能够有效地控制部署资源，实现实际的跨云部署。



#### [JGC 2022]Computing Offloading Strategy Using Improved Genetic Algorithm in Mobile Edge Computing System【5】

**摘要：**

目前对于计算卸载的研究，大多只考虑多用户任务卸载决策问题，或只考虑无线资源和计算资源分配问题。它们没有综合考虑卸载决策和资源分配对计算卸载性能的影响，难以实现高效的计算卸载。为此，本文提出了一种基于改进遗传算法(IGA)的边缘计算任务卸载策略。首先，将任务执行延迟与能耗的加权和定义为总开销的优化函数;综合考虑用户卸载决策、与任务卸载相关的上行功率分配以及MEC计算资源分配对系统性能的影响。其次，采用遗传算法建立通信模型，将卸载策略与算法中的染色体相对应，对基因进行整数编码;最后，利用IGA算法对任务进行求解，实现高效卸载。其中，利用整数编码、基于知识的交叉和种群分割的变异，提高了算法的优化能力。最后，实验结果表明，IGA算法的性能最好，总开销约为全局部算法的52.7%和Fulledge算法的28.8%。

 

#### [JGC 2022]MiCADO-Edge: Towards an Application-level Orchestrator for the Cloud-to-Edge Computing Continuum【4】

**摘要：**

云计算环境中基于微服务的应用程序的自动化部署和运行时管理已经通过几个成熟的解决方案得到了较好的研究。然而，在云到边缘连续体中管理这样的应用程序和任务绝非易事，目前还没有健壮的、生产级的解决方案。本文介绍了我们首次尝试扩展一个名为MiCADO的应用程序级云编排框架，以利用边缘和雾工作节点。本文阐述了MiCADO-Edge如何在这种多层云到边缘的环境中自动部署复杂的互联微服务集。此外，它还展示了如何从这些服务收集监视信息，以及如何在体系结构的任何层运行的应用程序组件上实施复杂的、用户定义的运行时管理策略。通过两个来自视频处理和安全医疗数据分析领域的实际案例研究，演示和评估了实现的解决方案。

 

#### [JGC 2022]SLA-aware Stochastic Load Balancing in Dynamic Cloud Environment【4】

**摘要：**

在过去的十年中，随着向云分配工作负载的企业数量显著增加，服务水平协议(sla)成为维护服务质量(QoS)的关键因素。为了使服务质量保持在令人满意的水平，云通过从过载的物理机(pm)迁移虚拟机(vm)来实现负载均衡。然而，在实现有效和高效的负载平衡方面存在一些挑战。首先，云中的虚拟机使用不同的资源为各种应用程序提供服务，这导致不同的pm存在不同程度的资源过度利用。其次，由于应用程序资源需求的时变异构性质，PM的资源消耗随时间变化，使得资源分析变得困难。以前的负载平衡技术中的迁移决策大多基于确定性的资源需求估计，这将平等地对待每个资源，并导致低效的迁移，在性能下降方面导致严重的SLA违规。为了解决这个问题，我们提出了一种基于虚拟机迁移的sla感知的随机负载均衡方案，即SLA-LB。它在满足SLA的同时，提供了防止资源过载的概率保证。与以往的方法不同的是，SLA-LB根据PM的过载概率动态地为不同的资源分配不同的权值，通过随机表征有效地解决了多维资源需求。利用PlanetLab和谷歌Cluster跟踪的实验结果表明，SLA-LB比以往的负载均衡方法RIAL、Sandpiper和CloudScale的性能下降幅度平均分别为10.8%、23.53%和33%。



#### [JGC2022]An Evolutionary Computing-Based Efficient Hybrid Task Scheduling Approach for Heterogeneous Computing Environment【4】

**摘要：**

任务调度优化可以在同构和异构的计算环境中获得高性能。任务调度的主要目标是最小化应用程序图的执行时间。然而，这是一个np完备(非确定性多项式)的任务。此外，由于现代计算系统在计算和通信成本方面的异质性，任务调度是一个具有挑战性的问题。应用程序可以被认为是一个任务图，使用有向无环图(DAG)表示。由于异构系统，每个任务在不同的处理器上有不同的执行时间。在这个问题领域中，主要关注的是如何以最小的复杂度降低调度过程的长度。这项工作提出了一对混合启发式，基于列表和引导随机搜索来解决这个问题。本文提出的启发式任务调度算法，即混合启发式和基于遗传的异构计算任务调度算法(HHG)，采用了遗传算法和基于列表的方法。本文还提出了另一种启发式算法，即混合任务复制和基于遗传的异构计算任务调度算法(HTDG)。本工作通过诱导两种不同的引导染色体来提高初始GA群体的质量。在此基础上，将该方法与4种最新的基于同一任务的进化算法(NGA和EGA-TS)，以及基于列表的异构最早完成时间算法(HEFT)和预测最早完成时间算法(PEFT)进行了比较。结果表明，基于最佳结果出现次数、平均完成时间、平均进度长度比、平均加速和平均运行时间，所提出的解决方案的性能优于其他同类解决方案。HTDG的结果比四种最先进的任务调度算法好89%，HHG的结果比四种最先进的任务调度算法好56%。

 

#### [JGC2022]Opportunistic Deployment of Distributed Edge Clouds for Latency-Critical Applications【4】

**摘要：**

对延迟至关重要的应用程序的数量不断增加，这给网络运营商、云/托管公司和应用程序提供商带来了新的挑战。边缘计算是提供低延迟响应的最强候选，但目前还不清楚边缘基础设施将是什么样的。本文介绍了一种新的平台来实现基于分类分布式云架构和基于裸金属提供商的机会模型的边缘基础设施。一个部署在真实地理分布边缘基础设施中的多服务器在线游戏应用程序的结果显示了该解决方案的可行性、性能和成本效率。

  

#### [JGC2022]Ultra-Reliable and Low-Latency Computing in the Edge with Kubernetes【4】

**摘要：**

新的应用需要扩展传统的云计算基础设施，将计算资源部署在接近最终用户的地方。边缘计算和雾计算与运营商网络紧密结合可以满足这一需求。重点是集成:严格的延迟约束，确保分布式、远程计算节点的可靠性，以及系统的绝对规模，都需要一个强大的资源供应平台，为应用程序提供最好的底层基础设施。因此，我们提出了kubernetes - edgesscheduler，它为边缘应用程序提供高可靠性，同时为该目的提供不到10%的资源，同时，它保证符合终端用户期望的延迟要求。我们提出了一种新的拓扑聚类方法，该方法考虑了应用程序延迟需求，并允许在全球范围内的边缘集群上调度应用程序。我们演示了在一个潜在的用例中，一个分布式流分析应用程序中，我们的编排系统可以将作业完成时间减少到默认Kubernetes调度程序提供的基线时间的40%。

 

#### [JGC2022]A Computing Resource Allocation Optimization Strategy for Massive Internet of Health Things Devices Considering Privacy Protection in Cloud Edge Computing Environment【4】

**摘要：**

随着5G的发展和海量健康物联网设备的爆炸式增长，现有的计算资源分配策略存在时延长、安全性能差等问题。为此，本文提出了一种云边缘计算环境下考虑隐私保护的海量IoHT设备计算资源分配优化策略。首先，构建5G异构云边缘计算网络。此外，根据网络状况，将设备的计算需求分配给本地执行或边缘计算。对边缘服务器的计算延迟、通信和计算资源分配进行建模。然后，以网络计算资源分配的延迟和能耗为优化目标，对子任务的优先级进行排序，实现计算资源的优化分配。最后，考虑到iht环境下大规模隐私数据泄露的风险，设计了一种即时消息隐私数据保护模型。同一局域网下的终端设备通过Socket连接到边缘服务器，无需云服务器转发，提高了隐私数据的安全性能。在MATLAB仿真平台上进行了实验验证。结果表明，边缘计算服务器的增加会影响CPU的比例。此外，与其他策略相比，用户数量、边缘计算服务器数量、设备计算能力和任务到达率对所提策略平均延迟的影响最小，有效提高了分配策略的性能。



#### [JGC2022]Deployment of Elastic Virtual Hybrid Clusters Across Cloud Sites【2】

**摘要：**

虚拟集群是一种广泛应用的计算平台，可以部署在多个云平台上。动态增长和收缩节点数量的能力为高性能计算和高吞吐量计算工作负载的定制弹性计算铺平了道路。然而，弹性通常局限于单个云站点，从而阻碍了从多个地理分布的云站点提供计算资源的能力。为此，本文提出了一种开源组件体系结构，该体系结构能够跨多个云站点协调部署虚拟弹性集群，实现大规模计算。这些混合虚拟弹性集群使用基础设施作为代码(Infrastructure as Code, IaC)方法在分布式混合测试平台上自动部署和配置，该测试平台跨越不同的组织，包括内部云和公共云，支持具有高级VPN拓扑的跨集群节点的自动通信隧道。结果表明，基于集群的令人尴尬的并行作业计算可以从混合虚拟集群中受益，这种混合虚拟集群将来自多个云后端的计算资源聚合在一起，并将它们整合到一个专用的(尽管是虚拟的)网络中。

 

 















