# Fix W3TC

Fix and customize W3 Total Cache by @ftownes

### Fix

- [ ] Fix deprecated `get_currentuserinfo()`
- [ ] Support PHP7
- [ ] Support APCu
- [ ] Support OPcache
- [ ] Add woff2 CORS support
- [ ] Halfdone CloudFlare support in trunk

### And customize

- [ ] Disable w3tc-edge-mode
- [x] Hide most widgets from W3TC Dashboard
- [ ] Remove informational submenus
- [x] Remove contextual help `w3tc_*`
- [x] Make admin pages smaller `#w3tc h2.logo { float: right; }`
- [x] Remove HTML comment by hooking `w3tc_can_print_comment`
- [x] Disable EDD/licensing

### Disabled submenus

- FAQ
- Support
- Install
- About

### Disabled W3TC plugins

- W3_Plugin_NewRelicAdmin
- W3_Licensing

### Disabled W3TC widgets

- W3_Widget_SpreadTheWord
- W3_Widget_News
- W3_Widget_Forum
- W3_Widget_MaxCDN
- W3_Widget_NetDNA
- W3_Widget_NewRelic

### Upstream

svn: https://plugins.svn.wordpress.org/w3-total-cache/

git: https://github.com/wp-plugins/w3-total-cache.git

### Alternatives

- https://github.com/bermanco/w3-total-cache-php7
- https://github.com/tperalta82/w3-total-cache-ng
- https://github.com/wp-plugins/w3tc-auto-pilot
- https://github.com/StefanoWP/W3-Total-Cache-WordPress-Plugin-Default-Settings

<!--
try Google Page Speed API on dashboard widget
-->
