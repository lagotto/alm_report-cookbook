ALM Reports Cookbook
===================

Chef cookbook for the alm-report application

Requirements
------------
Requires Chef 0.10.10+ and Ohai 0.6.10+ for `platform_family` attribute use.

### Platforms
Tested on the following platforms:

- Ubuntu 12.04, 14.04

### Cookbooks
Opscode cookbooks:

- apt
- build-essential
- mysql
- database
- memcached

Other cookbooks:

- [ruby](https://github.com/articlemetrics/ruby-cookbook)
- [passenger_nginx](https://github.com/articlemetrics/passenger_nginx-cookbook)
- [capistrano](https://github.com/articlemetrics/capistrano-cookbook)

Attributes
----------
* `node['ruby']['version']` - Can be `ruby1.9.1`, `ruby2.0` or `ruby2.1`, Defaults to `ruby2.1`. `ruby1.9.1` is Ruby 1.9.3.


Recipes
-------
### default
Installs the ALM Reports Ruby on Rails application with:

- Ruby 2.1
- Nginx with Passenger
- MySQL.
- Memcached


License & Authors
-----------------
- Author: Martin Fenner (<mfenner@plos.org>)
- Author: Jure Triglav (<jure@triglav.io>)

```text
Copyright: 2014, Public Library of Science

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
