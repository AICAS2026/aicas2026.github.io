---
layout: page-fullwidth
title: "Seasonal School"
permalink: "/seasonal-school/"
header:
    image_fullwidth: "ha-long-bay.jpg"
---
<div class="panel radius" markdown="1">
**Table of Contents**
{: #toc }
*  TOC
{:toc}
</div>

## Venue
- Time: Monday, September 14, 2026 (Full day)
- Location: Vietnam National University, Hanoi (Xuan Thuy Campus)
- Address: 144 Xuan-Thuy Road, Cau Giay Ward, Hanoi, Vietnam

## Sub-Theme #1: High-Speed Interconnect and Clock Circuits for AI Computing Infrastructures
### Introduction to High-Speed SerDes Communications
**Quan Pan**<br/>
*Southern University of Science and Technology, China*

**Abstract:** Low-power wireline integrated circuits have become extremely
attractive since they are extensively adopted in high-speed
communications, such as local area networks, board-to-board, and data
center-to-data centers. Basic concepts in high-speed SerDes are
elaborated, including transceiver architecture and fundamentals,
modulation, and channel. Then, energy-efficient high-speed links with
sophisticated equalizations are studied, including analog front-ends,
high-speed drivers, and finally crosstalk cancellations among
multi-channel systems are discussed.

<img src="/images/sschool/quan_pan.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:** Quan Pan
(Senior Member, IEEE) received his B.S degree in Electrical
Engineering (EE) at University of Science and Technology of China
(USTC) in 2005, and his Ph.D. degree in Electronics and Computer
Engineering (ECE) at the Hong Kong University of Science and
Technology (HKUST) in 2014.  From 2014 to 2018, he was Senior Staff
Engineer in one Silicon Valley startup company, working on 400GbE
high-speed SerDes. He joined in the School of Microelectronics,
Southern University of Science and Technology as an assistant
professor in 2018 and now a tenured full professor. His research
interests include High-speed optical transceiver, wireless and
wireline circuit design. Dr. Pan has contributed more than 100
peer-reviewed articles. He received the 2017 Outstanding Young Author
Award of IEEE Circuits and System Society. He serves as an active
reviewer for many international journals, including JSSC, TCAS, TVLSI,
JLT, PTL, JoS, and et al.


### Clock Generation Techniques for High-Speed Wireline Transceivers
**Hao Xu**<br/> *Fudan University, China*

**Abstract:** High speed wireline transceivers are critical circuit
building blocks enabling the large-scale deployment of scale-up and
scale-out data center infrastructures. Generating high-frequency and
low-jitter clocks has become increasingly challenging towards
200G/400G data links. This presentation introduces circuit techniques
in frequency synthesis, clock distribution, and multi-phase clock
generation for high-speed interfaces. Key evolution will be explained
in detail.

<img src="/images/sschool/hao_xu.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:** Hao Xu received the B.S. degree in microelectronics
from Fudan University, Shanghai, China, in 2010, the M.S. and
Ph.D. degrees in electrical engineering from University of California,
Los Angeles, in 2012 and 2018, respectively.  Between 2017 and 2019,
he was with Broadcom Inc., Irvine, CA, USA developing ADC-based
high-speed optical transceivers. Between 2019 and 2021, he was with
Apple Inc., San Diego, CA, USA developing high performance cellular RF
transceivers. He held various part-time positions with Broadcom,
Mediatek, Tensorcom during his graduate study. Since 2021, he has been
with Fudan University as a faculty member. His research interests
include mixed-signal, RF, and analog integrated circuit design.


### Design of Power-Efficient Reference-less PAM4 CDR for Ultra-High-Speed Wireline Communication
**Zhao Zhang**<br/>
*Institute of Semiconductors, Chinese Academy of Sciences, China*

**Abstract:** Referenceless CDR is flexible and a low-cost and
low-power choice for wireline transceiver because it is free of
external reference clock along with the global clock distribution
network in multi-lane RX. Although referenceless CDR is popular for
NRZ applications with the data-rate below 32Gbps, it is still
challenging for PAM4 design, thus preventing it from being applicated
for over-100Gb/s wireline communication. In this tutorial, we will
introduce the basics of NRZ reference-less CDR first, then showing how
to migrate NRZ design into the PAM4 counterpart. Finally, three design
examples based on the presenters' recent research progress are breifly
reviewed as the classic design examples, including a 64-Gb/s design, a
6-64-Gb/s design and a 112-Gb/s design.

<img src="/images/sschool/zhao_zhang.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/> **Biography:** Zhao
Zhang is now a a Full Professor with the Institute of Semiconductors,
Chinese Academy of Sciences, Beijing. His research interests include
the design of wireline transceivers, low-jitter and low-power PLLs,
and ultra-low voltage ICs for bio/energy-harvesting applications.
<br/>
<br/>
<br/>
<br/>
<br/>

### Clock and Data Synchronization Techniques for High-Performance Interconnection
**Xiaoteng Zhao**<br/>
*Xidian University, China*

**Abstract:** This tutorial focuses on clock and data synchronization
techniques for high-performance interconnection, covering serial and
parallel interface architectures. For serial interconnections, we
review clock and data recovery (CDR) architectures including
phase-locked loop (PLL)-based CDR, phase-interpolation (PI)-based CDR,
baud-rate CDR, burst-mode CDR, and reference-less CDR, et., al. For
parallel interconnection, we emphasize deskew technologies in forward
clock (FC) architectures, critical for mitigating skew-induced timing
errors in wide-parallel, high-throughput interconnections. This
tutorial aims to provides designers with insights to optimize
synchronization for next-generation high-performance interconnections.

<img src="/images/sschool/xiaoteng_zhao.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:** Xiaoteng
Zhao, Professor at Xidian University His research focuses on
high-speed serial interfaces and chiplet interconnection integrated
circuit design. He presides over one Key Program of the Major Research
Plan and one General Program funded by the National Natural Science
Foundation of China. He has authored over 50 peer-reviewed papers
published in top-tier IEEE journals and conferences including ISSCC,
JSSC, CICC, TMTT, ESSERC, ASSCC, RFIC Symposium, and TCAS-I. One of
his representative works was shortlisted for the Top 10 Semiconductor
Research Advances in China (2022). He holds more than 30 authorized
patents and software copyrights, and has received three technical
innovation awards and best paper honors. He participated in the
formulation of two IEEE industry standards and has served on the
Technical Program Committee (TPC) of IEEE ICTA for three consecutive
sessions.


### High-Speed Ultra-Low Latency Mixed-Signal SerDes Transceiver Design Techniques for AI Computing Infrastructures
**Xiaoyan Gui**<br/> *Xi’an Jiaotong University, China*

**Abstract:** AI computing's explosive growth, driven by
trillion-parameter models, has rendered high-speed inter-connections
the critical data backbone for modern infrastructures, demanding
designs that overcome AI-specific circuit challenges: the need for
high-speed ultra-low latency SerDes transceivers to meet ns-level
requirements for real-time inference and training. This tutorial
provides a focused study on advanced high-speed ultra-low latency
mixed-signal SerDes transceiver design techniques tailored to these
demands, detailing the implementation of 60Gb/s, 112-Gb/s and up to
200-Gb/s mixed-signal SerDes interfaces (via topology and CDR
optimization), thereby equipping researchers, engineers, and graduate
students with the systematic knowledge needed to develop
high-performance inter-connection circuits for next-generation AI
systems.

<img src="/images/sschool/xiaoyan_gui.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:**
Xiaoyan Gui (Senior Member, IEEE) received his Ph.D. degree from
University of California, Irvine, US., in 2011. He was with Broadcom,
Irvine, from 2008 to 2012 where he worked on high-speed SerDes
transceiver design as a design engineer and staff scientist. In 2012
he joined the faculty in School of Information and Electronics at
Beijing Institute of Technology (BIT), China, and later in 2017 the
faculty in School of Microelectronics at Xi’an JiaoTong University
(XJTU), China, where he is currently a Full Professor. His research
covers CMOS high-speed wireline and wireless communications integrated
circuits design. He is the co-author of more than 70 peer-reviewed
journal and conference papers including ISSCC and JSSC. He was the
recipient of 2007 Henry Samueli Fellowship by the UCI School of
Engineering, 2022 National Teaching Achievement Award in Higher
Education by Ministry of Education of P. R. China. Dr. Gui serves as
TPC co-chair (2022) and TPC chair (2023) of IEEE ICTA.


### Optical Receiver Front-Ends for AI Interconnect: Scenarios, Tradeoffs, and Design Guidelines
**Dan Li**<br/> *Xi'an Jiaotong University, China*

**Abstract:** The rapid growth of large AI models is driving
increasingly distributed computing platforms, making high-bandwidth,
energy-efficient communication between compute nodes more critical
than ever. As interconnect becomes a key system bottleneck, the
limitations of electrical links in bandwidth density, reach, and power
are making optical interconnect increasingly attractive. Meanwhile,
optical links are evolving across multiple deployment forms, including
pluggable optics, LPO, co-packaged optics (CPO), and optical I/O
(OIO). These deployment forms do not impose the same receiver
requirements: module-based and LPO links, switch-side or
package-proximal CPO links, and compute-proximal OIO links can lead to
substantially different design priorities for optical receiver
front-ends. This tutorial presents a scenario-driven view of optical
receiver front-ends for AI interconnect. The focus is on the receiver
side, with emphasis on the front-end tradeoffs that most strongly
affect practical designs, including sensitivity, noise, bandwidth,
tolerance to input parasitics, dynamic range, power efficiency, and
technology choice, especially CMOS versus SiGe. By comparing
representative AI optical interconnect scenarios, the tutorial will
show how receiver requirements shift with system context and
integration level. Attendees will gain a clearer design picture of
optical receiver front-ends for AI interconnect, together with
practical design guidelines and a forward-looking view of future
research and design opportunities.

<img src="/images/sschool/dan_li.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:**
Dan Li received the B.E. and M.E. degrees from Northwestern
Polytechnical University, Xi’an, China, in 2004 and 2007,
respectively, and the Ph.D. degree from the University of Pavia,
Italy, in 2013. From 2007 to 2009, he worked at NVIDIA Shanghai R&D
Center on custom SRAM circuitry. From 2011 to 2014, he was with
STMicroelectronics, Pavia, Italy, where he worked on CMOS optical
receivers for 100GbE optical links and silicon photonics
applications. He joined Xi’an Jiaotong University in 2015 and is
currently a professor. His research interests include high-speed
optical receivers, low-noise transimpedance amplifiers, 3D sensing,
and low-power mixed-signal circuits. He has published in IEEE JSSC,
TCAS-I, TCAS-II, JLT, PTL, and ISCAS, and has delivered invited talks
and tutorials on low-noise optical receiver front-end design. He
currently serves as an Associate Editor of IEEE Transactions on
Circuits and Systems II: Express Briefs, and has also served the
community in technical and organizing roles for IEEE conferences
including ICTA, BioCAS, and ICECS.

## Sub-Theme #2: AI-Enabled IC Design Automation and Intelligent Hardware Architectures
### AI-Driven Shift-Left for Circuit and System Design
**Xinfei Guo**<br/>
*Shanghai Jiao Tong University, China*

**Abstract:** The shift-left paradigm in chip design automation seeks
to move physically aware analysis into earlier design stages to
improve design quality, reduce iteration costs, and enable predictive
digital twins. However, a major bottleneck remains: determining
exactly where early prediction is both highly accurate and practically
impactful. This tutorial introduces cutting-edge, AI-fused shift-left
methodologies spanning critical stages of the EDA flow, from pre-RTL
design to signoff, covering both digital and analog regimes. Attendees
will explore real-world case studies and state-of-the-art frameworks,
including physically aware timing models integrated into logic
synthesis, macro connectivity-aware optimization for early
routability, fast timing estimation tightly coupled with ECO processes
for accelerated closure, and large language model (LLM)-assisted
analog circuit sizing. Concluding with a deep dive into the practical
opportunities and open challenges—such as model accuracy, cross-node
generalization, and seamless EDA toolchain integration—this tutorial
equips researchers and practitioners with actionable insights into how
AI-driven prediction is actively reshaping modern circuit and system
design automation workflows.

<img src="/images/sschool/xinfei_guo.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:**
Xinfei Guo is an Associate Professor at Shanghai Jiao Tong University
(SJTU), where he directs the Intelligent Circuits, Architectures, and
Systems (iCAS) Laboratory. He holds a Ph.D. in Computer Engineering
from the University of Virginia and an M.S. from the University of
Florida. Before entering academia, he gained extensive industry
experience at NVIDIA and IBM Research in the United States. Dr. Guo’s
research spans software–hardware co-design for efficient AI systems,
AI-driven electronic design automation (EDA), and resilient computing
architectures. A prolific researcher, he has co-authored over 70
publications and three books, earning several best paper and
presentation awards. He holds several roles within the IEEE community,
currently serving as Associate Editor-in-Chief of IEEE Transactions on
VLSI Systems (TVLSI) and Associate Editor for Integration, the VLSI
Journal. He also serves as General Co-Chair of IEEE MCSoC 2026,
Publication Chair of AICAS 2026, and TPC Co-Chair of ISICAS 2025,
alongside frequent technical program contributions to DAC, ICCAD, and
ISCAS. Dr. Guo is a Senior Member of both IEEE and ACM, and has been
honored as an IEEE Circuits and Systems Society (CASS) Distinguished
Lecturer for 2026–2027.

### AI for Analog IC Design Automation: Evolution and Open Challenges
**Nuno Horta**<br/>
*University of Lisbon, Portugal*

**Abstract:** This tutorial provides an overview of the evolution of
analog integrated circuit (IC) design automation, with a particular
focus on the growing role of Artificial Intelligence (AI) in
Electronic Design Automation (EDA). The tutorial begins with a brief
overview of the IC and EDA markets, highlighting the strategic
importance of semiconductor design and the increasing need for
advanced automation tools. It then presents a historical perspective
on the main milestones in IC design and EDA, showing how design
methods and tools have evolved over time to address increasing circuit
complexity and productivity demands. Building on this context, the
tutorial discusses the evolution of analog IC design automation, from
early manual and knowledge-based approaches to optimization-driven
methods and, more recently, AI-based EDA techniques. The tutorial also
introduces current commercial solutions and industrial trends,
illustrating how AI is being incorporated into modern EDA tools to
support designers, improve productivity, and accelerate design
exploration. Finally, it concludes with a summary of the main
challenges and opportunities in AI for analog IC design automation,
including data availability, robustness, integration into industrial
flows, and the balance between automation and designer
expertise. Overall, the tutorial aims to provide participants with a
clear and accessible understanding of how analog IC design automation
has evolved, where AI-based approaches stand today, and what
challenges remain for their broader adoption in research and industry.

<img src="/images/sschool/nuno_horta.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:**
Nuno Horta (S’89–M’97–SM’11) received the Licenciado, MSc, PhD, and
Habilitation degrees in Electrical Engineering from Instituto Superior
Técnico (IST), University of Lisbon, Portugal, in 1989, 1992, 1997,
and 2014, respectively. In 1998, he joined the Department of
Electrical and Computer Engineering at IST, where he is currently a
Full Professor and has served as Department Chair since 2025. He is
also a Senior Researcher at Instituto de Telecomunicações, where he
heads the Integrated Circuits Group. He has supervised more than 100
postgraduate works, including MSc and PhD theses, and has authored or
co-authored more than 200 publications, including books, book
chapters, international journal papers, and conference papers. He has
also participated, as researcher or coordinator, in several national
and European R&D projects. He was or is General Chair of AACD 2014,
PRIME 2016, SMACD 2016, and SMACD 2023, and has served on the
organizing and technical program committees of several international
conferences, including IEEE ISCAS, IEEE LASCAS, DATE, NGCAS, and
ESSCIRC. His research interests are mainly in Electronic Design
Automation and Applied Computational Intelligence, with applications
in analog and mixed-signal IC design, analog IC design automation, and
computational finance.

### Bio-inspired neuromorphic olfaction: From algorithms to chips
**Hong Chen**<br/>
*Tsinghua University, China*

**Abstract:** Inspired by the mammalian olfactory system, electronic
noses (E-noses)—which are designed for automatic gas identification
and analysis—are widely used in fields such as food safety, public
safety, and environmental monitoring. With the development of
microelectronics technology, E-noses have been evolving toward
miniaturization, intelligence, and portability. In addition to rapidly
detecting target gases, portable E-noses are also required to identify
a wider variety of gas types. As application scenarios become more
complex, there is an increasing demand for higher sensitivity and
accuracy in portable E-noses. Furthermore, to ensure longer standby
time, portable E-noses must feature low power consumption and high
energy efficiency. to meet the requirements, researchers face three
major challenges: (1) In terms of algorithms, it is essential to
overcome catastrophic forgetting and develop a brain-inspired
algorithmic model capable of identifying all target gas types within
complex gas mixtures. (2) In terms of architecture, to enhance the
learning capability of the neuromorphic olfactory processor, a
general-purpose reconfigurable neuromorphic olfactory processor
architecture that supports on-chip learning mechanisms must be
proposed to overcome sensor drift while improving adaptability and
applicability in dynamic environments. (3) In terms of circuit design,
for complex gas analysis tasks, a conflict arises between the
computational cost of algorithms and the constraints of chip power
consumption. This tutorial will introduce the methods to address these
challenges—from biological mechanisms to SNN models and their hardware
implementation—and demonstrate the design of an asynchronous
neuromorphic olfactory processor that balances low power consumption
with high efficiency through a software–hardware co-design approach
tailored to olfactory algorithms.

<img src="/images/sschool/hong_chen.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:**
Dr. Hong Chen received the Ph.D. degree from the Department of EE from
Tsinghua University in 2005. Since 2007, she has been working with the
School of Integrated Circuits at Tsinghua University and is now a full
professor. Her research interests include bio-inspired asynchronous
neuromorphic circuits, biomedical circuits and systems, and so on. She
has published over 140 papers at ISSCC, VLSI, DAC, ISCA, A-SSCC, ICML,
ICLR, JSSC, and so on and holds 40 patents. Dr. Chen is currently the
associate editor of IEEE transactions on biomedical circuits and
systems, a TPC member of IEEE ASYNC and IEEE ISCAS, and the general
chair of IEEE ASYNC 2023. Dr. Chen had won awards including the Best
Demo Award at ISCAS 2013, the Best Paper Nominee at ASYNC2021,
ASYNC2023 and ASYNC2026, the Best Paper at ICCBD+AI 2024, the First
and Second prizes of the Beijing and National Science and Technology
Progress Award in 2020 and 2023, respectively, etc.

### Product-Ready Neuromorphic MCU at the Sensor Edge
**Amir Zjajo**<br/>
*Innatera Nanosystems B.V., The Netherlands*

**Abstract:** A quest to minimize energy per inference requires i)
co-design across the compute stack enabling the algorithms and
applications to influence the underlying hardware design, ii) large
degree hardware-software co-optimization (e.g. towards minimizing
network size for given accuracy, or maximizing number of operations
within allowed power envelope), and iii) fully modular and flexible
hardware system to unify design process.

