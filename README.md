# Lapsus.js

A simple JavaScript error report application integrated with Google Analytics.

* Source: [https://github.com/evandroeisinger/lapsus](https://github.com/evandroeisinger/lapsus)
* Homepage: [http://evandroeisinger.com/lapsus](http://evandroeisinger.com/lapsus)

### Usage

It's easy to use, just setup your Google Analytics and insert Lapsus.js.

``` js

<!-- Google Analytics: change UA-XXXXX-X to be your site's ID. -->
<script>
    var _gaq=[['_setAccount','UA-XXXXX-X'],['_trackPageview']];
    (function(d,t){var g=d.createElement(t),s=d.getElementsByTagName(t)[0];
    g.src=('https:'==location.protocol?'//ssl':'//www')+'.google-analytics.com/ga.js';
    s.parentNode.insertBefore(g,s)}(document,'script'));
</script>
<!-- Import Lapsus.js -->
<script src="js/lapsus.js"></script>

```

The error report will be available in the Google Analytics tab Events with the category: Errors.

### Browser Support

All browsers (Firefox, Chrome, Safari, Opera, IE6+) should be supported. Please [open an issue](https://github.com/evandroeisinger/lapsus/issues) if Lapsus.js doesn't work on a particular browser.

### Contributing

Anyone and everyone is welcome to [contribute](https://github.com/evandroeisinger/lapsus/fork).

----

[Licensed under the MIT license.](http://www.opensource.org/licenses/mit-license.php)

Copyright © 2012 [Evandro Eisinger](http://evandroeisinger.com)