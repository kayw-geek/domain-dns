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

$serverIp = (new Dns('baidu.com','114.114.114.114'))->ParsingDomain();
```

## License
MIT
### 
