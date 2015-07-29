#apt-install
apt-get install from package list file.
  Usage:
  apt-install [package name | package list file]
  
  package name: APT .deb package name.
  package list file: write package name list to text file.
  
  ex) package.txt
--------
git
php5
php-pear
imagemagick
.
.
.
--------

># apt-install package.txt

Packages that are not installed on the system will be installed.
If you directly specify the package name, the package is installed.

