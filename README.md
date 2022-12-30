# Awesome-Voice-Conversion-Papers-Projects
Here are some interesting papers in speech field which I collected, may they help you.

## Overview

- [Voice Conversion](#Voice-Conversion)

- [Singing Voice Conversion](#Singing-Voice-Conversion)

- [Interesting papers](#Interesting-papers)


### Voice Conversion

#### 1. Challenge

Voice Conversion Challenge（VCC）[[Home]](https://link.zhihu.com/?target=http%3A//www.vc-challenge.org/)

ZeroSpeech Challenge [[Home]](https://link.zhihu.com/?target=https%3A//zerospeech.com/2020/news.html)

#### 2. Dataset

[[VCTK]](https://datashare.is.ed.ac.uk/handle/10283/3443)

[[ZeroSpeech 2020]](https://link.zhihu.com/?target=https%3A//download.zerospeech.com/) 

[[VCC2016]](https://link.zhihu.com/?target=https%3A//datashare.is.ed.ac.uk/handle/10283/2211) The Voice Conversion Challenge 2016

[[VCC2018]](https://link.zhihu.com/?target=https%3A//datashare.is.ed.ac.uk/handle/10283/3061) The Voice Conversion Challenge 2018


#### 3. Method

##### 3.1 Parallel VC
[VCC 2018 Baseline](https://link.zhihu.com/?target=https%3A//github.com/k2kobayashi/sprocket)


##### 3.2 Non-parallel VC

###### 3.2.1 Direct Conversion：

- **CycleGAN-VC**  (*arXiv:1711.11293, Nov. 2017 (EUSIPCO, 2018)*) author info: Takuhiro Kaneko Hirokazu Kameoka NTT Communication Science Laboratories, NTT Corporation

- **CycleGAN-VC2**  (*arXiv:1904.04631, Apr. 2019 ICASSP 2019*) author info: Takuhiro Kaneko Hirokazu Kameoka Kou Tanaka Nobukatsu HojoNTT Communication Science Laboratories, NTT Corporation

- **StarGAN-VC** (*arXiv:1806.02169, June 2018 (SLT, 2018)*) author info: Hirokazu Kameoka, Takuhiro Kaneko, Kou Tanaka, Nobukatsu HojoNTT Communication Science Laboratories, NTT Corporation

- **VAW-GAN-VC** (*arXiv:1704.00849, 4 Apr 2017. Interspeech, 2017*) author info: Chin-Cheng Hsu , Hsin-Te Hwang , Yi-Chiao Wu , Yu Tsao, and Hsin-Min Wang Institute of Information Science, Academia Sinica, Taiwan ，Research Center for Information Technology Innovation, Academia Sinica, Taiwan

- **StarGAN-VC2** (*arXiv:1907.12279, July 2019 Interspeech 2019*) author info: Takuhiro Kaneko Hirokazu Kameoka Kou Tanaka Nobukatsu HojoNTT Communication Science Laboratories, NTT Corporation

- **Contrastive Voice Conversion** (CVC) non-parallel voice conversion based on patch-wise contrastive learning and adversarial learning

###### 3.2.2 Feature Disentangle:

- **AUTO-VC** (*arXiv preprint arXiv:1905.05879 (2019)*) author info: Kaizhi Qian, Yang Zhang, Shiyu Chang, Xuesong Yang, Mark Hasegawa-Johnson University of Illinois at UrbanaChampaign, IL, USA , MIT-IBM Watson AI Lab, Cambridge, MA, USA , IBM Research, Cambridge, MA, USA.

- **CDVAE-VC** Unsupervised Representation Disentanglement Using Cross Domain Features and Adversarial Learning in Variational Autoencoder Based Voice Conversion

- **ACVAE-VC** (*arXiv:1808.05092, Aug. 2018. (IEEE/ACM Transactions on Audio, Speech, and Language Processing, May 2019)*) author info: Hirokazu Kameoka, Takuhiro Kaneko, Kou Tanaka, Nobukatsu HojoNTT Communication Science Laboratories, NTT Corporation

- **SpeechSplit** (*arXiv preprint arXiv:2004.11284 (2020)*) author info: Kaizhi Qian, Yang Zhang, Shiyu Chang, David Cox, Mark Hasegawa-Johnson MIT-IBM Watson AI Lab, USA University of Illinois at Urbana-Champaign, USA.

- **AGAIN-VC** AGAIN-VC: A One-shot Voice Conversion using Activation Guidance and Adaptive Instance Normalization (2020)

- **Crank** Non-parallel voice conversion based on vector-quantized variational autoencoder with adversarial learning author info：Kazuhiro Kobayashi Wen-Chin Huang Tomoki Toda

- **VQ-VAE-Speech** VQ-VAE + WaveNet by [*Chorowski et al., 2019*] and VQ-VAE on speech signals by [*van den Oord et al., 2017*].

- **VQ-VAE** for Acoustic Unit Discovery and Voice Conversion Train and evaluate the VQ-VAE model for the ZeroSpeech 2020 challenge.

- **RandomCNN-voice-transfer** Maybe the fastest voice style transfer with reasonable result

- **FragmentVC** (arXiv preprint arXiv:2010.14150(2020)). author info: Yist Y. Lin, Chung-Ming Chien, Jheng-Hao Lin, Hung-yi Lee, Lin-shan Lee, National Taiwan University College of Electrical Engineering and Computer Science

- **HVQ-VAE** Cross-lingual Voice Conversion using Hierarchical Vector-Quantized Variational Autoencoder author info: Tuan Vu Ho and Masato Akagi Japan Advanced Institute of Science and Technology （VCC2020）

- **CycleVAE** Provides a Cyclic Variational AutoEncoder (CycleVAE)-based voice conversion (VC) system with parallel WaveGAN (PWG)-based vocoder for Voice Conversion Challenge 2020 (VCC2020)

- Voice Conversion on unaligned data compare standard VAE, VQ-VAE and Gumbel VAE models as approaches to VC on the Voice Conversion Challenge 2016 dataset.

- **ZeroSpeech 2019:** TTS without T - Pytorch "Unsupervised End-to-End Learning of Discrete Linguistic Units for Voice Conversion", Interspeech 2019. 2nd place in terms of low bitrate, higher Mean Opinion Score (MOS) and lower CER than the 1st place team

- **Cascade ASR + TTS** Recipe for Voice Conversion Challenge 2020 baseline: Cascade ASR + TTS author info: Wen-Chin Huang @ Nagoya University Tomoki Hayashi Shinji Watanabe (JHU), Tomoki Toda (Nagoya U)

- **MelGAN-VC** MelGAN-VC: Voice Conversion and Audio Style Transfer on arbitrarily long samples using Spectrograms

- **Cotatron** Cotatron: Transcription-Guided Speech Encoder for Any-to-Many Voice Conversion without Parallel Data author info: Seung-won Park , Doo-young Kim, Myun-chul Joe2 1Seoul National University 2MINDsLab Inc.

- Voice Conversion with Non-Parallel Data Phonetic posteriorgrams for many-to-one voice conversion without parallel data training (PPGs based)

- Voice-Conversion Multi-target voice conversion without parallel data by adversarially learning disentangled audio representations.(2018)

- Voice Conversion Compare with Standard VAE, VQ-VAE and Gumbel VAE models, JointVAE approaches on the VCC 2016 dataset.

- **Wavenet_AutoEncoders**(ZeroSpeech 2020 challenge)WaveNet autoencoder + Instance Normalization (IN-WAE) WaveNet autoencoder + Sliced Vector Quantization (SVQ-WAE)

- Adversarial Voice Conversion Voice conversion using deep adversarial learning, based on WaveNet autoencoders. multiple decoders are used so that each one corresponds to a particular voice. adversarial domain adaptation technique is employed (2019)

- **Adversarial-Many-to-Many-VC** Improving the Speaker Identity of Non-Parallel Many-to-Many Voice Conversion with Adversarial Speaker Recognition(PPG2speech synthesizer with adversarial speaker classifier)

- **TransferLearning-CLVC** "Transfer Learning from Monolingual ASR to Transcription-free Cross-lingual Voice Conversion." author info: Che-Jui Chang Red Pill Lab（PPGs + Waveglow vocoder）

- **Non-parallel Seq2seq Voice Conversion** Non-Parallel Sequence-to-Sequence Voice Conversion with Disentangled Linguistic and Speaker Representations (2019)(PPGs based end2end train)

- **EA-SVC** Phonetic Posteriorgrams based Many-to-Many Singing Voice Conversion via Adversarial Training(PPG based SVC)

- **Audio-Style-Transfer** Neural Style Transfer for Audio Spectrograms

##### 4. Paper & Projects

:heavy_check_mark: - Kashkin, Anton, Ivan Karpukhin, and Svyatoslav Shishkin. "**HiFi-VC: High Quality ASR-Based Voice Conversion.**" arXiv preprint arXiv:2203.16937 (2022)..[[Paper]](https://arxiv.org/abs/2203.16937) [[Project]](https://github.com/tinkoff-ai/hifi_vc)

:heavy_check_mark: - Yuan, Ruibin, et al. "**DeID-VC: Speaker De-identification via Zero-shot Pseudo Voice Conversion.**" arXiv preprint arXiv:2209.04530 (2022).[[Paper]](https://arxiv.org/abs/2209.04530) [[Project]](https://github.com/a43992899/DeID-VC)

:heavy_check_mark: - Popov, Vadim, et al. "**Diffusion-based voice conversion with fast maximum likelihood sampling scheme.**" arXiv preprint arXiv:2109.13821 (2021). [[Paper]](https://arxiv.org/pdf/2109.13821.pdf) [[Project]](https://github.com/huawei-noah/Speech-Backbones/tree/main/DiffVC)

:heavy_check_mark: - Nguyen, Bac, and Fabien Cardinaux. "**Nvc-net: End-to-end adversarial voice conversion.**" ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2022. [[Paper]](https://arxiv.org/abs/2106.00992) [[Project]](https://github.com/sony/ai-research-code/tree/master/nvcnet)

:heavy_check_mark: - Zhao, Xintao, et al. "**Disentangling Content and Fine-Grained Prosody Information Via Hybrid ASR Bottleneck Features for Voice Conversion.**" ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2022.. [[Paper]](https://arxiv.org/pdf/2203.12813.pdf) [[Project]](https://thuhcsi.github.io/icassp2022-hybrid-bottleneck-vc/)

:heavy_check_mark: - Liu, Songxiang, et al. "**Any-to-many voice conversion with location-relative sequence-to-sequence modeling.**" IEEE/ACM Transactions on Audio, Speech, and Language Processing 29 (2021): 1717-1728.. [[Paper]](https://arxiv.org/abs/2009.02725v3) [[Project]](https://github.com/liusongxiang/ppg-vc)

:heavy_check_mark: - Neekhara, Paarth, et al. "**Expressive Neural Voice Cloning.**" *arXiv preprint arXiv:2102.00151(2021)*.[[Paper]](https://www.arxiv-vanity.com/papers/2102.00151/)

:heavy_check_mark: - Cifka, Ondrej, et al. "**Self-Supervised VQ-VAE For One-Shot Music Style Transfer.**" *arXiv preprint arXiv:2102.05749(2021)*.[[Paper]](https://arxiv.org/abs/2102.05749) [[Project]](https://github.com/cifkao/ss-vq-vae)

:heavy_check_mark: - Zhao, Shengkui, et al. "**Towards Natural and Controllable Cross-Lingual Voice Conversion Based on Neural TTS Model and Phonetic Posteriorgram.**"*arXiv preprint arXiv:2102.01991(2021)*.[[Paper]](https://www.arxiv-vanity.com/papers/2102.01991/)

:heavy_check_mark: - H. Kameoka, T. Kaneko, K. Tanaka, and N. Hojo. "**StarGAN-VC: Non-parallel Many-to-Many Voice Conversion with Star Generative Adversarial Networks.**" *arXiv:1806.02169, June 2018* (SLT, 2018). [[Paper]](https://arxiv.org/abs/1806.02169) [[Project]](https://www.kecl.ntt.co.jp/people/kameoka.hirokazu/Demos/stargan-vc/)

:heavy_check_mark: - J. Lorenzo-Trueba, J. Yamagishi, T. Toda, D. Saito, F. Villavicencio, T. Kinnunen, and Z. Ling. "**The Voice Conversion Challenge 2018: Promoting Development of Parallel and Nonparallel Methods.**" *Speaker Odyssey, 2018*. [[Paper]](https://arxiv.org/abs/1804.04262) [[Dataset]](https://datashare.ed.ac.uk/handle/10283/3061)

:heavy_check_mark: - K. Kobayashi and T. Toda. "**sprocket: Open-Source Voice Conversion Software.**" *Speaker Odyssey, 2018.* [[Paper]](https://nuss.nagoya-u.ac.jp/s/h8YKnq6qxjjxtU3#pdfviewer) [[Project]](https://github.com/k2kobayashi/sprocket) [[Samples (zip)]](https://nuss.nagoya-u.ac.jp/login)

:heavy_check_mark: - T. Kaneko and H. Kameoka. "**Parallel-Data-Free Voice Conversion Using Cycle-Consistent Adversarial Networks.**" *arXiv:1711.11293, Nov. 2017 (EUSIPCO, 2018)*. [[Paper]](https://arxiv.org/abs/1711.11293) [[Project]](http://www.kecl.ntt.co.jp/people/kaneko.takuhiro/projects/cyclegan-vc/index.html)

:heavy_check_mark: - T. Kaneko, H. Kameoka, K. Tanaka, and N. Hojo. "**CycleGAN-VC2: Improved CycleGAN-based Non-parallel Voice Conversion.**" *ICASSP, 2019*. [[Paper]](https://arxiv.org/abs/1904.04631) [[Project]](http://www.kecl.ntt.co.jp/people/kaneko.takuhiro/projects/cyclegan-vc2/index.html) [[github]](https://github.com/jackaduma/CycleGAN-VC2)

:heavy_check_mark: - H. Kameoka, T. Kaneko, K. Tanaka, and N. Hojo. "**ACVAE-VC: Non-parallel Many-to-Many Voice Conversion with Auxiliary Classifier Variational Autoencoder.**" *arXiv:1808.05092, Aug. 2018. (IEEE/ACM Transactions on Audio, Speech, and Language Processing, May 2019)*. [[Paper]](https://arxiv.org/abs/1808.05092) [[Project]](http://www.kecl.ntt.co.jp/people/kameoka.hirokazu/Demos/acvae-vc/)

:heavy_check_mark: - C. Hsu, H.-T. Hwang, Y.-C. Wu, Y. Tsao, and H.-M. Wang. "**Voice Conversion from Unaligned Corpora using Variational Autoencoding Wasserstein Generative Adversarial Networks.**" *Interspeech, 2017*. [[Paper]](https://arxiv.org/abs/1704.00849) [[Project]](https://jeremycchsu.github.io/vc-vawgan/)

:heavy_check_mark: - Kaneko, Takuhiro, et al. "**StarGAN-VC2: Rethinking conditional methods for StarGAN-based voice conversion.**" *arXiv preprint arXiv:1907.12279 (2019)*. [[Paper]](https://arxiv.org/abs/1907.12279) [[Project]](http://www.kecl.ntt.co.jp/people/kaneko.takuhiro/projects/stargan-vc2/index.html)

:heavy_check_mark: - Qian, Kaizhi, et al. "**Autovc: Zero-shot voice style transfer with only autoencoder loss.**" *arXiv preprint arXiv:1905.05879 (2019)*.[[Paper]](https://arxiv.org/pdf/1905.05879.pdf) [[Project]](https://github.com/auspicious3000/autovc)

:heavy_check_mark: - Qian, Kaizhi, et al. "**Unsupervised speech decomposition via triple information bottleneck.**" *arXiv preprint arXiv:2004.11284 (2020)*. [[Paper]](https://arxiv.org/abs/2004.11284) [[Project]](https://auspicious3000.github.io/SpeechSplit-Demo/)

:heavy_check_mark: - T. Toda, A. W Black, and K. Tokuda. "**Voice Conversion Based on Maximum Likelihood Estimation of Spectral Parameter Trajectory.**" *IEEE Trans. Audio Speech Lang. Process., 2007*. [[Paper]](https://ieeexplore.ieee.org/document/4317579?reload=true)

:heavy_check_mark: - Gatys, Leon A., Alexander S. Ecker, and Matthias Bethge. "**A neural algorithm of artistic style.**"*arXiv preprint arXiv:1508.06576(2015)*.[[Paper]](https://arxiv.org/abs/1508.06576)[[Project]](https://github.com/mazzzystar/randomCNN-voice-transfer)

:heavy_check_mark: - K. Kobayashi, T. Toda, and S. Nakamura. "**F0 Transformation Techniques for Statistical Voice Conversion with Direct Waveform Modification with Spectral Differential.**" *SLT, 2016*. [[Paper]](https://ieeexplore.ieee.org/document/7846338) [[Project]](https://github.com/k2kobayashi/sprocket)

:heavy_check_mark: - M. Morise, F. Yokomori, and K. Ozawa. "**WORLD: A Vocoder-Based High-Quality Speech Synthesis System for Real-Time Applications.**" *IEICE Trans. Inf. Syst., 2016*. [[Paper]](https://www.jstage.jst.go.jp/article/transinf/E99.D/7/E99.D_2015EDP7457/_article) [[Project]](http://www.kki.yamanashi.ac.jp/~mmorise/world/english/index.html)

:heavy_check_mark: - Wu, Da-Yi, and Yi-Hsuan Yang. "**Speech-to-Singing Conversion based on Boundary Equilibrium GAN.**"*arXiv preprint arXiv:2005.13835(2020)*.[[Paper]](https://arxiv.org/pdf/2005.13835.pdf) [[Project]](https://github.com/ericwudayi/speech2singing)

:heavy_check_mark: - Sisman, Berrak, et al. "**An Overview of Voice Conversion and its Challenges: From Statistical Modeling to Deep Learning.**"*arXiv preprint arXiv:2008.03648(2020)*.[[Paper]](https://arxiv.org/pdf/2008.03648.pdf)

:heavy_check_mark: - Peng, Yu-Huai, et al. "**The Academia Sinica Systems of Voice Conversion for VCC2020.**"*arXiv preprint arXiv:2010.02669(2020)*.[[Paper]](https://arxiv.org/abs/2010.02669)

:heavy_check_mark: - Huang, Wen-Chin, et al. "**The Sequence-to-Sequence Baseline for the Voice Conversion Challenge 2020: Cascading ASR and TTS.**"*arXiv preprint arXiv:2010.02434(2020)*.[[Paper]](https://arxiv.org/abs/2010.02434) [[Project]](https://github.com/espnet/espnet)

:heavy_check_mark: - Zhang, Mingyang, et al. "**Transfer Learning from Speech Synthesis to Voice Conversion with Non-Parallel Training Data.**"*arXiv preprint arXiv:2009.14399(2020)*.[[Paper]](https://arxiv.org/abs/2009.14399)

:heavy_check_mark: - Wen-Chin Huang,et al."**The NU Voice Conversion System for the Voice Conversion Challenge 2020: On the Effectiveness of Sequence-to-sequence Models and Autoregressive Neural Vocoders.**"*arXiv preprint arXiv:2010.04446(2020)*.[[Paper]](https://arxiv.org/abs/2010.04446)

:heavy_check_mark: - Oriol Barbany Mayor, Milos Cernak. "**FastVC: Fast Voice Conversion with non-parallel data.**" *arXiv preprint arXiv:2010.04185 (2020)*.[[Paper]](https://arxiv.org/abs/2010.04185)

:heavy_check_mark: - Patrick Lumban Tobing,Yi-Chiao Wu,Tomoki Toda. "**Baseline System of Voice Conversion Challenge 2020 with Cyclic Variational Autoencoder and Parallel WaveGAN.**"*arXiv preprint arXiv:2010.04429(2020)*[[Paper]](https://arxiv.org/abs/2010.04429)

:heavy_check_mark: - Kazuhiro Kobayashi Wen-Chin Huang Tomoki Toda . "**Non-parallel voice conversion based on vector-quantized variational autoencoder with adversarial learning**"

:heavy_check_mark: - Yamamoto, Ryuichi, Eunwoo Song, and Jae-Min Kim. "**Parallel WaveGAN: A fast waveform generation model based on generative adversarial networks with multi-resolution spectrogram.**"*ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2020*. [[Paper]](https://arxiv.org/pdf/1910.11480.pdf)

:heavy_check_mark: - K. Kobayashi, T. Toda, "**sprocket: Open-Source Voice Conversion Software.**" *Proc. Odyssey, pp. 203-210, June 2018*.[[Paper]](https://nuss.nagoya-u.ac.jp/s/h8YKnq6qxjjxtU3)

:heavy_check_mark: - Yukarin. **Realtime Yukarin: an application for real-time voice conversion.**[[Project]](https://github.com/Hiroshiba/realtime-yukarin)

:heavy_check_mark: - VQ-VAE for Acoustic Unit Discovery and Voice Conversion.[[Project]](https://github.com/bshall/ZeroSpeech)

:heavy_check_mark: - autovc-implement: [[f0-autovc]](https://github.com/hrnoh/f0-autovc), [[AutoVC.pytorch]](https://github.com/peisuke/AutoVC.pytorch), [[autovc_v2]](https://github.com/casperwang/autovc_v2), [[AutoVC-WavRNN]](https://github.com/freenowill/AutoVC-WavRNN), [[AutoVC]](https://github.com/CODEJIN/AutoVC)

:heavy_check_mark: - Lin, Yist Y., et al. "**FragmentVC: Any-to-Any Voice Conversion by End-to-End Extracting and Fusing Fine-Grained Voice Fragments With Attention.**"*arXiv preprint arXiv:2010.14150(2020)*. [[Paper]](https://arxiv.org/abs/2010.14150) [[Project]](https://github.com/yistLin/FragmentVC)

:heavy_check_mark: - Sun, Lifa, et al. "**Phonetic posteriorgrams for many-to-one voice conversion without parallel data training.**"*2016 IEEE International Conference on Multimedia and Expo (ICME). IEEE, 2016*.[[Paper]](https://ieeexplore.ieee.org/document/7552917) [[Project]](https://github.com/andabi/deep-voice-conversion)

:heavy_check_mark: - Huang, Wen-Chin, et al. "**Unsupervised Representation Disentanglement Using Cross Domain Features and Adversarial Learning in Variational Autoencoder Based Voice Conversion.**"*IEEE Transactions on Emerging Topics in Computational Intelligence(2020)*. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9057379) [[Project]](https://github.com/unilight/cdvae-vc)

:heavy_check_mark: - Chou, Ju-chieh, et al. "**Multi-target voice conversion without parallel data by adversarially learning disentangled audio representations.**"*arXiv preprint arXiv:1804.02812(2018)*.[[Paper]](https://arxiv.org/pdf/1804.02812.pdf) [[Project]](https://github.com/BogiHsu/Voice-Conversion)

:heavy_check_mark: - Grinstein, Eric, et al. "**Audio style transfer.**"*2018 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2018*.[[Paper]](https://hal.archives-ouvertes.fr/hal-01626389/document) [[Project]](https://github.com/inzva/Audio-Style-Transfer) [[HomePage]](https://egrinstein.github.io/2017/10/25/ast.html)

:heavy_check_mark: - Li, Tingle, et al. "**CVC: Contrastive Learning for Non-parallel Voice Conversion.**"*arXiv preprint arXiv:2011.00782(2020)*.[[Paper]](https://arxiv.org/abs/2011.00782) [[Project]](https://github.com/Tinglok/CVC)

:heavy_check_mark: - Huang, Wen-Chin, et al. "**Any-to-One Sequence-to-Sequence Voice Conversion using Self-Supervised Discrete Speech Representations.**"*arXiv preprint arXiv:2010.12231(2020)*.[[Paper]](https://arxiv.org/pdf/2010.12231.pdf)

:heavy_check_mark: - Li, Zhonghao, et al. "**PPG-based singing voice conversion with adversarial representation learning.**"*arXiv preprint arXiv:2010.14804(2020)*.[[Paper]](https://arxiv.org/pdf/2010.14804.pdf)

:heavy_check_mark: - Zhang, Jing-Xuan, Zhen-Hua Ling, and Li-Rong Dai. "**Non-parallel sequence-to-sequence voice conversion with disentangled linguistic and speaker representations.**"*IEEE/ACM Transactions on Audio, Speech, and Language Processing28 (2019): 540-552*.[[Paper]](https://arxiv.org/pdf/1906.10508.pdf) [[Project]](https://github.com/jxzhanggg/nonparaSeq2seqVC_code)

:heavy_check_mark: - Ding, Shaojin, Guanlong Zhao, and Ricardo Gutierrez-Osuna. "**Improving the Speaker Identity of Non-Parallel Many-to-Many Voice Conversion with Adversarial Speaker Recognition.**"*Proc. Interspeech 2020(2020): 776-780*.[[Paper]](http://www.interspeech2020.org/uploadfile/pdf/Mon-2-7-2.pdf) [[Project]](https://github.com/shaojinding/Adversarial-Many-to-Many-VC)

:heavy_check_mark: - Chang, Che-Jui. "**Transfer Learning from Monolingual ASR to Transcription-free Cross-lingual Voice Conversion.**"*arXiv preprint arXiv:2009.14668(2020)*.[[Paper]](https://arxiv.org/ftp/arxiv/papers/2009/2009.14668.pdf) [[Project]](https://github.com/cjerry1243/TransferLearning-CLVC)

:heavy_check_mark: - Guo, Haohan, et al. "**Phonetic Posteriorgrams based Many-to-Many Singing Voice Conversion via Adversarial Training.**"*arXiv preprint arXiv:2012.01837(2020)*.[[Paper]](https://arxiv.org/pdf/2012.01837.pdf) [[Project]](https://github.com/hhguo/EA-SVC)

:heavy_check_mark: - Wang, Zhichao, et al. "**Accent and Speaker Disentanglement in Many-to-many Voice Conversion.**"*arXiv preprint arXiv:2011.08609(2020)*.[[Paper]](https://arxiv.org/pdf/2011.08609.pdf) [[Project]](https://kerwinchao.github.io/AccentVoicejointConversion.github.io/)

:heavy_check_mark: - Zhao, Guanlong, and Ricardo Gutierrez-Osuna. "**Using phonetic posteriorgram based frame pairing for segmental accent conversion.**"*IEEE/ACM Transactions on Audio, Speech, and Language Processing27.10 (2019): 1649-1660*.[[Paper]](https://ieeexplore.ieee.org/document/8755490)

:heavy_check_mark: - Zhou, Kun, et al. "**Seen and unseen emotional style transfer for voice conversion with a new emotional speech dataset.**"*arXiv preprint arXiv:2010.14794(2020)*.[[Paper]](https://arxiv.org/pdf/2010.14794.pdf) [[Project]](https://kunzhou9646.github.io/controllable-evc/)

:heavy_check_mark: - Wang, Jie, et al. "**Adversarially learning disentangled speech representations for robust multi-factor voice conversion.**"*arXiv preprint arXiv:2102.00184(2021)*.[[Paper]](https://arxiv.org/pdf/2102.00184.pdf)

:heavy_check_mark: - Rebryk, Yurii, and Stanislav Beliaev. "**ConVoice: Real-Time Zero-Shot Voice Style Transfer with Convolutional Network.**"*arXiv preprint arXiv:2005.07815(2020)*.[[Paper]](https://www.dropbox.com/s/h781sva0dv177ot/ConVoice.pdf?dl=0)

:heavy_check_mark: - Serrà, Joan, Santiago Pascual, and Carlos Segura. "**Blow: a single-scale hyperconditioned flow for non-parallel raw-audio voice conversion.**"*arXiv preprint arXiv:1906.00794(2019)*.[[Paper]](https://www.dropbox.com/s/6bovin589qr78l8/Blow.pdf?dl=0)

:heavy_check_mark: - **Voice conversion using deep Bidirectional Long Short-Term Memory based Recurrent Neural Networks**(2015), *Lifa Sun et al*. [[Paper]](https://ieeexplore.ieee.org/document/7178896)

:heavy_check_mark: - **Phonetic posteriorgrams for many-to-one voice conversion without parallel data training**(2016), *Lifa Sun et al*. [[Paper]](https://ieeexplore.ieee.org/document/7552917)



### Music Modelling

- **Onsets and Frames: Dual-Objective Piano Transcription**(2017), Curtis Hawthorne et al. [[Paper]](https://arxiv.org/abs/1710.11153)

- **ByteSing- A Chinese Singing Voice Synthesis System Using Duration Allocated Encoder-Decoder Acoustic Models and WaveRNN Vocoders**(2020), Yu Gu et al. [[Paper]](https://arxiv.org/pdf/2004.11012)

- **HiFiSinger: Towards High-Fidelity Neural Singing Voice Synthesis**(2020), Jiawei Chen et al. [[Paper]](https://arxiv.org/pdf/2009.01776)

- **Jukebox: A Generative Model for Music**(2020), Prafulla Dhariwal et al. [[Paper]](https://arxiv.org/pdf/2005.00341)

- **PeriodNet: A non-autoregressive waveform generation model with a structure separating periodic and aperiodic components**(2021), Yukiya Hono et al. [[Paper]](https://arxiv.org/pdf/2102.07786)


### Singing Voice Conversion

- Lu, Junchen, et al. "**VAW-GAN for Singing Voice Conversion with Non-parallel Training Data.**" *2020 Asia-Pacific Signal and Information Processing Association Annual Summit and Conference (APSIPA ASC). IEEE, 2020*.[[Paper]](https://arxiv.org/pdf/2008.03992.pdf) [[Project]](https://github.com/KunZhou9646/Singing-Voice-Conversion-with-conditional-VAW-GAN)

- SingingVoiceConversion[[Project]](https://github.com/jshong0907/SingingVoiceConversion), Singing-Voice-Conversion[[Project]](https://github.com/solalala-12/Singing-Voice-Conversion)

- Mor, Noam, et al. "**A universal music translation network.**" *arXiv preprint arXiv:1805.07848(2018)*.[[Paper]](https://arxiv.org/abs/1805.07848) [[Project]](https://github.com/facebookresearch/music-translation)

- Guo, Haohan, et al. "**Phonetic Posteriorgrams based Many-to-Many Singing Voice Conversion via Adversarial Training.**" *arXiv preprint arXiv:2012.01837(2020)*.[[Paper]](https://arxiv.org/abs/2012.01837) [[Project]](https://github.com/hhguo/EA-SVC)

- Takahashi, Naoya, Mayank Kumar Singh, and Yuki Mitsufuji. "**Hierarchical disentangled representation learning for singing voice conversion.**" *arXiv preprint arXiv:2101.06842(2021)*.[[Paper]](https://arxiv.org/pdf/2101.06842.pdf)

- Basak, Sakya, et al. "**End-to-end lyrics Recognition with Voice to Singing Style Transfer.**" *arXiv preprint arXiv:2102.08575(2021).*[[Paper]](https://arxiv.org/pdf/2102.08575.pdf)

- Sankaran, Shreeviknesh, Sukavanan Nanjundan, and G. Paavai Anand. "**Anyone GAN Sing.**" *arXiv preprint arXiv:2102.11058(2021).*[[Paper]](https://arxiv.org/pdf/2102.11058.pdf)
- Tae, Jaesung, Hyeongju Kim, and Younggun Lee. "MLP Singer: Towards Rapid Parallel Korean Singing Voice Synthesis." *arXiv preprint arXiv:2106.07886 (2021).*[[Paper]](https://arxiv.org/pdf/2106.07886.pdf) [[Projects]](https://github.com/CODEJIN/MLPSinger)


### Interesting papers

- **The Reversible Residual Network: Backpropagation Without Storing Activations**(2017), Aidan N. Gomez et al. [[Paper]](https://arxiv.org/pdf/1707.04585)

- **FlowSeq: Non-Autoregressive Conditional Sequence Generation with Generative Flow**(2019), Xuezhe Ma et al. [[Paper]](https://arxiv.org/pdf/1909.02480)

- **Learning Problem-agnostic Speech Representations from Multiple Self-supervised Tasks**(2019), Santiago Pascual et al. [[Paper]](https://arxiv.org/pdf/1904.03416.pdf)

- **Self-supervised audio representation learning for mobile devices**(2019), Marco Tagliasacchi et al. [[Paper]](https://arxiv.org/pdf/1905.11796.pdf)

- **SinGAN: Learning a Generative Model from a Single Natural Image**(2019), Tamar Rott Shaham et al. [[Paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Shaham_SinGAN_Learning_a_Generative_Model_From_a_Single_Natural_Image_ICCV_2019_paper.pdf)

- **Audio2Face: Generating Speech/Face Animation from Single Audio with Attention-Based Bidirectional LSTM Networks**(2019), Guanzhong Tian et al. [[Paper]](https://arxiv.org/pdf/1905.11142)

- **Attention is Not Only a Weight: Analyzing Transformers with Vector Norms**(2020), Goro Kobayashi et al. [[Paper]](https://arxiv.org/pdf/2004.10102)


## Contact Me
If you have any questions, Contact Me ，thanks
