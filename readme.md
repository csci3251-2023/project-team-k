# Introduction
Task 1 Starting issues done by 1155159600 <br>
Task 2 Explore the Projects tab done by 1155147818 <br>
Task 3 Update readme.md done by 1155142698 <br>
Task 4 Write C code TODO <br>
Task 5 Get a status badge TODO <br>
Task 6 Showcase team done by 1155161439 <br>
Task 7 Register your repo TODO <br>


**Please read `tasks.md` to start your work.**
# Code

{% highlight c %} 
{% include_relative code.c %} 
{% endhighlight %}

=======
# Contributer
{% for contributor in site.contributor %}

<p>
  <ul>
    <li>
   <img src = "{{contributor.image}}"> @{{ contributor.user }}({{ contributor.name }})
    <ul><li>{{ contributor.content | markdownify }}</li></ul>
    </li>
  </ul>
</p>
{% endfor %}

Last updated: {{ site.time }}
