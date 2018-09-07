## Free Active Directory / LDAP Test Server

This is hosted on Microsoft Azure inside a small VM.

The server is operated and maintained by [Documize](https://documize.com)

### Connection Details

Use the following LDAP connection details:

	ServerHost:               "documize-ad.eastus.cloudapp.azure.com"
	ServerPort:               389
 	BaseDN:                   "DC=mycompany,DC=local"
	BindDN:                   "CN=Mr Manager,CN=Users,DC=mycompany,DC=local"
	BindPassword:             "Pass@word1!"

The following examples filters canbe used to retrieve users and groups.

    UserFilter:               "(|(objectCategory=person)(objectClass=user)(objectClass=inetOrgPerson))",
	GroupFilter:              "(|(cn=Accounting)(cn=IT))",

That's it!

### Support or Contact

[Contact Us](https://documize.com/contact) and we’ll help you sort it out.
