# READ ME

## Notes

When using jQuery plugins, it is important to follow the documentation provided by the plugin creator. You may need to use a specific version of jQuery (in this example, it was not happy with the current version, 3.3.1). Be wary of plugins with little documentation.


### Adding a plugin

Once you have found a plugin, read the documentation to find out what's required (i.e. html, css, images, etc.) you need to do the following:

1. Add the jQuery library. You may either include the file on your own server or use a [jQuery-approved Content Delivery Network (CDN)](http://jquery.com/download/#using-jquery-with-a-cdn).

2. Add your plugin scripts below the jQuery library. Be sure to add any dependencies. (The documentation will note this if the plugin requires another library for it to work).

3. Add your own settings. Most jQuery plugins require 1-2 lines of code to target the element being modified. You may also have the ability to add options to fine-tune the look, feel and effect the plugin offers.

*Note:* Remember, sometimes plugins require their own stylesheets. Be sure to include this with your files. Place the plugin's stylesheet *after* your own (so your styles do not cause a potential conflict).


### Reminders

- Adding a jQuery plugin is a *bonus* task for the final assignment. It's implementation still needs to follow best practices. For instance, you still need to organize script files in a `js` or `script` directory. Adding the plugin should not break other parts of your web page/site.

  If the plugin is added, but not according to best practices, you may end up with a standard deduction.

- If the HTML required for the jQuery plugin causes a validation error, I will overlook this. Not all jQuery plugins use 'good' code. (But, of course, all your other code should validate.)


### Resources

- [jQuery](http://jquery.com)
- [jQuery: Download](http://jquery.com/download)
- [jQuery: Using jQuery with a CDN](http://jquery.com/download/#using-jquery-with-a-cdn)
- [jQuery: API Documentation](http://api.jquery.com/)
- [TwentyTwenty](http://zurb.com/playground/twentytwenty) - The plugin used in this example
- [Unheap](http://www.unheap.com/) - A tidy repository of javascript plugins
