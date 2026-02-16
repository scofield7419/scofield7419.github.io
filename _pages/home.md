---
title: "Hao Fei - Home"
layout: homelay
excerpt: "Hao Fei - Home"
sitemap: false
permalink: /
---

{% for member in site.data.pi %}

<table>
    <tbody>
        <tr>
            <td width="35%">
              <a id="profile" href="{{site.url}}{{site.baseurl}}/"><img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="90%" style="block:inline; margin-left:auto; margin-right:auto; margin-top:20px; margin-bottom:20px;" /></a>
            </td>
            <td>
                <div id="toptitle" style="margin-left: 20px">
                    <h1>{{ member.name }} </h1>
                    <h3>{{ member.info }} </h3>
                    {{ member.location1 }}  <br>
                    {{ member.location2 }}  <br>
                    <div style="margin-top: 15px;margin-left: -80px">
                        <center>
                            {% if member.website %}<a href="{{ member.website }}" target="_blank" ><i class="fa fa-home fa-2x"></i></a> {% endif %}
                            {% if member.email2 %}<a href="mailto:{{ member.email2 }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %}
                            {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %}
                            {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-2x"></i></a> {% endif %}
                            {% if member.dblp %} <a href="{{ member.dblp }}" target="_blank"><i class="ai ai-dblp-square ai-2x"></i></a> {% endif %}
                            {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a> {% endif %}
                            {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a> {% endif %}
                            {% if member.semanticscholar %} <a href="{{ member.semanticscholar }}" target="_blank"><i class="ai ai-semantic-scholar-square ai-2x"></i></a> {% endif %}
                            {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-2x"></i></a> {% endif %}
                            {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-2x"></i></a> {% endif %}
                            {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-2x"></i></a> {% endif %}
                        </center>

                    </div>
                </div>
            </td>
        </tr>
    </tbody>
</table>

{% endfor %}



### Profile
I am a senior postdoctoral researcher at the University of Oxford, jointly working with Prof. [Yarin Gal](https://www.cs.ox.ac.uk/people/yarin.gal/website/) in the OATML Group and Prof. [Chris Holmes](https://www.stats.ox.ac.uk/people/chris-holmes) in the Big Data Institute.
Previously, I was a senior research fellow at National University of Singapore, where I worked with Prof. [Mong-Li Lee](https://www.comp.nus.edu.sg/~leeml/), Prof. [Wynne Hsu](https://www.comp.nus.edu.sg/~whsu/), Prof. [Tat-Seng Chua](https://www.chuatatseng.com/) and Prof. [Shuicheng Yan](https://yanshuicheng.info/).
I also worked as a visiting researcher at Microsoft Research Asia, an associate researcher at Skywork AI Singapore, and SEA AI lab, respectively.
I graduated as Ph.D from Wuhan University.
{: .text-justify}


My research has been published in top-tier ML/NLP/CV/MM venues, e.g., ICML, NeurIPS, ACL, CVPR, AAAI, WWW, SIGIR, IJCAI, EMNLP, ACM-MM, TPAMI, TKDE, TOIS, TNNLS, TASLP. 
I was awarded the World AI Conference Rising Star in 2023. 
My papers were selected as Most Influential Papers by Paper Digest, and ESI Highly Influential Papers and 2024 WAIC Outstanding Paper Award.
I was also the recipient of the 2023 WAIC Rising Star award, and ranked as Top 2% Scientists Worldwide 2024 (Single Year) by Stanford University.
I've regularly served as (Senior) Area Chair or Senior Program Committee of top-tier conferences.
I was the organization committee of WSDM 2022, EMNLP 2023, ACL 2024, ACM MM 2025. 
I serve as the Associate Editor of some journals, including TALLIP and Neurocomputing.
And I am a persistently-invited reviewer for many journals including TPAMI, IJCV, TNNLS, TKDE, TOIS, etc. 
My Ph.D thesis was awarded the Excellent Doctoral Thesis of Chinese Information Processing Society (CIPS). 
I won more than ten honors and awards during Ph.D stage. 
{: .text-justify}


<div style="margin-top: 20px"></div>

### Research



My research interests lie in NLP, CV, and the intersection of both (i.e., Multimodal/Vision-Language Learning).
My long-term goal is to achieve human-level AI centered around multimodal LLMs & generalists.
While previously I worked a lot on the topic of [Structural Modeling of Language&Vision]({{ site.url }}{{ site.baseurl }}/sail), I pay the most recent focus on the unified multimodal generalist towards human-level capacity (Modality, Task, Knowledge) and cognition (Reasoning, Affection), with following key topics and representative works (detailed in [research statement]({{ site.url }}{{ site.baseurl }}/research)):
{: .text-justify}



<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 0.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;">

&#9654;&nbsp; **`Multimodal Foundation Models`**: _Unified multimodal LLMs and generalists._
- [**NExT-GPT**](https://next-gpt.github.io/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st unified any-to-any multimodal LLM</em> 
- [**Vitron**](https://vitron-llm.github.io/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st unified pixel-level vision LLM for understanding, generating, segmenting, editing of image and video</em> 
- [**General-Level**](https://generalist.top/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Pioneer the path of MLLM evaluations towards multimodal generalists</em> 
- [**MLLM tutorial**](https://mllm2024.github.io/CVPR2024/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A pioneering & comprehensive tutorial series for MLLM techniques</em> 
</div>



<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 0.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;">

&#9654;&nbsp; **`Capacity`**: _Comprehension/generation of modalities/tasks, knowledge acquisition._
- [**JavisDiT**](https://javisdit.github.io/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A novel Diffusion Transformer for synchronized audio-video generation</em> 
- [**Any2Caption**](https://sqwu.top/Any2Cap/): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">A SoTA video generation framework from any input conditions</em>
- [**Dysen-VDM**](https://haofei.vip/Dysen-VDM/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Enhance temporal dynamics of text-to-video diffusion from LLMs</em> 
- [**LayoutLLM-T2I**](https://layoutllm-t2i.github.io/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">Enhance fidelity of text-to-image diffusion with layout from LLMs</em> 
- [**MUIE**](https://haofei.vip/MUIE/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st benchmark for grounded multimodal universal information extraction</em> 
</div>





<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 0.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;">

&#9654;&nbsp; **`Cognition`**: _Cross-modal neuro-symbolic reasoning, human-centric affective computing._
- [**MCoT-Survey**](https://github.com/yaotingwangofficial/Awesome-MCoT): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st systematic survey of MCoT reasoning</em> 
- [**Video-of-Thought**](https://haofei.vip/VoT/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st video chain-of-thought reasoning framework</em> 
- [**SymbCoT**](https://github.com/Aiden0526/SymbCoT): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st fully LLM-based logical reasoning framework based on chain-of-thought</em> 
- [**THOR-ISA**](https://haofei.vip/THOR/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st chain-of-thought reasoning framework for implicit sentiment analysis</em> 
- [**PanoSent**](https://panosent.github.io/): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st cognitive-level benchmark for multimodal conversational aspect-based sentiment analysis</em> 
- [**AvaMERG**](https://github.com/ChocoWu/SeTok): &nbsp;&nbsp;&nbsp;<em style="font-size: 15px;color:#C7254E;">The 1st avatar-based multimodal empathetic conversation benchmark</em> 
</div>


I also extensively explore the AI for science, including 1) clinical psychology & social studies, 2) bio-/medicine & healthcare, and 3) material science, by integrating the advanced LLM/agent methodologies.


<div style="margin-top: 20px"></div>

### Advertising


**I am constantly looking for collaborations** on the above topics. 
Remote manner is also supported.
For promising students I will provide sufficient GPUs.
Hit me up, if you are a Ph.D/master/bachelor student and interested in what I am doing now (with potential vacancies for research interns/RAs/visiting).
For students from University of Oxford, I'm particularly looking for collaborations on **world modeling + AI scientist**.
Please describe your research status and attach your resume & statement.
{: .text-justify}

