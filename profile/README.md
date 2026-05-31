# Project Introduction
This project focuses on Procedure Understanding. The core objective is to detect and verify the correctness of multi-step cooking activities from egocentric videos, based on the CaptainCook4D dataset. Our research starts from basic segment-level mistake detection and progressively extends to more complex, video-level Task Verification. In this process, we integrate temporal video features with semantic textual features by constructing and aligning Directed Acyclic Task Graphs. Finally, we utilize Graph Neural Networks (GNNs), such as DAGNN, to perform logical reasoning and global correctness classification over the entire recipe execution process.

# Team Members

- Amir Othmani 
- Lan Deng 
- Lei Gao
- Wenjie Zhou 

# Document Compilation

## Step 2: Mistake Detection baselines

### Substeps:

1. **Download the pre-extracted features**
   * [Drive](https://drive.google.com/drive/folders/1qJi7TFpGrKwC0CSPdq380BPPqYznmKjJ)

2. **Reproduce the V1 and V2 baselines from the CaptainCook4D**
   * [Colab: step1_evaluation.ipynb](https://colab.research.google.com/drive/1HRovfDNRQSbDjZjH0kMaKPVaNjAEgxEB)
   * [Github](https://github.com/T-Larm/aml-2025-mistake-detection-gp.git)
   * [Colab: step2.b_LSTM_baseline.ipynb](https://colab.research.google.com/drive/1NJAKohIaLYgLxvelg8IzTbcosMvKwzwN)
   * [Github](https://github.com/T-Larm/aml-2025-mistake-detection-gp.git)
         
3. **Extend the baselines to a new features extraction backbone**
   * [Colab: feature-extractors.ipynb](https://colab.research.google.com/drive/1iSASDchhBDYA48O_jKBJOReuw5Fniqyp)
   * [Github](https://github.com/FedWen128/feature_extractors.git)

## Extension

### Substeps:

1. **Recipe step localization**
   * [Drive](https://drive.google.com/drive/folders/1Hwl9zXqmnoXB_Mgwfb8euxVVWFMSkQWD)
   
   **1.1 Hiero Version**
   * [Colab: hiero-attempt.ipynb](https://colab.research.google.com/drive/15m776wBsRrqsr0XhkhagPVnxq34_VTEN)
   * [Github: gt-step-localization](https://github.com/Amir-Othmani00/gt-step-localization)
   * [Github: HiERO](https://github.com/amir-othmani/HiERO)
   
   **1.2 Actionformer Version**
   * [Github](https://github.com/T-Larm/aml_multi_step_localization/tree/egovlp)
  
2. **Simple Task-Verification baselines**
   * [Drive](https://drive.google.com/drive/folders/1h3aaqyj8echLDSWGgBblCpsxENuQR67V)
   * [Colab: task_verification_colab](https://colab.research.google.com/drive/15UmTUmZIVl3c1FhoGdzsQB4rEtDAgw9q#scrollTo=9ba97c6a)
   * [Github](https://github.com/AML-Project-3-Mistake-Detection/aml-2025-mistake-detection-gp.git)
	
3. **Task-Graph encoding + Step matching**
   * [Drive](https://drive.google.com/drive/folders/1LkDy1Ah6QzFtL-KOVddbrcvDGGZZc0J2)
   * [Github](https://github.com/Amir-Othmani00/EgoVLP)
