# TypedJS

Built using the WordPress Plugin Boilerplate generator https://wppb.me/.

Download the plugin from WordPress https://downloads.wordpress.org/plugin/mrlegend-typedjs.zip or search for it in the plugin section.

A WordPress plugin to allow you to use Typed JS in WordPress inside the given shortcode.

[typedjs]Content[/typedjs]

Simply download and upload the archive into the WordPress plugins section and activate. 


# Description
This plug-in allows you to use TypedJS in your WordPress installation. TypedJS is a typewriter style animation to engage your users and catch their attention. The text will be typed out. Just put your content between the `[typedjs][/typedjs]` tags. Use the + sign to use the backspace feature.
The additional parameters map up to TypedJS so `typespeed` parameter is in milliseconds and `loop` can only be `true` or `false`. It will add a typing effect. Added parameter for the cursor styles just use standard CSS as shown in the installation instructions. I'd recommend using !important if it doesn't work the first time.
To view a demo by the author, Matt Boldt of TypedJS click here: https://mattboldt.com/demos/typed-js/.

# Installation
1. Upload `typed-js.php` to the `/wp-content/plugins/` directory
2. Activate the plug-in through the 'Plug-ins' menu in WordPress
3. Place the shortcode wherever you need it. `[typedjs]Content[/typedjs]`.
4. To add parameters your would like for example: `[typedjs cursor="color:red;" typespeed="20" startdelay="800" backdelay="1002" backspeed="1" loop="false"]Text Line 1 + Text Line 2 + Text line 3[/typedjs]`.
