This module allows you to restrict access to a comment by changing the template for an internal comment.
For use with a ticketing system in which some comments should be invisible to customers/clients.
Forked from https://www.drupal.org/project/private_comment

INSTALLATION
Normally install the module in sites/all/modules, and enable it,
then go to admin/structure/types/manage/YOUR_CONTENT_TYPE/comment/fields
and add a boolean field with the machine name field_internal_comment.
Set it with
On value : Private comment
Off value : Public comment

Configure permission in admin/people/permissions#module-internal_comment

COMPATIBILITY
This module works with og-7.x-2.x. The module permission will be overridden by og module :
an internal comment can be accessible only to group members.
