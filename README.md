# dd
Laravel like dd helper for WordPress
A debug plugin for WordPress Developer which is made by an organization named 
<a href="https://www.wpmanageninja.com" target="_blank">wpmanageninja</a>.

## How to use:
* Download or clone from this repository (<a href="https://github.com/hasanuzzamanbe/dd/archive/master.zip">Quick Download</a>)
* Install as a WordPress plugin and activate
* Use `dd()` to debug on your PHP file instead of `var_dump()` which will provide you a smart log with formated data.

## Example:

`$value = '6456';
 dd($value); // 6456`
 
 Also it will show Json data more nice and formated than `var_dump()`
 
 ## Issue you may face sometimes to install on WordPress:
 
 Sometimes if any of your plugin already use this dd then when you activate this plugin it may shows a Fatal error like this-
 `Fatal error: Cannot redeclare dd() (previously declared in /home/xaaman/Projects/wp/wp-content/plugins/YourPluginName/app/Global/Common.php:26)`
 
 That means you can't declare twice which is already used on your `/plugins/YourPluginName` dirrectory.
 Don't worry just deactivate the conflicting plugin then activate dd and now activate the plugin which you deactivated first.
 
 
 
