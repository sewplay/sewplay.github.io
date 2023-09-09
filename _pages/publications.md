---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
You can also find my articles on my [Google Scholar](https://scholar.google.com/citations?user=H8Of2IIAAAAJ&hl) profile

***
## 2023

- Pruning self-attention for zero-shot multi-speaker text-to-speech [[paper](https://sewplay.github.io/files/papers/2023/IS_1301.pdf)][[demo](https://hcy71o.github.io/SparseTTS-demo/)]  
  <small>Hyungchan Yoon, Changhwan Kim, <strong style="color:orange">Eunwoo Song</strong>, Hyun-Wook Yoon, Hong-Goo Kang</small>  
  <small>Proc. INTERSPEECH, 2023, pp. 4299-4303.</small>  
  
- Period VITS: Variational inference with explicit pitch modeling for end-to-end emotional speech synthesis [[paper](https://sewplay.github.io/files/papers/2023/icassp_1241.pdf)][[demo](https://yshira116.github.io/period_vits_demo/)]  
  <small>Yuma Shirahata, Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Ryo Terashima, Jae-Min Kim, Kentaro Tachibana</small>  
  <small>Proc. ICASSP, 2023, pp. 4299-4303.</small>  


***
## 2022
- HierSpeech: Bridging the gap between text and speech by hierarchical variational inference using self-supervised representations for speech synthesis [[paper](https://sewplay.github.io/files/papers/2022/neurips_54658.pdf)][[demo](https://sh-lee-prml.github.io/hierspeech-demo/)]  
  <small>Sang-Hoon Lee, Seung-Bin Kim, Ji-Hyun Lee, <strong style="color:orange">Eunwoo Song</strong>, Min-Jae Hwang, Seong-Whan Lee</small>  
  <small>Proc. NeurIPS, 2022, pp. 16624-16636.</small>  
  
- TTS-by-TTS 2: Data-selective augmentation for neural speech synthesis using ranking support vector machine with variational autoencoder
[[paper](https://sewplay.github.io/files/papers/2022/IS_10134.pdf)]
[[demo](https://sewplay.github.io/demos/txt2/)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Ryuichi Yamamoto, Ohsung Kwon, Chan-Ho Song, Min-Jae Hwang, Suhyeon Oh, Hyun-Wook Yoon, Jin-Seob Kim, Jae-Min Kim</small>  
  <small>Proc. INTERSPEECH, 2022, pp. 1941-1945.</small>  
    
- Language model-based emotion prediction methods for emotional speech synthesis systems
[[paper](https://sewplay.github.io/files/papers/2022/IS_11133.pdf)]
[[demo](https://christophyoon.github.io/lmemotiontts/)]  
  <small>Hyun-Wook Yoon, Ohsung Kwon, Hoyeon Lee, Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Jae-Min Kim, Min-Jae Hwang</small>  
  <small>Proc. INTERSPEECH, 2022, pp. 4596-4600.</small>  
  
- Cross-speaker emotion transfer for low-resource text-to-speech using non-parallel voice conversion with pitch-shift data augmentation
[[paper](https://sewplay.github.io/files/papers/2022/IS_11278.pdf)]
[[demo](https://ryojerky.github.io/demo_vc-tts-ps/)]  
  <small>Ryo Terashima, Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Yuma Shirahata, Hyun-Wook Yoon, Jae-Min Kim, Kentaro Tachibana</small>  
  <small>Proc. INTERSPEECH, 2022, pp. 3018-3022.</small>
  
- Linear prediction-based Parallel WaveGAN speech synthesis
[[paper](https://ieeexplore.ieee.org/abstract/document/9748530)]  
  <small>Min-Jae Hwang, Hyun-Wook Yoon, Chan-Ho Song, Jin-Seob Kim, Jae-Min Kim, <strong style="color:orange">Eunwoo Song</strong></small>  
  <small>Proc. ICEIC, 2022, pp. 1-4.</small>  
  
- Effective data augmentation methods for neural text-to-speech systems
[[paper](https://ieeexplore.ieee.org/abstract/document/9748515)]  
  <small>Suhyeon Oh, Ohsung Kwon, Min-Jae Hwang, Jae-Min Kim, <strong style="color:orange">Eunwoo Song</strong></small>  
  <small>Proc. ICEIC, 2022, pp. 1-4.</small>    


***
## 2021

- High-fidelity Parallel WaveGAN with multi-band harmonic-plus-noise model
[[paper](https://sewplay.github.io/files/papers/2021/IS210976.pdf)]
[[demo](https://min-jae.github.io/interspeech2021/)]  
  <small>Min-Jae Hwang, Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Jae-Min Kim</small>  
  <small>Proc. INTERSPEECH, 2021, pp. 2227-2231.</small>  

- LiteTTS: A decoder-free lightweight text-to-wave synthesis based on generative adversarial networks
[[paper](https://sewplay.github.io/files/papers/2021/IS210188.pdf)]
[[demo](https://dsp136.github.io/2021-04-01-interspeech-samples/)]  
  <small>Huu-Kim Nguyen, Kihyuk Jeong, Seyun Um, Min-Jae Hwang, <strong style="color:orange">Eunwoo Song</strong>, Hong-Goo Kang</small>  
  <small>Proc. INTERSPEECH, 2021. pp. 3595-3599.</small>  

- Parallel waveform synthesis based on generative adversarial networks with voicing-aware conditional discriminators
[[paper](https://sewplay.github.io/files/papers/2021/icassp_0006024.pdf)]
[[demo](https://r9y9.github.io/demos/projects/icassp2021/)]  
  <small>Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Min-Jae Hwang, Jae-Min Kim</small>  
  <small>Proc. ICASSP, 2021, pp. 6039-6043.</small>  

- TTS-by-TTS: TTS-driven data augmentation for fast and high-quality speech synthesis
[[paper](https://sewplay.github.io/files/papers/2021/icassp_0006583.pdf)]
[[demo](https://min-jae.github.io/icassp2021/)]  
  <small>Min-Jae Hwang, Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Jae-Min Kim</small>  
  <small>Proc. ICASSP, 2021, pp. 6598-6602.</small>  

- Improved Parallel WaveGAN with perceptually weighted spectrogram loss
[[paper](https://sewplay.github.io/files/papers/2021/slt_0000470.pdf)]
[[demo](https://sewplay.github.io/demos/wavegan-pwsl/)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Ryuichi Yamamoto, Min-Jae Hwang, Jin-Seob Kim, Ohsung Kwon, Jae-Min Kim</small>  
  <small>Proc. SLT, 2021, pp. 470-476.</small>  

***
## 2020
    
- LP-WaveNet: Linear prediction-based WaveNet speech synthesis
[[paper](https://sewplay.github.io/files/papers/2020/apsipa_09306362.pdf)]
[[demo](https://min-jae.github.io/apsipa2020/)]  
  <small>Min-Jae Hwang, Frank Soong, <strong style="color:orange">Eunwoo Song</strong>, Xi Wang, Hyeonjoo Kang, Hong-Goo Kang</small>  
  <small>Proc. APSIPA, 2020, pp. 810-814.</small>  
    
- ExcitGlow: Improving a WaveGlow-based neural vocoder with linear prediction analysis
[[paper](https://sewplay.github.io/files/papers/2020/apsipa_0000831.pdf)]  
  <small>Suhyeon Oh, Hyungseob Lim, Kyungguen Byun, Min-Jae Hwang, <strong style="color:orange">Eunwoo Song</strong>, Hong-Goo Kang</small>  
  <small>Proc. APSIPA, 2020,  pp. 831-836.</small>    
    
- Neural text-to-speech with a modeling-by-generation excitation vocoder
[[paper](https://sewplay.github.io/files/papers/2020/interspeech_2116.pdf)]
[[demo](https://sewplay.github.io/demos/mbg_excitnet/)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Min-Jae Hwang, Ryuichi Yamamoto, Jin-Seob Kim, Ohsung Kwon, Jae-Min Kim</small>  
  <small>Proc. INTERSPEECH, 2020, pp. 3570-3574.</small>  
    
- Speaker-adaptive neural vocoders for parametric speech synthesis systems
[[paper](https://sewplay.github.io/files/papers/2020/mmsp_111.pdf)]
[[demo](https://sewplay.github.io/demos/vocoder_adaptation/)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Jinseob Kim, Kyungguen Byun, Hong-Goo Kang</small>  
  <small>Proc. MMSP, 2020, pp. 1-5.</small>  
    
- Parallel WaveGAN: A fast waveform generation model based on generative adversarial networks with multi-resolution spectrogram
[[paper](https://sewplay.github.io/files/papers/2020/icassp_0006194.pdf)]
[[demo](https://r9y9.github.io/demos/projects/icassp2020/)]  
  <small>Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Jae-Min Kim</small>  
  <small>Proc. ICASSP, 2020, pp. 6194-6198.</small>  
    
- Improving LPCNet-based text-to-speech with linear predictions-structured mixture density network
[[paper](https://sewplay.github.io/files/papers/2020/icassp_0007214.pdf)]
[[demo](https://min-jae.github.io/icassp2020/)]  
  <small>Min-Jae Hwang, <strong style="color:orange">Eunwoo Song</strong>, Ryuichi Yamamoto, Frank K. Soong, Hong-Goo Kang</small>  
  <small>Proc. ICASSP, 2020, pp. 7214-7218.</small>  

***
## ~2019
        
- Probability density distillation with generative adversarial networks for high-quality parallel waveform generation
[[paper](https://sewplay.github.io/files/papers/2019/interspeech_pWaveNet.pdf)]
[[demo](https://r9y9.github.io/demos/projects/interspeech2019/)]  
  <small>Ryuichi Yamamoto, <strong style="color:orange">Eunwoo Song</strong>, Jae-Min Kim</small>  
  <small>Proc. INTERSPEECH, 2019, pp. 699-703.</small>  
    
- ExcitNet vocoder: A neural excitation model for parametric speech synthesis systems
[[paper](https://sewplay.github.io/files/papers/2019/eusipco_PID5978469.pdf)]
[[demo](https://sewplay.github.io/demos/excitnet/)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Kyungguen Byun, Hong-Goo Kang</small>  
  <small>Proc. EUSIPCO, 2019, pp. 1179-1183.</small>  
    
- Excitation-by-SampleRNN model for text-to-speech
[[paper](https://sewplay.github.io/files/papers/2019/itccscc.pdf)]  
  <small>Kyungguen Byun, <strong style="color:orange">Eunwoo Song</strong>, Jinseob Kim, Jae-Min Kim, Hong-Goo Kang</small>  
  <small>Proc. ITC-CSCC, 2019, pp. 356-359. </small>  

- Acoustic modeling using adversarially trained variational recurrent neural network for speech synthesis
[[paper](https://sewplay.github.io/files/papers/2018/interspeech_1598.pdf)]  
  <small>Joun Yeop Lee, Sung Jun Cheon, Byoung Jin Choi, Nam Soo Kim, <strong style="color:orange">Eunwoo Song</strong></small>  
  <small>Proc. INTERSPEECH, 2018, pp. 917-921.</small>  
    
- A unified framework for the generation of glottal signals in deep learning-based parametric speech synthesis systems
[[paper](https://sewplay.github.io/files/papers/2018/interspeech_1590.pdf)]  
  <small>Min-Jae Hwang, <strong style="color:orange">Eunwoo Song</strong>, J.-S. Kim, Hong-Goo Kang</small>  
  <small>Proc. INTERSPEECH, 2018, pp. 912-916.</small>  
    
- Modeling-by-generation-structured noise compensation algorithm for glottal vocoding speech synthesis system
[[paper](https://sewplay.github.io/files/papers/2018/icassp_0005669.pdf)]  
  <small>Min-Jae Hwang, <strong style="color:orange">Eunwoo Song</strong>, Hong-Goo Kang</small>  
  <small>Proc. ICASSP, 2018, pp. 5669-5673.</small>  
    
- Perceptual quality and modeling accuracy of excitation parameters in DLSTM-based speech synthesis systems
[[paper](https://sewplay.github.io/files/papers/2017/asru_0000671.pdf)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Frank K. Soong, Hong-Goo Kang</small>  
  <small>Proc. ASRU, 2017, pp. 671–676.</small>  
    
- Effective spectral and excitation modeling techniques for LSTM-RNN-based speech synthesis systems
[[paper](https://sewplay.github.io/files/papers/2017/aslp_08017571.pdf)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Frank K. Soong, Hong-Goo Kang</small>  
  <small>IEEE/ACM Trans. Audio, Speech, and Lang. Process., vol. 25, no. 11, pp. 2152–2161, 2017.</small>   
    
- Improved time-frequency trajectory excitation vocoder for DNN-based speech synthesis
[[paper](https://sewplay.github.io/files/papers/2016/interspeech_IS160230.PDF)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Frank K. Soong, Hong-Goo Kang</small>  
  <small>Proc. INTERSPEECH, 2016, pp. 874–878.</small>  
    
- Multi-class learning algorithm for deep neural network-based statistical parametric speech synthesis
[[paper](https://sewplay.github.io/files/papers/2016/eusipco_1570245860.pdf)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Hong-Goo Kang</small>  
  <small>Proc. EUSIPCO, 2016, pp. 1951–1955.</small>  
    
- Deep neural network-based statistical parametric speech synthesis system using improved time-frequency trajectory excitation model
[[paper](https://sewplay.github.io/files/papers/2015/interspeech_IS150697.PDF)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Hong-Goo Kang</small>  
  <small>Proc. INTERSPEECH, 2015, pp. 874–878.</small>  
    
- A constrained two-layer compression technique for ECG waves
[[paper](https://sewplay.github.io/files/papers/2015/embc_07319791.pdf)]  
  <small>Kyungguen Byun, <strong style="color:orange">Eunwoo Song</strong>, H. Sim, H. Lim, Hong-Goo Kang</small>  
  <small>Proc. EMBC, 2015, pp. 6130–6133.</small>  
    
- Improved time-frequency trajectory excitation modeling for a statistical parametric speech synthesis system
[[paper](https://sewplay.github.io/files/papers/2015/icassp_0004949.pdf)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Young-Sun Joo, Hong-Goo Kang</small>    
  <small>Proc. ICASSP, 2015, pp. 4949–4953.</small>  

- Fixed-point implementation of MPEG-D unified speech and audio coding decoder
[[paper](https://sewplay.github.io/files/papers/2014/dsp_06900810.pdf)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Hong-Goo Kang, Joonil Lee</small>    
  <small>Proc. DSP, 2014, pp. 110–113.</small>  
    
- Speech enhancement for pathological voice using time-frequency trajectory excitation modeling
[[paper](https://sewplay.github.io/files/papers/2013/apsipa_06694125.pdf)]  
  <small><strong style="color:orange">Eunwoo Song</strong>, Jongyoub Ryu, Hong-Goo Kang</small>   
  <small>Proc. APSIPA, 2013, pp. 1–4.</small>    
