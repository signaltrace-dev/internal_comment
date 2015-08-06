This module allows you to restrict access to a comment by changing the template for a internal comment
For use with a ticketing system in which some comments should be invisible to customers/clients
Forked from https://www.drupal.org/project/internal_comment

INSTALLATION
Normally install the module in sites/all/modules, and enable it,
then go to admin/structure/types/manage/YOUR_CONTENT_TYPE/comment/fields 
and add a boolean field with the machine name field_internal_comment. 
Set it with 
On value : Internal comment
Off value : Public comment

Configure permission in admin/people/permissions#module-internal_comment

COMPATIBILITY 
This module works with og-7.x-2.x. The module permission will be override by og module :
a internal comment can be acessible only to group members.
