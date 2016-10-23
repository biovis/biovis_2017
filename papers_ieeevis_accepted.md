---
layout: page
title: Papers BioVis@VIS
permalink: /papers_ieeevis_Accepted/
back_title: IEEE VIS 2016
back_url: ieeevis
---
<!--**Attention paper Authors:**
When preparing accepted papers please note that your paper should not exceed the following dimensions: *46 inches wide by 45 inches high*. There will be 2 papers per side on the each paper board. One paper will be an odd number and the other will be an even number. View a diagram of the the paper board in pdf format [here](http://www.iscb.org/images/stories/ismb2016/downloads/ISMB2016-paperSampler.pdf).
-->


{% for paper in site.data.papers %}

<div class ="talk">
  <table>
  <tr>
    <td width="300px">
      <a href ="{{ site.baseurl}}/files/{{paper.image}}"> <img style="padding-right: 10px;" src="{{ site.baseurl }}/files/{{paper.image}}" alt="{{paper.title}}" height="250" width="250"></a>
    </td>
  <td>
    <div class="ttitle">paper: {{paper.title}}</div>
    <div><span class="tspeaker">{{paper.authors}}</span></div>
    <div>
      <p>{{paper.abstract}}</p>
    </div>
    <!--<div><span><a href="{{ site.baseurl}}/files/{{paper.abstract}}">Download Full Abstract</a></span></div>-->
  </td>
  </tr>
  </table>
</div>
{% endfor %}