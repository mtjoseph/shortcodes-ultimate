Shortcodes Ultimate for WordPress
=================================

Supercharge your site with mega pack of shortcodes.
Real swiss army knife for WordPress.

* [Demo video](http://www.youtube.com/watch?v=DR2c266yWEA)
* [Plugin homepage](http://gndev.info/shortcodes-ultimate/)
* [Documentation](http://gndev.info/kb/)
* [Page at wordpress.org](http://wordpress.org/plugins/shortcodes-ultimate/)

With this plugin you can easily create buttons, boxes, different sliders and much, much more. Turn your free theme to premium in just a few clicks. Using Shortcodes Ultimate you can quickly and easily retrieve premium themes features and display it on your site.

Forked from [gndev/shortcodes-ultimate](https://github.com/gndev/shortcodes-ultimate) to address:
# Problem in custom_gallery where specifying a "limit" value can result in "no images found" even when valid Posts exist. The problem behavior is that the code ignores Posts without an assigned featured image (thumbnail). So, if the limit (first N) requested Posts do not have images, then the error message "custom gallery, images not found" is displayed. This can be solved one of two ways:
* Use default image in-place of skipping a Post without a featured image
* Qualify query to include only Posts with a Featured image (thumbnail)

I chose the latter as for my use case.
