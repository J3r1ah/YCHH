  # YOU CANT HAVE HER!

# Story:

<img src="/YOU-HAVE-HER-official-blog-page-/images/YCHH" alt="rudo" height="500x" width="500px">


# Posts
<hr>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
