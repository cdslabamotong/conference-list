---
layout: page
title: Rumor Diffusion with the Effect of Debunking Information
---

--------

<!--Table-->
<div class="row justify-content-center">
<table id="tablePreview" class="table">
<!--Table head-->
  <thead>
    <tr>
      <th>#</th>
      <th>Name</th>
      <th>Submission</th>
      <th>Notification</th>
      <th>Conference</th>
      <th>Location</th>
    </tr>
  </thead>
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>AAAI</td>
      <td>N/A</td>
      <td>N/A</td>
      <td>Feb 7 - 12, 2020</td>
      <td>New York, U.S.</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>INFOCOM</td>
      <td>7/31/19</td>
      <td>11/28/19</td>
      <td>April 27 - 30, 2020</td>
      <td>Beijing, China</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>ICDCS</td>
      <td>1/5/19</td>
      <td>3/28/19</td>
      <td>July 7 - 10, 2019</td>
      <td>Dallas, Texas</td>
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>NIPS</td>
      <td>5/16/19</td>
      <td>7/15/19</td>
      <td>December 10 - 12, 2019</td>
      <td>Vancouver, Canada</td>
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>ICML</td>
      <td>1/18/19</td>
      <td>4/24/19</td>
      <td>June 10 - 15, 2019</td>
      <td>Long Beach, CA</td>
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>SIGMOD</td>
      <td>10/18/18</td>
      <td>1/19/18</td>
      <td>June 30 - July 5, 2019</td>
      <td>Amsterdam, The Netherlands</td>
    </tr>
    <tr>
      <th scope="row">7</th>
      <td>KDD</td>
      <td>2/3/19</td>
      <td>4/28/19</td>
      <td>August 4 - 8, 2019</td>
      <td>Anchorage, Alaska</td>
    </tr>
    <tr>
      <th scope="row">8</th>
      <td>IJCAI</td>
      <td>2/25/19</td>
      <td>5/9/19</td>
      <td>August 10 - 16, 2019</td>
      <td>Macao, China</td>
    </tr>
    <tr>
      <th scope="row">9</th>
      <td>WWW</td>
      <td>N/A</td>
      <td>N/A</td>
      <td>N/A</td>
      <td>Taipei, China</td>
    </tr>
    <tr>
      <th scope="row">10</th>
      <td>CIKM</td>
      <td>5/15/19</td>
      <td>8/6/19</td>
      <td>November 3 - 7, 2019</td>
      <td>Beijing, China</td>
    </tr>
  </tbody>
  <!--Table body-->
</table>
<!--Table-->
</div>
--------
<span style="color:darkgrey; size:2.5em; line-height:150%">Billions of data are generated from social media, such as Twitter and Facebook, which also provide a platform for fast rumor propagation. Validating the massive yet fast-spreading social media data is becoming extremely important but also challenging. By referencing the top 216 most widely spread rumors between May and July 2017 from [Snopes.com](https://www.snopes.com/), the first and largest fact-checking site online, we tracked the propagation of these rumors through millions of tweets on Twitter. In this paper, we examined the rumor cascade characteristics of both rumor and the associated debunking information. The time-series evolution of the rumors at different phases are monitored and analyzed, especially before and after rumor-busting media fact-checked the rumor. </span>

<div style="text-align:center"><img src="https://s2.ax1x.com/2019/03/09/ASepXd.png" alt="figure1" width="600"/></div>   

 <br /> 
<span style="color:darkgrey; size:2.5em; line-height:150%">For the purpose of studying the propagation of rumors on the social network, we cataloged top 216 rumor topics with total 425,333 tweets from April 2017 to September 2017 on Snopes.com, and the corpus of rumor-related tweets can also be obtained by Twitter Premium Search API. The result dataset has over 400 thousand tweets of 216 rumor topics, and the total number of involved users is 221029. For each rumor topic in our corpus, we obtained their broad thematic category from the web page on Snopes.com. The most popular rumor categories that were discussed from May to July 2017 are Politics, Fauxtography (fraudulent photography), and Junk News, which makes up approximately 65% of the total obtained rumor topics. The collected topics are ranging from politics to some specific rumor topics like Movies or Foods.</span>

 <br /> 
 
<span style="color:darkgrey; size:2.5em; line-height:150%">The following graphs illustratively present the misinformation evolution of the widely discussed rumor topic - '[Clinton/Lynch Pilot Breaks His Silence on What Was Said?](https://www.snopes.com/fact-check/clinton-lynch-pilot/)'. A rumor generally can spread rapidly at its early phase. Several comparatively large cascades are generated before the posting of debunking information (the lower left graph). However, after the intervention of debunking information, a rumor loses its ability to affect broader users since the average size of cascades drops while the total number of cascades keeps increasing (lower right graph).</span>

<div style="text-align:center">
<p float="left">
 <img src="https://s2.ax1x.com/2019/03/11/ACCRdf.png" alt="figure1" width="400"/>  
 <img src="https://s2.ax1x.com/2019/03/11/ACCIzj.png" alt="figure2" width="400"/>
</p>
</div>

<br /> 
<span style="color:darkgrey; size:2.5em; line-height:150%">
Identifying belief in rumors can help reveal many semantic aspects of their origination and propagation, and users' belief of a rumor may vary before and after the fact was checked. To further examine different phases of a rumor's propagation, we monitor users attitudes change in a rumor's propagation process, and the following graphs indicate the user's attitude change oppositely before and after the rumor fact was checked. Three curves reflect the positive, negative and neutral attritudes change over time of the aforementioned rumor topic in the following left graph, and right graph shows the overall sentiment change of the rumor. 
</span>

<div style="text-align:center">
<p float="left">
 <img src="https://s2.ax1x.com/2019/03/11/ACCrzd.png" alt="figure1" width="400"/>  
 <img src="https://s2.ax1x.com/2019/03/11/ACCcLt.png" alt="figure2" width="400"/>
</p>
</div>

<br />

<span style="color:darkgrey; size:2.5em; line-height:150%">
In this paper, we are set to analyze the role of debunking information in the diffusion of online rumors. To this end, we compare the various propagation patterns and user's attitude change towards rumor cascades before and after the intervention of fact-checking information. In addition, we apply machine learning algorithms to verify the existence of the influence of debunking information.
</span>
