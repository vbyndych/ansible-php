PHP
=========

This role install and configure PHP-FPM and some other PHP packages to run PHP-based projects

Requirements
------------

Dosn't have any requirements

Role Variables
--------------

- workers - will be converted to pm.max_children. Represents maximum PHP process count. Default: 4
- timezone - PHP default timezone. Default: Europe/Kiev

Dependencies
------------
This role depends of ansible (basic) role

Example Playbook
----------------
Example of role usage:

    - hosts: servers
      roles:
         - { role: php, php.workers: 4 }

License
-------

Copyright (c) 2015 Vlad Byndych

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Author Information
------------------

If you have any questions please write me yojemail@gmail.com