In this tutorial, we formulate hierarchical, modular neuromorphic
framework that enables product-ready hardware-software co-design and
efficient deployment of signal processing workloads on neuromorphic
SoCs. We exploit the synergy of hardware and software to examine
omnidirectional dependencies of the entire design stack with the goal
to optimize and/or satisfy smart sensing design constraints such as
energy-efficiency, performance, cost and time-to-market frame. In
particular, we emphasize: The trade-offs between biological and
artificial circuits, focusing on continuous-time processing
efficiency: we examine electro-chemically accurate, multi-compartment,
neurosynaptic computational elements, abstract their fundamental
functions by extracting the underlying dynamics, and analyze their
complexity, accuracy, and flexibility in signal processing of a
time-varying task.

Strategies to maximize energy-efficiency, latency of neuromorphic SoCs
that incorporate spiking neural network (SNN) cores: we follow through
on several design principles, among others, distributed computation,
specialization of neural designs at different scales, wiring costs
minimization, continuous-time processing to enable high information
rates, compartmentalization and complexing/extending of synaptic
capabilities for reliable and efficient (resource-aware) signal
processing, etc.

Product-ready modular neuromorphic SoC design methodology and
trade-offs: we define a full set of requirements for a product-ready
system-on-chip at the sensor edge and emphasize communication paradigm
between software driven blocks and hard IPs, programmability and
controllability of hard IPs, and DfT requirements.

