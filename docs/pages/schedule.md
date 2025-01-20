---
---

<!-- https://docs.google.com/spreadsheets/d/1SWVcahRbQ5pgE-LNVO61xZyoHdELlyfJs5iTqp34_6Y/edit#gid=0 -->

<!-- mv ~/Downloads/PDSB-syllabus-schedule\ -\ Sheet1.csv ~/Documents/hack-the-planet/docs/_data/schedule.csv -->


<table class="table table-sm table-striped table-hover table-bordered" style="font-size: 14px">
  <caption>Schedule of class sessions</caption>
  <thead class="thead-dark">
    <tr>   
	  {% for keyval in site.data.schedule[0] %}
	  <th scope="col">{{ keyval[0] }}</th>
	  {% endfor %}
	</tr>
  </thead>
  <tbody>
  	{% for row in site.data.schedule %}
  	<tr>
  	  <th scope="col">{{ row["Session"] }}</th>
  	  <th scope="col">{{ row["Date"] }}</th>
  	  <th scope="col">{{ row["Day"] }}</th>  	  
  	  <th scope="col">{{ row["Topic"] }}</th>
  	  <th scope="col">{{ row["subject"] }}</th>
  	  <th scope="col">{{ row["assignment_due"] }}</th>
  	</tr>
  	{% endfor %}
  </tbody>
</table>



<iframe 
	src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRO1smY1G-UGPdQ_qNbVdBDcBaqE9CRihfmO4xjuHQrzDyyXEH4NRxpSxtgBGr1BAKFb11oahluYY-R/pubhtml?widget=true&amp;headers=false"
	style="border: solid black 3px;" width="1200px" height="850px"
>
</iframe>
