---
layout: default
title: Program
---

# Program

<p>
The following is a draft program outline.
</p>

## Day 1: Monday 22nd

  * 12:00 Welcome Lunch<br>
    The symposium begins with a common lunch to initiate informal interaction and networking among participants.
  * 13:30 Opening
  * 14:00 Lightning talks<br>
    Each participant gives a short introduction of their research interests and motivation for attending. This session serves as an informal ice-breaker and helps set the stage for cross-disciplinary interaction.
  * 15:00 Coffee and Cake Break
  * 15:30 Keynote Speaker #1: Jens Malmodin:<br>
    Evaluating the energy consumption and greenhouse gas emissions associated with ICT products, networks, and services.
  * 16:30 Moderated Opening Discussion
  * 17:00 Student, Doctoral, and Young Researchers forum (ICT)<br>
  Early-career researchers will present their ongoing or exploratory work. Each presentation will receive structured feedback from senior researchers, fostering valuable input and mentoring.<br>
  	*Gudrun Gudmundsdottir*: "Modeling the Environmental Footprint of ICT Networks and Services"<br>
  	The purpose of the PhD project is to develop a scientifically valid and transparent absolute environmental sustainability assessment (AESA) model for ICT systems, aiming at laying ground for achieving absolute sustainability of ICT services. The project starts with looking at the life cycle impact and emissions of telecommunication network infrastructure (fixed and mobile), based on measured data in Sweden and Denmark through industry partnerships. By the end of year 2025 a first draft of a system model for user emissions of data transmission will be developed. State-of-the-art is embedded in the system model as well as considerations on the automation of calculations and communication/transfer of emissions between industry partners. <br>
	*Pascal Emmenegger*:"Designing Low-Carbon Networks Through Informed Hardware Choices"<br>
	I study how hardware changes affect a network’s carbon footprint. While most studies estimate the current footprint (attributional assessment), I use consequential assessments to evaluate how today’s actions influence future emissions. With Romain Jacob (ETH Zurich), I model how adding, replacing, or removing hardware alters energy use and carbon emissions over time. The results guide operators toward lower-carbon network designs. At SUITS, I aim to refine this approach by collaborating with experts in green communications and sustainable infrastructure.   

  * 17:45 Motivational Talk <br>
  Senior researchers share perspectives on pressing challenges and promising directions within sustainable IT. <br>
	*Mahyar Tourchi Moghaddam*: "Self-adaptive Architectures for Sustainable Edge Computing" <br>
		The growth of compute-intensive AI tasks highlights the need to mitigate the processing costs and improve performance and energy efficiency. This necessitates the integration of intelligent agents as architectural adaptation supervisors tasked with adaptive scaling of the infrastructure and efficient offloading of computation within the continuum. I present a self-adaptation approach for an efficient computing system of a mixed human-robot environment. The computation task is associated with a Neural Network algorithm that leverages sensory data to predict human mobility behaviors, to enhance mobile robots' proactive path planning, and ensure human safety. To streamline neural network processing, we built a distributed edge offloading system with heterogeneous processing units, orchestrated by Kubernetes. By monitoring response times and power consumption, the MAPE-K-based adaptation supervisor makes informed decisions on scaling and offloading.
	<br>
  * 18:10 The Experiment of the week<br>
    *Maja H. Kirkeby* In this talk I will introduce the running experiment of the week, where we evaluate the energy model for end-user devices which is used in the British and the Danish Energy Reporting Models DIMPACT and digst.
  * 18:30 Dinner
  * 20:00 Social event

## Day 2: Tuesday 23rd

  * 09:00 Keynote Speaker #2: Fernando Castor<br>
    Green software development and energy-efficient system design.
  * 10:00 Coffee Break
  * 10:30 Student, Doctoral, and Young Researchers Forum (Green Software) <br>
    *Lise Grønland*: "Energy code smells2<br>	As software systems grow in complexity and scale, energy consumption increases, and the importance of code smells grows. I will research which code smells lead to increased energy consumption. These code smells are referred to as energy code smells and contribute to energy debt. I will be addressing this problem by conducting experiments on code smells and measuring the energy consumption.  I will use both hardware- and software-based measurement tools, applied on open-source repositories using Python or Java. My aim is to compare repositories and commits, with and without energy smells.  The goal is to create a static tool that identifies and suggests energy efficient alternatives to developers.<br>
