---
layout: map_page
logo: ieee.svg
title: BioVis at IEEE VIS (BioVis@VIS)
location: Berlin, Germany
date: 22 October 2018
main_venue_rln: In conjunction
main_venue: IEEE VIS 2018
main_venue_url: http://ieeevis.org/
permalink: /ieeevis/
---

<!--<br>
<div style="background-color: #f2f2f2; border-style: solid; border-color: #009e9d; padding: 5px;">
<h4> Additional details for BioVis@VIS 2018 will be announced soon. In the meantime check out last year's event <a href="http://biovis.net/2017/ieeevis">BioVis@VIS</a> and our co-located meeting with <a href= "http://biovis.net/2017/ismb">ISMB 2017</a> </h4>
</div>-->

<div class="row center-align">

    <div class="col m6 s12 event-page-menu-block">
        <i class="material-icons large">create</i>
        <h3>BioVis Challenges</h3>
        <a class="btn waves-effect waves-light" href="{{site.baseurl}}/biovisChallenges_vis" type="submit" name="action">View Details</a>
    </div>

    <div class="col m6 s12 event-page-menu-block">
        <i class="material-icons large">list</i>
        <h3>Program</h3>
        <a class="btn waves-effect waves-light" href="{{site.baseurl}}/agenda_ieee" type="submit" name="action">View Details</a>
    </div>
</div>

<br/>
<br/>

<div class="row left-align">
    <div class="col s12 m6">
        <h4>Important Dates</h4>
        <p>Workshop date: October 22nd, 2018</p>
    </div>

    <div class="col s12 m6">
        <h4>Latest News</h4>
        <ul class="post-list">
         {% for post in site.posts %}
           {% capture category %}{{post.event}}{% endcapture %}
            {% if category == "ieee" %}
            <li class="post-list-item-event">
               <span class="date">{{ post.date | date: "%-d %b %Y" }}</span>
               <span class="post-list-title">
                 <a class="post-list-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
               </span>
               <p class="post-list-excerpt">
                 {{ post.excerpt }}
               </p>              
             </li>
            {% endif %}
           {% endfor %}
         </ul>
    </div>
</div>
