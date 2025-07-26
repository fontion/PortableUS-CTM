# Real-Time Identification of Cricothyrotomy Landmarks in Emergency Care and Obstetric Patients Using Wireless Handheld Ultrasound and Edge-Computing Artificial Intelligence: A Prospective Observational Study 
Cheng-Yi Wu, Jia-Da Li, Po-Yuan Shih, Cheng-Chia Huang, Hsiao-Liang Cheng, Chun-Yu Wu, Joyce Tay, Meng-Che Wu, Chih-Hung Wang, Chu-Song Chen, Chien-Hua Huang

# Abstract
Objectives: This study aimed to develop machine learning-based algorithms to assist physicians in ultrasound-guided localization of the cricoid cartilage (CC), thyroid cartilage (TC), and cricothyroid membrane (CTM) for cricothyroidotomy. 

Methods: Adult female participants presenting to the emergency department with dyspnea or to the obstetrics and gynecology department for a scheduled cesarean section between August 2022 and July 2024 were prospectively recruited. Ultrasonographic images were collected using a wireless handheld ultrasound device connected to an edge computing tablet. Three You Only Look Once (YOLO) model variants—v5n6, v8n, and v10n—were selected for development and evaluation. 

Results: A total of 608 participants (median age: 58.0 years, interquartile range [IQR]: 40.0–73.0; median body mass index: 23.2 kg/m², IQR: 20.2–26.5) contributed 117,094 ultrasonographic frames. All three YOLO-based models demonstrated high accuracy in detecting CC, TC, and CTM, with area under the receiver operating characteristic curve values exceeding 0.88. In correctly identified frames, the models effectively localized CC (Dice values: YOLOv5n6, 0.830 [95% confidence interval (CI): 0.819–0.840]; YOLOv8n, 0.833 [95% CI: 0.820–0.845]; YOLOv10n, 0.833 [95% CI: 0.820–0.845]; p value: 0.004) and TC (YOLOv5n6, 0.820 [95% CI: 0.807–0.831]; YOLOv8n, 0.824 [95% CI: 0.810–0.837]; YOLOv10n, 0.822 [95% CI: 0.809–0.834] ; p value<0.001), though localization accuracy was lower for CTM (YOLOv5n6, 0.512 [95% CI: 0.476–0.543]; YOLOv8n, 0.503 [95% CI: 0.470–0.534]; YOLOv10n, 0.496 [95% CI: 0.464–0.525] ; p value<0.001). The mean frames per second for YOLOv5n6, YOLOv8n, and YOLOv10n were 3.67, 13.83, and 14.13, respectively, when deployed on the handheld ultrasound platform. 

Conclusions: YOLO-based models demonstrated high accuracy in detecting and localizing CC, TC, and CTM. YOLOv8n and YOLOv10n achieved clinically acceptable real-time imaging performance when deployed on a wireless handheld ultrasound device with an edge computing tablet. Further studies are needed to assess whether this favorable performance translates into actual clinical benefits. 

# Dataset
[Download](https://miya.teracloud.jp/share/11d158075e365e97)
