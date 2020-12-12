# Ajira_Hackathon
<H3>Simulation model for prototyping a rover communication system via api and testing it on different environment</H3>
<h2>INSTRUCTIONS:</h2>
<h4>1. Run this python file 'rover.py' (required modules: Flask,Json,requests)<br>
2. First run "http://127.0.0.1:5000/" or "http://127.0.0.1:5000/api/environment/configure" on chrome (local host address may vary "http://127.0.0.1:5000" depending on port availability)<br>
3. For adding patch use "http://127.0.0.1:5000/api/environment/patch/<change>" (http://127.0.0.1:5000/api/environment/patch/storm:True or http://127.0.0.1:5000/api/environment/patch/storm:True temperature:40)<br>
4. For getting rover status "http://127.0.0.1:5000/api/rover/status"<br>
5. For getting rover movement  "http://127.0.0.1:5000/api/rover/move/<direction>" (http://127.0.0.1:5000/api/rover/move/up)<br>
  </h4>

<h3>To execute the sample testcase given in the Problem statement perform following ops:<h3>
<h4>
1.http://127.0.0.1:5000/api/environment/configure or http://127.0.0.1:5000/<br>
2./api/rover/move/right<br>
3./api/rover/status<br>
4./api/environment/patch/storm:True<br>
5./api/rover/status<br>
6./api/rover/move/up<br>
7./api/rover/status<br>
8./api/environment/patch/storm:False<br>
9./api/rover/status<br>
10./api/rover/move/up<br>
11./api/environment/patch/storm:True<br><h4>
<br><br>
A lil bit of modeling by representing rover position on a tabular cordinate is done in html and also the responses are also displayed on the html page and cmdline for better readability.<br>
Any doubts in the execution contact me via mail-saurabhraman1996@gmail.com or the registered phonenumber given while event registration.<br>
+-+-+-+
