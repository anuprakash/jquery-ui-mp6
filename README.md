# jquery-ui-mp6

jQuery UI Theme for WordPress admin panel.

Based on Smoothness on [jQuery ThemeRoller](http://jqueryui.com/themeroller/#!).

## How to use

Use `css` and `images` in `src` folder.

If you want use it with WordPress, register like this:

```php  
add_action('init', function(){  
    wp_register_script('jquery-ui-mp6', 'path/to/jquery-ui.css', array(), '1.0');  
});  
```

## Lisence

This source code is released under [MIT lisence](http://opensource.org/licenses/mit-license.php).