Insights into software tools that aid both design and deployment of
SNN accelerators and their ease of use: we highlight software tooling
required for the efficient network design and application deployment
on SoC architecture that incorporate SNN cores.

(Live demo): A quantitative validation of SNN accelerators’
competitive performance across various applications: In the
evaluation, we include both SNN and non-SNN approaches by utilizing
general, task-level benchmarking and hierarchical metric definitions,
which capture key performance indicators of interest, and we utilize a
common open-source benchmark tools, which facilitate actionable
benchmark implementation.


<img src="/images/sschool/amir_zjajo.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:**
Dr. Amir Zjajo is co-founder of Innatera Nanosystems B.V. and serves
as its Chief Scientist. Prior to that, he was a member of research
staff at Philips Research Laboratories and Corporate Research of NXP
Semiconductors. He was with the Delft University of Technology where
he was responsible for leading research into intelligent neuromorphic
systems. Dr. Zjajo has published 3 books, 3 book chapters, more than
100 papers in the areas of mixed-signal VLSI design, and neuromorphic
circuits and systems, and holds more than 20 US patents or patent
pending. He received the M.Sc. and DIC degrees from the Imperial
College London, U.K., and the PhD. degree from Eindhoven University of
Technology, The Netherlands. His research interests include
energy-efficient circuit and system design for neuromorphic signal
processing, and bionic electronic circuits for autonomous cognitive
systems. Dr. Zjajo won best paper award at BioDevices’15, LifeTech’19
and AICAS’23. He is a senior member of IEEE.

