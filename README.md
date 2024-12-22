# Standard ANM Dataset
## Standard Datasets for Autonomous Navigation and Mapping: A Full-Stack Construction Methodology

### Authors: 
[Yuanzhi Liu](https://github.com/lyzrose), [Yujia Fu](https://github.com/yayafu666)†, [Minghui Qin](https://github.com/SJTU-qin)†, [Yufeng Xu](https://github.com/feng15423)†, et al. († Contributed equally)

## Abstract: 
The development of intelligent Vehicles (IVs) requires extensive standard datasets for training, benchmarking, and improvement. Autonomous Navigation and Mapping (ANM), as a critical technology for IVs, imposes exceptionally high demands on dataset construction. This is significant in its requirements for comprehensive sensor calibration, precise time synchronization, and accurate generation of ground truth. Besides, the whole construction workflow also demands intricate knowledge and sophisticated practices, necessitating lengthy learning curves for researchers to attain proficiency. The above challenges have led to a slow production of qualified datasets, directly constraining the advancement of ANM. However, so far, an investigation focused on a mature construction methodology of ANM dataset is still missing. This paper strives to fill the gap. Specifically, based on our systematic reviews and extensive practices, for the first time, a full-stack construction methodology of ANM dataset is proposed, including modules of platform construction, sensor calibration, time synchronization, ground truth generation, synthetic data production, and benchmark criteria, with detailed techniques and methodological routes provided in each step. Several long-standing issues are resolved within the methodology. Importantly, we introduce versatile calibration and synchronization frameworks that attain up to us-level and mm-level precision. Besides, we propose a full-scenario ground truth system that can generate scene-map and trajectory at cm-level accuracy. To verify the effectiveness of our methodology, we design a high-quality dataset and benchmark multiple state-of-the-art algorithms on it. The successful workflow demonstrates that our methodology can significantly reduce the research threshold and help individuals and institutions to construct datasets in a standardized way.

## News!!!
### We contribute two new datasets into our standard dataset community-SEIEE and YULAN, for navigation performance testing in large-scale Office Building and Residential Block scenarios respectively.

## SEIEE Sequences

KeyWords: Low-texture, Degradation, Lighting Change
Senarios: Long Corridor, White Wall, Reflective Floor

Stat/Sequence|1010-00|1010-01|1010-02|1010-03|1010-04
:--:|:--:|:--:|:--:|:--:|:--:
Size/GB|24.3/4.8|25.0/5.1|26.3/5.3|41.7/8.2|13.8/2.9
VLIO-rosbag|onedrive [baidu](https://pan.baidu.com/s/1SsSHVatM52tmVIb9c2JQCA?pwd=sjtu)|onedrive [baidu](https://pan.baidu.com/s/1e1nvLn6kNRXW_8ZkAF-DUw?pwd=sjtu)|onedrive [baidu](https://pan.baidu.com/s/1LrHyfvJAxyBma82iGaVL7g?pwd=sjtu)|onedrive [baidu](https://pan.baidu.com/s/1NohF3MTXmjfKZNMEn3hVdA?pwd=sjtu)|onedrive [baidu](https://pan.baidu.com/s/1m37eIgWroUVa9jBSDw4NQA?pwd=sjtu)
LIO-rosbag|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgQ_K8PgFz_LvzIiZ?e=PQdgRs) [baidu](https://pan.baidu.com/s/1olc4R9P04dEz8XRQicdWfg?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRXMxjKNsiS-zBZ5?e=75pZVv) [baidu](https://pan.baidu.com/s/1dxjVL6SKLWYkGeObFeWyjQ?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRd_2k4zpH111fZ8?e=w6xjtp) [baidu](https://pan.baidu.com/s/1rg0p53cHUlwh0HN-hMT70w?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRNIbWeKNmQY2WM2?e=5LycAJ) [baidu](https://pan.baidu.com/s/1PIhjam4ld3sIvGiQ6t1bSA?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRDbU7qgJKgHbHab?e=94tdSe) [baidu](https://pan.baidu.com/s/1ss1E3gMQeLkF1dYAPgsNEQ?pwd=sjtu)
GT-pose|onedrive baidu|onedrive baidu|onedrive baidu|onedrive baidu|onedrive baidu

<div align="left">
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_00.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_01.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_02.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_00.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_01.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_02.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_03.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_04.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_05.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_03.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_04.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_05.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_06.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_07.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_08.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_06.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_07.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_08.png" alt="photo" width="30%" />
</div>