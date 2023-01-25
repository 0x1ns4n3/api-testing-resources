# api-testing-resources


## Generic University
Introduction
This is just docker of InsiderPHD's work https://github.com/InsiderPhD/Generic-University

How to Setup & Start
Install docker

Run following commands

```docker pull busk3r/genericuniversity:latest```

```docker run --name genericuniversity -itd --rm -p 80:8000 busk3r/genericuniversity && docker exec genericuniversity service mysql start && docker exec genericuniversity mysql -u root -p -e "ALTER USER 'root'@'localhost' IDENTIFIED BY 'password';"```

```docker exec genericuniversity php /root/Generic-University/artisan serve --host 0.0.0.0```

Go to 127.0.0.1 or system IP you're using.

