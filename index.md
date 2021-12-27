# My Projects
Here are a list of projects that I am/have been working on

# My Interests
I'm interested in sketching, creative writing, poetry, art, traveling, and all things cybersecurity.

# My Blog
I'm really excited to blog my journey on GitHub.com
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>

  {% endfor %}
</ul>

# Get in Touch
<ul>
  <li><a href="https://twitter.com/{{ site.twitter_username}}">Twitter</a></li>

  <li><a href="https://github.com/{{ site.github_username}}">GitHub</a></li>
</ul>
