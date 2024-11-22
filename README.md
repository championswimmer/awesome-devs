
# awesome-devs
Everytime I come across good Github profiles I index them here

> NOTE: If you are on the github repo currently,   
> go to the website 👇 to see the rendered list   

**<https://championswimmer.in/awesome-devs>**

## Devs 
{% for dev in site.data.devs %}
- **Github: <{{ dev.github }}>**   
  {% if dev.linkedin != "" and dev.linkedin != null %}
  LinkedIn: <{{ dev.linkedin }}>  
  {% endif %}
  {% if dev.twitter != "" and dev.twitter != null %}
  Twitter: <{{ dev.twitter }}>  
  {% endif %}
  Skills : \[{% for skill in dev.skills %} {{ skill }}, {% endfor %}\]

{% endfor %}
