+++
author = "Carlo Ramponi"
title = "Mitigating Code Injection Attacks on Modern GPUs at CCS26"
date = "2026-06-24"
tags = [
    "publication",
    "conference",
]
+++

This paper grew out of a three-month internship at Huawei and was completed with additional work at the University of Trento.

It studies a security gap that has long remained underexplored in modern GPUs: despite the adoption of protections such as ASLR and stack canaries, the lack of hardware-enforced Data Execution Prevention still leaves room for code-injection attacks. The paper shows that these attacks are possible independently of CPU-side vulnerabilities, and that a software-based DEP mechanism can enforce W\oplusX-style memory protection while remaining compatible with proprietary vendor toolchains and precompiled libraries.

The implementation achieves strong security gains with minimal cost, introducing less than 0.5% runtime overhead and 0.2% memory overhead on average across the evaluated benchmarks.

I will present the paper at CCS 2026 in The Hague this November, and the preprint PDF will be available soon for download.

I am very grateful to all the co-authors for their support and collaboration, with special emphasis on Mahmoud, whose technical and academic guidance has been essential to this result.
