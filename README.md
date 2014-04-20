Custom Blocks
=============
Custom Blocks lets you easily manage small content blocks on your website.
This can be usefull for, e.g., footer content.

Go to admin/config/content/custom_blocks and start adding blocks.
They will automatically appear in your blocklist so you can drag them in your
regions or add them to your panelized page.

Compatible with features, just add custom_blocks_data in strongarm and optionally
administer custom blocks in the permissions.

NOTICE: Don't export custom_blocks_local_data! If you do, your saved data will
be restored to default settings each time you run a kraftwagen update.
