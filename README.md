
# awesome-devs
Everytime I come across good Github profiles I index them here

> NOTE: If you are on the github repo currently,   
> go to the website 👇 to see the rendered list   

**<https://championswimmer.in/awesome-devs>**


## Devs 
{% for dev in site.data.devs %}
- **Github: <{{ dev.github }}>**   
  LinkedIn: <{{ dev.linkedin }}>  
  Skills : \[{% for skill in dev.skills %} {{ skill }}, {% endfor %}\]

{% endfor %}


