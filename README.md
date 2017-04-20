# Lesson Learned

April 20, 2017
- EventRepo submit API accepts a filter parameter containing a field name and a regular expression to match it against
   - https://was-intra-sit.toronto.ca/cc_sr_admin_v1/retrieve/eventrepo/it_SWMS_App?json={"limit":1000,"repo":"it_SWMS_App/employeeinnovates","filter":"status~(DEL)|(REQ)"}&sid=wtQrIlmwxecwqio_I2rgEF1O8UbunNpjKz8Tn5NOZq8

April 11, 2017
- ACL is controlled by files and app configuration.
   - Through files, ACL is found inside __settings.properties__ or __acls.properties__
   - Through app configuration, ACL is found inside __app.roles__, __app.appAdmins__, __app.businessLead__, __app.editors__
   - ACLs are matched agains the __user.userID__, __user.cotUser.groupMemberships__, __user.cotUser.division__
- When configuring an Appfactory app, the cc_config's ACL is used, when running an Appfactory app, the app configuration ACL is used
