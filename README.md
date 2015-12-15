Ansible role for install libsass / sassc
========================================

Installation and configuration by:

* [http://askubuntu.com/questions/566675/how-to-install-node-sass-gulp-sass-on-ubuntu-14-04-or-linux-mint-17](http://askubuntu.com/questions/566675/how-to-install-node-sass-gulp-sass-on-ubuntu-14-04-or-linux-mint-17)
* [https://gist.github.com/edouard-lopez/503d40a5c1a49cf8ae87](https://gist.github.com/edouard-lopez/503d40a5c1a49cf8ae87)
* [http://mattferderer.com/compile-sass-with-sassc-and-libsass](http://mattferderer.com/compile-sass-with-sassc-and-libsass)

Installation methods
--------------------
* Binary packages from the github repository (role name: ansible.libsass)
* Ansible Galaxy: ansible-galaxy install lciolecki.libsass (role name: lciolecki.libsass) 
 
Recommended way installation is ansible galaxy.

Usage
-----

```yaml
---
- hosts: all

  roles:
    - lciolecki.libsass

  vars:
  ....
```

Variables
---------

```yaml
---

libssas_version: 3.3.2

libsass_path: "/usr/local/lib/libsass"

sassc_version: 3.3.0

sassc_path: "/usr/local/lib/libsass/sassc"

```

License
-------
The MIT License (MIT)

Copyright (c) 2015 Łukasz Ciołecki

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.