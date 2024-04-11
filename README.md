##  PML4LRS @ <a target='_blank' href='https://iclr.cc/'> ICLR 2024</a>

{% if jekyll.environment  == "production" %}
        {% assign basepath = "/iclr2024" %}
        {%else%}
        {% assign basepath = "" %}
        {% endif %}

<!-- ## Practical ML for Low Resource Settings -->

### Practical ML for Low Resource Settings

<!--<div class="update">
        ICLR 2022 will be a fully virtual conference. While the details for remote presentation are being finalized, authors of accepted papers/posters are encouraged to view the <a href="https://iclr.cc/Conferences/2022/virtual"> ICLR virtual presentation guidelines here </a> .-->

       
The constant progress being made in machine learning needs to extend across borders if we are to democratize ML in developing countries. Adapting state-of-the-art (SOTA) methods to resource constrained environments such as developing countries can be challenging in practice. Recent breakthroughs in natural language processing and generative image models, for instance, rely on increasingly complex and large models that are pre-trained on large unlabeled datasets. In most developing countries, resource constraints make the adoption of these breakthroughs challenges. Methods such as transfer learning will not fully solve the problem either due to bias in pre-training datasets that do not reflect environments in developing countries or the cost of fine-tuning larger models. This gap in resources between SOTA requirements and developing country capacities hinders a democratic development of machine learning methods and infrastructure. 


Practical Machine Learning for Low Resource Settings (PML4LRS) workshop is a full-day event that has been running regularly for the past 3 years at ICLR (past events include <a href="https://pml4dc.github.io/iclr2020/" target="_blank">PML4DC 2020</a>, <a href="https://pml4dc.github.io/iclr2021/" target="_blank"> PML4DC 2021</a>, <a href="https://pml4dc.github.io/iclr2022/" target="_blank"> PML4DC 2022</a> and <a href="https://pml4dc.github.io/iclr2023/" target="_blank"> PML4DC 2023</a>). PML4LRS aims to foster collaborations and build a cross-domain community by featuring invited talks, panel discussions, contributed presentations (oral and poster) and round-table mixers. 


The main goal of PML4LRS is to bring together researchers and practitioners (from academia, industry and government agencies) to reflect on aspects of designing, implementing, deploying and monitoring machine learning (ML) solutions that are typical in low resource environments across multiple sectors, such as healthcare, finance, agriculture, or education. Specifically, we encourage contributons that highlight issues related to:
* Advances in algorithms and methods tailored for problems related with data-scarcity, imbalanced representations and limited computational resource
*  Industry practices to scale-up ML solutions in low resource settings while balancing performance and latency tradeoffs
* Societal and policy impacts of ML solutions in developing countries obtained via pilot studies, qualitative research, and human-in-the-loop settings.


## Keynote Speakers
<div>

 <div class="iblock headshotname"> Dalton D Lunga </div>
 <p><a href="https://www.ornl.gov/staff-profile/dalton-d-lunga" class="headshotaffiliation" target="_blank">ORNL</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/Dalton.jpg" class="headshot" alt="picture of Dalton D Lunga"></p>
  <p align='justify'>

          Dalton is a group leader for GeoAI and a senior R&D staff scientist at ORNL.  He is also an Associate Editor for Geoscience and Remote Sensing Letters. He is an interdisciplinary scientist with expertise in artificial intelligence, computer vision, high-performance computing and remote sensing. Dalton leads multidisciplinary teams and projects focused on developing novel methods at the intersection of AI, computer vision, and geography toward the built and physical environment mapping using earth observation data. His research is impacting the generation of accurate population estimates and information about urban growth and decline, informing disaster response, identifying at-risk areas to support national security application challenges. Prior to ORNL, Dalton was a Team Lead and Senior Research Scientist at the Council for Scientific and Industrial Research, South Africa where he established and led a Data Science for Decision Impact team. He received his Ph.D in Electrical and Computer Engineering from Purdue University, West Lafayette.

  </p>
 </div>
<!--
 <br><br>

  <div class="iblock headshotname"> Aditya Grover </div>
 <p><a href="https://aditya-grover.github.io/" target="_blank">UCLA </a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/aditya.jpeg" class="headshot" alt="picture of Aditya"></p>
  <p align='justify'>
Aditya Grover is assistant professor of computer science at UCLA. He lead the Machine Intelligence (MINT) group, where we develop AI systems that can interact and reason with limited supervision. His current research is at the intersection of generative models and sequential decision making. On the applied side, He actively ground this research for developing systems and software for data-driven scientific discovery, particularly in climate and sustainability domains via the ML4Climate initiative.

