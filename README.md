# jquery.qrcode.js

jquery.qrcode.js is jquery plugin for a pure browser qrcode generation. It allow you to easily add qrcode to your webpages. It is standalone, less than 4k after minify+gzip, no image download. It doesnt rely on external services which go on and off, or add latency while loading. It is based on a library which build qrcode in various language. jquery.qrcode.js wraps it to make it easy to include in your own code.

Show, dont tell, here is a example

### How to Use It

Let me walk you thru it. First include it in your webpage with the usual script tag

```
<script type="text/javascript" src="jquery.qrcode.min.js"></script>
```

Then create a DOM element which gonna contains the generated qrcode image. Lets say a div

```
<div id="qrcode"></div>
```

Then you add the qrcode in this container by

```
jquery('#qrcode').qrcode("this plugin is great");
```

This is it. see it live.


### Conclusion

jquery.qrcode.js is available on github here under MIT license. If you hit bugs, fill issues on github. Feel free to fork, modify and have fun with it :)

































