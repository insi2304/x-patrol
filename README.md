## Github leaked patrol

Github leaked patrol is a GitHub leak cruise tool:

Provides WEB management terminal, back-end database supports SQLITE3, MYSQL and POSTGRES
Dual engine search, github code interface search global github and local search repos for routine monitoring
Support rule management (github search rules and local repos search rules)
Support GitHub token management and user management
Support auditing of scan results in WEB

Installation Instructions:
-------------
1. Navigate to GoPath Src directory
2. Run "cd /root/gopath/src/"
3. Run "mkdir insi2304"
4. Run "cd insi2304"
5. Run "git clone https://github.com/insi2304/x-patrol.git"
6. Run "cd x-patrol"
7. Run "./build.sh"

OR 

Run the below gist
https://gist.githubusercontent.com/insi2304/2b3c768954545b592752fa90449320b4/raw/12d223ee4fe233835d1913059681940213712103/install_xpatrol.sh


Running Instructions:
---------------------
The command line parameters are as follows:
web command means start web management
The scan command indicates that only github search is started
scan -m local, indicating that only the local code search function is enabled
scan -m all, mean to start github code search and local Repos search function at the same time


After configuring the parameters in conf / app.ini, use the WEB parameters to start the WEB server. By default, it will listen to the local port 8000. The default administrator account and password are: xsecand x@xsec.io. 

Log in to the WEB management terminal and enter the github token and rules. 

Start the search function:



Audit results
GitHub code search results review: 
Local repos detailed search results review: 
update record
5/25/2018, modified local scan logic
Only scan repositories added in the background
Supports both git remote and local addresses in the following format: 
