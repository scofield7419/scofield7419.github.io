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
                            {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %}
                            {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-2x"></i></a> {% endif %}
                            {% if member.dblp %} <a href="{{ member.dblp }}" target="_blank"><i class="ai ai-dblp-square ai-2x"></i></a> {% endif %}
                            {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a> {% endif %}
                            {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a> {% endif %}
                            {% if member.semanticscholar %} <a href="{{ member.semanticscholar }}" target="_blank"><i class="ai ai-semantic-scholar-square ai-2x"></i></a> {% endif %}
                            {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-2x"></i></a> {% endif %}
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
I am currently a postdoc research fellow of National University of Singapore, working with Prof. [Tat-Seng Chua](https://www.chuatatseng.com/) at [NExT++ research center](https://www.nextcenter.org/team) and Prof. [Wynne Hsu](https://www.comp.nus.edu.sg/~whsu/) at [Institute of Data Science](https://ids.nus.edu.sg/).
I am also an associate researcher at [Kunlun 2050 Research Lab](#) Singapore, working with Prof. [Shuicheng Yan](https://yanshuicheng.info/) (previously an associate researcher at [SEA AI lab](https://sail.sea.com/)).
Prior to that, I received my Ph.D degree at Wuhan University, advised by Prof. [Donghong Ji](https://scholar.google.com/citations?user=2Q-7u3AAAAAJ); 
and received B.E degree from Xidian University.
I was an intern at Baidu Inc. when I was in my B.E stage.
{: .text-justify}


<div style="margin-top: 20px"></div>

### Research Briefing
My research direction lies in the intersection of Natural Language Processing (NLP) and Computer Vision (CV), i.e., Vision-Language Learning,
with broad-covering interests, such as **Large Language Model**, **Information Extraction**, **Affective Computing**, **Syntax/Semantic Parsing**, 
**Text-Image/Video/Audio/3D Modeling**.
I am apt to construct learning models, with the fundamental goal of building systems capable of human-level understanding of the world. 
My ongoing research focuses on the particular angle of **`Structure-aware Intelligence Learning` (SAIL)**, 
which aims at enhancing the semantics understanding of varied modalities with the intrinsic data structure modeling.
The __SAIL__ idea works effectively for the deep learning based AI, and also holds for the current large language models (LLMs), 
which will ultimately help achieve AGI of universal modalities (world modeling).
See my [research statement]({{ site.url }}{{ site.baseurl }}/research) for more details.
Also, I believe so much that the key to realizing human-level AGI lies in two fundamental aspects simultaneously,
**A. `human-level complex reasoning ability`** and **B. `mastering of the world knowledge`**, with one not doing without the other.
{: .text-justify}



My research has been published in top-tier ML/NLP/DM venues, including, ICML, NeurIPS, ACL, AAAI, WWW, SIGIR, IJCAI, EMNLP, COLING, TOIS, TNNLS, TASLP, etc.
My Ph.D thesis was awarded the Excellent Doctoral Thesis of Chinese Information Processing Society (CIPS).
I won more than ten honors and awards when I was in Ph.D stage.
I've served as (Senior) Area Chair or Senior Program Committee of top-tier conferences, such as ACL, IJCAI, EMNLP, WSDM, ARR. Also, I am the persistently-invited reviewer for prestigious journals including TPAMI, TNNLS, TKDE, TOIS, TAFFC and TASLP, etc.
I am (was) the organization committee of WSDM 2022 (Volunteer Chair), NSSDM 2023 (Program Chair), EMNLP 2023 (Workshop Chair). 
{: .text-justify}



<div style="margin-top: 20px"></div>

### Advertising

**I am constantly looking for collaborations**, especially on the topics mentioned above. 
Remote manner is also supported.
For promising students I will provide sufficient GPUs.
Hit me up, if you are a Ph.D/master/bachelor student and interested in what I am doing now.
When you are from Chinese universities, there are also vacancies for research interns (e.g., self-/CSC-funded joint PhD project).
Please describe your research status and attach your resume.
{: .text-justify}

