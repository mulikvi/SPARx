<b>Sponsors</b><br><br>
SPARx Cal: https://sites.uci.edu/sparxcal/<br>
Dr. Tirtha Banerjee, Dr. Janine Baijnath-Rodino, Shu Li - Department of Civil and Environmental Engineering, UCI
 
<b>Current git repositories:</b><br><br>
Burn-client (hosts webpage) - https://github.com/mulikvi/burn-client<br>
Burn-window (hosts backend window calculations) - https://github.com/mulikvi/burn-window<br>
Burn-Server (hosts database files from SPARx team) - https://github.com/mulikvi/burn-server<br>


<b>Fire Map Dashboard</b> 

AWS link to view map: http://fire-map-dashboard.s3-website-us-west-1.amazonaws.com/

<b>Browsers Tested On:</b>

● 	Microsoft Edge<br>
● 	Google Chrome<br>
● 	Firefox: Caching problem with images not changing when generating burn window raster

<b>Current State of Project</b>
<ul>
 <li>Can sort fires (prescribed, wildfires, unknown, etc) by using filters</li>
<li>Plot fires</li>
<ul><li>Can currently generate burn-window, temperature (avg and max C), and humidity (min C) plots on the map</li></ul>
 <li>Show Information on left side of dashboard</li>
     <ul><li>Under Statistics: data based on fires</li>
<li>Under Counties: percentage for each county in California based on whether it satisfies the burn-window conditions within a specified period of time</li></ul>
<li>Project hosted on Amazon Web Services</li>
<li>Project has more optimized calculation by splitting data in chunks</li>
</ul>