<!-- ### Hardware-Assisted Verification for Next-Generation AI Hardware Accelerators -->
<!-- **Ibrahim Elfadel**<br/> -->
<!-- *Khalifa University, United Arab Emirates* -->

<!-- **Abstract:** -->

<!-- <img src="/images/sschool/ibrahim_elfadel.jpg" width=150 -->
<!-- style="float:left;padding: 5px 5px 5px 5px;"/> -->
<!-- **Biography:** -->

### Reconfigurable Accelerator Design for Multi-Precision Floating-Point Computing: From Processing Elements to SME-Oriented Architectures
**Wei Mao**<br/>
*Xidian University, China*

**Abstract:**
Reconfigurable Accelerator Design for Multi-Precision
Floating-Point Computing: From Processing Elements to SME-Oriented
Architectures The convergence of High-Performance Computing (HPC) and
Artificial Intelligence (AI) demands diverse computing precisions,
exposing the limitations of traditional architectures that suffer from
physically isolated datapaths, low hardware utilization, and high
energy overhead. To address these challenges, this tutorial first
introduces a reconfigurable multi-precision computing unit (PE) and a
high-throughput vector systolic array. By proposing a 12-bit
redundancy-minimized bit-splitting method based on low-precision
combination, the design achieves 100% multiplier utilization across
FP64, FP32, and FP16 formats. To further optimize performance, we
detail novel hardware structures, including a Cascaded Enumeration
Comparison (CEC) strategy to drastically reduce critical path delay
and a dual-output Carry Select Adder (CSLA) that significantly
optimizes the power-delay product. The array-level design leverages
orthogonal output flows and efficient data reuse to minimize partial
sum accumulation latency and memory bandwidth
bottlenecks. Furthermore, the tutorial explores a unified architecture
that natively fuses floating-point and fixed-point calculations to
adapt to the fragmented precision requirements of modern AI, including
emerging formats like BF16 and TF32. Built upon a universal 4-bit
unit, this architecture supports diverse training and inference
scenarios within a single PE. We will present a highly optimized
six-stage pipeline utilizing Pipelined Enumeration Comparison (PEC) to
handle multi-input exponent comparisons. Finally, we demonstrate a
specialized multi-precision accelerator microarchitecture tailored for
the ARM Scalable Matrix Extension (SME) instruction set, detailing its
reconfigurable outer and inner product array configurations, complete
with a comprehensive UVM platform.


<img src="/images/sschool/wei_mao.jpg" width=150
style="float:left;padding: 5px 5px 5px 5px;"/>
**Biography:**
Wei Mao (Senior Member, IEEE) received the B.Eng. degree from
Southeast University (SEU) in 2011 and the Ph.D. degree from the
National University of Singapore (NUS) in 2017. From 2017 to 2019, he
was an Analog IC Designer with HiSilicon Technologies Co., Ltd. He
then served as a Research Associate Professor at the Southern
University of Science and Technology from 2019 to 2023. He is
currently an Associate Professor with Xidian University, Xi'an,
China. His research interests include emerging computing and memory
chip design for AI applications.  He has published over 80 papers in
top-tier IEEE/ACM journals and conferences, along with one
first-author monograph and two book chapters. His awards include the
2020 Wu Wenjun AI Science and Technology Award and the 2021 IEEE CAS
Society Regional Chapter of the Year Award. He serves as an Associate
Editor for the IEEE ICAS and a Guest Editor for IEEE TCAS-I. He has
also served on the organizing or technical program committees of
several renowned conferences, such as ISCAS, ISICAS, AICAS, BioCAS,
APCCAS, VLSI-SoC, and CCF DAC.
