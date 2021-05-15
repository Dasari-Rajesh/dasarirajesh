---

nav: About

---
<html>
<body style="background-color:lightblue;" >

</body>
</html>

<h2> Some information about me!</h2>

Name    : Dasari Rajesh

DOB    : 06-01-2002
## Education

College : IIT Bombay

Branch  : C.S.E

BTech Started in : 2019

BTech ending will be : 2023(hopefully)


## Contact me

[rdasari245@gmail.com](mailto:rdasari245@gmail.com)

<div id="socialMedia">
{% if site.social-media.email %}
    <a href="mailto:{{ site.social-media.email }}" title="Email"><i class="fa fa-envelope-square"></i></a>
{% endif %}
{% if site.social-media.facebook %}
    <a href="https://www.facebook.com/{{ site.social-media.facebook }}" title="Facebook"><i class="fa fa-facebook-square"></i></a>
{% endif %}
{% if site.social-media.twitter %}
    <a href="https://www.twitter.com/{{ site.social-media.twitter }}" title="Twitter"><i class="fa fa-twitter-square"></i></a>
{% endif %}


</div>
