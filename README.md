# TinyXAI: A Consumer-Grade Stress Monitoring Engine for Always-On Wearable Devices

Authors: G. Kirubavathi*, Anagha C.*, Vaibhav S.*, Abdul Khader Jilani Saudagar†*, and Ateeq Ur Rehman‡*


Abstract: Lightweight and comprehensible models that are appropriate for real-time edge deployment are needed for wearable stress detection. We suggest TinyXAI, a CNN-LSTM
hybrid architecture with only 47K parameters, exhibiting strong
generalization to unseen subjects with 78.7% accuracy and a
0.37 stress F1-score under subjectwise splits, while attaining
97.0% accuracy and a 0.90 F1-score on the WESAD dataset
under window-wise evaluation. TinyXAI shows better crosssubject performance (F1: 0.368 vs. 0.313) than a 1D-CNN baseline
(34K parameters, 98.8% window-wise accuracy), which is crucial
for practical wearable applications. The suggested framework
uses a lightweight hybrid architecture that strikes a balance
between temporal dependency modeling using LSTM units and
spatial feature extraction via Conv1D layers. It also incorporates
memory-efficient preprocessing through per-subject normalization and light data augmentation, producing 89K effective training windows. Furthermore, model interpretability is enhanced
through Integrated Gradients (IG), which consistently identify
respiration (RESP) as the dominant physiological biomarker
for stress, with attribution concentrated in the mid-window
temporal region. Ablation studies indicate that while a TinyCNN
variant achieves higher window-wise F1 performance (0.82 vs.
0.80), the CNN–LSTM architecture provides substantially better
subject-wise generalization (F1: 0.42 vs. 0.30, a 39% improvement). Channel-wise ablation further confirms the necessity of
multimodal sensing, with removal of the accelerometer (ACC)
channel resulting in the largest degradation in window-wise F1
(0.43). TinyXAI enables always-on stress monitoring on consumer
wearables (smartwatches, chest straps) with 0.25 ms inference,
184 KB memory, privacy-preserving processing, and explainable
user feedback

Repository Overview

This repository contains the implementation of TinyXAI: A Consumer-Grade Stress Monitoring Engine for Always-On Wearable Devices. 

Detailed instructions for each component will be provided soon.




