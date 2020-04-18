#INTRODUCTION TO MOODLE
14 Feb,2020

Moodle is an acronym for "Modular Object-Oriented Dynamic Learning Environment." It is a free and open-source learning management system (LMS) written in PHP and distributed under the GNU General Public License.Developed on pedagogical principles,Moodle is used for blended learning, distance education, flipped classroom and other e-learning projects in schools, universities, workplaces and other sectors.

#INSTALLATION OF MOODLE
14 Feb,2020

Step 1: Install Ubuntu sudo apt-get install vim

Step 2: Install Apache/MySQL/PHP sudo apt install apache2 mysql-client mysql-server php libapache2-mod-php

Step 3: Install Additional Software sudo apt install graphviz aspell ghostscript clamav php7.2-pspell php7.2-curl php7.2-gd php7.2-intl php7.2-mysql php7.2-xml php7.2-xmlrpc php7.2-ldap php7.2-zip php7.2-soap php7.2-mbstring

sudo service apache2 restart

sudo apt install git

Step 4: Download Moodle cd /opt sudo git clone git://git.moodle.org/moodle.git cd moodle sudo git branch -a sudo git branch --track MOODLE_38_STABLE origin/MOODLE_38_STABLE sudo git checkout MOODLE_38_STABLE

Step 5: Copy local repository to /var/www/html/ sudo cp -R /opt/moodle /var/www/html/ sudo mkdir /var/moodledata sudo chown -R www-data /var/moodledata sudo chmod -R 777 /var/moodledata sudo chmod -R 0755 /var/www/html/moodle

Step 6: Setup MySQL Server sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf sudo service mysql restart sudo mysql -u root -p

