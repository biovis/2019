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
    <!--<div class="ttitle">TBA</div>-->
    <div><span class="tspeaker"><a href="https://petra.isenberg.cc/wiki/pmwiki.php">Petra Isenberg</a></span>, <span> AVIZ/INRIA </span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/petra-isenberg.png" style="width: 250px;" alt="Petra Isenberg"></div>

    <div class="tbioabstract"> 
	
	<!--<div class="tabstract"><b>Abstract:</b>TBA</div>-->
	
	 <div class="tbio"><b>Bio:</b>
	Petra Isenberg is a research scientist (CR) at Inria, Saclay, France in the Aviz research group. Prior to joining Inria, she received her PhD from the University of Calgary in 2010 working with Sheelagh Carpendale on collaborative information visualization. Petra also holds a Diplom-engineer degree in Computational Visualistics from the University of Magdeburg. Her main research areas are information visualization and visual analytics with a focus on off-desktop data analysis, interaction, and evaluation. She is particularly interested in exploring how people can most effectively work together when analyzing large and complex data sets on novel display technology such as small touch-screens, wall displays, or tabletops.  Petra is associate editor-in-chief at IEEE CG&A, associate editor of the IEEE Transactions on Visualization and Computer Graphics, has served on many organizing committee roles at IEEE VIS including as papers co-chair for Information Visualization (InfoVis), and has been the co-chair of the biennial Beliv workshop since 2012.  
	</div>
	
	<br/><br/><br/>
    </div>
</div>

<a name="sheelagh"></a>
<div class="talk">
    <div class="ttitle">Visualisation as a Partner to AI and Machine Learning in Drug Discovery</div>
    <div><span class="tspeaker"><a href="https://scholar.google.com/citations?user=jWcQDOsAAAAJ&hl=en">Lindsay Edwards</a></span>, <span> GSK </span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/lindsay-edwards.jpg " style="width: 250px;" alt="S.Carpendale">
    </div>

    <div class="tbioabstract">

        <!--<div class="tabstract"><b>Abstract:</b>TBA</div>-->

       <div class="tbio"><b>Bio:</b>
       Lindsay Edwards is UK Head of Artificial Intelligence and Machine Learning (AI/ML) for Glaxo Smith Kline (GSK)’s Pharma R&D, having previously led the Digital, Data & Analytics Unit globally for GSK’s Respiratory division. Alongside his role at GSK, he is also a Fellow of the Royal Society of Biology and a member of the scientific strategy board of the Xtreme Everest Project. Originally a specialist in systems biology, he joined GSK in 2014 from a Lectureship in Physiology at King’s College London, and has held positions in both Australia and the UK. With a background that spans human physiology and biochemistry, metabolomics, computational biology and data science, he has extensive experience of applying novel analytical methods (including machine learning) to biological datasets. His interests currently centre on the use of contemporary analytical tools (including AI) to bring transformational change to drug discovery.
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

