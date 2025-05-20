---
title: "Nurse Activity Recognition in Gastrostomy Tube Feeding Using Video-Based Pose with Large Language Model-Guided Features"
collection: publications
permalink: /publication/2025-05-16-paper-title-number-1
# excerpt: 'xxxx'
date: 2025-04-22
venue: '7th International Conference on Activity and Behavior Computing (ABC 2025), Khalifa University, Abu Dhabi, UAE
paperurl: 'http://zhao-lingfeng.github.io/files/paper1.pdf'
citation: 'Lingfeng Zhao*, Christina Garcia, Shunsuke Komizunai, Noriyo Colley, Atsuko Sato, Mayumi Kouchiyama, Toshiko Nasu, Sozo Inoue'
---

In this paper, we improve nursing activity recognition in gastrostomy tube feeding (GTF) with temporal variations and sequential errors by integrating activity context to Large Language Model (LLM) for guided feature selection and post-processing. GTF is a delicate nursing procedure that allows direct stomach access in children for supplemental feeding or medication, but it is underrepresented in datasets, posing challenges for accurate detection. Manual feature engineering may overlook subtle but important motion cues, particularly in opening and closing the gastrostomy cover, where changes are minimal and localized to the hands. Additionally, sequence inconsistencies and missed activities limit the effectiveness of pose estimation methods in healthcare. Leveraging the contextual adaptability of LLMs, we generate new features suggested by the language model, combining them with hand-crafted features to optimize the model. For post-processing, a sliding window smoothing method based on majority voting is applied. To mitigate duration-based discrepancies, a priority handling is incorporated for short-duration activities to pre- serve their recognition accuracy while addressing repeated labels caused by long-duration actions. Particularly, we applied activity recognition to our unique GTF dataset collected from recorded video of two nurses, two students, and two staff members for three days with 17 labeled activities. Keypoints are extracted using YOLO11. Compared to the baseline, the application of LLM to GTF nurse activity recognition with pose estimation improved the Random Forest performance of F1-score from 54% to 57%. Additionally, incorporating the sliding window smoothing approach based on majority voting with short-term action priority, resulted in a 3% further increase.
