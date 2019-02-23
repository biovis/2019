---
layout: page
title: Program BioVis@ISMB
permalink: /program_ismb/
back_title: ISMB
back_url: ismb
---


## BioVis@ISMB 2019 Program

### July 22, 2018


## Invited Speakers

<div class="talk">
    <div class="ttitle">TBA</div>
    <div><span class="tspeaker"><a href="https://petra.isenberg.cc/wiki/pmwiki.php">Petra Isenberg</a></span>, <span> AVIZ/INRIA </span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/petra-isenberg.png" style="width: 250px;" alt="Petra Isenberg"></div>

    <div class="tbioabstract"> 
	
	<div class="tabstract"><b>Abstract:</b> 
	</div>
	
	 <div class="tbio"><b>Bio:</b>
	Petra Isenberg is a research scientist (CR1) at INRIA in the AVIZ research group headed by Jean-Daniel Fekete. Her main research interests are: information visualization, visual analytics, computer-supported cooperative work, and human-computer interaction more generally. 
	</div>
	
	<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
    </div>
</div>

<a name="sheelagh"></a>
<div class="talk">
    <div class="ttitle">TBA</div>
    <div><span class="tspeaker"><a href="https://scholar.google.com/citations?user=jWcQDOsAAAAJ&hl=en">Lindsay Edwards</a></span>, <span> GSK </span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/lindsay-edwards.jpg " style="width: 250px;" alt="S.Carpendale">
    </div>

    <div class="tbioabstract">

        <div class="tabstract"><b>Abstract:</b>
        TBA
        </div>

        <div class="tbio"><b>Bio:</b>
       Lindsay Edwards is a senior leader with expertise in drug discovery, human physiology, data science, machine learning and deep learning. He is currently Head of AI and Machine Learning (AI/ML) for GSK Pharma R&D in the UK and Europe. In particular, his role is focused on identifying opportunities to apply recent advances in machine learning (and particularly deep learning) to existing bottlenecks in the drug discovery pipeline, as well as identifying opportunities to disrupt the existing model entirely. Lindsay Edwards has over ten years’ experience as a scientist and communicator, including eight years in systems biology and machine learning. He continue to collaborate closely with academia, act on a number of advisory boards, speak regularly at international conferences.
        </div>
		<br/><br/><br/><br/>
    </div>
</div>

<br>
<br>

<!--
A full list of accepted papers is available [here]({{site.baseurl}}/papers_ismb_accepted/).
<br>
-->

<!-- WELCOME --->
<div>
    <div class="sumTime2">10:15 - 10:20</div>
    <div>
        <div class="sumContent">BioVis Welcome</div>
          <div class="sumDetail" style="padding-left:120px;"><i>TBA</i></div>
    </div>
</div>

<hr class="style-one">


<!-- SESSION 1 --->

<div>
    <div class="sumTime2"> 10:20 - 12:40</div>
    <div>
        <div class="sumContent">1st Session</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: TBA</i> </div>
    <!-- <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div> -->
</div>

{% for paper in site.data.program2018%}
{% if paper.session == "session1"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      {% if paper.doi != nil %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;">
          <b><!--<a href="{{paper.doi}}">--> [{{paper.type}}] <!--</a>--></b> <b>{{paper.title}}</b></div>
      </div>
      {% else %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"> <b>[{{paper.type}}] {{paper.title}}</b></div>
      </div>
      {% endif %}
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- SESSION 2 -->
<hr class="style-one">

<div>
    <div class="sumTime2">2:00 - 4:00</div>
    <div>
        <div class="sumContent">2nd Session</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: TBA</i> </div>
     <!-- <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div> -->
</div>

{% for paper in site.data.program2018%}
{% if paper.session == "session2"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      {% if paper.doi != nil %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;">
          <b><!--<a href="{{paper.doi}}">--> [{{paper.type}}] <!--</a>--></b> <b>{{paper.title}}</b></div>
      </div>
      {% else %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"> <b>[{{paper.type}}] {{paper.title}}</b></div>
      </div>
      {% endif %}
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- SESSION 3 -->
<hr class="style-one">

<div>
    <div class="sumTime2">4:40 - 5:50</div>
    <div>
        <div class="sumContent">3rd Session</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: TBA</i> </div>
     <!-- <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div> -->
</div>

{% for paper in site.data.program2018%}
{% if paper.session == "session3"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      {% if paper.doi != nil %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;">
          <b><!--<a href="{{paper.doi}}">--> [{{paper.type}}] <!--</a>--></b> <b>{{paper.title}}</b></div>
      </div>
      {% else %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"> <b>[{{paper.type}}] {{paper.title}}</b></div>
      </div>
      {% endif %}
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- CLOSING REMARKS AND POSTER SESSION -->
<hr class="style-one">
<div>
    <div class="sumTime2">5:50 - 6:00</div>
    <div>
        <div class="sumContent">Closing Remarks</div>
          <div class="sumDetail" style="padding-left:120px;"><i>TBA</i></div>
    </div>
</div>

<hr class="style-one">


<div>
    <div class="sumTime2">6:00 - 7:00</div>
    <div>
        <div class="sumContent">Poster Session</div>
       
		<div class="sumDetail" style="padding-left:120px;"><a href="">BioVis posters</a></div>
		
    </div>
</div>

