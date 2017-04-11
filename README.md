# Lesson Learned

_April 11, 20117_
- ACL is controlled by files and app configuration.
   - Through files, ACL is found inside settings.properties or acls.properties
   - Through app configuration, ACL is found inside app.roles, app.appAdmins, app.businessLead, app.editors
   - ACLs are matched agains the user.userID, user.cotUser.groupMemberships, user.cotUser.division
- When configuring an Appfactory app, the cc_config's ACL is used, when running an Appfactory app, the app configuration ACL is used
