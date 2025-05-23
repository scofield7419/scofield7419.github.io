---
title: "Hao Fei - Research"
layout: textlay
excerpt: "Hao Fei -- Research"
sitemap: false
permalink: /research/
---

# Research Statement
<div style="margin-top: 35px"></div>


### **`On Multimodal Generalist towards Human-level Capacity and Cognition`**



The emergence of large language models (LLMs) has bestowed unprecedented levels of intelligence upon human society. 
We human beings live in a world where vairous sensory modalities of signals coexist, which means that integrating multimodal capabilities—Multimodal might largely be the most promising path toward the ultimate goal of AGI. 
The human-level AI we envision should be a multimodal generalist, embodying human-like behavioral patterns: not only perceive the semantic content of various modalities and scenarios but also generate and output signals across different modalities to interact with the external world. 
This implies possessing universal modalities and universal task capacities with strong synergistic generalizability. 
To achieve true human-level AI, in addition to perception, it should also encompass complex-reasoning, knowledge-applying, and empathy capabilities, akin to human beings. 
With these beliefs in mind, my research topic is: studying and building unified multimodal generalists towards human-level capacity (_Modality_, _Task_, _Knowledge_) and cognition (_Reasoning_, _Affection_).
{: .text-justify}
I also extensively explore the AI for vertical domains such as medicine, healthcare, clinical psychology, and social studies, by integrating these advanced general-purpose LLM/agent methodologies.





<div style="margin-top: 10px"></div>

My research can be sliced into multiple blocks, with the following image illustrating the overall logical architecture.





<p align="center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/research-state3.png" width="97%"/>
</p>



<div style="margin-top: 20px"></div>



Below each research topic is shown, with representative publications [\[View complete publications\]]({{ site.url }}{{ site.baseurl }}/publications):




<div style="margin-top: 40px"></div>

#### **`▶ Foundation-level: Multimodal LLMs and Generalists`**


<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 1.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;line-height: 19px;">


