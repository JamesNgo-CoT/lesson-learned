# Lesson Learned

April 11, 20117
- ACL is controlled by files and app configuration.
   - Through files, ACL is found inside __settings.properties__ or __acls.properties__
   - Through app configuration, ACL is found inside __app.roles__, __app.appAdmins__, __app.businessLead__, __app.editors__
   - ACLs are matched agains the __user.userID__, __user.cotUser.groupMemberships__, __user.cotUser.division__
- When configuring an Appfactory app, the cc_config's ACL is used, when running an Appfactory app, the app configuration ACL is used
