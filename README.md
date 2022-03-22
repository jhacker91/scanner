Open Terminal <br/>
Change User to Root - sudo su <br/>
Control if you have git - apt install git <br/>
Git Repo - git clone https://github.com/jhacker91/vulnerability_web_scanner.git <br/>
Control if you hacker zip - apt install zip <br/>
Control if you have docker - apt install docker-compose <br/>
Change directory - cd vulnerability_web_scanner <br/>
Extract all file - unzip vulnerability_web_scanner <br/>
Change directory - cd scanner_website-main <br/>
Run Docker - docker-compose build <br/>
Change file /etc/hosts - nano /etc/hosts <br/>
Add this on a new line - 0.0.0.0 test-site <br/>
Run Docker - docker-compose up (if receive an error - service apache2 stop ) and re-run the command (docker-compose up) <br/>
Open Browser and type - http://test-site <br/>
User and Passw - admin admin <br/>
