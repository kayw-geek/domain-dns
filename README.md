# PHP Domain DNS

:peach: The library resolves the address of the nearest server to you by domain name and Your IP address

![GitHub top language](https://img.shields.io/github/languages/top/kayw-geek/domain-dns) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kayw-geek/domain-dns) ![GitHub](https://img.shields.io/github/license/kayw-geek/domain-dns)
## Installing

```
$ composer require kayw-geek/domain-dns
```

## Usage

```php
<?php
use KaywGeek\Dns\Dns;

$myIp = '124.64.165.53';
$domain = 'google.com';
$serverIp = (new Dns($domain,$myIp))->ParsingDomain();
```

## License
MIT
### 
