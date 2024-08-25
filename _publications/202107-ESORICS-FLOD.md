---
title: "FLOD: Oblivious Defender for Private Byzantine-Robust Federated Learning with Dishonest-Majority"
collection: publications
category: pubpapers
permalink: /publication/202107-ESORICS-FLOD
date: 2021-07-25
venue: 'European Symposium on Research in Computer Security(ESORICS)'
paperurl: 'https://eprint.iacr.org/2021/993'
---
**Authors:** Ye Dong, **Xiaojun Chen**, Kaiyun Li, Dakui Wang, and Shuai Zeng

**KeyWords:** *Secure Multiparty Computation*, *Federated Learning*

**Abstract:** Privacy and Byzantine-robustness are two major concerns of federated learning (FL), but mitigating both threats simultaneously is highly challenging: privacy-preserving strategies prohibit access to individual model updates to avoid leakage, while Byzantine-robust methods require access for comprehensive mathematical analysis. Besides, most Byzantine-robust methods only work in the honest-majority setting.

We present FLOD, a novel oblivious defender for private Byzantine-robust FL in dishonest-majority setting. Basically, we propose a novel Hamming distance-based aggregation method to resist $>1/2$ Byzantine attacks using a small root-dataset and server-model for bootstrapping trust. Furthermore, we employ two non-colluding servers and use additive homomorphic encryption (AHE) and secure two-party computation (2PC) primitives to construct efficient privacy-preserving building blocks for secure aggregation, in which we propose two novel in-depth variants of Beaver Multiplication triples (MT) to reduce the overhead of Bit to Arithmetic (Bit2A) conversion and vector weighted sum aggregation (VSWA) significantly. Experiments on real-world and synthetic datasets demonstrate our effectiveness and efficiency: (i) FLOD defeats known Byzantine attacks with a negligible effect on accuracy and convergence, (ii) achieves a reduction of $\approx 2\times$ for offline (resp. online) overhead of Bit2A and VSWA compared to $\mathsf {ABY}$-AHE (resp. ABY-MT) based methods (NDSS’15), (iii) and reduces total online communication and run-time by $167–1416\times$ and $3.1–7.4\times$ compared to FLGUARD (Crypto Eprint 2021/025).
