
# awesome-devs
Everytime I come across good Github profiles I index them here

{% for dev in site.data.devs %}
- <{{ dev.github }}>   
  [LinkedIn]({{ dev.linkedin }})   
  Skills : 
  {% for skill in dev.skills %}
  - {{ skill }}  
  {% endfor %}

{% endfor %}


