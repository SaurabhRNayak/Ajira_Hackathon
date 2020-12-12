# Ajira_Hackathon
<H3>Simulation model for prototyping a rover communication system via api and testing it on different environment</H3>
<br>
<h2>INSTRUCTIONS:</h2><br>
<h4>1. Run this python file 'rover.py' (required modules: Flask,Json,requests)<br>
2. First run "http://127.0.0.1:5000/" or "http://127.0.0.1:5000/api/environment/configure" on chrome (local host address may vary "http://127.0.0.1:5000" depending on port availability)<br>
3. For adding patch use "http://127.0.0.1:5000/api/environment/patch/<change>" (http://127.0.0.1:5000/api/environment/patch/storm:True or http://127.0.0.1:5000/api/environment/patch/storm:True temperature:40)<br>
4. For getting rover status "http://127.0.0.1:5000/api/rover/status"<br>
5. For getting rover movement  "http://127.0.0.1:5000/api/rover/move/<direction>" (http://127.0.0.1:5000/api/rover/move/up)<br>
  </h4>
