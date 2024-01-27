# This is the code of Gated-S2R-PCP, in reviewing by IEEE TITS.

<b>a) Introduction:</b> 

Pedestrian Crossing Prediction (PCP) in driving scenes plays a critical role in ensuring the safe operation of intelligent vehicles. Due to the limited observations of pedestrian crossing behaviors in typical situations, recent studies have begun to leverage synthetic data with flexible variation to boost prediction performance, employing domain adaptation frameworks. However, different domain knowledge has distinct cross-domain distribution gaps, which necessitates suitable domain knowledge adaption ways for PCP tasks. In this work, we propose a Gated Syn-to-Real Knowledge transfer approach for PCP (Gated-S2R-PCP). Gated-S2R-PCP advocates three different pathways for transferring the pedestrian locations, visual context, and semantic-depth clues in the synthetic data to the real data that is only with the pedestrian locations and raw RGB frames.

<p align="center">
  <img src="https://github.com/JWFanggit/Gated-S2R-PCP/blob/main/method.png">
</p>
<p align="center">Fig. 1: Gated-S2R-PCP advocates different knowledge transfer ways from synthetic data to real data.</p>

A Learnable Gated Unit (LGU) is employed to fuse suitable cross-domain knowledge to boost pedestrian crossing prediction. We construct a new synthetic benchmark S2R-PCP-3181 with 3181 sequences (489,740 frames) which contains the pedestrian locations, RGB frames, semantic images, and depth images. With the synthetic S2R-PCP-3181, we transfer the knowledge to two real challenging datasets of PIE and JAAD, and superior PCP performance is obtained to the state-of-the-art methods. Additionally, we evaluate the Gated-S2R-PCP on all pedestrian crossing sequences (50 ones) in the DADA-2000 dataset to verify the PCP performance in near-collision scenes. 

The flowchart of Gated-S2R-PCP is shown as follows.
<p align="center">
  <img src="https://github.com/JWFanggit/Gated-S2R-PCP/blob/main/method1.png">
</p>
<p align="center">Fig. 2. The flowchart of Gated-S2R-PCP.</p>

<b>b) Code:</b>
The code can be downloaded from [here](https://pan.baidu.com/s/17IqCSb0VoTp8br-jxE3Csg ). (Extraction code:ljhq). 

To run the ```main.py```, the training phase can be conducted.

<b>c) Dataset:</b> The dataset S2R-PCP-3181 can be downloaded from [here](https://pan.baidu.com/s/1YFj2WW2jOst40XNlikH0lQ?pwd=gkap). (Extraction code:gkap).

<b>Note:</b> The whole size of S2R-PCP-3181 takes 300G space.