*Simão Cunha*:"Sustainability of Local LLMs: Energy Measurement, Analysis and Optimization" <br>	I'm a PhD student at the University of Minho, Portugal, working on a thesis on sustainability of local large language models. My research interests include LLMs, machine learning, and green software. My recent work includes a paper published at SLE'24 on applying CPU power caps to reduce energy consumption across programming languages while preserving performance. As a teaching assistant, I teach software development courses integrating Green Software principles and promoting sustainable coding. At SUITS, I aim to engage with fellow researchers, exchange ideas, collaborate on advancing sustainable, energy-efficient IT systems with real-world impact, and improve my skills to strengthen my PhD research.<br>
*Brage Isak Bakkane Keiserås*:"Leveraging Energy-aware Programming"<br> My research focuses on energy-efficient computing, with a particular interest in algorithms.  I am currently investigating whether GCC has become more energy-efficient throughout its evolution. This is to see if the principle of ""Compiler Optimizations Should Pay for Themselves"" holds in terms of energy, and to provide the groundwork for determining which types of compiler optimizations produce the most energy-efficient programs. Following that, I am aiming to do a similar analysis of which types of algorithms are the most energy-efficient. Overall, the goal of my research is to determine what the most energy-efficient programs are, and to create a simple yet impactful abstract model for the energy-consumption of algorithms.<br>
*Esther Hahyeon Kim*:"From Legacy to Green Software: Energy Consumption and LLM-Enhanced Analysis"<br> This study examines the energy consumption characteristics of legacy and modernized IT systems through a real-world case provided by an industrial partner, thereby contributing to research on green software. The case study evaluates an ASP.NET Web Forms–based legacy application and a system migrated to ASP.NET Core API with Angular under identical workload conditions. Furthermore, beyond mere measurement, the study explores the potential of Large Language Models (LLMs) to automate energy data analysis and to support decision-making in modernization strategies, thereby demonstrating how intelligent tools can advance sustainable software engineering.<br>
  * 12:00 Lunch
  * 13:30 Excursion & Dinner<br>
    An excursion with dinner at an external venue will facilitate informal networking in a relaxed setting.

