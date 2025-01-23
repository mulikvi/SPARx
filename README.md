<b>Sponsors:</b><br>
SPARx Cal: https://sites.uci.edu/sparxcal/<br>
Dr. Tirtha Banerjee, Dr. Janine Baijnath-Rodino, Shu Li - Department of Civil and Environmental Engineering, UCI

<img width="269" alt="poster" src="https://github.com/user-attachments/assets/3dd23b7e-13cc-4b8f-a73a-84a3aa7d0a91" />





<br><br>
<b>Current git repositories:</b><br>
Burn-client (hosts webpage) - https://github.com/mulikvi/burn-client<br>
Burn-window (hosts backend window calculations) - https://github.com/mulikvi/burn-window<br>
Burn-Server (hosts database files from SPARx team) - https://github.com/mulikvi/burn-server<br>


<b>Fire Map Dashboard:</b><br>
AWS link to view map: http://fire-map-dashboard.s3-website-us-west-1.amazonaws.com/
![firemap](https://github.com/user-attachments/assets/c3fecf1c-c4f5-43c5-b57f-83c930134a78)

<b>Browsers Tested On:</b><br>
● 	Microsoft Edge<br>
● 	Google Chrome<br>
● 	Firefox: Caching problem with images not changing when generating burn window raster

<b>Current State of Project:</b><br>
<ul>
 <li>Can sort fires (prescribed, wildfires, unknown, etc) by using filters</li>
 <img width="481" alt="filters" src="https://github.com/user-attachments/assets/08d3b028-5c28-40eb-84b9-7dc9f88bcf3d" />

<li>Plot fires</li>
<ul><li>Can currently generate burn-window, temperature (avg and max C), and humidity (min C) plots on the map</li></ul>
<img width="446" alt="fires" src="https://github.com/user-attachments/assets/da5154c7-ffd8-425a-9e88-8f1b76b6031f" />


 <li>Show Information on left side of dashboard</li>
     <ul><li>Under Statistics: data based on fires</li>
<li>Under Counties: percentage for each county in California based on whether it satisfies the burn-window conditions within a specified period of time</li></ul>
 <img width="275" alt="statistics" src="https://github.com/user-attachments/assets/08ebce0d-525c-4167-87fe-ea1da48f5fe5" />

<li>Project hosted on Amazon Web Services</li>
<li>Project has more optimized calculation by splitting data in chunks</li>
</ul>






<b>PowerBI Dashboard is built to provide a comprehensive analysis of wildfire trends in California from 1900 to 2021. 
Key features include:</b>
<ul>
<li>Wildfire Trends: Annual trends in the number of wildfires and acres burned.</li>
<li>Top Counties Impacted: Analysis of counties most affected by wildfires, highlighting acreage burned and wildfire occurrences.</li>
<li>Fire Types and Burn Types: Breakdown of wildfires by type (e.g., escaped, cleaned burns, unknown) and burn types.</li>
<li>Seasonal Patterns: Insights into wildfire activity by month.</li>
<li>Largest Wildfires: Details on the top 100 largest wildfires, including location, date, and size.</li>
<li>Interactive Filters: Explore data by county, year, fire type, and burn type for customized insights.</li></ul><br>
This project aims to make historical wildfire data more accessible, enabling data-driven decision-making for wildfire prevention and management efforts.
