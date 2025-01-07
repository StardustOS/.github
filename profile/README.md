
![alt text](https://github.com/StardustOS/.github/blob/main/profile/logo.png "Stardust")

# What is Stardust?

Stardust is a unikernel operating system designed to run Cloud applications in a protected, single-address space environment. It delegates the management of physical resources to an underlying hypervisor which is treated as a trusted platform. Stardust has a small code base that can be maintained easily, and relies on static linking to combine a minimal kernel with a single application, along with the libraries and associated programming language run-time required for the execution of the application. Due to static linking, an executable binary of Stardust is packaged within an immutable single-purpose virtual machine image. Stardust supports multiple cores, preemptive threads, and basic block and networking drivers, and provides a collection of standard POSIX-compatible libraries.

Stardust is being used in supporting the teaching and research activities at the University of St Andrews.

# Projects

- [Stardust](https://github.com/StardustOS/stardust) provides the unikernel implementation in C.
- [Stardust-oxide](https://github.com/StardustOS/stardust-oxide) is a re-implementation of the unikernel in Rust.
- [Duster](https://github.com/StardustOS/duster) provides a small debugger for para-virtualised Unikernels written in C that run on the Xen hypervisor.

# Talks

- Jaradat, W., Dearle A. and Lewis, J. Unikernel Support for Lambda Functions. In the [Fifth Annual UK System Research Challenges Workshop](https://uksystems.org/), United Kingdom, 2020. Accepted Talk 
- Ahmad, K., Dearle A., Lewis, J. and Jaradat, W. Debugging Unikernel Operating Systems ([Slides](https://tinyurl.com/yxq9w6tz)). In the [Fifth Annual UK System Research Challenges Workshop](https://uksystems.org/), United Kingdom, 2020. Accepted Talk
- Jaradat, W. [On Engineering Unikernels](https://blogs.cs.st-andrews.ac.uk/csblog/2018/03/13/srg-seminar-on-engineering-unikernels-by-ward-jaradat/), Systems Seminars Series, University of St Andrews, United Kingdom, 2018. Talk
- Jaradat, W., Dearle, A. and Lewis, J. [Unikernel support for the deployment of light-weight, self-contained, and latency avoiding services](https://research-repository.st-andrews.ac.uk/bitstream/handle/10023/13099/Jaradat_2018_Unikernel_support_3rdSRCW.pdf?sequence=1&isAllowed=y). In the [Third Annual UK System Research Challenges Workshop](http://uksystems.org/workshop/2018/), United Kingdom, 2018. Talk
- Jaradat, W. Towards Unikernel Support for Distributed Microservices. [Adobe Tech Summit](https://research.adobe.com/news/tech-summit-adobe-explores-whats-next/), San Francisco, United States of America, 2019. Talk
- Jaradat, W., Dearle, A. and Lewis, J. The Case for Unikernels. In the [Fourth Annual UK System Research Challenges Workshop](http://uksystems.org/workshop/2019/), United Kingdom, 2019. Lightning Talk

# Material

- Jaradat, W., Dearle, A. and Lewis, J. Unikernel support for the deployment of light-weight, self-contained, and latency avoiding services. In the Third Annual UK System Research Challenges Workshop, United Kingdom, 2018.
- McKeogh, F., [Stardust Oxide](https://github.com/StardustOS/stardust-oxide/blob/main/discussion/Dissertation.pdf), Dissertation, University of St Andrews, United Kingdom.
