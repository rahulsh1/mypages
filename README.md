# mypages

##### Description
This is a simple blog

##### Posts
  <ul class="posts">
    {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>

    {% endfor %}
  </ul>
  
##### FootNote
End blog
