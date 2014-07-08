Limit Post Revisions
===========
Contributors: [@wordpress] (https://github.com/wordpress), [@davidstehle] (https://github.com/davidstehle)<br>
License: [GPLv2 or later] (http://www.gnu.org/licenses/gpl-2.0.html)

Description
-----------
By default, WordPress saves 10 post revisions for every post! Overtime this can lead to unwanted bloat in your WordPress Database. Limit database bloat by limiting post revisions.

Installation
-----------
*NOTE: It should go without saying, always backup your files before making any changes. This is especially true with the “wp-config.php" file that we will be working with because it’s one of the most important files in your WordPress installation.*

Install in just four simple steps!

1. Locate and open your “wp-config.php" (in the root install-directory).
2. Edit the line that reads **define( 'WP_POST_REVISIONS', 10 );**
3. Change the number **10** to **1**.
4. Save and upload back into your directory, overwriting your previous “wp-config.php” file.

FAQ
-----------
**Q) Where can I get more help?**<br>
Visit http://codex.wordpress.org/Revisions

**Q) I’m scared to edit this file. Is there an alternative method?**<br>
Yes. You can also limit post revisions with the wp_revisions_to_keep filter — http://codex.wordpress.org/Plugin_API/Filter_Reference/wp_revisions_to_keep
