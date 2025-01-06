# Registration After Completion
## Introduction
This repository contains the implementation of our RegistrationAfterCompletion:Towards Sparse and Partial Point Set Registration for Computer-Assisted Orthopedic Surgery
## Abstract
In computer-assisted orthopedic surgery (CAOS), accurate point set registration is essential for enhancing surgical precision.
However, the sparse and low-overlap nature of intraoperative point sets presents significant challenges for reliable registration.
To address these limitations, we propose a novel registration-after-completion framework, where intraoperative point set is completed after which the two full point sets are registered.
Our contributions include the follows. (1) 
For sparse and partial intraoperative point set completion, we propose a progressive two-stage strategy to progressively complete the sparse point set.  Additionally, we introduce a Local Normal-direction Consistency (LNC) Loss to constrain the final generated point set, ensuring improved shape and density consistency.
(2) In the registration phase, we apply a Hybrid Mixture Model (HMM) to represent positional and normal information, reformulating the registration task as a KL divergence minimization problem. At the same time, a bidirectional strategy is further introduced into the registration paradigm to handle errors from completion and noise in both sets. Our experiments on a dataset comprising 1,399 human femur and 1,301 hip models demonstrate that our method achieves state-of-the-art performance across overlap rates from 15\% to 35\% and at various point counts (i.e., 20, 35, and 50 points) under conditions with less than 50\% overlap. Additionally, real phantom experiments on human femur and hip models were performed to validate the method’s performance in conditions simulating actual surgical scenarios.