<span style="font-size: 20px;">&#8226;</span> &nbsp; **Unified Multimodal LLMs** with universal capability of comprehension and generation, with synergistic ability
- [**NExT-GPT**](https://next-gpt.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st unified any-to-any multimodal LLM</em> 
- [**Vitron**](https://vitron-llm.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st unified pixel-level vision LLM for understanding, generating, segmenting, editing of image and video</em> 
- [**OMG-LLaVA**](https://lxtgh.github.io/project/omg_llava/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A pioneering vision LLM for pixel-level, object-level, and image-level understanding and reasoning</em> 
- [**General-Level**](https://generalist.top/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Pioneer the path of MLLM evaluations towards multimodal generalists</em> 


<span style="font-size: 20px;">&#8226;</span> &nbsp;  **MLLMs** for Image/Video/3D/etc
- [**Setok**](https://chocowu.github.io/SeTok-web/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Enhance Vision LLMs with a dynamic semantic-equivalent vision tokenizer</em> 
- [**VPGTrans**](https://vpgtrans.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">For the first time investigate the vision encoder transferability across LLMs</em> 
- [**LL3DA**](https://ll3da.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A pioneering 3D-LLM (3D point cloud)</em> 
- [**Momentor**](https://github.com/DCDmllm/Momentor): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A pioneering Video-LLM for fine-grained comprehension and localization in videos</em> 
- [**Molca**](https://acharkq.github.io/MolCA/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A pioneering Protein LLM</em> 


<span style="font-size: 20px;">&#8226;</span> &nbsp; **Multimodal Agent** for addressing a wide range of downstream applications, with embodied intelligence 
</div>





<div style="margin-top: 40px"></div>

#### **`▶ Capacity-level: Cross-modal Information Comprehension, Generation and Acquisition`**


<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 1.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;line-height: 19px;">

<span style="font-size: 20px;">&#8226;</span> &nbsp; **Multimodal Perception**: low-/high-level audio/speech/image/video/3D modeling, cross-modal captioning/retrieval, scene graph parsing
- [**Finsta**](https://arxiv.org/abs/2406.19255): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Enhance video-language models with a fine-grained structural spatio-temporal alignment learning</em>
- [**GO3D-SG**](https://arxiv.org/abs/2305.11768): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Enhance visual spatial understanding with holistic 3D spatial scene graph</em> 
- [**HostSG**](https://arxiv.org/abs/2308.05081): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Explore a novel holistic spatio-temporal scene graph for video event analysis</em> 
- [**USG**](https://github.com/ChocoWu/SeTok): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A Universal Scene Graph representation across any modalities including images, text, videos, and 3D</em> 




<span style="font-size: 20px;">&#8226;</span> &nbsp; **Multimodal Generation**: text/vision/audio synthesis, text-to-vision generation, joint multimodal generation
- [**JavisDiT**](https://javisdit.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A novel Joint Audio-Video Diffusion Transformer for synchronized audio-video generation</em> 
- [**Any2Caption**](https://sqwu.top/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A any-condition video generation by leveraging MLLMs to interpret diverse inputs into dense, structured captions</em> 
- [**Dysen-VDM**](https://haofei.vip/Dysen-VDM/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Enhance temporal dynamics of text-to-video diffusion from LLMs</em> 
- [**LayoutLLM-T2I**](https://layoutllm-t2i.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Enhance fidelity of text-to-image diffusion with layout from LLMs</em> 
- [**Salad**](https://is.gd/BrQaIH): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Improve text-to-image synthesis under abstract-to-intricate setting with scene graph representation</em> 





<span style="font-size: 20px;">&#8226;</span> &nbsp; **Knowledge Acquisition**: cross-modal information extraction, translation
- [**MUIE**](https://haofei.vip/MUIE/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st benchmark for grounded multimodal universal information extraction</em> 
- [**SpeechEE**](https://speechee.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st benchmark for extracting events from speech</em> 
- [**W2NER**](https://haofei.vip/W2NER-page/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Unify flat, overlapped and discontinuous NER as word-word relation classification</em> 
- [**LasUIE**](https://haofei.vip/LasUIE-page): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Pioneer universal information extraction with a latent adaptive structure-aware generative LM</em> 
- [**UMMT**](https://arxiv.org/abs/2305.12256): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Pioneer the inference-time image-free unsupervised multimodal machine translation with visual scene hallucination mechanism</em> 
</div>








<div style="margin-top: 40px"></div>

#### **`▶ Cognition-level: Multimodal Human-centric Reasoning and Affection`**



<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 1.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;line-height: 19px;">

<span style="font-size: 20px;">&#8226;</span> &nbsp; **Reasoning**: complex reasoning, neuro/symbolic reasoning, cross-modal reasoning
- [**MCoT-Survey**](https://github.com/yaotingwangofficial/Awesome-MCoT): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st systematic survey of MCoT reasoning</em> 
- [**Video-of-Thought**](https://haofei.vip/VoT/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st video chain-of-thought reasoning framework</em> 
- [**SymbCoT**](https://github.com/Aiden0526/SymbCoT): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st fully LLM-based logical reasoning framework based on chain-of-thought</em> 




<span style="font-size: 20px;">&#8226;</span> &nbsp; **Affective Computing**: cross-modal, fine-grained affection and opinion analysis in social media

- [**AvaMERG**](https://github.com/ChocoWu/SeTok): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st Avatar-based Multimodal Empathetic Conversation Benchmark</em> 
- [**PanoSent**](https://panosent.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st cognitive-level benchmark for multimodal conversational aspect-based sentiment analysis</em> 
- [**THOR-ISA**](https://haofei.vip/THOR/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">For the 1st time address implicit sentiment reasoning with chain-of-thought framework</em>
- [**DiaASQ**](https://diaasq-page.pages.dev/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st benchmark for conversational aspect-based sentiment analysis</em> 
- [**UABSA**](https://haofei.vip/UABSA): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A multiplex cascade framework for unified aspect-based sentiment analysis</em> 
</div>








<div style="margin-top: 30px"></div>


---------


Previously I paid my particular focus on [Structure-aware Intelligence Learning (SAIL)]({{ site.url }}{{ site.baseurl }}/sail), and worked on the following topics:


- **NLP** 
  - Text Generation ([**paper**](https://arxiv.org/pdf/2403.15776))
  - Dialogue/Document Analysis ([**paper**](https://arxiv.org/abs/2306.03975))
  - Semantic Parsing ([**XSRL**](https://haofei.vip/XSRL))
  - Syntax Parsing and Grammar Induction ([**XNLP**](https://arxiv.org/abs/2308.01846))


- **Multimodal Learning** 
  - Image/Video Captioning
  - Multimodal Grammar Induction ([**VAT-GI**](https://arxiv.org/abs/2410.03739))


- **Langauge Modeling** 
  - Structure-aware Langauge Modeling ([**StructLM**](https://arxiv.org/abs/2009.07408))
  - KG-empowered Langauge Modeling ([**BioLM**](https://academic.oup.com/bib/article-pdf/22/3/bbaa110/37963251/bbaa110.pdf))


- **Machine Learning** 
  - Prompt Learning/Tuning ([**TKDP**](https://arxiv.org/pdf/2306.03974.pdf))
  - In-context Learning ([**Paper**](https://arxiv.org/pdf/2402.01182))
  - Dual Learning ([**StructDual**](https://haofei.vip/SMDL/))
  - Reinforcement Learning ([**Paper**](https://ieeexplore.ieee.org/document/9352534))



<div style="margin-top: 50px"></div>



