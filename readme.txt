=== Buttons With Style ===
Tags: button, button generator, button shortcode, buttons, CSS button generator, responsive buttons
Contributors: wponlinesupport, anoopranawat 
Requires at least: 3.1
Tested up to: 4.7
Author URI: http://wponlinesupport.com
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WordPress Buttons Generator: Lets you build custom buttons with 5 class of buttons, 3 type and 3 styles with simple shortcode.

== Description ==
Button lets you build custom buttons with 5 class of buttons, 3 type and 3 styles. Perfect for hyperlinks, downloads, promotions, or redirects. plugin allows you add, manage and display buttons on your WordPress website.

View [DEMO](http://demo.wponlinesupport.com/buttons-with-style-demo/) for more details.

Now you can also Display Buttons With Style.

= Features =
* Use 5 class of buttons ie success, primary, secondary, info, alert.
* Use 3 types of buttons style ie  radius, square, round
* Use 3 styes ie shadow, plane, border.

= Here is the example =
<code>
type
[bws_button link="http://www.goggle.com" type="radius"]
class
[bws_button name="button-name" class="success"]
style
[bws_button name="button-name" style="shadow"]
target
[bws_button name="button-name" target="blank"]
</code>

= Shortcode parameters are =
* **link** : <code>[bws_button link="http://www.goggle.com"]</code> (ie button link parameter)
* **name** : <code>[bws_button name="button-name"]</code> (ie name of button ie Submit OR Send etc)
* **type** : <code>[bws_button type="radius"]</code> (ie type can be used radius, square, round)
* **class** :<code>[bws_button class="success"]</code> (ie class can be used  success, primary, secondary, info, alert)
* **style** :<code>[bws_button style="shadow"]</code> (ie style can be used  shadow, plane, border ie all)
* **target** : <code>[bws_button target="blank"]</code> (ie target can be used  blank, self )
* **size** : [bws_button size="tiny"] (ie tiny, small, largem, expand)

= Complete shortcode with all parameters =

[bws_button name="button-name" type="square" class="success" style="shadow" target="blank"]

== Installation ==

1. Upload the 'buttons-with-style' folder to the '/wp-content/plugins/' directory.
2. Activate the "Buttons With Style" list plugin through the 'Plugins' menu in WordPress.
3. Add this short code where you want to display button
<code>[bws_button]</code>

== Changelog ==

= 1.0.2 =
* [*] Removed unnecessary string being disply at button.

= 1.0.1 =
* Changed plugin shortcode from 'button' to 'bws_button' to avoid conflict with some theme.

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 1.0.2 =
* [*] Removed unnecessary string being disply at button.

= 1.0.1 =
* Changed plugin shortcode from 'button' to 'bws_button' to avoid conflict with some theme.

= 1.0 =
* Initial release.