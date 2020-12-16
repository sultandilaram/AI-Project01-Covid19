<h1>Covid-19 Data Project</h1>
<hr>
<p>
From Wikipedia,
Coronavirus disease 2019 (COVID-19) is an infectious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). The disease was first identified in 2019 in Wuhan, China, and has since spread globally, resulting in the 2019–20 coronavirus pandemic. Common symptoms include fever, cough and shortness of breath. Muscle pain, sputum production and sore throat are less common. The rate of deaths per number of diagnosed cases is on average 3.4%, ranging from 0.2% in those less than 20 to approximately 15% in those over 80 years old.
Data Source (Date wise) : 2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE
Data Source: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports
File naming convention
MM-DD-YYYY.csv in UTC.
</p>
<h3>Field description</h3>
<ul>
<li>Province/State: China - province name; US/Canada/Australia/ - city name, state/province name; Others - name of the event (e.g., "Diamond Princess" cruise ship); other countries - blank.</li>
<li>Country/Region: country/region name conforming to WHO (will be updated).</li>
<li>Last Update: MM/DD/YYYY HH:mm (24 hour format, in UTC).</li>
<li>Confirmed: the number of confirmed cases. For Hubei Province: from Feb 13 (GMT +8), we report both clinically diagnosed and lab-confirmed cases. For lab-confirmed cases only (Before Feb 17), please refer to who_covid_19_situation_reports. For Italy, diagnosis standard might be changed since Feb 27 to "slow the growth of new case numbers." (Source)</li>
<li>Deaths: the number of deaths.</li>
<li>Recovered: the number of recovered cases.</li>
</ul>
Update frequency
<ul>
<li>Files after Feb 1 (UTC): once a day around 23:59 (UTC).</li>
<li>Files on and before Feb 1 (UTC): the last updated files before 23:59 (UTC).</li>
</ul>
