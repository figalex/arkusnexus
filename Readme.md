![arkus icon](http://arkusnexus.com/wp-content/uploads/2013/03/logo.png)
## PageSpeed Optimization

This is the result of pagespeed modifications applied to the arkusnexus website. 

### Performance as UX
>Adding half a second to a search results page can decrease traffic and ad revenues by 20 percent, according to a Google study. The same article reports Amazon found that **every additional 100 milliseconds of load time decreased sales by 1 percent**. Users expect pages to load in two seconds, and **after three seconds, up to 40 percent will simply leave**.

>[_**Improving UX Through Front-End Performance**_][ALA]

<br>

>This data set allowed me to view the following data points: 

> - If your site loads in **5 seconds** it is faster than approximately **25% of the web**
- If your site loads in 2.9 seconds it is faster than approximately 50% of the web
- If your site loads in 1.7 seconds it is faster than approximately 75% of the web
- If your site loads in 0.8 seconds it is faster than approximately 94% of the web

>[_**Site Speed - Are You Fast? Does it Matter for SEO?**_][SEOMOZ]

## Where does that put ArkusNexus?
![WebPageTest](https://dl.dropboxusercontent.com/u/2906909/arkus-pagespeed/WPT.png)
 
## Observations
- jQuery should be loaded from CDN - [Why should I use Google's CDN for jQuery?][JQCDN]
- Too many HTTP requests - [Minimize HTTP Requests][HTTP]
- Missing expires headers - [Best Practices: Optimize caching][CACHE]
- JavaScript loaded in <head> - [High Performance Web Sites:  Move Scripts to the Bottom][FOOTER]
- Third party scripts not loaded asynchronously - [Thinking Async][ASYNC]
- CSS and JS are not minified - [The Importance of Minifying your CSS and JavaScript][MINI]
- CSS should not use @import - [Best Practices - Avoid CSS @import][IMPORT]
- Gzip is not being used - [GZIP Compression Techniques for Better Page Speeds][GZIP]
- Images are not combined into sprite - [http://css-tricks.com/css-sprites/][SPRITES]
- Images are not optimized - [Minimize Payload Size - Optimize Images][IMG]
- Static resources should not use query strings - [Leverage proxy caching][QUERY]

=====================================
### Colophon
[`Yeoman`](http://yeoman.io/)
[`Grunt`](http://gruntjs.com/)
[`Bower`](https://github.com/twitter/bower)
[`Chrome Canary`](https://www.google.com/intl/en/chrome/browser/canary.html)
[`UglifyJS`](https://github.com/mishoo/UglifyJS)
[`cssmin`](https://code.google.com/p/cssmin/)
[`html-minifier`](https://github.com/kangax/html-minifier)
[`grunt-usemin`](https://github.com/yeoman/grunt-usemin)
[`grunt-rev`](https://github.com/cbas/grunt-rev)
[`Sass`](http://sass-lang.com/)
[`Compass`](http://compass-style.org/)
[`YSlow!`](http://yslow.org/)
[`PageSpeed Insights`](https://developers.google.com/speed/pagespeed/insights)
[`Mou`](http://mouapp.com/)
[`ImageOptim`](http://imageoptim.com/)
[`ImageAlpha`](http://pngmini.com/)
[`WebPageTest`](http://webpagetest.com/)
[`mod_rewrite`](http://httpd.apache.org/docs/current/mod/mod_rewrite.html)

[ALA]: http://alistapart.com/article/improving-ux-through-front-end-performance
[SEOMOZ]: http://www.seomoz.org/blog/site-speed-are-you-fast-does-it-matter
[JQCDN]: http://stackoverflow.com/a/2180401
[HTTP]: http://developer.yahoo.com/performance/rules.html#num_http
[CACHE]: https://developers.google.com/speed/docs/best-practices/caching
[FOOTER]: http://developer.yahoo.com/blogs/ydn/high-performance-sites-rule-6-move-scripts-bottom-7200.html
[ASYNC]: http://css-tricks.com/thinking-async/
[MINI]: http://www.hanselman.com/blog/TheImportanceAndEaseOfMinifyingYourCSSAndJavaScriptAndOptimizingPNGsForYourBlogOrWebsite.aspx
[GZIP]: http://rpardz.com/blog/gzip-compression-techniques-better-page-speeds/
[SPRITES]: http://css-tricks.com/css-sprites/
[IMG]: https://developers.google.com/speed/docs/best-practices/payload#CompressImages
[IMPORT]: https://developers.google.com/speed/docs/best-practices/rtt#AvoidCssImport
[QUERY]: https://developers.google.com/speed/docs/best-practices/caching#LeverageProxyCaching
