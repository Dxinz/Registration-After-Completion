# Registration After Completion
## Introduction
This repository contains the implementation of our "Registration After Completion:Towards Sparse and Partial Point Set Registration for Computer-Assisted Orthopedic Surgery".
## Abstract
In computer-assisted orthopedic surgery (CAOS), accurate point set registration is essential for enhancing surgical accuracy.
However, the sparse and low-overlap nature of intraoperative point sets presents significant challenges for reliable registration.
To deal with these challenges, we propose a novel registration-after-completion framework, where the intraoperative point set is first completed, after which the two full point sets are registered. Our main contributions include the follows. First, we propose a progressive two-stage strategy to progressively complete the sparse and partial intraoperative point set. 
Second, considering that 1) intra-operative point set contains noise 2) the point completion process is not perfect, and 3) the resolution of preoperative image is limited, we adopt the bidirectional hybrid mixture models (HMMs) to represent the point set pairs and formulate the probabilistic registration network. In the proposed novel correspondence network where a dual-path cross-attention mechanism is adopted for feature fusion and a clustering mechanism is leveraged for calculating point-to-mixture correspondences. Furthermore, the bidirectional registration mechanism is leveraged to compute the transformation based on estimated correspondences. Third, we have extensively validated the proposed approach on various datasets and bone phantoms.
Our experiments on 1399 human femur and 1301 hip models demonstrate that our method achieves state-of-the-art performance across overlap rates from 15\% to 35\% and at various point counts (i.e., 25, 50, and 100 points) under conditions with less than 50\% overlap. 
Additionally, real phantom experiments on femur and hip models validate the method’s performance in simulated surgical scenarios. Experiments on ModelNet40 further confirmed our method's effectiveness and generalizability.
