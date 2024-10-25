# Awesome Natural TTS

- [Awesome Natural TTS](#awesome-natural-tts)
  - [Vocoder](#vocoder)
  - [Emotional TTS](#emotional-tts)
  - [Natural TTS](#natural-tts)
  - [MultiLingual TTS](#multilingual-tts)
  - [Unsupervised TTS](#unsupervised-tts)
  - [Prompt TTS](#prompt-tts)
  - [Misc](#misc)

## Evaluation
- [TTS Arena: Benchmarking Text-to-Speech Models in the Wild](https://huggingface.co/blog/arena-tts)
- [**TTS-Arena**](https://huggingface.co/spaces/TTS-AGI/TTS-Arena) - TTS-AGI 🤗

## Vocoder
- **Accelerating High-Fidelity Waveform Generation via Adversarial Flow
  Matching Optimization**, `arXiv, 2408.08019`, [arxiv](http://arxiv.org/abs/2408.08019v1), [pdf](http://arxiv.org/pdf/2408.08019v1.pdf), cication: [**-1**](None)

	 *Sang-Hoon Lee, Ha-Yeong Choi, Seong-Whan Lee* · ([periodwave.github](https://periodwave.github.io/demo/)) · ([PeriodWave](https://github.com/sh-lee-prml/PeriodWave) - sh-lee-prml) ![Star](https://img.shields.io/github/stars/sh-lee-prml/PeriodWave.svg?style=social&label=Star)
- [**BigVGAN**](https://github.com/NVIDIA/BigVGAN) - NVIDIA ![Star](https://img.shields.io/github/stars/NVIDIA/BigVGAN.svg?style=social&label=Star)

	 *Official PyTorch implementation of BigVGAN (ICLR 2023)*
- **EVA-GAN: Enhanced Various Audio Generation via Scalable Generative
  Adversarial Networks**, `arXiv, 2402.00892`, [arxiv](http://arxiv.org/abs/2402.00892v1), [pdf](http://arxiv.org/pdf/2402.00892v1.pdf), cication: [**-1**](None)

	 *Shijia Liao, Shiyi Lan, Arun George Zachariah* · ([double-blind-eva-gan](https://double-blind-eva-gan.cc/))
- **Multi-Scale Sub-Band Constant-Q Transform Discriminator for
  High-Fidelity Vocoder**, `arXiv, 2311.14957`, [arxiv](http://arxiv.org/abs/2311.14957v1), [pdf](http://arxiv.org/pdf/2311.14957v1.pdf), cication: [**-1**](None)

	 *Yicheng Gu, Xueyao Zhang, Liumeng Xue, Zhizheng Wu* · ([Amphion](https://github.com/open-mmlab/Amphion/blob/main/models/vocoders/gan/discriminator/mssbcqtd.py) - open-mmlab) ![Star](https://img.shields.io/github/stars/open-mmlab/Amphion.svg?style=social&label=Star) · ([vocodexelysium.github](https://vocodexelysium.github.io/MS-SB-CQTD/))

## Emotional TTS
- **EmoPro: A Prompt Selection Strategy for Emotional Expression in LM-based
  Speech Synthesis**, `arXiv, 2409.18512`, [arxiv](http://arxiv.org/abs/2409.18512v1), [pdf](http://arxiv.org/pdf/2409.18512v1.pdf), cication: [**-1**](None)

	 *Haoyu Wang, Chunyu Qiang, Tianrui Wang, Cheng Gong, Qiuyu Liu, Yu Jiang, Xiaobao Wang, Chenyang Wang, Chen Zhang* · ([whyrrrrun.github](https://whyrrrrun.github.io/EmoPro/))
- **EmoKnob: Enhance Voice Cloning with Fine-Grained Emotion Control**, `arXiv, 2410.00316`, [arxiv](http://arxiv.org/abs/2410.00316v1), [pdf](http://arxiv.org/pdf/2410.00316v1.pdf), cication: [**-1**](None)

	 *Haozhe Chen, Run Chen, Julia Hirschberg* · ([huggingface](https://huggingface.co/spaces/tonychenxyz/emo-knob))
- **EmoSphere-TTS: Emotional Style and Intensity Modeling via Spherical
  Emotion Vector for Controllable Emotional Text-to-Speech**, `arXiv, 2406.07803`, [arxiv](http://arxiv.org/abs/2406.07803v1), [pdf](http://arxiv.org/pdf/2406.07803v1.pdf), cication: [**-1**](None)

	 *Deok-Hyeon Cho, Hyung-Seok Oh, Seung-Bin Kim, Sang-Hoon Lee, Seong-Whan Lee*
- **Exploring speech style spaces with language models: Emotional TTS
  without emotion labels**, `arXiv, 2405.11413`, [arxiv](http://arxiv.org/abs/2405.11413v1), [pdf](http://arxiv.org/pdf/2405.11413v1.pdf), cication: [**-1**](None)

	 *Shreeram Suresh Chandra, Zongyang Du, Berrak Sisman*
- **Fine-Grained Quantitative Emotion Editing for Speech Generation**, `arXiv, 2403.02002`, [arxiv](http://arxiv.org/abs/2403.02002v1), [pdf](http://arxiv.org/pdf/2403.02002v1.pdf), cication: [**-1**](None)

	 *Sho Inoue, Kun Zhou, Shuai Wang, Haizhou Li*
- **ED-TTS: Multi-Scale Emotion Modeling using Cross-Domain Emotion
  Diarization for Emotional Speech Synthesis**, `arXiv, 2401.08166`, [arxiv](http://arxiv.org/abs/2401.08166v1), [pdf](http://arxiv.org/pdf/2401.08166v1.pdf), cication: [**-1**](None)

	 *Haobin Tang, Xulong Zhang, Ning Cheng, Jing Xiao, Jianzong Wang*
- [**EmotiVoice**](https://github.com/netease-youdao/EmotiVoice) - netease-youdao ![Star](https://img.shields.io/github/stars/netease-youdao/EmotiVoice.svg?style=social&label=Star)

	 *EmotiVoice 😊: a Multi-Voice and Prompt-Controlled TTS Engine*
- [**emotional-vits**](https://github.com/innnky/emotional-vits) - innnky ![Star](https://img.shields.io/github/stars/innnky/emotional-vits.svg?style=social&label=Star)

	 *无需情感标注的情感可控语音合成模型，基于VITS*

- **ZET-Speech: Zero-shot adaptive Emotion-controllable Text-to-Speech
  Synthesis with Diffusion and Style-based Models**, `arXiv, 2305.13831`, [arxiv](http://arxiv.org/abs/2305.13831v1), [pdf](http://arxiv.org/pdf/2305.13831v1.pdf), cication: [**-1**](None)

	 *Minki Kang, Wooseok Han, Sung Ju Hwang, Eunho Yang*

## Natural TTS
- **SimpleSpeech 2: Towards Simple and Efficient Text-to-Speech with
  Flow-based Scalar Latent Transformer Diffusion Models**, `arXiv, 2408.13893`, [arxiv](http://arxiv.org/abs/2408.13893v2), [pdf](http://arxiv.org/pdf/2408.13893v2.pdf), cication: [**-1**](None)

	 *Dongchao Yang, Rongjie Huang, Yuanyuan Wang, Haohan Guo, Dading Chong, Songxiang Liu, Xixin Wu, Helen Meng* · ([dongchaoyang](https://dongchaoyang.top/SimpleSpeech2\_demo))
- [Fetching Title#l2yg](https://lilyn3125.github.io/flytts/)

	 · ([lilyn3125.github](https://lilyn3125.github.io/flytts/))
- **Enhancing Zero-shot Text-to-Speech Synthesis with Human Feedback**, `arXiv, 2406.00654`, [arxiv](http://arxiv.org/abs/2406.00654v1), [pdf](http://arxiv.org/pdf/2406.00654v1.pdf), cication: [**-1**](None)

	 *Chen Chen, Yuchen Hu, Wen Wu, Helin Wang, Eng Siong Chng, Chao Zhang*
- **BASE TTS: Lessons from building a billion-parameter Text-to-Speech model
  on 100K hours of data**, `arXiv, 2402.08093`, [arxiv](http://arxiv.org/abs/2402.08093v2), [pdf](http://arxiv.org/pdf/2402.08093v2.pdf), cication: [**-1**](None)

	 *Mateusz Łajszczak, Guillermo Cámbara, Yang Li, Fatih Beyhan, Arent van Korlaar, Fan Yang, Arnaud Joly, Álvaro Martín-Cortinas, Ammar Abbas, Adam Michalski* · ([amazon-ltts-paper](https://amazon-ltts-paper.com))

	 · ([jiqizhixin](https://www.jiqizhixin.com/articles/2024-02-16-4))
- **Pheme: Efficient and Conversational Speech Generation**, `arXiv, 2401.02839`, [arxiv](http://arxiv.org/abs/2401.02839v1), [pdf](http://arxiv.org/pdf/2401.02839v1.pdf), cication: [**-1**](None)

	 *Paweł Budzianowski, Taras Sereda, Tomasz Cichy, Ivan Vulić* · ([polyai-ldn.github](https://polyai-ldn.github.io/pheme/)) · ([pheme](https://github.com/PolyAI-LDN/pheme) - PolyAI-LDN) ![Star](https://img.shields.io/github/stars/PolyAI-LDN/pheme.svg?style=social&label=Star) · ([huggingface](https://huggingface.co/spaces/PolyAI/pheme))
- **Incremental FastPitch: Chunk-based High Quality Text to Speech**, `arXiv, 2401.01755`, [arxiv](http://arxiv.org/abs/2401.01755v1), [pdf](http://arxiv.org/pdf/2401.01755v1.pdf), cication: [**-1**](None)

	 *Muyang Du, Chuan Liu, Junjie Lai*
- **Boosting Large Language Model for Speech Synthesis: An Empirical Study**, `arXiv, 2401.00246`, [arxiv](http://arxiv.org/abs/2401.00246v1), [pdf](http://arxiv.org/pdf/2401.00246v1.pdf), cication: [**-1**](None)

	 *Hongkun Hao, Long Zhou, Shujie Liu, Jinyu Li, Shujie Hu, Rui Wang, Furu Wei*
- **Schrodinger Bridges Beat Diffusion Models on Text-to-Speech Synthesis**, `arXiv, 2312.03491`, [arxiv](http://arxiv.org/abs/2312.03491v1), [pdf](http://arxiv.org/pdf/2312.03491v1.pdf), cication: [**-1**](None)

	 *Zehua Chen, Guande He, Kaiwen Zheng, Xu Tan, Jun Zhu* · ([bridge-tts.github](https://bridge-tts.github.io)) · ([Bridge-TTS](https://github.com/thu-ml/Bridge-TTS) - thu-ml) ![Star](https://img.shields.io/github/stars/thu-ml/Bridge-TTS.svg?style=social&label=Star)
- **Schrodinger Bridges Beat Diffusion Models on Text-to-Speech Synthesis**, `arXiv, 2312.03491`, [arxiv](http://arxiv.org/abs/2312.03491v1), [pdf](http://arxiv.org/pdf/2312.03491v1.pdf), cication: [**-1**](None)

	 *Zehua Chen, Guande He, Kaiwen Zheng, Xu Tan, Jun Zhu* · ([bridge-tts.github](https://bridge-tts.github.io/))
- **Encoding Speaker-Specific Latent Speech Feature for Speech Synthesis**, `arXiv, 2311.11745`, [arxiv](http://arxiv.org/abs/2311.11745v1), [pdf](http://arxiv.org/pdf/2311.11745v1.pdf), cication: [**-1**](None)

	 *Jungil Kong, Junmo Lee, Jeongmin Kim, Beomjeong Kim, Jihoon Park, Dohee Kong, Changheon Lee, Sangjin Kim* · ([speechelf.github](https://speechelf.github.io/elf-demo/))
- **Dict-TTS: Learning to Pronounce with Prior Dictionary Knowledge for
  Text-to-Speech**, `arXiv, 2206.02147`, [arxiv](http://arxiv.org/abs/2206.02147v3), [pdf](http://arxiv.org/pdf/2206.02147v3.pdf), cication: [**-1**](None)

	 *Ziyue Jiang, Zhe Su, Zhou Zhao, Qian Yang, Yi Ren, Jinglin Liu, Zhenhui Ye*
- **DPP-TTS: Diversifying prosodic features of speech via determinantal
  point processes**, `arXiv, 2310.14663`, [arxiv](http://arxiv.org/abs/2310.14663v1), [pdf](http://arxiv.org/pdf/2310.14663v1.pdf), cication: [**-1**](None)

	 *Seongho Joo, Hyukhun Koh, Kyomin Jung*
- **Matcha-TTS: A fast TTS architecture with conditional flow matching**, `arXiv, 2309.03199`, [arxiv](http://arxiv.org/abs/2309.03199v2), [pdf](http://arxiv.org/pdf/2309.03199v2.pdf), cication: [**-1**](None)

	 *Shivam Mehta, Ruibo Tu, Jonas Beskow, Éva Székely, Gustav Eje Henter* · ([shivammehta25.github](https://shivammehta25.github.io/Matcha-TTS/))
- **DC CoMix TTS: An End-to-End Expressive TTS with Discrete Code
  Collaborated with Mixer**, `arXiv, 2305.19567`, [arxiv](http://arxiv.org/abs/2305.19567v4), [pdf](http://arxiv.org/pdf/2305.19567v4.pdf), cication: [**-1**](None)

	 *Yerin Choi, Myoung-Wan Koo* · ([dc-comix-tts](https://github.com/lakahaga/dc-comix-tts) - lakahaga) ![Star](https://img.shields.io/github/stars/lakahaga/dc-comix-tts.svg?style=social&label=Star)
- **A Vector Quantized Approach for Text to Speech Synthesis on Real-World
  Spontaneous Speech**, `arXiv, 2302.04215`, [arxiv](http://arxiv.org/abs/2302.04215v1), [pdf](http://arxiv.org/pdf/2302.04215v1.pdf), cication: [**-1**](None)

	 *Li-Wei Chen, Shinji Watanabe, Alexander Rudnicky* · ([MQTTS](https://github.com/b04901014/MQTTS) - b04901014) ![Star](https://img.shields.io/github/stars/b04901014/MQTTS.svg?style=social&label=Star)
- **JETS: Jointly Training FastSpeech2 and HiFi-GAN for End to End Text to
  Speech**, `arXiv, 2203.16852`, [arxiv](http://arxiv.org/abs/2203.16852v2), [pdf](http://arxiv.org/pdf/2203.16852v2.pdf), cication: [**-1**](None)

	 *Dan Lim, Sunghee Jung, Eesung Kim* · ([jets](https://github.com/imdanboy/jets) - imdanboy) ![Star](https://img.shields.io/github/stars/imdanboy/jets.svg?style=social&label=Star) · ([imdanboy.github](https://imdanboy.github.io/interspeech2022/))
- **StyleTTS 2: Towards Human-Level Text-to-Speech through Style Diffusion
  and Adversarial Training with Large Speech Language Models**, `arXiv, 2306.07691`, [arxiv](http://arxiv.org/abs/2306.07691v2), [pdf](http://arxiv.org/pdf/2306.07691v2.pdf), cication: [**-1**](None)

	 *Yinghao Aaron Li, Cong Han, Vinay S. Raghavan, Gavin Mischler, Nima Mesgarani* · ([StyleTTS2](https://github.com/yl4579/StyleTTS2) - yl4579) ![Star](https://img.shields.io/github/stars/yl4579/StyleTTS2.svg?style=social&label=Star) · ([styletts2.github](https://styletts2.github.io/))
- **CLAPSpeech: Learning Prosody from Text Context with Contrastive
  Language-Audio Pre-training**, `arXiv, 2305.10763`, [arxiv](http://arxiv.org/abs/2305.10763v1), [pdf](http://arxiv.org/pdf/2305.10763v1.pdf), cication: [**-1**](None)

	 *Zhenhui Ye, Rongjie Huang, Yi Ren, Ziyue Jiang, Jinglin Liu, Jinzheng He, Xiang Yin, Zhou Zhao*

- [CLAPSpeech](https://clapspeech.github.io/)

- **PortaSpeech: Portable and High-Quality Generative Text-to-Speech**, `arXiv, 2109.15166`, [arxiv](http://arxiv.org/abs/2109.15166v5), [pdf](http://arxiv.org/pdf/2109.15166v5.pdf), cication: [**-1**](None)

	 *Yi Ren, Jinglin Liu, Zhou Zhao*
    - [Abstract | PortaSpeech: Portable and High-Quality Generative Text-to-Speech](https://portaspeech.github.io/)
- [**PortaSpeech**](https://github.com/keonlee9420/PortaSpeech) - keonlee9420 ![Star](https://img.shields.io/github/stars/keonlee9420/PortaSpeech.svg?style=social&label=Star)

	 *PyTorch Implementation of PortaSpeech: Portable and High-Quality Generative Text-to-Speech*
- [**NATSpeech**](https://github.com/NATSpeech/NATSpeech) - NATSpeech ![Star](https://img.shields.io/github/stars/NATSpeech/NATSpeech.svg?style=social&label=Star)

	 *A Non-Autoregressive Text-to-Speech (NAR-TTS) framework, including official PyTorch implementation of PortaSpeech (NeurIPS 2021) and DiffSpeech (AAAI 2022)*

## MultiLingual TTS
- **Extending Multilingual Speech Synthesis to 100+ Languages without
  Transcribed Data**, `arXiv, 2402.18932`, [arxiv](http://arxiv.org/abs/2402.18932v1), [pdf](http://arxiv.org/pdf/2402.18932v1.pdf), cication: [**-1**](None)

	 *Takaaki Saeki, Gary Wang, Nobuyuki Morioka, Isaac Elias, Kyle Kastner, Andrew Rosenberg, Bhuvana Ramabhadran, Heiga Zen, Françoise Beaufays, Hadar Shemtov*
- **XPhoneBERT: A Pre-trained Multilingual Model for Phoneme Representations
  for Text-to-Speech**, `arXiv, 2305.19709`, [arxiv](http://arxiv.org/abs/2305.19709v1), [pdf](http://arxiv.org/pdf/2305.19709v1.pdf), cication: [**-1**](None)

	 *Linh The Nguyen, Thinh Pham, Dat Quoc Nguyen*

    - [GitHub - VinAIResearch/XPhoneBERT: XPhoneBERT: A Pre-trained Multilingual Model for Phoneme Representations for Text-to-Speech (INTERSPEECH 2023)](https://github.com/vinairesearch/xphonebert)
	- trained using the RoBERTa pre-training approach on 330M phoneme-level sentences from nearly 100 languages and locales.

- **Scaling Speech Technology to 1,000+ Languages**, `arXiv, 2305.13516`, [arxiv](http://arxiv.org/abs/2305.13516v1), [pdf](http://arxiv.org/pdf/2305.13516v1.pdf), cication: [**-1**](None)

	 *Vineel Pratap, Andros Tjandra, Bowen Shi, Paden Tomasello, Arun Babu, Sayani Kundu, Ali Elkahky, Zhaoheng Ni, Apoorv Vyas, Maryam Fazel-Zarandi*
    - [Scaling Speech Technology to 1,000+ Languages](https://scontent-hkg4-2.xx.fbcdn.net/v/t39.8562-6/348836647_265923086001014_6878005808275791319_n.pdf?_nc_cat=104&ccb=1-7&_nc_sid=ae5e01&_nc_ohc=5exJiCqt0Y4AX-gUgT_&_nc_ht=scontent-hkg4-2.xx&oh=00_AfA82VNjMcz4sukDglzRUxbHcDa1eHwx8a3iRZ7sE-Rrnw&oe=6471ACCF)
    - [Introducing speech-to-text, text-to-speech, and more for 1,100+ languages](https://ai.facebook.com/blog/multilingual-model-speech-recognition/)
    - [fairseq/examples/mms at main · facebookresearch/fairseq · GitHub](https://github.com/facebookresearch/fairseq/tree/main/examples/mms)
    - [规模性能双杀OpenAI，Meta语音达LLaMA级里程碑！开源MMS模型可识别1100+语言](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652332307&idx=2&sn=1b511ce129b3629be3ee5ea9d75f2563)

- **Voicebox: Text-Guided Multilingual Universal Speech Generation at Scale**, `arXiv, 2306.15687`, [arxiv](http://arxiv.org/abs/2306.15687v2), [pdf](http://arxiv.org/pdf/2306.15687v2.pdf), cication: [**-1**](None)

	 *Matthew Le, Apoorv Vyas, Bowen Shi, Brian Karrer, Leda Sari, Rashel Moritz, Mary Williamson, Vimal Manohar, Yossi Adi, Jay Mahadeokar*
- [UMM-TTS: Unified Multilingual Multispeaker Text to Speech Synthesis in Low Resource Setting](https://paper2438.github.io/tts/)
- **Adapting TTS models For New Speakers using Transfer Learning**, `arXiv, 2110.05798`, [arxiv](http://arxiv.org/abs/2110.05798v2), [pdf](http://arxiv.org/pdf/2110.05798v2.pdf), cication: [**-1**](None)

	 *Paarth Neekhara, Jason Li, Boris Ginsburg*

- **Better speech synthesis through scaling**, `arXiv, 2305.07243`, [arxiv](http://arxiv.org/abs/2305.07243v2), [pdf](http://arxiv.org/pdf/2305.07243v2.pdf), cication: [**-1**](None)

	 *James Betker*
    - [TorToiSe - These words were never spoken.](https://nonint.com/static/tortoise_v2_examples.html)
    - [GitHub - neonbjb/tortoise-tts: A multi-voice TTS system trained with an emphasis on quality](https://github.com/neonbjb/tortoise-tts)


## Unsupervised TTS

- [Bag of Tricks for Unsupervised Text-to-Speech | OpenReview](https://openreview.net/forum?id=SbR9mpTuBn)
    - [Bag of Tricks for Unsupervised TTS](https://unsupertts-tricks.github.io/)
    - [https://openreview.net/pdf?id=SbR9mpTuBn](https://openreview.net/pdf?id=SbR9mpTuBn)

## Prompt TTS

- **PromptTTS++: Controlling Speaker Identity in Prompt-Based Text-to-Speech
  Using Natural Language Descriptions**, `arXiv, 2309.08140`, [arxiv](http://arxiv.org/abs/2309.08140v2), [pdf](http://arxiv.org/pdf/2309.08140v2.pdf), cication: [**-1**](None)

	 *Reo Shimizu, Ryuichi Yamamoto, Masaya Kawamura, Yuma Shirahata, Hironori Doi, Tatsuya Komatsu, Kentaro Tachibana*

- **InstructTTS: Modelling Expressive TTS in Discrete Latent Space with
  Natural Language Style Prompt**, `arXiv, 2301.13662`, [arxiv](http://arxiv.org/abs/2301.13662v2), [pdf](http://arxiv.org/pdf/2301.13662v2.pdf), cication: [**-1**](None)

	 *Dongchao Yang, Songxiang Liu, Rongjie Huang, Chao Weng, Helen Meng*
    - [InstructTTS | The deme page of InstructTTS](http://dongchaoyang.top/InstructTTS/)

- **PromptTTS: Controllable Text-to-Speech with Text Descriptions**, `arXiv, 2211.12171`, [arxiv](http://arxiv.org/abs/2211.12171v1), [pdf](http://arxiv.org/pdf/2211.12171v1.pdf), cication: [**-1**](None)

	 *Zhifang Guo, Yichong Leng, Yihan Wu, Sheng Zhao, Xu Tan*
    - [PromptTTS: controllable text-to-speech with text descriptions - Speech Research](https://speechresearch.github.io/prompttts/#promptspeech)

## Efficient TTS
- **Zero-Shot Text-to-Speech from Continuous Text Streams**, `arXiv, 2410.00767`, [arxiv](http://arxiv.org/abs/2410.00767v1), [pdf](http://arxiv.org/pdf/2410.00767v1.pdf), cication: [**-1**](None)

	 *Trung Dang, David Aponte, Dung Tran, Tianyi Chen, Kazuhito Koishida*
- **Single-stage TTS with Masked Audio Token Modeling and Semantic Knowledge
  Distillation**, `arXiv, 2409.11003`, [arxiv](http://arxiv.org/abs/2409.11003v1), [pdf](http://arxiv.org/pdf/2409.11003v1.pdf), cication: [**-1**](None)

	 *Gerard I. Gállego, Roy Fejgin, Chunghsin Yeh, Xiaoyu Liu, Gautam Bhattacharya*
- **SimpleSpeech: Towards Simple and Efficient Text-to-Speech with Scalar
  Latent Transformer Diffusion Models**, `arXiv, 2406.02328`, [arxiv](http://arxiv.org/abs/2406.02328v2), [pdf](http://arxiv.org/pdf/2406.02328v2.pdf), cication: [**-1**](None)

	 *Dongchao Yang, Dingdong Wang, Haohan Guo, Xueyuan Chen, Xixin Wu, Helen Meng*
- **Speak While You Think: Streaming Speech Synthesis During Text Generation**, `icassp 2024-2024 ieee international conference on acoustics …, 2024`, [arxiv](http://arxiv.org/abs/2309.11210v1), [pdf](http://arxiv.org/pdf/2309.11210v1.pdf), cication: [**1**](https://scholar.google.com/scholar?cites=2989454037175742919&as_sdt=2005&sciodt=0,5&hl=en&oe=ASCII)

	 *Avihu Dekel, Slava Shechtman, Raul Fernandez, David Haws, Zvi Kons, Ron Hoory*
- **CM-TTS: Enhancing Real Time Text-to-Speech Synthesis Efficiency through
  Weighted Samplers and Consistency Models**, `arXiv, 2404.00569`, [arxiv](http://arxiv.org/abs/2404.00569v1), [pdf](http://arxiv.org/pdf/2404.00569v1.pdf), cication: [**-1**](None)

	 *Xiang Li, Fan Bu, Ambuj Mehrish, Yingting Li, Jiale Han, Bo Cheng, Soujanya Poria*

	 · ([CM-TTS](https://github.com/XiangLi2022/CM-TTS) - XiangLi2022) ![Star](https://img.shields.io/github/stars/XiangLi2022/CM-TTS.svg?style=social&label=Star)

## Misc
- **Investigating Neural Audio Codecs for Speech Language Model-Based Speech
  Generation**, `arXiv, 2409.04016`, [arxiv](http://arxiv.org/abs/2409.04016v1), [pdf](http://arxiv.org/pdf/2409.04016v1.pdf), cication: [**-1**](None)

	 *Jiaqi Li, Dongmei Wang, Xiaofei Wang, Yao Qian, Long Zhou, Shujie Liu, Midia Yousefi, Canrun Li, Chung-Hsien Tsai, Zhen Xiao*
- **Codec Does Matter: Exploring the Semantic Shortcoming of Codec for Audio
  Language Model**, `arXiv, 2408.17175`, [arxiv](http://arxiv.org/abs/2408.17175v1), [pdf](http://arxiv.org/pdf/2408.17175v1.pdf), cication: [**-1**](None)

	 *Zhen Ye, Peiwen Sun, Jiahe Lei, Hongzhan Lin, Xu Tan, Zheqi Dai, Qiuqiang Kong, Jianyi Chen, Jiahao Pan, Qifeng Liu* · ([xcodec](https://github.com/zhenye234/xcodec) - zhenye234) ![Star](https://img.shields.io/github/stars/zhenye234/xcodec.svg?style=social&label=Star)
- **Enabling Beam Search for Language Model-Based Text-to-Speech Synthesis**, `arXiv, 2408.16373`, [arxiv](http://arxiv.org/abs/2408.16373v1), [pdf](http://arxiv.org/pdf/2408.16373v1.pdf), cication: [**-1**](None)

	 *Zehai Tu, Guangyan Zhang, Yiting Lu, Adaeze Adigwe, Simon King, Yiwen Guo* · ([tuzehai.github](https://tuzehai.github.io/trad-bs.github.io/))
- [CALL TO BUILD OPEN MULTI-MODAL MODELS FOR PERSONAL ASSISTANTS](https://laion.ai/notes/open-gpt-4-o/)
- **Expressive TTS Driven by Natural Language Prompts Using Few Human
  Annotations**, `arXiv, 2311.01260`, [arxiv](http://arxiv.org/abs/2311.01260v1), [pdf](http://arxiv.org/pdf/2311.01260v1.pdf), cication: [**-1**](None)

	 *Hanglei Zhang, Yiwei Guo, Sen Liu, Xie Chen, Kai Yu*
- **E3 TTS: Easy End-to-End Diffusion-based Text to Speech**, `arXiv, 2311.00945`, [arxiv](http://arxiv.org/abs/2311.00945v1), [pdf](http://arxiv.org/pdf/2311.00945v1.pdf), cication: [**-1**](None)

	 *Yuan Gao, Nobuyuki Morioka, Yu Zhang, Nanxin Chen*
- [**edge-tts**](https://github.com/rany2/edge-tts) - rany2 ![Star](https://img.shields.io/github/stars/rany2/edge-tts.svg?style=social&label=Star)

	 *Use Microsoft Edge's online text-to-speech service from Python WITHOUT needing Microsoft Edge or Windows or an API key*
- **VoiceLDM: Text-to-Speech with Environmental Context**, `arXiv, 2309.13664`, [arxiv](http://arxiv.org/abs/2309.13664v1), [pdf](http://arxiv.org/pdf/2309.13664v1.pdf), cication: [**-1**](None)

	 *Yeonghyeon Lee, Inmo Yeon, Juhan Nam, Joon Son Chung* · ([voiceldm.github](https://voiceldm.github.io/))
- **Large-Scale Automatic Audiobook Creation**, `arXiv, 2309.03926`, [arxiv](http://arxiv.org/abs/2309.03926v1), [pdf](http://arxiv.org/pdf/2309.03926v1.pdf), cication: [**-1**](None)

	 *Brendan Walsh, Mark Hamilton, Greg Newby, Xi Wang, Serena Ruan, Sheng Zhao, Lei He, Shaofei Zhang, Eric Dettinger, William T. Freeman*
- **ComedicSpeech: Text To Speech For Stand-up Comedies in Low-Resource
  Scenarios**, `arXiv, 2305.12200`, [arxiv](http://arxiv.org/abs/2305.12200v1), [pdf](http://arxiv.org/pdf/2305.12200v1.pdf), cication: [**-1**](None)

	 *Yuyue Wang, Huan Xiao, Yihan Wu, Ruihua Song*
- **Controllable Speaking Styles Using a Large Language Model**, `arXiv, 2305.10321`, [arxiv](http://arxiv.org/abs/2305.10321v2), [pdf](http://arxiv.org/pdf/2305.10321v2.pdf), cication: [**-1**](None)

	 *Atli Thor Sigurgeirsson, Simon King*

## OpenTTS
- [**tts-generation-webui**](https://github.com/rsxdalv/tts-generation-webui) - rsxdalv ![Star](https://img.shields.io/github/stars/rsxdalv/tts-generation-webui.svg?style=social&label=Star)

	 *TTS Generation Web UI (Bark, MusicGen + AudioGen, Tortoise, RVC, Vocos, Demucs, SeamlessM4T, MAGNet, StyleTTS2, MMS)*
- [**Awesome-ChatTTS**](https://github.com/libukai/Awesome-ChatTTS) - libukai ![Star](https://img.shields.io/github/stars/libukai/Awesome-ChatTTS.svg?style=social&label=Star)

	 *官方推荐的 ChatTTS 最佳入门指南，整理和汇总了常见问题和相关资源*
- [**IMS-Toucan**](https://github.com/DigitalPhonetics/IMS-Toucan) - DigitalPhonetics ![Star](https://img.shields.io/github/stars/DigitalPhonetics/IMS-Toucan.svg?style=social&label=Star)

	 *Multilingual and Controllable Text-to-Speech Toolkit of the Speech and Language Technologies Group at the University of Stuttgart.*
- [**ChatTTS**](https://github.com/2noise/ChatTTS) - 2noise ![Star](https://img.shields.io/github/stars/2noise/ChatTTS.svg?style=social&label=Star)

	 *TTS*
	 - [GitHub - jianchang512/ChatTTS-ui: 一个简单的本地网页界面，直接使用ChatTTS将文字合成为语音，同时支持对外提供API接口。](https://github.com/jianchang512/ChatTTS-ui)
- [**MassTTS**](https://github.com/anyvoiceai/MassTTS) - anyvoiceai ![Star](https://img.shields.io/github/stars/anyvoiceai/MassTTS.svg?style=social&label=Star)

	 *a TTS demo for training new characters.*
- [**parler-tts**](https://github.com/huggingface/parler-tts?tab=readme-ov-file) - huggingface ![Star](https://img.shields.io/github/stars/huggingface/parler-tts.svg?style=social&label=Star)

	 *Inference and training library for high-quality TTS models.*

	 · ([huggingface](https://huggingface.co/parler-tts/parler_tts_mini_v0.1))
	 - [parler-tts/parler-tts-mini-expresso · Hugging Face](https://huggingface.co/parler-tts/parler-tts-mini-expresso)
- [**StableTTS**](https://github.com/KdaiP/StableTTS) - KdaiP ![Star](https://img.shields.io/github/stars/KdaiP/StableTTS.svg?style=social&label=Star)

	 *Next-generation TTS model using flow-matching and DiT, inspired by Stable Diffusion 3*
- [**MeloTTS**](https://github.com/myshell-ai/MeloTTS) - myshell-ai ![Star](https://img.shields.io/github/stars/myshell-ai/MeloTTS.svg?style=social&label=Star)

	 *High-quality multi-lingual text-to-speech library by MyShell.ai. Support English, Spanish, French, Chinese, Japanese and Korean.*
- [**piper**](https://github.com/rhasspy/piper) - rhasspy ![Star](https://img.shields.io/github/stars/rhasspy/piper.svg?style=social&label=Star)

	 *A fast, local neural text to speech system*
- [**xVA-Synth**](https://github.com/DanRuta/xVA-Synth) - DanRuta ![Star](https://img.shields.io/github/stars/DanRuta/xVA-Synth.svg?style=social&label=Star)

	 *Machine learning based speech synthesis Electron app, with voices from specific characters from video games* · ([huggingface](https://huggingface.co/spaces/Pendrokar/xVASynth))