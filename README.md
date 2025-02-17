# Computer Engineering Resources [![Awesome](https://img.shields.io/badge/view%20as-gitbook-blueviolet)](http://rajesh-s.gitbook.io/compengg) [![GitHub contributors](https://img.shields.io/github/contributors/rajesh-s/awesome-computer-engineering)](https://github.com/rajesh-s/awesome-computer-engineering/graphs/contributors/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg?style=flat-square)](http://makeapullrequest.com) [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)

A curated catalogue of Computer Engineering/Computer Architecture/Computer Systems resources

<p align="center">
  <img width="50%" height="50%" src="./graphic.jpg">
</p>

[Image Source](https://www.tudelft.nl/en/education/programmes/masters/msc-computer-embedded-systems-engineering)

 [`The special charm of Computer Engineering is there's a relatively good understanding of abstraction layers. - Jim Keller`](https://www.happyscribe.com/public/lex-fridman-podcast-artificial-intelligence-ai/jim-keller-moore-s-law-microprocessors-abstractions-and-first-principles#paragraph_258?utm_source=public_transcript&utm_medium=paragraph&utm_campaign=public_promo)
 
The six ideas in Computer Architecture - [Prof. Trevor Mudge](https://tnm.engin.umich.edu/)

```
Surprisingly, there are only six distinct concepts used to design computers, apart from technology advances, that reappear in many guises over and over again: 
Locality – spatial & temporal, e.g. caches
Prediction – no state change, e.g. branch prediction
Speculation – state change, e.g. prefetching
Indirection, e.g. virtualization
Parallelism, e.g. pipelining, OoO, vectors
Specialization, e.g. GPUs, accelerators
```

**Table of Contents**

[Direct link to the page on simulators](./area_specific/tools_and_utils.md)

- [Conferences/Workshops](#conferencesworkshops)
  - [Computer Architecture \& Systems](#computer-architecture--systems)
  - [High Performance Computing](#high-performance-computing)
  - [Machine Learning Systems](#machine-learning-systems)
  - [Halls of Fame](#halls-of-fame)
  - [Search tools for conferences](#search-tools-for-conferences)
- [Digging Deeper](#digging-deeper)
- [Communities](#communities)
  - [Industry Organizations](#industry-organizations)
- [Great courses on Computer Architecture](#great-courses-on-computer-architecture)
  - [Video channels](#video-channels)
- [Blogs](#blogs)
- [Podcasts](#podcasts)
- [Interesting Resources](#interesting-resources)
- [Other specific curated lists related to CompEngg](#other-specific-curated-lists-related-to-compengg)

## Conferences/Workshops

Area specific conferences/workshops are captured under their [specific pages](./area_specific/README.md)

### Computer Architecture & Systems

- [**ISCA**](https://iscaconf.org/) - International Symposium on Computer Architecture
- [ASPLOS](https://asplos-conference.org/) - ASPLOS is the premier forum for interdisciplinary systems research, intersecting computer architecture, hardware and emerging technologies, programming languages and compilers, operating systems, and networking.
- [**MICRO**](https://www.microarch.org/) - IEEE International Symposium on Microarchitecture
- [USENIX](https://www.usenix.org/conferences) - Systems Researchers Conf
- [TACO](https://dl.acm.org/journal/taco) - ACM Transactions on Architecture and Code Optimization focuses on hardware, software, and system research spanning the fields of computer architecture and code optimization
- [PACT](https://pact20.cc.gatech.edu/) - Conference on Parallel Architectures and Compilation Techniques
- [NAS](http://www.nas-conference.org/NAS-2020/) - Conference on Networking, Architecture, and Storage
- [HotOS](https://sigops.org/s/conferences/hotos/2021/) - Workshop on Hot Topics in Operating Systems

### High Performance Computing

- [SuperComputing](https://sc19.supercomputing.org/) -  International Conference for High Performance Computing, Networking, Storage, and Analysis.
- [**HPCA**](https://www.computer.org/conferences/cfp/HPCA2020) - International Symposium on High-Performance Computer Architecture by IEEE Computer Society
- [Hot Chips](https://www.hotchips.org/) - A Symposium on High Performance Chips
- [PASC](https://pasc-conference.org/) - The Platform for Advanced Scientific Computing (PASC) Conference is an interdisciplinary conference in HPC that brings together domain science, applied mathematics and computer science – where computer science is focused on enabling the realization of scientific computation.
- [ISC High Performance](https://www.isc-hpc.com/) - Event for HPC, Networking, Storage, AI/ML
- [HiPEAC](https://www.hipeac.net/events/#/) - Events on High-Performance and Embedded Architectures and Compilers
  - [MULTIPROG](https://sites.google.com/view/multiprog/) - Workshop on Programmability and Architectures for Heterogeneous Multicores
- [ICS](https://ics2020.bsc.es/) - ACM International Conference on Supercomputing of research results in HPC systems
- [HPCKP](https://hpckp.org/) - HPC Knowledge meeting to share expertise and strategies in High-Performance Computing, Data Analysis, and Artificial Intelligence.

### Machine Learning Systems

- [MLSYS](https://mlsys.org/) - Conference on Machine Learning and Systems
- [ASSYST](https://sites.google.com/view/assyst?pli=1) - Architecture and System Support for Transformer Models

### Halls of Fame

- [SOSP/OSDI](https://www.cs.utexas.edu/~vijay/hall.html) - Systems Research
- [ISCA](http://pages.cs.wisc.edu/~arch/www/iscabibhall.html)
- [MICRO](http://newsletter.sigmicro.org/micro-hof.txt/view) - Microarchitecture
- [Computer Architecture Aggregated Hall-of-Fame](http://moin.ece.gatech.edu/cathof.html)

State of Computer Architecture Conferences: [Source: Elba Garza](https://twitter.com/heyelbs/status/1340497478794309633)
![](https://pbs.twimg.com/media/EppnBtDXEAAaLnH?format=jpg&name=large)

### Search tools for conferences

- [ConfSearch](http://confsearch.ethz.ch/confsearch/)
- [WikiCfp](http://www.wikicfp.com/cfp/)
- [HGPU](https://hgpu.org/)
- [CORE Rankings](http://portal.core.edu.au/conf-ranks/?search=architecture&by=all&source=CORE2020&sort=arank&page=1)
- [NSF Funding](https://www.nsf.gov/awardsearch/advancedSearchResult?PIId=&PIFirstName=&PILastName=&PIOrganization=&PIState=&PIZip=&PICountry=&ProgOrganization=&ProgEleCode=&BooleanElement=All&ProgRefCode=&BooleanRef=All&Program=&ProgOfficer=&Keyword=%22NoC%22+%22on-chip%22+%22network-on-chip%22+%22networks-on-chip%22+%22interconnection+network%22&AwardNumberOperator=&AwardAmount=&AwardInstrument=&ActiveAwards=true&OriginalAwardDateOperator=&StartDateOperator=&ExpDateOperator=) - The NSF site provides a great filtering tool to list NSF funded projects, PIs in specific areas. A good tool to follow active research trends in areas of your interest. Here's an example for NoC/interconnection networks.

## Digging Deeper

Computer Architecture is diverse and there's interplay between domains that are under it. Look under each of these pages to find specific information or check the full list [here](./area_specific/README.md)

- [Tools, Utilities, Simulators, Emulators and more](./area_specific/tools_and_utils.md)

- [Systems for Machine Learning](./area_specific/mlsys.md)
- [High Performance Computing](./area_specific/hpc.md)
- [Systems](./area_specific/systems.md)
- [Performance](./area_specific/performance.md)
- [Parallel Computing](./area_specific/parallel.md)
- [Operating Systems](./area_specific/os.md)
- [Computer Programming(Compilers, DSA and more)](./area_specific/programming.md)
- [Hardware-Software Interface](./area_specific/hw_sw.md)
- [Accelerators](./area_specific/accelerators.md)
- [Hardware Design](./area_specific/hardware_design.md)
- [FPGA](./area_specific/fpga.md)
- [Processors](./area_specific/processors.md)
- [Interconnects](./area_specific/interconnects.md)
- [Electronics](./area_specific/electronics.md)

## Communities

- [ACM](https://www.acm.org/) Association for Computing Machinery
- [SIGARCH](https://www.sigarch.org/) Computer professionals working on the forefront of computer design in both industry and academia.
- [SIGHPC](http://www.sigcas.org/) - Special interest groupt for HPC
- [SIGMICRO](http://www.sigmicro.org/) - The ACM Special Interest Group on Microarchitecture
- [Semiconductor Research Coroportation](https://www.src.org/)
- [ITRS](http://www.itrs2.net/) - International Technology Roadmap for semiconductors
- [Eurolab4HPC](https://www.eurolab4hpc.eu/) - To strengthen academic research excellence and innovation in HPC in Europe
- [PRACE](https://prace-ri.eu/) - Partnership for Advanced computing in Europe
- [CASA](https://www.comparchsa.org/join/index.html) - Computer Architecture Student Association
- [Students@Systems](https://students-at-systems.org/) -  Group of students that organizes talks, podcasts, and panels within the systems community.
- [MLCommons](https://mlcommons.org/en/) - A collaborative engineering organization focused on developing the AI ecosystem through benchmarks, public datasets, and research.

### Industry Organizations

- [OpenHW Group](https://www.openhwgroup.org/) - Proven Processor IP
- [CHIPS Alliance](https://chipsalliance.org/) - Common Hardware for Interfaces, Processors and Systems harnesses the energy of open source collaboration to accelerate hardware development.
- [RISC-V](https://riscv.org/) - RISC-V is a free and open ISA enabling a new era of processor innovation through open standard collaboration.
- [MultiCore Association](https://www.multicore-association.org/index.php) -  Define and promote open specifications to enable multicore product development.
- [Storage Networking Industry Association](https://www.snia.org/) - A non-profit global organization dedicated to developing standards and education programs to advance storage and information technology.
- [OpenFabrics Alliance](https://www.openfabrics.org/#) - The Alliance’s mission is to develop and promote software that enables maximum application efficiency by delivering wire-speed messaging, ultra-low latencies and maximum bandwidth directly to applications with minimal CPU overhead.
- [Open Compute Project](https://www.opencompute.org/) - Focus on reimagining hardware, making it more efficient, flexible, and scalable.
- [Open Chiplet Initiative](https://zglue.com/oci) - zGlue Open Chiplet Initiative is a gallery of open designs, tools, and file formats that span the chiplet ecosystem from toolsets all the way to completed designs. The goal of the initiative is to lower the barrier for entry to create a collaborative environment for chiplet-based systems.

## Great courses on Computer Architecture

- Prof. Onur Mutlu's [lectures](https://www.youtube.com/channel/UCIwQ8uOeRFgOEvBLYc3kc3g/playlists) and [talks](https://people.inf.ethz.ch/omutlu/talks.htm)
- [Computer Organization](https://www.youtube.com/playlist?list=PLm7BxCUdWqZzjZ-jRe73KUfj2GsSS2FPy) and [Computer Architecture](https://www.youtube.com/playlist?list=PL8EC1756A7B1764F6) courses by Prof. Rajeev Balasubramonian 
- Computer Architecture [course](https://www.coursera.org/learn/comparch) by David Wentzlaff on Coursera
- Prof. David Black-Schaffer's [lectures](https://www.youtube.com/channel/UCzf_XjIoKSf4Ve2fH7xn-3A/videos) on Virtual Memory etc.
- [HPCA](https://www.udacity.com/course/high-performance-computer-architecture--ud007) - Prof. Milos Prvulovic covers High Performance Computer Architecture

### Video channels

- [TSMC and semiconductor engineering: 101](https://www.youtube.com/watch?v=GU87SH5e0eI)
- [Coffee before Architecture](https://www.youtube.com/channel/UCsi5-meDM5Q5NE93n_Ya7GA) - Videos covering beginner, intermediate, and advanced programming concepts, as well as things related to computer engineering and research.
- [Talks hosted by Prof. Matthew Guthaus](https://www.youtube.com/channel/UCCB5_vo6tjp9el-PyGIRwvg/featured)

## Blogs

- [Chips and Cheese](https://chipsandcheese.com/) - In-depth analysis on memory and performance data for modern hardware
- [Computer Architecture Today](https://www.sigarch.org/blog/)
- [WikiChip](https://en.wikichip.org/wiki/WikiChip)
- [SemiEngineering](http://semiengineering.com/)
- [HPCWire](https://www.hpcwire.com/)
- [The Next Platform](https://www.nextplatform.com/)
- [Inside HPC](https://insidehpc.com/)
- [FPGA CPU News](http://fpga.org/) - Exploring Parallel Computer Architecture with FPGAs
- [Real world technology](https://www.realworldtech.com/) - Everything from cloud, chips, processors and software. Some interesting articles such as [Power delivery in a CPU](https://www.realworldtech.com/power-delivery/)
- [TechInsights](https://www.techinsights.com/) - Die shots, analysis, reverse engineering and more
- [Coffee Before Architecture](https://coffeebeforearch.github.io/)

## Podcasts

- [Computer Architecture Podcast](https://comparchpodcast.podbean.com/)
- [Happy Hour with Architects](https://www.youtube.com/channel/UC2iMjxGk-DU6hhcRxCHZbrw/featured)
- [TLB hit](https://tlbh.it)
- [Signals and Threads](https://signalsandthreads.com/)

## Interesting Resources

- [The evolution of chiplets illustrated by Financial times](https://ig.ft.com/microchips/)
- [The Great ISAs - Adrian Sampson](https://www.cs.cornell.edu/courses/cs7491/2020sp/)
- [A great resource on upcoming Systems conferences and venues](http://www.cs.technion.ac.il/~dan/index_sysvenues_deadline.html)
- [Computer Architecture Zotero Research library](https://www.zotero.org/groups/2426044/coffeebeforearch/items/)
- [Computer Latency at a Human Scale](https://www.prowesscorp.com/computer-latency-at-a-human-scale/)
- [Networking conference search tool](http://confsearch.ethz.ch/confsearch/faces/pages/staticresults.jsp?query=usenix%20asplos%20ewsn%20hotnets%20hotos%20ipsn%20isca%20micro%20mobicom%20mobihoc%20mobisys%20nsdi%20osdi%20sensys%20sigcomm%20sosp%20uist&sortMode=1&graphicView=1)
- [Chips for Machine Intelligence in 2019](https://www.jameswhanlon.com/new-chips-for-machine-intelligence.html)
- [Microprocessor trend data](https://github.com/karlrupp/microprocessor-trend-data)
- [Demonstration of Hardware Effects](https://github.com/Kobzol/hardware-effects) - This repository demonstrates various hardware effects that can degrade application performance in surprising ways and that may be very hard to explain without knowledge of the low-level CPU and OS architecture.
- [Die shots of chips](https://github.com/misdake/ChipAnnotationViewer)
- [Bottom Up Computer Science](http://www.bottomupcs.com/)
- [Computing and Internet History Posters](http://tcm.computerhistory.org/marketing.html)
- [Selected Historical Computer Designs](https://people.cs.clemson.edu/~mark/hist.html)
- [Who are Computer Architects?](https://people.cs.clemson.edu/~mark/architects.html)
- [Which machines do Computer Architects admire?](https://people.cs.clemson.edu/~mark/admired_designs.html)
- [Moore's law till date](http://www.transistorcount.com/) - Counting transistors
- [AI Chip Landscape in 2020](https://github.com/basicmi/AI-Chip) - A list of ICs and IPs for AI, Machine Learning and Deep Learning.
- [Animations for concepts in Computer Architecture](https://www.scss.tcd.ie/Jeremy.Jones/VivioJS/)

## Other specific curated lists related to CompEngg

- [awesome-hardware-tools](https://github.com/aolofsson/awesome-hardware-tools) - A curated list of awesome open source hardware tools.
- [awesome-semiconductor-startups](https://github.com/aolofsson/awesome-semiconductor-startups) - A curated list of awesome semiconductor startups.
- [Deep Learning Hardware resources](https://github.com/RaviVijay/awesome-dl-hw-resources) A curated list of awesome hardware/chip design resources for deep learning
- [HGPU](https://hgpu.org/) - Resources for HPC on graphics processing units
- [Awesome-HDL](https://github.com/drom/awesome-hdl) A curated list of amazingly awesome hardware description language projects.
- [Awesome-Quantum-Computing](https://github.com/desireevl/awesome-quantum-computing) - A curated list of awesome quantum computing learning and developing resources.
- [Awesome RISCV](https://github.com/xmpf/awesome-risc-v/blob/master/README.md) - A curated list of RISCV resources
- [Awesome RISCV](https://github.com/drom/awesome-riscv) - A curated list of awesome RISC-V implementations
- [Awesome-DV](https://github.com/troyguo/awesome-dv) - Awesome ASIC design verification
- [Awesome Thesis](https://github.com/ocean1/awesome-thesis) - Resources for thesis/research writing
- [EDA-Wiki](https://github.com/daitoto/EDA-wiki)
- [Computer Architecture Resources](https://github.com/the-akira/Computer-Science-Resources/blob/master/db/computer_architecture.md)
- [Awesome IoT](https://github.com/HQarroum/awesome-iot) - A curated list of awesome Internet of Things projects and resources.
- [Awesome C](https://github.com/kozross/awesome-c) - A curated list of awesome C frameworks, libraries, resources
- [Professional Programming](https://github.com/charlax/professional-programming/blob/master/README.md#must-read-books) - A collection of full-stack resources for programmers.
- [Digital Design Resources](https://github.com/digital-design-hq/Digital-Resources)
