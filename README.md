# template-costum

untuk memakai template zerodiums-php.yaml agar akurat harus di set -timeout 60 nuclei karena default nuclei sampai 10 detik :

nuclei -u http://target.com -t /home/javahack/costum/phpdev.yaml -timeout 60
