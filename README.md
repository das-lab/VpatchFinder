# VpatchFinder
面向项目版本差异性的漏洞识别技术研究

Vulnerability identification technology based on         project version difference 
## Research paper
We present the findings of this work in the following research paper:

黄诚, 孙明旭, 段仁语, 吴苏晟, 陈斌. 面向项目版本差异性的漏洞识别技术研究[J]. 网络与信息安全学报, 2022, 8(1): 52-62.

Cheng HUANG, Mingxu SUN, Renyu DUAN, Susheng WU, Bin CHEN. Vulnerability identification technology research based on project version difference[J]. Chinese Journal of Network and Information Security, 2022, 8(1): 52-62.

## Introduction
The open source code hosting platform has brought power and opportunities to software de-velopment, but there are also many security risks. The open source code has poor quality, the dependency libraries of projects are complex, and vulnerability collection platforms(CVE, NVD, etc.) are inadequate in collecting vulnerabilities. All these problems affected the security of open source projects, and most security patches can't be discovered and applied in time. To discover the vulnerability in the open source community fully and timely, a vulnerability identification system based on project version difference was proposed. The update contents of projects in the open source community were collected automatically, then features were defined from the code and log in patches, 40 features including comment information feature group, page statistics feature group, code statistics feature group and vulnerability type feature group were proposed to build feature set, and random forest model was built to learn classifiers for vulnerability identification. The results show that VpatchFinder achieves a precision rate of 0.844, an accuracy rate of 0.855 and a recall rate of 0.851. Besides, 68.07% of community vulnerabilities can be discovered by VpatchFinder in advance.
## Dataset
All data are divided into two parts:
* security_patch
* non_security_patch

## Reference
If you use the dataset in a scientific publication, please indicate the reference:

黄诚,孙明旭,段仁语,吴苏晟,陈斌.面向项目版本差异性的漏洞识别技术研究[J/OL].网络与信息安全学报:1-11[2022-02-09].http://kns.cnki.net/kcms/detail/10.1366.TP.20211028.0904.002.html.
