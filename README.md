# [Organic Web README.md](https://github.com/LafeLabs/ORGANIC-WEB)

## [branch.html](branch.html)

The organic web is an operating system independent self-replicating and self-editing set of files from the following formats:

 - [HTML](https://en.wikipedia.org/wiki/HTML)
 - [CSS](https://en.wikipedia.org/wiki/CSS)
 - [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
 - [Markdown](https://en.wikipedia.org/wiki/Markdown)
 - [JSON](https://en.wikipedia.org/wiki/JSON)
 - [PHP](https://en.wikipedia.org/wiki/PHP)
 - [LaTeX](https://en.wikipedia.org/wiki/LaTeX)
 - [Text](https://en.wikipedia.org/wiki/Text_file)

This system can be used to publish any media on any hardware and any software. It can be used for scientific publication, writing and distributing a wide range of application software, journalism, music distribution, social media, and arbitrary media distribution of all kinds.

To run on a Windows or Mac computer, install [XAMPP](https://www.apachefriends.org/) and put the set into the web folder.  To install on a linux machine, copy the following commands into the terminal one by one:

```
sudo apt update
sudo apt install apache2 -y
sudo apt install php libapache2-mod-php -y
cd /var/www/html
sudo rm index.html
sudo apt-get install curl
sudo curl -o replicator.php https://raw.githubusercontent.com/LafeLabs/ORGANIC-WEB/refs/heads/main/php/replicator.txt
cd ..
sudo chmod -R 0777 *
cd html
php replicator.php
sudo chmod -R 0777 *
ln -s /var/www/html ~/Desktop/html
```

# Edit files

 - [edit-index.html](edit-index.html)
 - [edit-web-files.html](edit-web-files.html)
 - [edit-text-files.html](edit-text-files.html)
 - [edit-markdown-files.html](edit-markdown-files.html)
 - [edit-php-files.html](edit-php-files.html)
 - [edit-readme.html](edit-readme.html)

# Read markdown and text files

 - [read-markdown-files.html](read-markdown-files.html)
 - [read-markdown-latex-files.html](read-markdown-latex-files.html)
 - [read-text-files.html](read-text-files.html)

# Delete files:

 - [delete-web-files.html](delete-web-files.html)
 - [delete-text-files.html](delete-text-files.html)
 - [delete-markdown-files.html](delete-markdown-files.html)
 - [delete-php-files.html](delete-php-files.html)
 - [delete-images.html](delete-images.html)

# PHP FILES AS TEXT

 - [php/branch.txt](php/branch.txt)
 - [php/compile-php.txt](php/compile-php.txt)
 - [php/copy.txt](php/copy.txt)
 - [php/delete-branch.txt](php/delete-branch.txt)
 - [php/delete-file.txt](php/delete-file.txt)
 - [php/edit-markdown-file.txt](php/edit-markdown-file.txt)
 - [php/generate-dna.txt](php/generate-dna.txt)
 - [php/list-branches.txt](php/list-branches.txt)
 - [php/list-files.txt](php/list-files.txt)
 - [php/load-file.txt](php/load-file.txt)
 - [php/local-replicator.txt](php/local-replicator.txt)
 - [php/read-markdown-file-latex.txt](php/read-markdown-file-latex.txt)
 - [php/read-markdown-file.txt](php/read-markdown-file.txt)
 - [php/replicator.txt](php/replicator.txt)
 - [php/save-file.txt](php/save-file.txt)
 - [php/save-png.txt](php/save-png.txt)
 - [php/upload-image.txt](php/upload-image.txt)