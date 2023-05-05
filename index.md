# My Projects
Here is a list of projects that i am working on:
# My Interests
My interests are in developing games which the players can enjoy!
# Get In Touch
<ul>
<li><a href="https://github.com/{{ site.github_username}}">GitHub</a></li>
</ul>
# My Blog
<ul>
{% for post in site.posts %}
<li>
<a href="{{post.url}}">{{post.title}}</a>
</li>
{% endfor %}
</ul>