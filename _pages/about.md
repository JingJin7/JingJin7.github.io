---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hello! I’m Jin Jing, an IC design engineer with a background in microelectronics from Hefei University of Technology.

I’m currently working at Beijing Net-Swift, focusing on ASIC design and hign-speed NIC.

My research interests are **VLSI/ASIC/SoC Design, NIC, Neuromorphic Hardware and Efficient AI Hardware Accelerator**.

I am actively seeking graduate (Master’s/PhD) opportunities to further my research and expertise in these areas.

# 🔥 News
- *2024.09*: &nbsp;🎉📝 Finished the front-end design of this chip!
- *2023.12*: &nbsp;🎉📝 Started the debugging and optimization process for the entire Ethernet NIC (100Gbps) chip.
- *2023.04*: &nbsp;🎉📝 Began the ASIC implementation of the RDMA network protocol.
- *2023.03*: &nbsp;🎉📝 The multicast packet system has achieved a 25% improvement in search rate with minimal hardware overhead. Patent in progress.
- *2022.09*: &nbsp;🎉📝 Led the hardware implementation of a resource-efficient multicast model in large-scale network systems.
- *2022.07*: &nbsp;🎉💼 Joined .[Beijing Net-swift Technology Co.](https://www.net-swift.com/) as a Digital IC Design Engineer!
- *2022.06*: &nbsp;🎉🎓 Graduated from Hefei University of Technology with a Bachelor’s degree in Microelectronics, ranked 15th in a class of 104, supervised by [Xiaolei Wang](https://wdzxy.hfut.edu.cn/2020/1105/c11547a247642/page.htm).
- *2021.09*: &nbsp;🎉🏆 Participated in the China College IC Competition and won a national third prize for the design of a Face Detection SoC on FPGA!

# 🎖 Honors and Awards
- *2019* National Scholarship (top 0.2%). 
- *2021, 2020, 2019* Scholarship of Hefei University of Technology (top 10%).
- *2021, 2019* Merit Student of Hefei University of Technology (top 5%).

# 🎓 Education

- **Hefei University of Technology**, Hefei, China  
  *B.Eng. in Microelectronics, National Demonstration Microelectronics School*  
  *2018.09 - 2022.07*  
  - Average Grade: 87.78/100 (Ranked 15th out of 104)
  - Relevant Coursework: Microcontroller and Embedded Systems (94/100), Digital Signal Processing (91/100), Digital Logic Circuits (93/100), Electromagnetic Field and Electromagnetic Wave (94/100), Analog Electronic Technology (88/100), C/C++ Language Program Design (84/100), Probability Theory and Mathematical Statistics (90/100), Linear Algebra (85/100)


# 🧪 Research Experience

- **Resource-Efficient Multicast Hardware Implementation in Network Systems**  
  *Leader, Patent in Progress*  
  *2022.09 - Present*  
  Designed a novel multicast group hardware implementation model for large-scale NICs, improving search rate by 25% with minimal hardware overhead. Utilized configurable parameters to dynamically adjust the multicast group linked list length, balancing resource usage and search time for various scenarios. Implemented the multicast management system in Verilog, covering register configurations and command handling.

- **Hardware Design of FPGA-Based Gesture Recognition Algorithm**  
  *Undergraduate Graduation Design*  
  *2021.09 - 2022.05*  
  Developed a recognition system that processes gesture graphics input and outputs digital recognition results. Created modules for image acquisition, image processing, and gesture recognition using Verilog HDL, achieving real-time performance. Utilized Altera’s EP4CE10F17C8 FPGA and a CMOS image sensor for gesture acquisition and VGA display, achieving 80% accuracy in recognizing six distinct hand gestures. Authored a thesis detailing the design, implementation, and results.

- **Design of Face Detection System on Chip (SoC) Based on FPGA**  
  *China College IC Competition - National Third Prize*  
  *2021.01 - 2021.09*  
  Conducted research on face detection algorithms and helped develop a face detection SoC system that integrated a camera, LCD, digital display, LED, UART, and timer. Implemented the Viola-Jones algorithm for face detection, trained in PyTorch, and stored precomputed weights in FPGA RAM. The system used a Cortex-M3 core for software operations, enabling real-time face detection with Verilog HDL.

# 💼 Working Experience

- **Beijing Net-swift Technology Co.** (Top 10 NIC manufacturer in China), Hangzhou, China  
  *Digital Integrated Circuit Design Engineer*  
  *2022.07 - Present*

  - **Debugging and Optimization for Ethernet NIC (100Gbps)**  
    Conducted in-depth debugging and performance optimization for Ethernet NIC chips designed for 100Gbps data transmission. Resolved timing violations at a 2ns clock frequency through advanced synthesis techniques, leading to significant design improvements. Collaborated with firmware and driver departments for FPGA validation, ensuring robust real-world performance, with a focus on key components like PCIe interfaces, PHY, and DMA.

  - **RDMA Network Protocol RoCE Design and Optimization**  
    Specialized in the architectural design and optimization of the RDMA protocol (RoCE) for efficient packet transmission and reception. Authored and refined RTL code in Verilog, employing VCS for case verification and Verdi for waveform analysis, achieving stringent verification standards. Developed optimizations for reliable connection scenarios, resulting in performance increases ranging from 100% to 300%.

# 📖 Self-Studying

- **Deep Learning** - Ian Goodfellow, Yoshua Bengio, Aaron Courville  
  A foundational textbook covering the basics and various aspects of deep learning and neural networks.

- **Neural Networks and Deep Learning** - Michael Nielsen  
  An accessible online resource introducing neural network fundamentals and deep learning principles.

- **Deep Learning with Python** - François Chollet  
  Focuses on deep learning with Python, especially using the Keras library, with practical insights and applications.

- **SystemVerilog Verification Methodology** - Yuwen Xia
  A comprehensive book on SystemVerilog, covering foundational knowledge and applications in verification. It includes UVM and OVM methodologies, with extensive code examples and exercises, suitable for professionals and students in digital circuit design.

- **Computer Organization and Design: The Hardware/Software Interface** (5th Edition) - David A. Patterson, John L. Hennessy  
  A classic textbook on computer architecture, covering processor design, memory hierarchy, and hardware-software interaction. It includes examples of ARM and x86 architectures, with in-depth discussions on performance optimization and parallelism, making it ideal for a comprehensive understanding of computer systems.

- **[High-Speed Communication Circuits](https://ocw.mit.edu/courses/6-776-high-speed-communication-circuits-spring-2005/)** - MIT OpenCourseWare  
  Explores the design principles of high-speed communication circuits, covering topics such as transmission lines, clock and data recovery, and signal integrity. This course is essential for understanding the fundamentals of high-speed data communication and circuit design.

- **[Network and Computer Security](https://ocw.mit.edu/courses/6-857-network-and-computer-security-spring-2014/)** - MIT OpenCourseWare  
  Covers fundamental topics in network and computer security, including cryptography, system vulnerabilities, and secure protocols. This course provides a strong foundation in understanding security threats and defense mechanisms for networks and systems.


# 🌟 Extra-Curricular Activities

- **Psychological Department of Student Union**, Hefei University of Technology, Hefei, China  
  *Secretary*  
  *2018.09 - 2019.06*  
  Organized mental health education activities, including lectures and workshops, promoting mental wellness among students.

- **Department of HFUT Innovation and Entrepreneurship @ Big Data Center**, Hefei University of Technology, Hefei, China  
  *Secretary*  
  *2019.03 - 2020.07*  
  Organized student exchange events and contributed to public communications by editing content for the INOW Creators' public account.

- **Volunteer Work**, China  
  *2018.09 - Present*  
  Accumulated over 100 hours of volunteer service in various community activities and events, demonstrating a strong commitment to social responsibility.
