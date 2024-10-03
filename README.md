# Dir-Recce
Dir-Recce is a Advanced Web Application Reconnaissance of Directories (AWARD) Tool.

It is an Open-Source Tool scripted for Cyber-Security Researchers and Bug Hunters to help them Brute-Force Directories and Files on Web-Application.


<h2>Installation</h2>

Install Dir-Recce by cloning the Git repository in your system:

git clone https://github.com/Bl4cKc34sEr/Dir-Recce.git

**Install 'pip' with**

cd Dir-Recce && pip install -r requirements.txt

**Run Dir-Recce**

python3 recce.py

<h2>Features</h2>

<h5>-Provide Dir for Recursively Brute Force   ✔ </h5>
<h5>-URL Injection Point                       ✔ </h5>
<h5>-Provide Sub-Dir for Brute Force           ✔ </h5>
<h5>-Response Size Process                     ✔ </h5>
<h5>-Multiple Methods                          ✔ </h5>
<h5>-Split extension in wordlist               ✔ </h5>
<h5>-Ignore word in wordlist using regexp      ✔ </h5>


<h2>Usage</h2>
Basic -
<h6>● python3 konan.py -u/--url http://example.com/ </h6>
Multiple Methods (check GET,POST,PUT and DELETE for word entry) -
<h6>● python konan.py -u/--url http://example.com/ -m/--methods"</h6>
Content size process (show response if the response size is ">[number]","<[number]","=[number]")-
<h6>● python konan.py -u/--url http://example.com/ -C/--length "<1000" </h6>
Wordlist split (test.php -> to -> test) -
<h6>● python konan.py -u/--url http://example.com/ -w/--wordlist /root/dict.txt -s/--split </h6>
Wordlist Ignore word,letters,number,..etc provided by regexp (\w*.php|\w*.html,^[0-9_-]+) -
<h6>● python konan.py -u/--url http://example.com/ -w/--wordlist -I/--ignore "\?+"</h6>
Recursive -
<h6>● python konan.py -u/--url http://example.com/ -E/--recursive</h6>
Brute Force directory provided by -S/--sub-dir -
<h6>● python konan.py -u/--url http://example.com/ -S/--sub-dir "admin,dashboard,robots,dev,shadow"e</h6>
 <br>
 <br>
 <br>
 <h3>Developer</h3> 
 https://www.github.com/Bl4cKc34sEr
