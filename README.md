# Khalti Payment Plugin for OpenCart

## Requirement and Compatibility
- Requires OpenCart 3.x
- Tested & working upto 3.0.3.6

### Installation
- Copy all files on the root folder
- Login to OpenCart's Admin area and go to `Extensions` > `Extensions`
- Choose `Payments` from the `Choose the Extension Type` filter
- Scroll the page and search for `Khalti` and click on green `+` button on the right side to install the plugin.
- Click on the blue button with pencil icon to configure the plugin. 
- Place your Public and Private keys provided by Khalti and finish the Plugin installation. 
- include `<script src="https://unpkg.com/khalti-checkout-web@latest/dist/khalti-checkout.iffe.js"></script>` inside `<head></head>` tags on your themes header file which is located on `catalog/view/theme/YOUR_THEME_NAME/template/common/header.twig`
- clear Opencart cache
