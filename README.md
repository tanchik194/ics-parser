# PHP ICS Parser
============================

[![Build Status](https://secure.travis-ci.org/tanchik194/ics-parser.png?branch=master)](https://travis-ci.org/tanchik194/ics-parser)
[![Dependency Status](https://www.versioneye.com/user/projects/56e27f6ddf573d00495ab917/badge.svg?style=flat)](https://www.versioneye.com/user/projects/56e27f6ddf573d00495ab917)

[![Coverage Status](https://coveralls.io/repos/github/tanchik194/ics-parser/badge.svg?branch=master)](https://coveralls.io/github/tanchik194/ics-parser?branch=master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/tanchik194/ics-parser/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/tanchik194/ics-parser/?branch=master)

[![Latest Stable Version](https://poser.pugx.org/johngrogg/ics-parser/v/stable.png)](https://packagist.org/packages/johngrogg/ics-parser)
[![Total Downloads](https://poser.pugx.org/johngrogg/ics-parser/downloads.png)](https://packagist.org/packages/johngrogg/ics-parser)

## License
This ics-parser is under [MIT License](http://opensource.org/licenses/MIT). You may use it for your own sites for free, but I would like to get a notice when you use it (info@martin-thoma.de). If you use it for another software project, please state the information / links to this project in the files.

It is hosted at [https://github.com/MartinThoma/ics-parser/](https://github.com/MartinThoma/ics-parser/) and the PEAR coding standard is used.

It was modified by John Grogg to properly handle recurring events (specifically with regards to Microsoft Exchange).

## Requirements
  - PHP 5 >= 5.6.0

## Installation

### composer

Установка с использованием менеджера пакетов [Composer](http://getcomposer.org):

```bash
$ curl -s https://getcomposer.org/installer | php
```

Теперь вносим изменения в ваш `composer.json`:

```yaml
{
    "require": {
        "johngrogg/ics-parser": "dev-master"
    }
}
```

## Credits
  - Martin Thoma (programming, bug fixing, project management)
  - Frank Gregor (programming, feedback, testing)
  - John Grogg (programming, addition of event recurrence handling)
  - Jonathan Goode (programming, bug fixing, enhancement, coding standard)