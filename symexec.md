---
layout: page
title: Combining Quantum Mechanical and Classical Molecular Dynamics
---

> Wright Group, Portland State University  
> June - August 2013, 2014

![theme logo](breqm_scheme.png){:.ioda}


We entrust software to protect much of our sensitive information. Therefore, software security is absolutely essential. However, modern programs are often so large and complicated that they almost always have crash bugs, or defects that make execution stop unexpectedly. Crash bugs can be exploited by malicious third parties in order to access personal data and to destroy vital systems. Furthermore, crash bugs are frustrating to the user. A method to test software for crash bugs before release would be very beneficial. We researched symbolic execution, a cutting edge technique to weed out crash bugs in large programs. In symbolic execution, programs are run in a simulated environment with inputs that represent all possible inputs. We tested qmail, a popular mail transfer agent, with Cloud9, a symbolic execution tool. Our goal was to thoroughly test qmail and either find crash bugs in the program or prove that the program was crash bug-free. More broadly, we wanted to evaluate whether or not symbolic execution is ready for use in industry. In the end, we found no bugs in qmail. Unfortunately, we only managed to test 17.65% of the program. Given all of our effort still translated to low coverage, we concluded that symbolic execution is still in its infancy and is not yet ready for use in industry.