## Day 3: Wednesday 24th
 
  * 09:00 Keynote Speaker #3: Michael Welzl<br>
    Energy-efficient networking and data transmission.
  * 10:00 Coffee Break
  * 10:30 Student, Doctoral, and Young Researchers Forum (Systems & Measurement)<br>
 *Nilma Abbas*:"Accuracy and Precision in Raspberry Pi 5’s Software-Reported Power Dissipation"<br>	This study presents initial work on evaluating the precision and accuracy of power dissipation reported by the Raspberry Pi 5. These values, originating from the on-board power management IC, capture selected internal rails but exclude 5 V input loads (e.g., USB peripherals). Reliable software-based measurement is critical for reproducible energy studies in sustainable computing, particularly for web systems requiring cross-platform comparability. In this initial study we focus on controlled CPU workloads, where device-reported values are compared against external reference measurements. The results provide an important step toward validating the Raspberry Pi 5 as a platform for software-based power measurement and assessing its suitability for sustainability research and education.<br>
 *Timmie Lagermann*:"Energy Analysis of UI Automation Testing Frameworks"<br>	We evaluate per-action energy use across four web UI automation frameworks (Selenium, Puppeteer, Playwright, Nightwatch). Because frameworks implement actions differently, their overhead can bias energy measurements; measuring at the action level under controlled conditions provides a fair basis for comparison. In a client–server environment with external power metering, we study eight common actions—refresh; left/right/double click; checkbox; drag-and-drop; text input; scroll. Results show that per-action energy differs across frameworks and actions; we quantify these effects and analyze their implications for cross-framework comparability.<br>
 *Judith Herrmann*:""<br>	RAPL filtering (RAPL: Running Average Power Limit), as a counter measure to the PLATYPUS attacks, introduces noise into the believed-to-be-precise measured values on Intel platforms. In this work, we want to understand, how this artificially introduced noise impacts energy measurements. We have found, that for short code paths or snippets up to one second, the consumed energy between a filtered and unfiltered measurement can differ up to 20%. For visualizing this, we built a tool showing the gap allowing everyone to see the adverse effects on their own machine. Additionally we looked into the introduced noise to quantify and understand it better. With the help of statistical signal processing we were able to categorize the noise as Brownian noise.<br>
 *Samuel Xavier de Souzas*:"Holistic Software Operation for Sustainable Computing"<br>	The growing complexity of multicore and heterogeneous hardware has created an exponentially large software configuration space. Portable code often results in non-specialized software that requires runtime optimization for energy efficiency. Our research addresses this with a holistic approach to energy-aware software operation. We use a low-overhead combination of offline/online modeling, integrated with the OS and phase-aware techniques, to dynamically optimize configurations like thread count and NUMA mapping. This enables user-centric tools that guide applications to quasi-optimal energy points, achieving results close to an oracle solution and orders of magnitude better than worst-case scenarios. Our work contributes to energy-efficient scalable computing infrastructures.<br>
 
  * 12:00 Lunch
  * 13:30 Student, Doctoral, and Young Researchers Forum (AI/LLM)<br>  
  *Dragoș Ionescus*:"EnergyBench: A Holistic and Systematic Benchmark for Measuring the Correctness and Energy-Efficiency of LLM-Generated Code"<br>	The increasing use of Large Language Models (LLMs) for automated software development creates a paradox: while LLM-generated code can boost energy-efficiency across industries through digital transformation, their often unsupervised usage in software development has the unintended effect of generating energy-inefficient code when trading for functional correctness. This work introduces a benchmarking framework to systematically assess when and how LLMs generate energy-efficient code. Results reveal that prompt engineering can enhance code efficiency by up to 91.9% for some LLMs, but often reduces code accuracy. To address complex trade-offs and gaps, we advocate community-driven, crowdsourced benchmarking via an online platform to enable more comprehensive, empirical testing.<br>
  *Ehsan Yousefzadeh-Asl-Miandoabs*:"CARMA: Collocation-Aware Resource Manager with GPU Memory Estimator"<br>	Deep learning (DL) training tasks often underutilize GPUs due to lack of fine-grained sharing and collocation-unaware scheduling, causing out-of-memory (OOM) failures and inefficiency. My research addresses this by designing CARMA, a resource management system that enables safe, interference-aware GPU collocation. It integrates GPUMemNet, a predictive model for estimating peak GPU memory usage, allowing informed mapping and crash recovery. This work enhances GPU utilization, reduces energy use and training time, and contributes toward sustainable and efficient DL infrastructure for shared GPU clusters.<br>
  * 15:00 Coffee and Cake Break
  * 15:30 Motivational talks 
  *Raghavendra Selvan*:
    "Efficiency Is Not Enough: Toward Systems Thinking in Sustainable IT/AI" <br>
    In this talk, I will point out why the pursuit of efficiency improvements is a necessary but not a sufficient condition when discussing sustainable IT/AI. I will point out rebound effects and how systems thinking can help advance sustainability.
    
  *Michael Kirkedal*: "" <br>
  <br>
  * 16:30 Technical Q/A (Tools and Hands-on) <br>
    This interactive session will provide hands-on advice and best practices for sustainable computing experiments, including power measurement techniques, experimental setup, and statistical anal
    sis.
    *Simão Cunha*<br>: 
    "Exploring Energy-Efficient Power Caps with Intel RAPL" <br>
    This session introduces practical techniques for measuring and optimizing software energy consumption using Intel RAPL. 
	We will start with a short presentation explaining how the RAPL-based tool works, followed by a live demonstration to explore the framework's features. Then, you will complete a small exercise measuring the energy consumption (and other metrics) of a Fibonacci function in a programming language of your choice. Finally, we will collaboratively build a dataset with all participants' measurements in a shared Google Sheets file.
    *Raghavendra Selvan* <br>
    "Carbontracker for Endpoint Devices: Measuring Energy and Carbon Emissions"<br>
    Measuring the energy consumption and carbon emissions of IT infrastructure is challenging, and more so, when tackling it across the lifecycle. In this demo, we will use Carbontracker to measure the environmental impact of endpoint devices, and discuss the limitations and challenges in expanding this to the entire lifecycle of IT infrastructure using AI models as a use-case.
    *Maja H. Kirkeby*<br>
    "Evaluating models of Digital Services:From Experiment Design to Statistical Analysis" <br>
    This hands-on session introduces participants to the design and execution of experiments for measuring the energy use of end-user devices, with a focus on web browsing workloads. Using external power meters, we will walk through how to set up reproducible tests, control for confounding factors (e.g., device generation, display brightness, workload type), and collect usable datasets. The session also covers essential statistical techniques for analyzing measurement variability, comparing results across devices, and evaluating existing energy models against empirical data.
  * 18:30 Dinner

## Day 4: Thursday 25th

  * 09:00 Keynote Speaker #4: Kerstin Eder<br>
    System-level energy optimization and energy-aware software design.
  * 10:00 Coffee Break
  * 10:30 Panel debate<br>
    A closing panel with keynote speakers and selected participants will discuss future challenges and potential collaborative directions.
  * 11:00 Summary lightnings<br>
    Participants will summarize key takeaways and potential collaborations.
  * 12:00-13:00 Closing Lunch



