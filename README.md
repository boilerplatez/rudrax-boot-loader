# rudrax-boot-loader


## Setup
- Install  XAMPP [instructions](http://docs.spamjs.org/boilerplatez/docs/master/markdown/xampp/MAC.md)
- Setup PHP Composer [instructions](http://docs.spamjs.org/boilerplatez/docs/master/markdown/php/ENV.md)
- [Download](https://github.com/boilerplatez/rudrax-boot-loader/archive/master.zip) project
    Or you can optionally setup whole project manually following these setups
    - Create RudraX Project [instructions](http://docs.spamjs.org/boilerplatez/docs/master/markdown/php/rudrax.md)
    - Setup Node Environment [instructions](http://docs.spamjs.org/boilerplatez/docs/master/markdown/node/ENV.md)
    - Setup bootloader Project [instructions](http://docs.spamjs.org/boilerplatez/docs/master/markdown/node/bootloader.md)
- Point your dummy/virtual domain to your project directory [instructions](http://docs.spamjs.org/boilerplatez/docs/master/markdown/xampp/domain.md)



## Build
- Whenever there are changes in Any Controller-Annotations you need to hit this url

```
    http://local.piggy.com?RX_MODE_DEBUG=true&RX_MODE_BUILD=1&_display_errors_=2
    
```

## Wroking?
- Hit these urls in your browser and see the outputs you get
```
    http://local.piggy.com/welcome?name=Lucas
    http://local.piggy.com/api/data/7
    http://local.piggy.com
    
```

