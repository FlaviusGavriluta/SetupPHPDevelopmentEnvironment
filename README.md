# Setup PHP Development Environment

## Story

We will get familiar with a totally new programming language called PHP.
Starting a new language and a new concept will need discipline and tools!
This project helps you set up an ecosystem with the tools you'll need for the following projects.

## What are you going to learn?

- install and configure `Apache`
- install `PHP and extensions`
- change configurations of PHP
- debug PHP code

## Tasks

1. Make sure that `Apache` is installed on your system (Ubuntu: `apache2 -v`, macOS: `httpd -v`).
    - Student installed `Apache` on her/his machine.

2. Make sure that the latest release of `PHP` is installed on your system (`php -v`).
    - Student installed `PHP` on her/his machine.

3. Install `PhpStorm` Integrated Development Environment
    - Student has the most recent version of `PhpStorm IDE`.
    - The following plugins are selected during installation:
  - `PHP Annotations`
  - `.env files support`
  - `Blade`
  - `Laravel`

4. Make sure that `Xdebug` PHP extension is installed on your system (`php -v` should display "with Xdebug").
    - Student installed `XDebug` PHP extension on her/his machine.

5. Create PHPInfo page in your Web Root directory to check if everything is working properly.
    - Student created PHPInfo page and checked if it is available on `http://localhost/path-to-php-info-file.php`

## General requirements

None

## Hints

- You can boost your terminal experience with Git by displaying the current branch in Bash prompt
  - [How to show current git branch with colors in Bash prompt](https://thucnc.medium.com/how-to-show-current-git-branch-with-colors-in-bash-prompt-380d05a24745)
  - [Mathias's dotfiles](https://github.com/mathiasbynens/dotfiles)

## Background materials

- <i class="far fa-exclamation"></i> [Install Apache on Ubuntu](project/curriculum/materials/pages/apache/install-apache-ubuntu.md)
- <i class="far fa-exclamation"></i> [Install PHP on Ubuntu](project/curriculum/materials/pages/php/install-php-ubuntu.md)
- <i class="far fa-exclamation"></i> [Install Apache, PHP and MySQL on macOS](https://jasonmccreary.me/articles/install-apache-php-mysql-mac-os-x-catalina/)
- <i class="far fa-book-open"></i> [macOS Apache Setup: Multiple PHP Versions](https://getgrav.org/blog/macos-bigsur-apache-multiple-php-versions)
- <i class="far fa-book-open"></i> [Basics of php.ini](http://www.phpknowhow.com/configuration/basics-of-php-ini/)
- <i class="far fa-exclamation"></i> [Install PhpStorm](https://www.jetbrains.com/help/phpstorm/installation-guide.html)
- <i class="far fa-candy-cane"></i> [Download and install Xdebug](https://github.com/xdebug/xdebug#installation)
- <i class="far fa-candy-cane"></i> [Install XDebug Helper for Chrome](https://chrome.google.com/webstore/detail/xdebug-helper/eadndfjplgieldjbigjakmdgkmoaaaoc?hl=en)
- <i class="far fa-candy-cane"></i> [Install XDebug Helper for Firefox](https://addons.mozilla.org/en-US/firefox/addon/xdebug-helper-for-firefox/)
- <i class="far fa-candy-cane"></i> [Zero-configuration debugging with PhpStorm](https://www.jetbrains.com/help/phpstorm/zero-configuration-debugging.html)
- <i class="far fa-book-open"></i> [PHP Releases](https://www.php.net/releases/index.php)
- <i class="far fa-book-open"></i> [How can I create a PHPInfo page?](https://mediatemple.net/community/products/dv/204643880/how-can-i-create-a-phpinfo.php-page)
- <i class="far fa-candy-cane"></i> [PHP's ini_set()](https://www.oreilly.com/library/view/php-in-a/0596100671/re59.html)
- <i class="far fa-candy-cane"></i> [Setting up Apache Virtual Hosts](project/curriculum/materials/pages/apache/setup-virtual-hosts.md)
