# OpenKaunt 

This is a fork of Akaunting(tm) without the License Change from GPL 3.0 to BSL 1.1.

OpenKaunt is a free, open source and online accounting software designed for small businesses and freelancers. It is built with modern technologies such as Laravel, VueJS, Tailwind, RESTful API etc.

## Motivation

Akaunting(tm) switched its license from the GNU General Public License version 3 (GPL v3) to the Business Source License 1.1 (BSL 1.1). One of the main concerns with their implementation of the BSL 1.1 is the restriction they added, which only allows the software to be used by up to two users and for a single business. We believe that this restriction is not in line with the spirit of open software and it can hinder the software's potential growth and usage.

By maintaining a fork of Akaunting(tm) under the GPL v3, our intention is to provide an alternative for those who share our concerns and wish to use, modify, and distribute the software without these restrictions.

## Requirements

* PHP 8.1 or higher
* Database (eg: MySQL, PostgreSQL, SQLite)
* Web Server (eg: Apache, Nginx, IIS)

## Framework

Akaunting uses [Laravel](http://laravel.com), the best existing PHP framework, as the foundation framework and [Module](https://github.com/akaunting/module) package for Apps.

## Installation

* Install [Composer](https://getcomposer.org/download) and [Npm](https://nodejs.org/en/download)
* Clone the repository: `git clone https://github.com/akaunting/akaunting.git`
* Install dependencies: `composer install ; npm install ; npm run dev`
* Install Akaunting:

```bash
php artisan install --db-name="akaunting" --db-username="root" --db-password="pass" --admin-email="admin@company.com" --admin-password="123456"
```

* Create sample data (optional): `php artisan sample-data:seed`

## Contributing

More will follow.

## Translation

More will follow

## Changelog

Please see [Releases](../../releases) for more information what has changed recently.

## Security

## Credits
* [Denis Duliçi](https://github.com/denisdulici)
* [Cüneyt Şentürk](https://github.com/cuneytsenturk)
* [All Contributors](../../contributors)

## License

Akaunting is released under the [GPLv3 license](LICENSE.txt). This Branch will forever stay GPLv3. 
