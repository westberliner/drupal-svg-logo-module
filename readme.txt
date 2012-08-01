1. Install and activate this plugin.
2. Goto to admin theme settings and add a svg logo.
3. In your templates is now the svg_logo as variable accessable.

Example code to add logo with fallback:
<object id="header-logo" data='<?php print $svg_logo; ?>' alt="<?php print t('Home'); ?>" style="">
  <img alt="<?php print t('Home'); ?>" src='<?php print $logo; ?>'  />
</object>