{
"projects":[
{% for repository in site.github.public_repositories %}
  {
    name="{{ repository.name }}"
    url="{{ repository.html_url }}"
  },
{% endfor %}
]
