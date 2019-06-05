# TypedJS

Built using the WordPress Plugin Boilerplate generator https://wppb.me/.

Download the plugin from WordPress https://downloads.wordpress.org/plugin/mrlegend-typedjs.zip or search for it in the plugin section.

A WordPress plugin to allow you to use Typed JS in WordPress inside the given shortcode.

[typedjs]Content[/typedjs]

Simply download and upload in the archive into the WordPress plugins section and activate. 
<style>.bmc-button img{width: 27px !important;margin-bottom: 1px !important;box-shadow: none !important;border: none !important;vertical-align: middle !important;}.bmc-button{line-height: 36px !important;height:37px !important;text-decoration: none !important;display:inline-flex !important;color:#FFFFFF !important;background-color:#FF813F !important;border-radius: 3px !important;border: 1px solid transparent !important;padding: 1px 9px !important;font-size: 22px !important;letter-spacing: 0.6px !important;box-shadow: 0px 1px 2px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;margin: 0 auto !important;font-family:'Cookie', cursive !important;-webkit-box-sizing: border-box !important;box-sizing: border-box !important;-o-transition: 0.3s all linear !important;-webkit-transition: 0.3s all linear !important;-moz-transition: 0.3s all linear !important;-ms-transition: 0.3s all linear !important;transition: 0.3s all linear !important;}.bmc-button:hover, .bmc-button:active, .bmc-button:focus {-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;text-decoration: none !important;box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;opacity: 0.85 !important;color:#FFFFFF !important;}</style><link href="https://fonts.googleapis.com/css?family=Cookie" rel="stylesheet"><a class="bmc-button" target="_blank" href="https://www.buymeacoffee.com/JyrlWUz"><img src="https://www.buymeacoffee.com/assets/img/BMC-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:5px">Buy me a coffee</span></a>


# Description
This plug-in allows you to use TypedJS in your WordPress installation. TypedJS is a typewriter style animation to engage your users and catch their attention. The text will be typed out. Just put your content between the `[typedjs][/typedjs]` tags. Use the + sign to use the backspace feature.
The additional parameters map up to TypedJS so `typespeed` parameter is in milliseconds and `loop` can only be `true` or `false`. It will add a typing effect.
To view a demo by the author, Matt Boldt of TypedJS click here: https://mattboldt.com/demos/typed-js/.

# Installation
1. Upload `typed-js.php` to the `/wp-content/plugins/` directory
2. Activate the plug-in through the 'Plug-ins' menu in WordPress
3. Place the shortcode wherever you need it. `[typedjs]Content[/typedjs]`.
4. To add parameters your would like for example: `[typedjs typespeed="20" startdelay="800" backdelay="1002" backspeed="1" loop="false"]Text Line 1 + Text Line 2 + Text line 3[/typedjs]`.
