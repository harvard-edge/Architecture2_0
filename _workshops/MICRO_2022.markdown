---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
conference: MICRO 
date: 2022-10-01
prettify-conference-date: "October 1, 2022 - CANCELED"
collectionid: 'micro-2022-pages'
canceled: true
conference-url: "https://www.microarch.org/micro55/program/workshops.php"
---

<div id="toc_container" style="position: absolute" markdown="1">
<p class="toc_title">Contents</p>

- TOC
{:toc}
</div>

### About 
Running machine learning (ML) on embedded edge devices, as opposed to in the cloud, is gaining increased attention for multiple reasons such as privacy, latency, security, and accessibility. Given the need for energy efficiency when running ML on these embedded platforms, custom processor support and hardware accelerators for such systems could present the needed solutions. However, ML acceleration on microcontroller-class hardware is a new area, and there exists a need for agile hardware customization for tiny machine learning (tinyML). Building ASICs is both costly and time-consuming, though, and the opportunity exists with an FPGA platform to customize the processor to adapt it to perform the application’s computation efficiently while adding a small amount of custom hardware that exploits the bit-level flexibility of FPGAs. 

To this end, we present CFU Playground, a full-stack open-source framework that enables rapid and iterative design of tightly-coupled accelerators for tinyML systems. Our toolchain integrates open-source software, RTL generators, and FPGA tools for synthesis, place, and route. This full-stack development framework gives engineers access to explore bespoke architectures that are customized and co-optimized for tinyML. The rapid deploy-profile-optimization feedback loop lets ML hardware and software developers achieve significant returns out of a relatively small investment in customization for repetitive ML computations. CFU Playground is available as an open-source project here: https://github.com/google/CFU-Playground.

#### What is the goal of the workshop?
- Learn what are the challenges and opportunities for designing TinyML hardware.
- Design and develop model-specific accelerators quickly on FPGAs.
- Get hands-on knowledge on how to build an ML accelerator using CFU playground!

#### Who is the audience for this workshop?
New ML accelerators are being announced and released each month for a variety of applications. However, the large cost & complexity associated with designing an accelerator, integrating it into a larger System-on-Chip, and developing its software stack has made it a non-trivial task that is difficult for one to rapidly iterate upon. Attendees will be able to deploy their very own accelerated ML solutions within minutes, empowering them to explore the breadth of opportunity that exists in hardware acceleration. This in conjunction with the relevance and excitement surrounding ML today should welcome people with many different backgrounds and interests in ML, FPGAs, embedded systems, computer architecture, hardware design, and software development. 

#### Scope and Topics 
- Custom Hardware Acceleration on FPGAs
- Tiny Machine Learning (TinyML)
- Open-Source Tools/Frameworks for HW & SW Development (Full-Stack)

### Requirements
#### Pre-requisites
- Knowledge of computer organization (RISC pipeline, registers, opcodes, etc.)
- Basic experience with HDL (being able to read Verilog) & synthesis concepts for FPGAs
- Familiarity with C and Python
- Familiarity with ML “cycle” (inputs, preprocessing, training, inference, etc.) is helpful but not required

#### Hardware
- For the *workshop*, or to experiment with CFU-Playground using simulators, none is required.
- To develop on an FPGA, one of the supported FPGA boards is required (or you might be able to add support!)

#### Software
- For the workshop, we expect most people will use the colabs, in which case only a Google account is needed.
- All software (RISCV toolchain, Symbiflow, etc.) installed in via environment pre-packaged with CFU Playground. 

### Schedule

*TBA Coming Soon* 
