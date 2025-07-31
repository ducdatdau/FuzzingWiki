# FuzzingWiki

🔎 Happy Fuzzing - Happy Hacking

## 0x01 Binary Fuzzing 

### [[RAID 2020] Binary-level Directed Fuzzing for Use-After-Free Vulnerabilities](./Binary_Fuzzing/Binary-level_Directed_Fuzzing_for_Use-After-Free_Vulnerabilities.pdf)

*Abstract:* Directed fuzzing focuses on automatically testing specific parts of the code by taking advantage of additional information such as (partial) bug stack trace, patches or risky operations. Key applications include bug reproduction, patch testing and static analysis report verification. Although directed fuzzing has received a lot of attention recently, hard-to-detect vulnerabilities such as Use-After-Free (UAF) are still not well addressed, especially at the binary level. We propose UAFUZZ, the first (binary-level) directed greybox fuzzer dedicated to UAF bugs. The technique features a fuzzing engine tailored to UAF specifics, a lightweight code instrumentation and an efficient bug triage step. Experimental evaluation for bug reproduction on real cases demonstrates that UAFUZZ significantly outperforms state-of-the-art directed fuzzers in terms of fault detection rate, time to exposure and bug triaging. UAFUZZ has also been proven effective in patch testing, leading to the discovery of 30 new bugs (7 CVEs) in programs such as Perl, GPAC and GNU Patch. Finally, we provide to the community a large fuzzing benchmark dedicated to UAF, built on both real codes and real bugs. 