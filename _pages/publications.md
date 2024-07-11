---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
  $(document).ready(function () {
    $(".abstract").hide();
    $(".button").on("click", function () {
        $(this).next(".abstract").slideToggle(400);
    });
});
</script>


<style>
.abstract{text-align:justify; }
.button{ text-align:justify; }
</style>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}



<ol reversed>
<div id="1">
<li> <b>BotNet Intrusion Detection System in Internet of Things with Developed Deep Learning</b>, 2023 
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
    The rapid growth of technology has led to the creation of computing networks. The applications of the Internet of
    Things are becoming more and more visible with the expansion and development of sensors and the use of a series
    of equipment to connect to the Internet. Of course, the growth of any network will also provide some challenges.
    The main challenge of IoT like any other network is its security. In the field of security, there are issues such
    as attack detection, authentication, encryption and the so on. One of the most important attack is cyber-attacks
    that disrupt the network usage. One of the most important attacks on the IoT is BotNet attack. The most important
    challenges of this topic include very high computational complexity, lack of comparison with previous methods,
    lack of scalability, high execution time, lack of review of the proposed approach in terms of accuracy to
    detect and classify attacks and intrusions. Using intrusion detection systems for the IoT is an important
    step in identifying and detecting various attacks. Therefore, an algorithm that can solve these challenges
    has provided a near-optimal method. Using training-based models and algorithms such as Deep
    Dearning-Reinforcement Learning and XGBoost learning in combination (DRL-XGBoost) models can be an
    interesting approach to overcoming previous weaknesses. The data of this research is Bot-IoT-2018.
</div></li></div>
</ol>







<!-- 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
