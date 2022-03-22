Open Terminal \n
Change User to Root - sudo su \n
Control if you have git - apt install git \n
Git Repo - git clone https://github.com/jhacker91/vulnerability_web_scanner.git
Control if you hacker zip - apt install zip
Control if you have docker - apt install docker-compose
Change directory - cd vulnerability_web_scanner
Extract all file - unzip vulnerability_web_scanner
Change directory - cd scanner_website-main
Run Docker - docker-compose build
Change file /etc/hosts - nano /etc/hosts
Add this on a new line - 0.0.0.0 test-site
Run Docker - docker-compose up (if receive an error - service apache2 stop ) and re-run the command (docker-compose up)
Open Browser and type - http://test-site
User and Passw - admin admin