Before joining UCLA, He spent a gap year as a research scientist in the Core ML team at FAIR, Meta. He completed His postdoctoral training at UC Berkeley (advisor: Pieter Abbeel), PhD at Stanford University (advisor: Stefano Ermon) and bachelors at IIT Delhi (co-advisors: Mausam, Parag Singla), all in computer science. During his PhD, He spent wonderful summers interning at Google Brain, Microsoft Research, and OpenAI.
  </p>
 </div>

 <br><br>
 <div class="iblock headshotname"> Georgina Curto Rex </div>
  <p><a href="https://www.georginacurto.com/" target="_blank">ND Technology Ethics Center, University of Notre Dame</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/georgina.jpeg" class="headshot" alt="picture of georgina"></p>
  <p align ='justify'>
  Georgina is a Postdoctoral Fellow at the ND Technology Ethics Center (University of Notre Dame) and incoming faculty at the Lucy Family Institute for Data and Society.  She has the honor to Chair the IJCAI Symposia in the Global South and Co-Chair the AI & Social Good Special Track at the International Joint Conference on Artificial Intelligence (IJCAI'23). 

Focusing on issues of poverty mitigation, fairness and inclusion, she works on the design of AI socio-technical systems that provide new insights to counteract inequality, and more broadly, to advance interdisciplinary research towards the achievement of the UN Sustainable Development Goals (SDGs). 

She conduct research that contributes to the AI state of the art  in Natural Language Processing, Agent-Based Modeling, Social Networks and Machine Learning, with the ultimate goal to offer insights for innovative interventions to local and global challenges. Some of these lines of research were awarded Best AI for Good Project at the 31st International Joint Conference on Artificial Intelligence (IJCAI'22) and Outstanding Paper at the ACL (Association of Computational Linguistics) within the 7th Workshop on Online Abuse and Harms. 

  </p>
 </div>

  <!--
  <br><br>

 <div class="iblock headshotname"> Joshua Blumenstock </div>
  <p><a href="https://www.jblumenstock.com/" class="headshotaffiliation" target="_blank">University of California, Berkeley</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/jos.jpg" class="headshot" alt="picture of Joshua"></p>
  <p align ='justify'>
   Joshua Blumenstock is a Chancellor’s Associate Professor at the U.C. Berkeley School of Information and the Goldman School of Public Policy. He is the Co-director of the Global Policy Lab and the Center for Effective Global Action. Blumenstock does research at the intersection of machine learning and empirical economics, and focuses on applications of novel data to global poverty and inequality. He has a Ph.D. in Information Science and a M.A. in Economics from U.C. Berkeley, and Bachelor’s degrees in Computer Science and Physics from Wesleyan University. He is a recipient of awards including the NSF CAREER award, the Intel Faculty Early Career Honor, and the U.C. Berkeley Chancellor's Award for Public Service. His work has appeared in general interest journals including Science, Nature, and Proceedings of the National Academy of Sciences,as well as top economics journals (e.g., the American Economic Review) and computer science conferences (e.g., ICML, KDD, AAAI, WWW, CHI).
  </p>
 </div>
 
   <br><br>

 <div class="iblock headshotname">Rose Nakasi </div>
  <p><a href="https://www.jblumenstock.com/" class="headshotaffiliation" target="_blank">Researcher, AI LAB, Makerere University</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/Nakasi.jpg" class="headshot" alt="picture of Joshua"></p>
  <p align ='justify'>
  Rose Nakasi is a PhD Researcher of Computer Science at AI and Data Science Lab, Makerere University in Uganda as well as Chair for Topic Group AI-based detection of Malaria (TG-Malaria) at the ITU-Focus Group AI for Health (FGAI4H). Her research interests are in Artificial Intelligence and Data Science and particularly in the use of these for developing improved automated tools and techniques for diagnosis and prediction of Malaria in low resourced but highly endemic Countries.
  </p>
 </div>
  </div>

 



## Panelists
<div class="panelists">
<div>
  <div class="iblock headshotbox"> 
  <img src="{{basepath}}/images/speakers/jade.jpeg" class="headshot"  alt="picture of Jade">
  </div>
  <div class="iblock headshotname">Jade Abbott</div>
  <p><a href="https://www.jabbott.io" class="headshotaffiliation" target="_blank">lelapa.ai</a></p>
</div>


<div>
  <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/teka.jpeg" class="headshot"  alt="picture of teka"></p>
  </div>
  <div class="iblock headshotname">Asmelash Teka Hadgu </div>
  <p><a href="https://twitter.com/asmelashteka" class="headshotaffiliation" target="_blank">Lesan</a></p>
</div>
        

</div>

<div class="panelists">

<div>
  <div class="iblock headshotbox"> 
  <img src="{{basepath}}/images/speakers/paul.jpeg" class="headshot"  alt="picture of paul">
  </div>
  <div class="iblock headshotname">Paul Azunre</div>
  <p><a href="https://www.azunre.com/" class="headshotaffiliation" target="_blank">Ghana NLP</a></p>
</div>
        
<div>
   <div class="iblock headshotbox"> 
   <p><img src="{{basepath}}/images/speakers/timit.jpeg" class="headshot"  alt="picture of Timnit"></p>
   </div>
   <div class="iblock headshotname">Timnit Gebru</div>
   <p><a href="https://www.dair-institute.org/about" class="headshotaffiliation" target="_blank">DAIR</a></p>
 </div>
</div>
-->

