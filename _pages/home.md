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
              <a id="profile" href="{{ '/' | relative_url }}"><img src="{{ '/images/teampic/' | relative_url }}{{ member.photo }}" class="img-responsive" width="90%" style="block:inline; margin-left:auto; margin-right:auto; margin-top:20px; margin-bottom:20px;" /></a>
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
I am a senior postdoctoral researcher at the CS department and the Big Data Institute in the University of Oxford, working with Prof. [Yarin Gal](https://www.cs.ox.ac.uk/people/yarin.gal/website/).
Previously, I was a senior research fellow at National University of Singapore, where I worked with Prof. [Mong-Li Lee](https://www.comp.nus.edu.sg/~leeml/), Prof. [Wynne Hsu](https://www.comp.nus.edu.sg/~whsu/), Prof. [Tat-Seng Chua](https://www.chuatatseng.com/) and Prof. [Shuicheng Yan](https://yanshuicheng.info/).
I also worked as a visiting researcher at Microsoft Research Asia, an associate researcher at Skywork AI Singapore, and SEA AI lab, respectively.
I graduated as Ph.D from Wuhan University.
{: .text-justify}


My research has been published in top-tier ML/NLP/CV/MM venues, e.g., ICML, NeurIPS, ACL, CVPR, AAAI, WWW, SIGIR, IJCAI, EMNLP, ACM-MM, TPAMI, TKDE, TOIS, TNNLS, TASLP. 
I was awarded the World AI Conference Rising Star in 2023. 
My papers were selected as Most Influential Papers by Paper Digest, and ESI Highly Influential Papers and 2024 WAIC Outstanding Paper Award.
I was also the recipient of the 2023 WAIC Rising Star award, and ranked as Top 2% Scientists Worldwide 2024&2025 by Stanford University.
I've regularly served as (Senior) Area Chair or Senior Program Committee of top-tier conferences.
I was the organization committee of conferences, WSDM, EMNLP, ACL, ACM MM, etc. 
I serve as the Associate Editor of some journals, including TALLIP and Neurocomputing.
And I am a persistently-invited reviewer for many journals including TPAMI, IJCV, TNNLS, TKDE, TOIS, etc. 
My Ph.D thesis was awarded the Excellent Doctoral Thesis of Chinese Information Processing Society (CIPS). 
I won more than ten honors and awards during Ph.D stage. 
{: .text-justify}


<div style="margin-top: 20px"></div>

### Research

My research interests lie in NLP, CV, and the intersection of both (i.e., Multimodal/Vision-Language Learning). 
My long-term goal is to achieve human-level AI centered around multimodal LLMs & generalists.
I pay the main focus on building large foundation multimodal models and bridging physical and mental worlds.
Know me via some latest series of representative works (see [research statement]({{ '/research/' | relative_url }}) for more):
{: .text-justify}


<div class="home-signature-highlight" style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 1.0pt;padding-top: 4.0pt;">
- [**Any-to-Any MLLM (NExT-GPT) series**](https://any2any-mllm.github.io/)
- [**Universal Video Agent (UniVA) series**](https://univa-agent.github.io)
- [**Unified Vision LLMs (UniVision) series**](https://univision-llm.github.io/)
- [**Towards Multimodal Generalist series**](https://path2generalist.github.io/)
- [**Joint Audio-Video (Javis) series**](https://javisverse.github.io/)
- [**Neuro-symbolic Logic Reasoning series**](https://llm-symbol.github.io/)
- [**Cognition-driven Affective Computing (CogAFFC) series**](https://cogaffc.github.io/)
</div>

Recently, I also extensively explore the AI for science, including 1) psychology & social norm studies, 2) bio-/medicine & healthcare & clinics, and 3) material science, by integrating the advanced LLM/agent methodologies.
{: .text-justify}


<div style="margin-top: 20px"></div>

### Advertising


**I am constantly looking for collaborations** on the above topics. 
Remote manner is also supported.
For promising students I will provide sufficient GPUs.
Hit me up, if you are a Ph.D/master/bachelor student and interested in what I am doing now (with potential vacancies for research interns/RAs/visiting).
For students from University of Oxford, I'm particularly looking for collaborations on **world modeling + AI scientist**.
Please describe your research status and attach your resume & statement.
{: .text-justify}
